---
layout: post
title:  "OGJunkyard's Stream Setup - Part 2: Streaming PC"
author: ogjunkyard
categories: [ stream setup ]
image: "og-desk.webp"
featured: true
---

The streaming PC is the bedrock of every stream. If your foundation is cracked, broken, and shaky, how can you deliver your best?

Hey folks, it's OGJunkyard.

Today, we are talking about streaming PCs and what goes into them. This is often times the first major upgrade streamers make, and if we get this right, we are typically set for 3+ years of streaming day in, day out.

In this post, we are looking at individual component selection (at a high level) and what options are out there for some of the more streamer-focused parts. We'll talk about ways to build your setup to support more cameras, audio sources, and peripherals to help you drive your stream.

Finally, we'll talk specifically about my streaming PC, what I've got in it, and how it's all hooked up for streaming.

[If you just want to see my streaming gear, click here.]({% post_url 2021-02-12-ogjunkyard-stream-setup-pc %}#ogjunkyards-streaming-gear)

### The (Hypothetical) Streaming PC

The backbone of your entire stream that holds everything together is what you are streaming from, and in most cases, that's a Streaming PC. Here's a few things your streaming PC does that can cause people to bounce out of your stream:

- A stuttering and choppy stream. ("This jank will be over in a minute, trust me.")
- Being unreliable. ("Hang on guys, we're gonna need a quick reboot. Please don't leave!")
- Being on WiFi. ("Ugh, my neighbor started her microwave again?!")

For people streaming and gaming on the same device (console or PC), you are taking a quality hit on two fronts. You are using the same resources to run two different demanding workloads: Gaming and Streaming. You are asking your device to take resources away from running the game efficiently and effectively to produce a stream, which also takes a hit because it doesn't have all the resources available that it should in the first place.

### The Quality Difference

Before we get into the details of what goes into a streaming PC, let's talk about the quality difference a QUALITY dedicated streaming PC can make. To illustrate this point first, I want to show you a few clips from my Twitch stream. We'll look at some "before" clips when I first started streaming and was streaming off a 2012 MacBook Pro and gaming on a Nintendo Switch. Technically speaking, I WAS using a dedicated streaming PC by using the Macbook Pro and playing on the Nintendo Switch. At the time, I was using a Blackmagic Design Intensity Shuttle to feed in the game signal to my MacBook, and I was limited to streaming at 720p at 30 frames per second (FPS):

[Before I upgraded my streaming PC - Clip #1](https://www.twitch.tv/ogjunkyard/clip/TameAltruisticBeefBibleThump)

[Before I upgraded my streaming PC - Clip #2](https://www.twitch.tv/ogjunkyard/clip/WimpySincereEggplantCeilingCat)

In Before Clip \#1, I want you to notice the little blocky-looking artifacts, the blurriness in the overall image, and the mediocre frame rate. You can see little skips and stutters in the gameplay, especially as the camera pans around Donkey Kong waiting for the race to start, and the floating character Lakitu holding the starting lights in the top left.

In Before Clip \#2, when the speed picks up during the race and the race goes around a corner, you'll notice that even my webcam image in the lower left-hand corner takes a hit, even though I'm not really moving. The edges of the webcam get soft, blocky, and blurry. Devices that are underpowered REALLY suffer when it comes to fast moving action where a lot of the game environment is sliding across the screen. First-Person Shooter games are perfect examples of this as it's very easy for the player to whip the camera around really fast, causing a lot of visual information on the screen to change.

After I spent a few months streaming this way, I decided to upgrade to an actual, good-quality streaming PC in late 2018. I was incredibly nervous that this wouldn't be a worthwhile investment (even though I was streaming 20-50 hours a week on a computer built in 2012). I spent a lot of time researching components and talking to friends. I bought everything on a Black Friday/Cyber Monday sale on [NewEgg](https://www.newegg.com), which turned out to be a great idea as I saved about $600 on the price of my computer.

The VERY first stream, I noticed a big quality improvement. See here for yourself:

[After I upgraded my streaming PC - Clip #1](https://www.twitch.tv/ogjunkyard/clip/FunSnappyCasetteMrDestructoid)

[After I upgraded my streaming PC - Clip #2](https://www.twitch.tv/ogjunkyard/clip/FrailArbitraryGuanacoHumbleLife)

[After I upgraded my streaming PC - Clip #3](https://www.twitch.tv/ogjunkyard/clip/SmoothMoralShrewPermaSmug)

In all of these, you can notice a big improvement in a variety of ways. The framerate is running at a smooth 60 FPS, most of the visual blocky artifacts are gone or greatly reduced. You'll also notice that it's just more pleasing to watch because you can actually make out what's going on without having to focus on individual portions of the screen.

Simply put, you can just sit back and enjoy the content. That's what you are going for when you invest in a quality streaming PC.

### What's YOUR Use Case?

While I've built a number of computers for a variety of different use cases, I'm not building computers so often that I know all the manufacturers by heart all the time. I have to do my research every time I build a computer. It's not uncommon for me to spend 50-100 hours (OR MORE!) on research just to figure out what I'd LIKE to put in the computer I'm speccing out.

This means that I encourage you to strongly consider your use case. Make sure you know exactly what you want to show your audience, then decide what you would need for your parts and go from there. If you are a gaming streamer, you have very different needs than someone who is a cooking streamer. If you are like MrGreggles, you have a second, third, or potentially fourth PC to help you manage all the cameras and moving parts for your drumming streams. Seriously, if you want inspiration on what a fun, interactive, well-executed stream is like, that's a great streamer to go check out.

[Click here to go to MrGreggles' Twitch Channel.](https://twitch.tv/MrGreggles)

Things to consider for your stream are what the main purpose is (gaming, cooking, art, etc.) and what you'd like your viewers to see/watch. Do you want them to see all the angles of your drum kit like MrGreggles? You may need quite a few multi-port PCIe capture cards and/or USB capture cards just for cameras alone. Do you want to show all the different steps of your cooking show? You may need extra accessories and/or special equipment to protect your microphone(s) and camera(s) from the messy process that is making a nice meal. Or, if you are like most streamers, you may not need a super elaborate setup and you can get away with a streaming PC and a gaming PC or console.

In my particular case, I currently have my streaming PC in a server rack. Server racks are what companies use to organize lots of computers, networking equipment, power, etc. After I had been streaming for over a year, I knew that I wanted to invest in a gaming PC and I also wanted to make content for YouTube, so I decided to start switching over my streaming setup to be organized in a server rack. When I was first considering going this route, I actually ended up DMing MrGreggles about it and he gave me some great guidance. Thanks again, MrGreggles!

When I eventually have the server rack filled out like I want to, I'll have three computers (Streaming PC, Gaming PC, and Network-Attached Storage) in the server rack along with multiple shelves, networking equipment, power delivery equipment, and more to keep it all contained and organized. Some people like to show off their equipment and I prefer to hide the mess all away.

### Part Selection

Computers come down to just a handful of parts, and I'll list them in the order that I typically pick them out. I'm assuming that you are a streamer who is doing a fairly standard gaming-focused stream, so I'm tailoring the rest of the post towards that. (Sorry MrGreggles...)

- CPU (Processor)
- Graphics Card
- Other PCIe Cards
- Motherboard
- RAM
- Hard Drive (HDD) / Solid State Drive (SSD) / NVMe Drive (M.2 typically)
- Power Supply

Before we get too deep on this, I'll be the first to admit that I err on the side of caution and often times buy more performance than I truly need. I'd rather have an overpowered PC that I'm happy with than one I'm looking at upgrading in 6 months. Do your research, save up for what will work well for YOUR SPECIFIC USE CASE, and wait for there to be a deal if you want to or need to.

### CPU

I 100% think this should be the most important part you should stick in your streaming PC, and you should spend accordingly.

### Graphics Card


### OGJunkyard's Streaming Gear

{% include post_content/og_stream_gear-ordered_first-pc.html %}
