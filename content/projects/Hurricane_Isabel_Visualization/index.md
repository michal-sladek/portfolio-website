---
title: "Hurricane Isabel visualization"
weight: 3
draft: false
description: ""
summary: "An interactive visualisation of the 2003 hurricane Isabel dataset."
categories: ["JavaScript", "team"]
---

[link](https://kaslonat.pages.fel.cvut.cz/hurricane/)

An interactive visualisation of a single time frame of the 2003 hurricane Isabel dataset (specifically air temperature,
wind direction and wind speed). 

This project was created by me and my colleague. In my portion of the implementation I focused on stream tubes (objects that represent wind direction and speed) 
as well as the color map legend. The implementation is done using JavaScript and the objects are drawn using the **Three.js** library.

{{< figure
    src="gallery/showcase.png"
    >}}

Hurricane Isabel data produced by the Weather Research and Forecast (WRF) model, courtesy of NCAR, and the U.S. National Science Foundation (NSF). 
