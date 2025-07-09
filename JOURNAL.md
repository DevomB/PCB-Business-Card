---
title: "PCB Business Card"
author: "Devom B"
description: "Custom NFC-enabled PCB Business Card"
created_at: "7-7-2025"
---

<em>Total Time Spent: 7.5h</em>

# [7-7] P1: Initial Design Phase (v0.5)

To start off, I chose this project primarily because of two things, I wanted to make a cool item that was a convo starter, and also wanted to create something that I can use @ a CS event to network more effectively. This fit both of the criteria but I was also motivated bu the fact that I saw a really cool one and decide that I wanted to make one for myself. I didn't really took too much at tutorials, I used the Hack Club link for a PCB card [here](https://jams.hackclub.com/jam/hacker-card) to start but did not want to rely on it so that I can build my own understanding of PCB design. I also asked ChatGPT and Gemini most of my questions. 

To start the development process, I noted which parts need to be imported from the EasyEDA library, and afterwhich I did. Then after a reiterative, and recurvsive process with ChatGPT with asking questions about ports and parts, and subsequently switching to Gemini due to image upload limits, I finished the PCB Circuit. 

For the circuit design, here's my [v0.5 schematic file](images/Circuit_Design/)

Key components used:
- NFC antenna coil
- LED indicators  x 2
- Resistors

The main challenge trying to understand what each port does and why things are done the way they are. 

**Time Spent: 4.5h**

---

# [7-9] P2: Iteration and Visual Design (v1.0 and 2.0)

Now that I woke up in the morning, I aimed to get the PCB and design part of this down, I would say this was the hardest part due to the reiterative and tedious nature of the development process. I started by organizing my parts on the PCB and after setting the NFC tag on the right and setting the LED on the eyes of the smiley face that I added to the design I started trying to route the items. I spent about 20 minutes trying to route around things and make it look organized. After which, I found out short circuiting and had to figure out a way around the 4-deep short circuit that was my PCB. After of which I spent about 3 hours of on and off work trying to find a way to create route set that wouldn't short circuit, but also looks sophisticated. At somepoint, Gemini suggested Auto-Routing and having my resolve completely depleted, I gave in and had it auto route. 

Then I adjusted the location of the text and images so that they were inline with the auto-routed PCB, and I finished. 

![v3.0_2d](images/v3_PCB_Design/v3.0_2d.png)

**Time Spent: 3.0h**


**Total Time Spent: 7.5h**
