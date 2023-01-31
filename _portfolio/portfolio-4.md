---
title: "Game Engine Development"
excerpt: "<img src='/images/gameengine_banner.png'><br/><i>Solo Developer / C++ / Custom Engine<i>"
author_profile: false
collection: portfolio
---

### Overview
These technical demos are built in [Prime Engine](https://sites.google.com/site/artemscode/primeengine) (a custom engine developed by Artem Kovalovs).

### Tech Stack
C++, Visual Studio, DirectX 11, 3D Graphics and Physics

### 3D Physics and Collision
<iframe width="480" height="270"
src="https://www.youtube.com/embed/SryMYZlaygs">
</iframe>

* Developed 3D physics component with collision detection and gravity
* Implemented sphere collider for characters and AABB collider for static objects

### View Fustum Culling
<iframe width="480" height="270"
src="https://www.youtube.com/embed/9NLnsgOIQcI">
</iframe>

* Created view fustum component for the camera
* Performed intersection tests between view fustum and AABB of objects

### Wind Shader
<iframe width="480" height="270"
src="https://www.youtube.com/embed/ISrmnJjMNjQ">
</iframe>

* In this demo, I added wind source to camera and two soliders. We can see wind deformation become strongly when solider/camera are close to the meshes. 
* I passed texture coordination into the DirectX 11 rendering pipepline and modified its vertex shader to achieve deformation.