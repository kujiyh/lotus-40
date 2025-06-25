---
title: Lotus 40
author: kuji
description: 40% keyboard with oled
created: 2025-06-23
---
# june 23

mostly just did research on keyboard layouts, what components to use, what is and isn't feasible (power draw etc.) and [how to add oled screens](https://www.reddit.com/r/MechanicalKeyboards/comments/5xubd7/adding_oled_display_to_your_build_using_qmk/) (SSD1306) to a keyboard.

finished keyboard layout: 

![image](https://github.com/user-attachments/assets/51d3bd32-1b42-4540-a29f-3105bcd739a0)

installed KiCad and played around with it to learn some of its functions

time spent: ~ 1.5 hr

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


