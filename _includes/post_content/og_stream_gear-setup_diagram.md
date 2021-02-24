{% mermaid %}
graph LR;
    subgraph video
        PC(Streaming PC):::myPC
        SNES(Analogue Super NT) ==> HS(HDMI Switch)
        PS4(Playstation 4) ==> HS
        Switch(Nintendo Switch) ==> HS
        GPC(Gaming PC) ==> HS
        HS ==> HSplit(HDMI Splitter)
        PC ==> M1(Monitor 1)
        PC ==> M2(Monitor 2)
        HSplit ==> M3(Gaming Monitor)
        Cam(Blackmagic Design Pocket Cinema Camera 4K) ==> PC
        HSplit ==> PC
    end
    subgraph audio
        GPC -.-> ANI5(Audio Noise Isolator 5)
        HSplit -.->|HDMI Audio Only| HDAC(Digital Audio to Analog Audio Converter)
        HDAC -.-> ANI1(Audio Noise Isolator)
        PC -.->|Desktop Audio| ANI2(Audio Noise Isolator 2)
        Mic(Heil PR 40 Microphone) -.-> CL(Cloud Lifter)
        ANI5 -.-> Mixer
        ANI1 -.-> Mixer
        ANI2 -.-> Mixer
        CL -.-> Mixer
        Mixer -.->|Mic Only| HD(Hum Destroyer)
        HD -.->|Mic Only| Compressor
        Compressor -.->|Mic Only| HD
        HD -.->|Mic Only| Mixer
        Mixer -.->|Master Out| Headphones
        Mixer -.->|AUX SEND 1 microphone only| ANI3(Audio Noise Isolator 3)
        Mixer -.->|MAIN OUT| ANI4(Audio Noise Isolator 4)
        ANI3 -.-> PC
        ANI4 -.-> PC
    end
    linkStyle 0,1,2,3,4,5,6,7,8,9 stroke:blue,stroke-width:4px;
    linkStyle 10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27 stroke:red,stroke-width:4px,stroke-dasharray: 5.5;
{% endmermaid %}
