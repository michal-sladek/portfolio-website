---
title: "Other projects"
weight: 7
draft: false
description: ""
showTableOfContents: true
summary: "A collection of smaller projects."
categories: ["Blender", "Maya", "UE5", "C++", "team", "solo"]
---

{{< lead >}}
A collection of smaller projects.
{{< /lead >}}

## Particle-based fluid simulation
{{< keywordList >}}
{{< keyword >}} UE5 {{< /keyword >}}
{{< keyword >}} C++ {{< /keyword >}}
{{< keyword >}} Team {{< /keyword >}}
{{< /keywordList >}}

{{< button href="https://github.com/michal-sladek/Fluid-simulation/tree/main" target="_blank" >}}
{{< icon "github" >}} project files
{{< /button >}}
<br><br>

A fluid simulation in Unreal Engine 5 based on the paper [*Particle-Based Fluid Simulation for Interactive Applications (Müller et al.)*](https://matthias-research.github.io/pages/publications/sca03.pdf)

The implementation calculates pressure and density at the position of each particle and uses these scalar fields to
calculate forces between particles. More information on the approach and implementation can be found in our
[report](/fluid_simulation_report.pdf).

{{< video
    src="Fluid_simulation.mp4"
    loop=false
    muted=false
>}}

## Blender
{{< keywordList >}}
{{< keyword >}} Python {{< /keyword >}}
{{< keyword >}} Solo {{< /keyword >}}
{{< /keywordList >}}

For anything 3D-related, I really like using Blender. I especially enjoyed working with material nodes and 
creating procedural materials in my personal projects.

### procedural materials

{{< gallery >}}
  <img src="gallery/procedural_materials_blackhole.png" class="grid-w100" />
  <img src="gallery/procedural_materials_icosphere.png" class="grid-w50" />
  <img src="gallery/procedural_materials_atlas.png" class="grid-w50" />
  <img src="gallery/procedural_materials_pillar.png" class="grid-w100" />
  <img src="gallery/procedural_materials_rose.png" class="grid-w100" />
{{< /gallery >}}

### scripting

{{< gallery >}}
  <img src="gallery/scripting_dodecahedron.png" class="grid-w100" />
  <img src="gallery/scripting_sierpinski.png" class="grid-w100" />
{{< /gallery >}}

### minimalistic

{{< gallery >}}
  <img src="gallery/minimalistic_racetrack1.png" class="grid-w100" />
  <img src="gallery/minimalistic_racetrack2.png" class="grid-w50" />
  <img src="gallery/minimalistic_island.jpg" class="grid-w50" />
  <img src="gallery/minimalistic_table.png" class="grid-w100" />
  <img src="gallery/minimalistic_space.png" class="grid-w100" />
{{< /gallery >}}

### other

{{< figure
    src="gallery/other_architectural_visualization.png"
    alt="archviz"
    caption="A very early visualization of a production hall."
>}}

## Maya
{{< keywordList >}}
{{< keyword >}} Solo {{< /keyword >}}
{{< /keywordList >}}

I also tried using Autodesk Maya for its history-based approach to 3D modeling, but I found that 
Blender's workflow suits me better.

{{< gallery >}}
  {{< figure src="gallery/maya_landmine1.png" figureClass="grid-w100" >}}
  {{< figure src="gallery/maya_landmine2.png" figureClass="grid-w100" caption="TM-46 Anti Tank Blast Mine">}}
{{< /gallery >}}

<br>

{{< gallery >}}
  {{< figure src="gallery/HoN2.jpg" figureClass="grid-w100" >}}
  {{< figure src="gallery/HoN4.jpg" figureClass="grid-w50" caption="Replica of the Hierarchy of Needs 3D model, original by [Seth Perlstein](https://www.artstation.com/artwork/obdQLJ?album_id=8340349).">}}
  {{< figure src="gallery/HoN3.jpg" figureClass="grid-w50" >}}
  {{< figure src="gallery/HoN_wireframe.png" figureClass="grid-w50" >}}
  {{< figure src="gallery/HoN1.jpg" figureClass="grid-w50" >}}
{{< /gallery >}}

## Raytracing projects
{{< keywordList >}}
{{< keyword >}} C++ {{< /keyword >}}
{{< keyword >}} Solo {{< /keyword >}}
{{< /keywordList >}}

Ray tracing is more relevant than ever thanks to modern, high-performance GPUs.

I have worked on two ray tracing projects. The first is a simple CPU-based ray tracer, which served as a great
learning exercise to understand the basic principles.

{{< gallery >}}
  <img src="gallery/raytracing1.png" class="grid-w50" />
  <img src="gallery/raytracing2.png" class="grid-w50" />
  <img src="gallery/raytracing3.png" class="grid-w50" />
  <img src="gallery/raytracing4.png" class="grid-w50" />
{{< /gallery >}}

The second project focuses on optimizing the BVH (Bounding Volume Hierarchy) data structure used to 
accelerate ray–triangle intersection tests. The approach is based on the paper [*Fast Insertion-Based Optimization of
Bounding Volume Hierarchies (Bittner et al.)*](https://dcgi.fel.cvut.cz/wp-content/wpallimport-dist/publications/pdf/publications-2013-bittner-cgf-fiobvh-paper.pdf). 
It identifies inefficient nodes in the BVH using a cost heuristic, removes them, and reinserts their 
children in a way that minimizes the overall tree cost.

More information on this project can be found in my [report](/BVH_optimization.pdf).

Due to academic integrity policies, I am unable to share the source code for these implementations.