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


