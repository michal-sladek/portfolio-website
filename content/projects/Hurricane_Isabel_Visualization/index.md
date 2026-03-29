---
title: "Hurricane Isabel visualization"
showDate: true
date: 2025-01-25
weight: 3
draft: false
description: ""
summary: "An interactive visualisation of the 2003 hurricane Isabel dataset."
categories: ["JavaScript", "team"]
---

{{< button href="https://kaslonat.pages.fel.cvut.cz/hurricane/" target="_blank" >}}
{{< icon "link" >}} try it
{{< /button >}}
<br><br>

An interactive visualisation of a single time frame of the 2003 hurricane Isabel dataset (specifically air temperature,
wind direction and wind speed). 

This project was created by me and my colleague. In my portion of the implementation I focused on stream tubes (objects that represent wind direction and speed) 
as well as the color map legend. The implementation is done using JavaScript and the objects are drawn using the **Three.js** library.

{{< video
    src="Hurricane_showcase_cropped.mp4"
    loop=false
    muted=false
>}}

{{< figure
    src="gallery/showcase.png"
    >}}

Hurricane Isabel data produced by the Weather Research and Forecast (WRF) model, courtesy of NCAR, and the U.S. National Science Foundation (NSF). 
