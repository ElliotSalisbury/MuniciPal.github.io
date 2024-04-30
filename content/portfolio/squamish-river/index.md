---
title: Squamish River Art
description: This is the description of our sample project
date: "2024-01-05T12:00:00-07:00"
jobDate: 2024
work: [python, geospatial, art]
techs: [python, geospatial, QGIS, LIDAR]
designs: [art]
thumbnail: squamish-river/river.jpeg
---

Revealing the underlying scars to the land as the ever-changing flow of the river Squamish cuts through the mountain valleys.
In its wake, it leaves behind ox bow lakes, and carved out meandering bends. 
Towards the mouth of the river, you can see our attempts to control the flow with a series of dikes protecting our town.

### Methodology

Processing BC Hydro LIDAR data with a custom terrain DTM interpolation algorithm in Python that avoids interpolating across the river width.

Then, the elevation of the river is subtracted from the terrains elevation, leaving the height of the terrain relative to the river and revealing the rivers' past.

Finally, it was colorized in QGIS, and made ready to print on canvas.
