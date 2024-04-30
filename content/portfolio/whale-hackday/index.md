---
title: Whale Tracking Hackday
description: This is the description of our sample project
date: "2024-04-30T12:00:00-07:00"
jobDate: 2024
work: [python, computer vision]
techs: [python, computer vision]
designs: []
thumbnail: whale-hackday/whales.jpg
projectUrl: https://www.sampleorganization.org
---

I organised and took part in a [MLSquamish](http://www.mlsquamish.ca/) Hackday.
In this event we were helping a biologist, [David Gaspard](https://www.linkedin.com/in/david-gaspard-79bb29239) conduct research on whale health.
He studies the body mass of humpback whales over time, as healthy mass indicates their environments health and their ability to succesfully hunt.

Drone imagery is collected, and David manually watches the footage. choosing the best few pictures of each whale.
Then using some photogrammetry software, he is able to make measurements along the whales length, estimating it's body mass.

This is a labour intensive research, our machine learning community got together to attempt to use computer vision to help automate some of this work.

we trained and used a YOLO model to track inidividual whales in the drone footage, and used a custom algorithm to detect the best frame when the whale is most visible.