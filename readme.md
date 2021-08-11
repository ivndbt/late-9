# LATE-9

## Overview

The LATE-9 is a multi-tap input keyboard based on mobile phones from the late '90s. LATE-9 is intended as a dev board with 18 buttons and an OLED screen, made by through-hole components only. With this, you can experiment [QMK](https://qmk.fm/) OLED capabilities with very little expense.

![LATE-9](https://i.imgur.com/QXycTC3.jpg "LATE-9 first proto")

Read the full development log on my website: [rookiebwoy.eu](https://www.rookiebwoy.eu/projects/late-9/late-9.html).


## In this repo

Here you can find the gerbers I used to manufacture the LATE-9.

![LATE-9 PCB](https://i.imgur.com/NtRZ4ew.png "LATE-9 PCB front and back")
PCB's frontside and backside.


## Description

+ Total PCB dimensions are 97.63mm x 47.62mm


## BOM

|Qty    |Description                            |
|------:|:--------------------------------------|
|1x 	|Pro-Micro (or clone with ATmega32u4)   |
|1x 	|SSD1306 0.91" 128x32 IIC OLED Screen   |
|18x    |Diodes THT do-35 1N4148                |
|18x	|Button switch 4 pin 6mm x 6mm	        |


## Firmware

You can find the QMK Firmware for LATE-9 on the official QMK repository at [this link](https://github.com/qmk/qmk_firmware/tree/master/keyboards/late9). (**waiting for approval, check out my fork**)


## References

Here some links to discussions/articles that I used for achieve this project:

+ @drashna comment to [this reddit thread](https://www.reddit.com/r/olkb/comments/dngjt8/tap_dance_triple_tap_example/) for triple tap dance function
+ [splitkb.com](https://docs.splitkb.com/hc/en-us/articles/360013811280) for the walkthrough about display your own logo on OLED screens

