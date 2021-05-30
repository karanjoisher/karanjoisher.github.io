---
layout: page
title: cross platform layer
description: A platform layer API, developed from scratch, that provides an interface for window creation, sound, input/output and graphics to develop applications on Windows and Linux
img: /assets/img/cross_platform_layer.png
importance: 1
category: work
---

## Demo video
<div class="aspect-ratio">
<iframe width="100%" height="100%" src="https://www.youtube-nocookie.com/embed/RHCYtrhFRr4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<hr>

## Source code
- [Github](https://github.com/karanjoisher/platform_layer){:target="\_blank"}
- [Final build](https://github.com/karanjoisher/platform_layer/releases/tag/v1.0){:target="\_blank"}

<hr>

## Features

- Window creating and software rendering
- Keyboard and mouse input
- OpenGL library loading
- Sound
- File and memory I/O

<hr>

## Technologies used

- <strong>Languages</strong>: C/C++, Python (for code generation), GLSL
- <strong>Libraries</strong>: Kernel32, User32, Graphics Display Interface (GDI), X Window Subsystem (X11), X Keyboard Extension Library (XKBLib), Windows Audio Session API (WASAPI), Advanced Linux Sound Architecture (ALSA)
- <strong>Tools</strong>: msvc compiler and debugger, RenderDoc, GDB