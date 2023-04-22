---
title: "NavMesh Pathfinder Tech Demo "
excerpt: "<img src='/images/navmesh_banner.png'><br/><i>Solo Developer / C++ / Custom Engine<i>"
author_profile: false
collection: portfolio
---

<iframe width="480" height="270"
src="https://www.youtube.com/embed/aFLzpxjzieY&autoplay=1" &autoplay=1>
</iframe>

This NavMesh Pathfinder is built in [Prime Engine](https://sites.google.com/site/artemscode/primeengine) (a custom engine developed by Artem Kovalovs). I imported a triangulated NavMesh from Maya into the Engine and implemented A* algorithm as pathfinder. I also developed a third-person character controller and camera. Lastly, I implemented some AI behaviours to make it a hide-and-seek mini game.

### Tech Stack
C++, Prime Engine, Visual Studio, Lua

### Development Time
Dec 2022 (1 month)

### NavMesh
<img src='/images/navmesh_debugrender.png'>
* Imported a static NavMesh from Maya and transformed it into a graph
    
### Path Smoothing
<img src='/images/navmesh_upath.png'>
* Implemented funnel algorithm to smooth paths