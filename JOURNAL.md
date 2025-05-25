---
title: "Liqued Propane Thermal Sensor"
author: "Your name (name or slack username)"
description: "Uses an infrared thermal sensor array to identify how full a propane tank is"
created_at: "2025-05-25"
---

# May 25: Beginning research and brainstorming
Session length: 2 hours

This session was mostly focused on deciding what thermal sensor and microcontroller to use. I have tentatively decided on the MLX90640 for the thermal sensor. It is a 32x24 array of infrared sensors.
I debated about going with a 16x12 array, but I decided that the additional resolution would be better, and the 32x24 doesn't cost that much more. The sensor appears to be ~$30, I still need to compare vendors and find the best price.
For the microcontroller, I'm thinking about the ESP32-H, but I need to do a little more research before I decide for sure. I want somthing that suports zigbee.

I also created a basic list of requirements of the PCB and case:

**PCB**
+ Thermal sensor
  + MLX90640
+ Microprocessor
  + Preferably Zigby
  + Alternatively wifi
    + Need to check signal strength on that side of the house
+ Battery
+ Solar panel



**Case**
+ Some degree of waterproofness
  + Not submergabul, but withstand heavy rain
+ Mount to something
  + Options:
    + Side of the house
      + This might interfere with the effectiveness of solar panels due to shade
    + Pole stuck in the ground
  + Should withstand moderate to heavy winds

 Finally, I set up the git repository and journal file. Probably should have have done this first, but at least I did it before I have files to commit.
