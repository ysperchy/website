---
layout: default
title: 3D engine
permalink: /engine/
exclude: true
categories: engine
---

## Educational Game Engine

{:.text-justify}
This is portal for a small game engine I wrote for teaching purposes. It's written in C and compiles in GNU/Linux, Mac OSX and Windows(through DirectX). It is intended for pedagogic ends, so usability and readability prime over performance and portability.

**Main features:**
- Texture integration (through [SDL_image][sdl-image]).
- Model loading (through [libassimp][assimp]).
- Font rendering (through [SDL_ttf][stdl-ttf]).
- Terrain creation and rendering with skyboxes (through heightmaps).
- Per-pixel lighting (through shaders).
- Particle system management
- Shadows (through [shadow mapping][shadows]).
- Collision detection (using the methods in [here][method1], [here][method2] and [here][method3]).
- Music and Sound FX (through [OpenAL][openal] and [libogg][libogg])

**Screenshots:**

[![][screenshot1]][screenshot1] | [![][screenshot2]][screenshot2] | [![][screenshot3]][screenshot3] | [![][screenshot4]][screenshot4]

<br>
**Downloads:**

- Linux [[ZIP][linux]]
- MacOS [[ZIP][mac]]
- Windows [[ZIP][windows]]

[sdl-image]:  http://www.libsdl.org/projects/SDL_image/
[assimp]:     http://www.assimp.org/
[sdl-ttf]:    http://www.assimp.org/
[shadows]:    https://en.wikipedia.org/wiki/Shadow_mapping
[openal]:     https://www.openal.org/documentation/OpenAL_Programmers_Guide.pdf
[libogg]:     https://xiph.org/ogg/doc/libogg/
[method1]:    https://books.google.fr/books?id=cZ0LAAAAQBAJ&pg=PA220&dq=calculate+bounding+ellipsoid&hl=fr&sa=X&ved=0ahUKEwin_perx7zbAhVIFCwKHUECBLkQ6AEIMzAB#v=onepage&q=calculate%20bounding%20ellipsoid&f=false
[method2]:    http://www.peroxide.dk/papers/collision/collision.pdf
[method3]:    http://blackpawn.com/texts/pointinpoly/default.html

[screenshot1]:  /assets/img/engine-screenshot1.png
[screenshot2]:  /assets/img/engine-screenshot2.png
[screenshot3]:  /assets/img/engine-screenshot3.png
[screenshot4]:  /assets/img/engine-screenshot4.png

[windows]:      /assets/other/engine-windows.zip
[linux]:        /assets/other/engine-linux.zip
[mac]:          /assets/other/engine-mac.zip
