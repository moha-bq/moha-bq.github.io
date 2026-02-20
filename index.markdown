---
title: My Projects
layout: default
---

<br>
<br>

<div style="text-align: center;">
<h1> Medit </h1>
<h3> My personal C/C++ editor </h3>
</div>

As a learning experience and a service to myself, I decided to make a code editor tailored to my needs and habits. It is still a work in progress though it is very much in a usable state.

Features: 
* Basic text editing: Copy/Paste, Undo/Redo, UTF-8, Find and Replace, ...
* Syntax highlighting
* Word complete
* Multi-cursor edit
* Auto-indentation: The programmer shall never indent code again!
* Build and navigate errors (Only MSVC output is supported for now)
* Search symbols and jump to their definition
* Fast (Loads and parses mackron/miniaudio.h with no visible delays)

You can see it in action in this video: 

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/s4VdSb1_dxQ?si=RYwg0Dg84Zx7vyow" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<br>

It was written in C++. It uses WIN32 for the platform layer(windowing, memory, filesystem,... etc), D3D11 to draw rectangles and Freetype for glyph rasterization  and TTF parsing.

<div style="text-align: center;">
<a href="https://github.com/moha-bq/Medit-Release/releases/tag/Medit" class="my_btn">Download Medit</a>
</div>

<br>

* * * 

<br>
<br>

<div style="text-align: center;">
<h1> 3D Demo </h1>
<h3> Implementation of different lighting algorithms, particle systems and skeletal animation</h3>
</div>


Features:

* Shading: Forward, Deferred, Tiled Forward, Tiled Deferred
* Light culling for Tiled variants is done on GPU usin a Compute Shader.
* 2.5 Light culling (as described in Takahiro Harada paper)
* Point, Spot and directional lights
* Blinn-Phong lighting model
* Normal mapping
* Simple sky/sun model (interpolating between colors using elevation of view direction)
* Particle effects
* Skeletal animation (Skinning is done in Vertex Shader)
* Editor UI
* Custom 3D Gizmo
* Instrumentation-based CPU and GPU profiler
* Custom 3D model binary format (supports geometry, materials, textures and animation)


You can see it in action in this video: 

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/TmroTbdkY5I?si=-UWbF91SeLwIYzjV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></div>
<br>

Written in C++. It uses WIN32, D3D11, Freetype, stb_image and Dear Imgui. Blender was used through its Python interface to write a custom 3D model binary format which supports geometry, materials, textures and animation data.

<div style="text-align: center;">
<a href="https://github.com/moha-bq/Demo3D/releases/tag/Demo-Release" class="my_btn"> Download demo</a>
<a href="https://github.com/moha-bq/Demo3D" class="my_btn"> Source code</a>
</div>

<br>
* * *


<br>
<br>

<div style="text-align: center;">
<h1> Virtual Memory Simulator</h1>
<br>
<!-- <h3> School project </h3> -->
</div>

As part of a school project, I developed a system that provides a general purpose allocator on top of a page allocation and virtualization layer.
The OS(implemented as a thread) takes alloc/free requests from processes(implemented also as threads). 
The system also serves network queries by returning a TARGA image representing the memory state of the system or of a process. 
It also uses steganography to conceal information about the client requests in the returned images.

<div style="text-align: center;">
<img src="https://github.com/moha-bq/vmem_simulator/raw/master/imgs/arch.png" />
</div>
<br>

Written in C using POSIX API for multi-threading and sockets.
 
 
<div style="text-align: center;">
<a href="https://github.com/moha-bq/vmem_simulator" class="my_btn"> Source code</a>
</div>


<br>
* * *

<br>
<br>

<div style="text-align: center;">
<h1> Jelly Couple</h1>
<h3> Android game about controlling two jellys at the same time</h3>
</div>

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/B9TVaaU090k?si=75y2VLyYowQwkpl5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<br>

Written in C++ using Cocos2Dx.

<div style="text-align: center;">
<a href="https://github.com/moha-bq/Jelly-Couple" class="my_btn"> Source code</a>
</div>

<br>

* * *


<br>
<br>

<div style="text-align: center;">
<h1> Miscellaneous</h1>
<h3> Other projects, prototypes and unfinished works</h3>
</div>

The following video show a FPS prototype, some car physics and a Tilemap editor: 

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/vC1n0iNAx38?si=wOpHFLYN1UVfyoOQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<br>

You can find my other projects on my github:

* Software renderer with perspective-correct texture mapping - C++, SIMD using SSE2
* Raytracer - C++ 
* LearnD3D_Demo: Implementation of stable cascaded shadow maps - C++, D3D11
* T-Spline(NURBS with T-junctions) editor and visualizer - C++, SDL2, OpenGL3
* And many others...
<div style="text-align: center;">
<a href="https://github.com/moha-bq?tab=repositories" class="my_btn"> View on Github</a>
</div>