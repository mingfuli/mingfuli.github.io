---
title: "CPU Graphics Rendering Library"
excerpt: "<img src='/images/rasterizer-banner.png'><br/><i>Solo Developer / C++ / 3D Graphics Pipeline<i>"
author_profile: false
collection: portfolio
---

### Overview
This is a customized CPU graphics library which supports rasterization, three shading modes, texturing and Anti-Aliasing.

### Tech Stack
C++, 3D Graphics, Visual Studio, Windows APIs

### Development Time
Aug - Nov 2021 (3 month)

### Rasterization
<img src='/images/rasterizer-shader.png'>
<center><small>Gouraud shading vs Phong shading</small></center>
* Implemented transform matrix queue which supports local-world-view-projection-screen space transformation
* Incorporated flat, Gouraud, and Phong shading into the rendering library
    
### Texture and Anti-Aliasing
<img src='/images/rasterizer-aa.png'>
<center><small>Before SSAA vs After SSAA</small></center>
* Implemented image and procedural texturing with prospective correction
* Developed Supersampling Anti-Aliasing (SSAA) using Jitter algorithm