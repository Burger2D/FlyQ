```
---
title: "FlyQ"
author: "Burger"
description: "Fixed-wing ultralight autonomous UAV"
created_at: "2025-06-01"
---
```

# FlyQ
An Ultralight fixed wing autonomous UAV.

## June 1st
Project inception, I researched on the different types of drones and decided what I want to build. Here is all of the research condensed down for reader's consumption.
Project goals:
 - ultralight
 - should have autonomous flying capabilities with failsafe RTH
 - medium range (4-8 km)
 - cameras
 - fixed wing
 - durable
 
Considering all goals, I have decided:
It is going to be a flying wing design with single rotor at the back (pusher).

Time spent: ~3-4 hrs (research)

## June 2nd
Agenda: Airframe
I am researching on the airframe, how it's going to be made, design desisions, extra provisions etc.
I have decided it is best to buy a commercial frame for it being made out of molded EPP foam goes a long way towards crash resistance (EPP foam compresses and does not break (shatter) like defron sheets if I were to DIY it). There are a few downsides to this, notablily this kinda makes future customization on the drone itself a bit difficult but I think that is acctable considering the other factors.
Time spent: ~2-3 hrs
I had some more time today so I have decided to look into which commercial frame that is readyly available here that can be bought.
I am going for a single prop design as it is cheaper due to only one motor being persent and the cruise current being lower for the same reason.
I've chosen the 'Reptile S800 V2 Flying Wing'
![Reptile S800 V2 Flying Wing Racer Kit](https://cdn11.bigcommerce.com/s-3fd3md1ghs/images/stencil/1280x1280/products/36148/21431/FR-098erewr__81961.1727956334.jpg?c=2)
I chose this due to it's avaibility in an Indian store and alignment with the project goals. It's made with EPP ensuring the drone dosen't break on impact.
Time spent: ~3 hrs

## June 3rd
Agenda: Flight Control systems
I'll try to decide which control systems to put on drone as per my budget and other factors like compatibility with Ardupilot/INAV (autonomy), ELRS etc.
I've decided to go with the "SpeedyBee F405 WING MINI Fixed Wing Flight Controller"
![](https://cdn11.bigcommerce.com/s-fhxxhuiq8q/images/stencil/1280x1280/products/240/1367/SB_WING-MINI-1__04828.1707096339.jpg?c=2)
![](https://store-fhxxhuiq8q.mybigcommerce.com/product_images/img_SpeedyBee_F405_WING_MINI/SB_F405-WING-MINI-16.jpg)
It is very light at 23g and supports INAV and Ardupilot. It is well within budget at US$35.99 (around $47 USD in Indian sites)
I've checked out some 40 FCs but this seems to be the best in it's capabilities and price based on the STM32F405. It has integrated IMU, barometer and OSD.

Also selected the GPS module to be used with this FC, it's a Flywoo GOKU GM10 Mini V3 GPS
![](https://rcmumbai.com/cdn/shop/files/e85e2d6c7765468327dd6c4a101d5d48_1.jpg?v=1746496476&width=810)
Time spent: ~4 hrs

## June 4th
Agenda: Other parts
Selecting other parts in accordance with compatibilty with FC, budget and project goals.
### Motor
XING 2205 FPV Motor (12/M2) - 2300KV
![](https://robu.in/wp-content/uploads/2017/10/robu-1-20.jpg)
Within budget, efficient rating.
### ESC
Readytosky 40A 2-6S Multi-Rotor UAV Drone ESC
![Readytosky 40A 2-6S Multi-Rotor UAV Drone ESC, Brushless Electronic Speed Controller for F450, X500, S500, ZD550 RC Helicopters and Quadcopters, OPTO Design, Lightweight 33.2g.](https://cdn11.bigcommerce.com/s-3fd3md1ghs/images/stencil/500x659/products/36110/21347/E-138-N94__21508.1727675782.jpg?c=2)
Also within budget and has sufficient rating.
### ELRS RX
![](https://rcmumbai.com/cdn/shop/files/elrs-r24-v_2_2.jpg?v=1746496897&width=1946)
MATEKSYS ELRS 2.4GHz Vario Receiver ELRS-R24-V
### Camera DVR
https://shop.runcam.com/runcam-mini-fpv-dvr/![Image 1](https://cdn10.bigcommerce.com/s-m8o52p/products/284/images/1105/RUNCAM-DVR-S-700__61064.1545124056.500.750.jpg?c=3)
It is a RunCam Mini FPV DVR, fits right in budget.

### Camera
![Buy Caddx Ant Lite Analog Camera at Best Price](https://robu.in/wp-content/uploads/2023/04/ss.jpg)
It's a Caddx Ant Lite Analog Camera (FPV Cycle Edition) (4:3), cheapest while having great quality.

Time spent: ~6-8 hrs

## June 5th
Remaining electronic stuff for the drone.

### VTX![](https://cdn11.bigcommerce.com/s-fhxxhuiq8q/images/stencil/1280x1280/products/136/1271/tx800-1__98008.1698739675.jpg?c=2)
 SpeedyBee TX800 5.8 GHz VTX
### Battery
![](https://aerokartindia.in/wp-content/uploads/2023/06/1366608-1.JPG.png.jpg)
 Samsung INR18650-35E 7.4V 3500mAh 2C 2S1P Li-ion Battery Pack
### VTX Antenna
![Buy Pagoda 2 Antenna 5.8GHz with cover Online at Best Price in India](https://robu.in/wp-content/uploads/2020/01/P-Antenna1.jpg)
Pagoda 2 Antenna 5.8GHz with cover

Time spent: ~4-5 hrs

## June 6th
Ground station stuff

### VRX
![5.8G UVC OTG Android AV Phone Receiver](https://robu.in/wp-content/uploads/2017/10/5.8G-UVC-OTG-Android-AV-Phone-Receiver.png)
5.8G UVC OTG Android AV Phone Receiver

> ## Budget check (retail prices at 1USD = 85.76INR)
>  Airframe - $49.05
>  FC - $39.77
>  GPS - $19.80
>  Motor - $9.32
>  ESC (!!) - $8.71
>  ELRS RX - $29.71
>  DVR - $17.99
>  Camera - $18.80
>  VTX - $37.03
>  Battery - $12.57
>  Antenna (drone) - $4.19
>  ### Total till now - $ 246.94
Prices taken from best retailers found.

Time spent: 4.5 hrs

## June 7th
We can do better. Revamping materials and stategry to bring this greatly under budget.