---
title: Whale Tracking Hackday
description: This is the description of our sample project
date: "2024-04-30T12:00:00-07:00"
jobDate: 2024
work: [python, drone, computer vision]
techs: [python, drone, computer vision, deep learning]
designs: []
thumbnail: whale-hackday/whales.jpg
projectUrl: http://www.mlsquamish.ca/
---

I organised and took part in a [MLSquamish](http://www.mlsquamish.ca/) hackday, aimed to support the research efforts of biologist [David Gaspard](https://www.linkedin.com/in/david-gaspard-79bb29239), who focuses on assessing the health of humpback whales. Gaspard's research involves monitoring the body mass of these whales over time, as it serves as an indicator of their environment's health and their hunting success.
 
Traditionally, David has manually reviewed drone footage to select the most suitable images of each whale. Then, he utilizes photogrammetry software to estimate the body mass of the whales by measuring multiple widths down the length  of the whale.

Recognizing the labor-intensive nature of this process, the machine learning community collaborated to explore the potential of computer vision to streamline aspects of Gaspard's work.

Through the utilization of a YOLO model, the team endeavored to automate the identification of individual whales within the drone footage. Additionally, a proprietary algorithm was developed to identify optimal frames showcasing maximum visibility of the whales, thus enhancing the efficiency of data collection and analysis.
