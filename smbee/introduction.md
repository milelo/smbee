---
title: Introduction
parent: Make a bee
has_children: false
nav_order: 1
---

I love designing and making stuff, I get an idea and start on a path to realise it, but not many ideas get to see the light of day. There are many reasons, maybe it is the scale of the task, I encounter problems that don't seem to have a practical solution, not worth the effort to overcome, or it's just that a better or more interesting idea comes along to displace it. It doesn't matter, I learn so much from just messing around with tools and stuff just to understand how something works and its a fun type of learning, problem solving and just following ideas my imagination throws up. Even if there are no end results worth showing off, I've learned something, got a new skill, that's whats fun and gives a sense of achievement.

Good projects take on a life of their own as more and more ideas come to build on an initial concept and make it through to being a product, this has been mainly been on projects in my profession but with the bee badge it started off as a simple idea not specifically to make anything useful but, to evaluate and develop skills in EDA and 3D CAD tools that when the complexities inevitably grew the project was small enough I was still happy to invest the time to pursue it to completion. The idea came from MADLAB Manchester's fantastic travelling MakeStuff weekly events in 2017 where I went as a regular volunteer mainly on the Animal Badge soldering activity where we would show people how to solder a colour-changing LED, battery holder and pin to a PCB in the shape of various animals with screen printed features. This was always a very popular stand with an endless queue of visitors of all ages probably largely because they got to take something they had
made home. I usually went home exhausted at the end of the day but it was rewarding seeing the sense of achievement as the battery was inserted and the LED lit up.

Like with everything I start wondering if the badge could be improved, maybe an on-off switch but aren't they big and clunky? Maybe modern surface mounted components rather than through-hole mounted but are there any surface mount LEDs that flash?, isn't surface mount soldering to too difficult? The solutions aren't obvious but the concept lingers in my sub-conscious until weeks, months, years later, an idea comes from nowhere or I see something that may solve a problem and another piece to the jigsaw in my mind pops into place, first I came across a wafer-thin tactile (clicky) switches, then a piece of black PCB with gold plated contacts that looked good but I wasn't sure what I could make it into then I want to design a PCB to learn free-to use EDA software and something in 3D to learn free to use 3D CAD. What can I design?

### Making a bee badge

I've tried to develop simple techniques that I will explain here with the hope that anybody of any age with a reasonable amount of dexterity, care and supervision can learn to make a bee badge. In reality I haven't tried this out on anybody yet so I don't know how effective they are.

I would like to make the project a lot more than just making a bee for those that are interested, and want to go deeper to explore the tools and skills I've used to develop it including:

* Micro Controllers and embedded programming
* PCB design and hacking using KiCad
* Some electronics theory
* GitHub code and document control

The badge has the minimum number of components to achieve its functionality:

* Printed circuit board
* 5 LEDs, 4 of them individually controllable
* 6-pin flash-programmable microcontroller
* Tactile, momentary action, push button as an on-off switch
* Battery holder for a 3V lithium button cell
* Locking brooch clasp

The retail cost of the components for each badge is about £4 in small quantities, £2 for 100 off, the PCB is
the main cost. I've tried to keep the cost of the tools low so they can be purchased by a small group of people. Electronics hobbyists may have access to most of them anyway or find them useful for other purposes.

### The programmer

You will need access to a flash programmer to programme the badge firmware with either the standard code or code you have tweaked to give your badge a unique personality. There are commercial programmers that can do this but they are very expensive and don't provide a way to connect to the MCU on the badge. To solve this I've designed an inexpensive programmer based on a custom PCB integrating a couple of readily available electronic modules, a few discrete components and a custom laser cut case/jig with a total retail parts cost of about £12. I will treat this as a separate project.

This projects introduces:

Further skills used to make the bee programmer:
* 3D CAD using Fusion360
* Laser cutting

* [SMBeeHive]{:target="SMBeeHive"} on GitHub

[SMBeeHive]: https://github.com/milelo/SMBeeHiveKiCad
