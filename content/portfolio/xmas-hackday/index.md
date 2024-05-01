---
title: Christmas Tree Hackday
description: This is the description of our sample project
date: "2021-12-05T12:00:00-07:00"
jobDate: 2021
work: [python, hackday, computer vision]
techs: [python, raspberry pi, computer vision]
designs: []
thumbnail: xmas-hackday/output.gif
projectUrl: https://github.com/ElliotSalisbury/winter_hackday
---

I organised a [MLSquamish](http://www.mlsquamish.ca/) hackday to animate a Christmas tree's lights.
We used individually addressable RGB lights, connected to a raspberry pi running python scripts to control the lights.
We also connected a camera in order to use computer vision to spatially map out the lights.

### Methodology

* Turn each light on and off individually, and use the camera to take a picture of that single light.
* Rotate the tree 90 degrees, and repeat the process.
* identify the brightest spot in the image as the light, and collect it's x,y,z coordinates from the image space.
* The 3d positions are stored, and used in an animation loop. 