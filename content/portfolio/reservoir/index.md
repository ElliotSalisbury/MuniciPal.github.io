---
title: Satellite Reservoir Monitoring
description: This is the description of our sample project
date: "2022-06-05T12:00:00-07:00"
jobDate: 2022
work: [python, satellite, computer vision, geospatial]
techs: [python, satellite, computer vision, geospatial]
designs: []
thumbnail: reservoir/reservoir.gif
---

I leveraged Sentinel-2 and Landsat-8 data to estimate the volume of water in remote reservoirs. By developing a custom computer vision algorithm, I was able to monitor changes in water levels over time, thereby informing emergency response efforts and shaping healthcare policy in vulnerable communities.
![graph of reservoir volume changing over time](graph.png)

### Methodology

* Collect, reproject, and crop, imagery from Sentinel-2 and Landsat-8
* Use NDWI to identify the body of water
* monitor the shoreline of the reservoir, observing when the volume increases or decreases.
* detect cloudcover and only monitor the parts of the shoreline that are visible. 