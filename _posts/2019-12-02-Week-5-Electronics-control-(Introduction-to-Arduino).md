---
layout: post
title: "Week 5: Electronics control: Introduction to Arduino"
date: 2019-12-02
---

As with every week, this week also kickstarted with a fabacademy video.

![fab academy home page](/images/fabacademyweek5.png){:height="360px" width="500px"}

The assignment for this week as a part of the fabacademy course is to make one's own programmer this week. The objective is also to make a circuit.

Notes from the video:
1. PCB - stands for printed circuit board - the industrial way to make it is to etch it. Etchants are nasty materials like ferric/cupric, or chloride, ammonium or sodium per sulfate - so they need to be disposed properly.
2. Machining - required holding the board down and milling it. Below the board is a tape and then a sacrificial layer/board (This usually has a lifetime), and finally a millbed. The set screws should be just snug.
3. Vinyl cutter
4. Ordinary laser cutter doesn't cut copper, so need fiber laser - let's you make high-resolution board but very expensive. 
5. Printing
6. Plating
7. Sewing (using conducting threads)
8. PCB materials include: a) common PCB material is fr4 - should not go near milling machine. We use fr1 instead - this is phenolic paper & machines beautifully. fr1 is slightly yellowish. b) flexible circuits use epoxy film and copper tape. c) for high frequency, use teflon & glass. d) Copper.
9. Boards - a) PCB:NG, AP circuits, Advanced Sierra, Screaming circuits, AQS, Gold phoenix, 3PCB, speed, PCB way, JLCPCB, PCB kit, BOM (bill of materials), b) design rules - width spacing (15,5 mils) - each mil is 1/1000th of an inch, c) layers - 1, 1.5, 2, 4, N, d) mechanical, drill, solder mask, silk screen, and e) rivets, plated, blind, buried.
10. Components - a) through - hole, b) surface - mount, c) chip - scale. [Chinese vendors are competitive and make really cheap PCBs].
11. Breadboards - we won't be using it, popular among hobbyists, they sometimes have bad electrical performance.
12. Assembly - a) solder (lead + tin) - entectic, wetting, flux, wire, paste bar, manual, reflow, wave, ROHS, b) stuffing - component orientation, tacking down parts, bottom to top, inside to outside, fumes, washing, b) desoldering - braid, hot air, gravity, c) cutting traces/adding jumpers, d) pick and place, and e) encapsulation.
13. CAM - a) formats (gerber/RS-274X, PNG resolution), b) mods - video, c) trace width - traces, interior, 1/64 inch, 0.010 inch.

After watching the video, Richard suggested I do some additional reading on the following topics (my reading is ongoing):
1. Programming of microchips and microcontrollers
2. Programmers for microchips and microcontrollers
3. Programming code - Integrated Development Environment (IDE)
4. Evolution of electronics - basic electronics, power electronics, vacuum tubes & relays, transistors (which were a major breakthrough), and integrated circuits.
5. 555 timer microchips - useful for timer, pulse generator, oscillator applications
6. Interesting youtube channels to follow for pet projects and inspiration: Blackfish and the Q.
7. Solderless breadboards
8. Architecture of the Arduino - different types of Arduino
9. ATMEGA 328P
10. Ladyada tutorials on microcontrollers

Here are three pictures on basic electronics that Richard drew out on a notebook while explaining:

![fab academy home page](/images/notes1.jpeg){:height="360px" width="500px"}

![fab academy home page](/images/notes2.jpeg){:height="360px" width="500px"}

![fab academy home page](/images/notes3.jpeg){:height="360px" width="500px"}

After this, I worked on DFRobot's Beginner Kit for Arduino. This is what the kit looks like and these are the components that are available with the kit.

![fab academy home page](/images/arduinokit.jpeg){:height="360px" width="500px"}

![fab academy home page](/images/arduinocomponents.jpeg){:height="360px" width="500px"}

The kit has a series of 15 tasks or projects for a user to get comfortable with the components. I downloaded the Arduino IDE, which allowed me to write codes to programme the arduino to perform the tasks listed in the kit.

For the codes, I used the ones available on the [DFRobot website](<https://wiki.dfrobot.com/DFRduino_Beginner_Kit_For_Arduino_V3_SKU_DFR0100>). For me, the objective of using and working with the kit was to understand the capabilities of the multiple components in the kit, and also to understand the codes associated with each of the projects. 

Here are pictures what each project was about, the components required to execute the project, and a video of the completed project.

Project 1: Blinking a LED

![fab academy home page](/images/project1/project1-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project1/project1-2.jpg){:height="360px" width="500px"}

<video src="/images/project1/project1-3.mp4" width="320" height="200" controls preload></video>

Project 2: SOS Beacon

![fab academy home page](/images/project2/project2-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project2/project2-2.jpg){:height="360px" width="500px"}

<video src="/images/project2/project2-3.mp4" width="320" height="200" controls preload></video>

Project 3: Traffic light

![fab academy home page](/images/project3/project3-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project3/project3-2.jpg){:height="360px" width="500px"}

<video src="/images/project3/project3-3.mp4" width="320" height="200" controls preload></video>

Project 4: Fading light

![fab academy home page](/images/project4/project4-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project4/project4-2.jpg){:height="360px" width="500px"}

<video src="/images/project4/project4-3.mp4" width="320" height="200" controls preload></video>

Project 5: RGB LED

![fab academy home page](/images/project5/project5-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project5/project5-2.jpg){:height="360px" width="500px"}

<video src="/images/project5/project5-3.mp4" width="320" height="200" controls preload></video>

Project 6: Alarm

![fab academy home page](/images/project6/project6-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project6/project6-2.jpg){:height="360px" width="500px"}

<video src="/images/project6/project6-3.mp4" width="320" height="200" controls preload></video>

Project 7: Temperature Alarm

![fab academy home page](/images/project7/project7-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project7/project7-2.jpg){:height="360px" width="500px"}

<video src="/images/project7/project7-3.mp4" width="320" height="200" controls preload></video>

Project 8: Detecting Vibration

![fab academy home page](/images/project8/project8-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project8/project8-2.jpg){:height="360px" width="500px"}

<video src="/images/project8/project8-3.mp4" width="320" height="200" controls preload></video>

Project 9: Auto light

![fab academy home page](/images/project9/project9-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project9/project9-2.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project9/project9-3.jpg){:height="360px" width="500px"}

Project 10: Moving a Servo

![fab academy home page](/images/project10/project10-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project10/project10-2.jpg){:height="360px" width="500px"}

<video src="/images/project10/project10-3.mp4" width="320" height="200" controls preload></video>

Project 11: Interact with Servo

![fab academy home page](/images/project11/project11-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project11/project11-2.jpg){:height="360px" width="500px"}

<video src="/images/project11/project11-3.mp4" width="320" height="200" controls preload></video>

Project 12: RGB Light Dimmer

![fab academy home page](/images/project12/project12-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project12/project12-2.jpg){:height="360px" width="500px"}

<video src="/images/project12/project12-3.mp4" width="320" height="200" controls preload></video>

Project 13: Motor Fan

![fab academy home page](/images/project13/project13-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project13/project13-2.jpg){:height="360px" width="500px"}

<video src="/images/project13/project13-3.mp4" width="320" height="200" controls preload></video>

Project 14: Infrared Controlled Light

![fab academy home page](/images/project14/project14-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project14/project14-2.jpg){:height="360px" width="500px"}

<video src="/images/project14/project14-3.mp4" width="320" height="200" controls preload></video>

Project 15: Infrared Controlled LED Matrix

![fab academy home page](/images/project15/project15-1.jpg){:height="360px" width="500px"}

![fab academy home page](/images/project15/project15-2.jpg){:height="360px" width="500px"}

<video src="/images/project15/project15-3.mp4" width="320" height="200" controls preload></video>