---
title: "Traffic sign generator"
weight: 1
params: 
  dateString: "2025 - ongoing" 
draft: false
description: ""
summary: "An application for generating 3D meshes of vertical traffic signs from 2D vector data."
categories: ["C++", "solo"]
---

A C++ application for generating 3D meshes of vertical traffic signs from 2D vector data, developed as part of
my master’s thesis. 

The project focuses on procedural generation of polished 3D geometry including supporting structures. Over 30 parameters
are used to set dimensions and spacing of supports, traffic signs and their mounts and levels of detail of the
generated geometry.

It is currently in progress, with additional results and documentation to be published upon completion.

Some WIP results:
{{< gallery >}}
  {{< figure src="gallery/Zone_30_Front.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Zone_30_Back.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Zone_30_Result_Front.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Zone_30_Result_Back.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Zone_30_Geometry_Front.png" figureClass="grid-w33" caption="Pole support." >}}
  {{< figure src="gallery/Zone_30_Geometry_Back.png" figureClass="grid-w33" >}}
{{< /gallery >}}

<br>
<br>

{{< gallery >}}
  {{< figure src="gallery/Portal_Front.png" figureClass="grid-w50" >}}
  {{< figure src="gallery/Portal_Back.png" figureClass="grid-w50" >}}
  {{< figure src="gallery/Portal_Result_Front.png" figureClass="grid-w50" >}}
  {{< figure src="gallery/Portal_Geometry_Front.png" figureClass="grid-w50" >}}
  {{< figure src="gallery/Portal_Result_Back.png" figureClass="grid-w50" caption="Portal support." >}}
  {{< figure src="gallery/Portal_Geometry_Back.png" figureClass="grid-w50" >}}
{{< /gallery >}}

<br>
<br>

{{< gallery >}}
  {{< figure src="gallery/HalfPortal_Front.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/HalfPortal_Back.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/HalfPortal_Result_Front.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/HalfPortal_Result_Back.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/HalfPortal_Geometry_Front.png" figureClass="grid-w33" caption="Half portal support." >}}
  {{< figure src="gallery/HalfPortal_Geometry_Back.png" figureClass="grid-w33" >}}
{{< /gallery >}}

<br>
<br>

{{< gallery >}}
  {{< figure src="gallery/Two_Pole_Front.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Two_Pole_Back.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Two_Pole_Result_Front.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Two_Pole_Result_Back.png" figureClass="grid-w33" caption="Pole support with multiple poles." >}}
  {{< figure src="gallery/Two_Pole_Geometry_Front.png" figureClass="grid-w33" >}}
  {{< figure src="gallery/Two_Pole_Geometry_Back.png" figureClass="grid-w33" >}}
{{< /gallery >}}

<br>

The real world reference pictures were taken from [*Google Maps*](https://www.google.com/maps).