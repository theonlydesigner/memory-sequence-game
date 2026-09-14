---
title: "memory sequence game"
author: "theonlydesigner"
description: "a led memory game with an arduino nano, dc barrel jack, jst connector, buzzer/vibration motor and more!"
created_at: "2026-09-15"
---

# september 15(log 1): the crazy marathon session & schematic start
pulled off an absolutely insane one-day work session today to get this entire board designed from scratch. started out by dropping in the core symbols to the schematic: leds, tactile buttons, current limiting resistors, the arduino nano and a buzzer. created the net labels and started the initial wiring spaghetti. spent some time brainstorming the rest of the features and mapping out a solid plan [before i lose my mind later].

https://github.com/user-attachments/assets/3a849660-60fd-400a-b150-f533264552a7

**total time spent: 31 minutes**

# september 15(log 2): finalizing schematic & layout theory
after the initial brainstorming and a long break [because staring at raw schematics drains my soul], i added all the final peripheral components and wired them into the main matrix. spent some time visualizing the physical pcb layout so i don't paint myself into a corner later when it comes to trace routing.

https://github.com/user-attachments/assets/6e46e15e-fe6b-4ae6-a1a1-a7f3514cc424

**total time spent: 1 hour 17 minutes**

# september 15(log 3): pcb layout speedrun
locked in the finalized schematic and aggressively transitioned to the pcb editor. assigned footprints to every single component and started placing them according to my mental layout plan. it's basically just playing digital tetris but if you mess up the board doesn't actually work.

https://github.com/user-attachments/assets/c51fe556-855b-412e-b04d-bd3921c337f6

**total time spent: 1 hour 4 minutes**

# september 15(log 4): routing hell & final touches
finally finished the whole pcb routing and getting all the copper traces down. threw in some hack club silkscreen art because empty pcbs look boring. added a jst connector for a battery and threw in a dc barrel jack too [idk who would connect a desktop wall supply to a portable memory game lol, but i added an ldo voltage regulator just in case someone tries to fry it]. the board is finally done.

https://github.com/user-attachments/assets/89f49a14-93c5-45c5-82a5-db46f538ad68

**total time spent: 1 hour 19 minutes**

---
**total time worked to finish project designing: 4 hours 11 minutes** [fixed the final calculation because math is hard after a marathon session]
