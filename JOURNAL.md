---
title: Lotus 40
author: kuji
description: 40% keyboard with oled
created: 2025-06-23
---

# Total time spent designing: 23 hours
# Total time spent assembling: TBA

# june 23

mostly just did research on keyboard layouts, what components to use, what is and isn't feasible (power draw etc.) and [how to add oled screens](https://www.reddit.com/r/MechanicalKeyboards/comments/5xubd7/adding_oled_display_to_your_build_using_qmk/) (SSD1306) to a keyboard.

finished keyboard layout: 

![image](https://github.com/user-attachments/assets/51d3bd32-1b42-4540-a29f-3105bcd739a0)

installed KiCad and played around with it to learn some of its functions

time spent: ~ 2 hr

# june 24

decided to go simple and use an arduino micro pro and a 128x32 i2c oled display
lotta time spent on figuring out whether the current would be a problem

thought i could make a hall effect magnetic pcb but that was way too hard lol
tried doing hotswap mx switches but didn't want to have to run a via for EVERY single switch, so ended up just opting for regular old soldered on switches

fininshed schematic and pcb (except adding logo) today tho i had nothing else to do

schematic:

![image](https://github.com/user-attachments/assets/20292e4b-2e47-4380-b39e-f41227bd368d)

pcb:

![image](https://github.com/user-attachments/assets/ff3f34cf-637d-4334-a6f5-d579f115ff23)

time spent: ~ 10 hr

# june 25

did some research on ways to build a case and where to buy components (jlc, aliexpress, etc.)
started a shopping list

![image](https://github.com/user-attachments/assets/6bebe3fb-ebc9-45f9-9b7f-74cf043c0baf)

time spent: ~ 1.5 hr

# june 26

fixed a bunch of pcb mistakes, tried for like 2 hours to make the board tray mount with pcb and plate screws, but gave up
decided on just gluing pcb to supports in the case 
almost finished cadded case today (fusion is hell)

![image](https://github.com/user-attachments/assets/63c8542b-e709-4dd7-9c51-0b833c2610a3)

time spent: ~ 4 hr

# june 27

lowkey did not feel very good after getting a vaccine so just researched how to write my own firmware using QMK 
https://docs.qmk.fm/newbs_getting_started 

time spent: ~ 1.5 hr

# june 28

found mistakes in original case design and tried to fix them, but just kept making things more complicated
decided to restart, opting for a wedge at the bottom of the board to give it its 5 degree tilt
took longer than it should have to design the rounded corners on the board...

![image](https://github.com/user-attachments/assets/ba6df84e-d967-4237-a48a-8e65c6531670)

used [swillkb](http://builder.swillkb.com/) to make the plate

![image](https://github.com/user-attachments/assets/c2b3bea5-8895-4035-9cf6-243abaca535f)

organized BOM (optimizing prices took longer than it should have since aliexpress has a million different vendors for the most obscure keyboard switch)

time spent: ~ 4 hr

# june 30

reduced details on case a little to avoid 3d printing issues

time spent: ~ 2 hr

