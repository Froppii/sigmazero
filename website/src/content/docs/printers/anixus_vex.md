---
title: "Anixus Vex"
description: "A powerful, fast, precise CoreXY 3D printer aimed at intense speed"
project_name: "Anixus Vex"
repository: "https://raw.githubusercontent.com/invictus-anic3tus/anixus-vex/refs/heads/main/journal.md"
---
# firstly,

This 3D printer has been made possible by Hack Club and the awesome Alex Ren. Let's give them a hand! 👏👏👏

# about the anixus vex

I'm Anicetus, and I'm making a CoreXY because my Anycubic Kobra 2 Neo doesn't print over 250mm/s and can't print hotter than PETG. This will change all of that.

🕐Speed I want: >350mm/s (probably can get faster)  
📐Build size I want: >300mm<sup>3</sup> (maybe not, may have to go 250mm<sup>3</sup>)  
👍Materials I want to print with: TPU, PLA, PETG, HIPS (maybe,) PVA (probably not)  


You may be wondering where I got the name "Anixus Vex." It seems rather strange.  
First of all, the first word is a play on my name, Anicetus (which means unconquerable in Latin). It's basically just compressed to three syllables. Next, "Nixus" is Latin for "soaring" or "effort," invoking a powerful vibe. "Nexus" is also the English (and Latin) word for the hub or the connection between things, which makes sense for an FDM printer that connects things! Also sounds really cool.  
The second word, "vex," is English (and Latin!!) for making somebody annoyed or frustrated, as you probably know.  
It gives off a vibe of hot, fast anger, speedy and deliberate. Another Latin translation for it is to rouse or to excite, again invoking heat and agility. It is also a shortening of "vexare," the Latin word meaning agitation or shaking.  

Again, a short, fiery, awesome name.


OK, good. Down to business.

# day 1
Today I'm researching some parts!! Good stuff. I think ima use the Phaetus Rapido ACE hotend and BTT SKR E3 mainboard. Other than that, I have no idea.

The Rapido ACE HF is built for ~45mm<sup>3</sup>/s printing, which is really really fast and happy. I may upgrade to the UHF if I'm underbudget and want to go 75mm<sup>3</sup>/s.

I'm going with Nema 17 stepper motors, the most popular for CoreXY.

So far, we're at 125 USD. 😬

Next, I looked for extruders. I went with the Orbiter v1.5, since it's smaller and has a lot of support. For PSU, I went a generic 24v 600W.

I started CAD-ing, and got only the hotend and extruder in their places :P

Research and parts: 3 hrs  
CAD: 30 minutes

# day 2
I started today off by doing some research! Some Slack members told me that the Orbiter v1.5 wasn't going to cope with the high-flow Rapido Ace, so I decided to look for a new power pair.

I asked ChatGPT about some stuff, and it pointed me eventually to the Orbiter v2.0 and the Phaetus Dragonfly BMS, getting closer to 450mm/s which is pretty nice! The Dragonfly can also get to around 300°C, which is perfect for PETG and some hotter filaments.

Next, I remembered something kind of big: Klipper host. In my opinion, Klipper is way better than Marlin at a lot of things, and it was a must in my design. I overlooked the hosting, however.
I thought, "Well I can use the Raspberry Pi 3B from my other printer, right?" While that could be a viable option, ChatGPT (coming in clutch yet again) showed me instead the BigTreeTech Manta M4P + CB1, which is a mainboard that has a Klipper host integrated with the mainboard! If I'm under budget by the end of this thing (unlikely,) I'll upgrade the the M8P, which has more capabilities for extra motors and stuff.
I looked for some linear rods and got a good idea of pricing, although I haven't CAD-ed anything since deciding to use the Orbiter v2.0 and Dragonfly. I added a BLTouch to my cart, bringing the total so far to... $240 😭  

Yes, that's nearly the budget right there, without any extrusions or cables or anything. I think I can fit the extrusions and such in the $60, but it may be tight. We'll have to see!

(Later) OK I did some MORE research and decided to go back to the BigTreeTech SKR E3 Mainboard and host both off my one Rpi. If it goes bad, I'll buy a Rpi Zero W.  
I figured out some stuff with part cooling and whatnot, readjusted the CAD, got the printhead semi-set up, and more! Well that's it for today.

Research and parts: 4.5 hrs  
CAD: 1.5 hrs

