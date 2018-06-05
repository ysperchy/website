---
layout: default
title: Racing game
permalink: /racing/
exclude: true
categories: racing
---

{:.text-center}
### RoadFighter Android <br> (a formally developed game)

Welcome to the RoadFighter Android site, in here you can find specs, screenshots, details and download links of this project.

**--About--**

RoadFighter is a remake of the old NES (nintendo entertainment system) [game][game], it was programmed for the Android platform using the [Rodin][rodin] plugin on the [Eclipse IDE][eclipse]. Its logic module (rules and behavior) was entirely developed in a formal fashion as to provide a bug-free software.

It used the [EventB2Jml][eventb2jml] tool to translate from [EventB][eventb] code to [JML][jml] and onto Java code.

You can read the [article] detailing the SW design pattern used, technologies employed, specifications of the game as well as details on its implementation and results.

**--Screenshots--**

[![][screenshot1]][screenshot1]{:.img-small.thumbnail} | [![][screenshot2]][screenshot2]{:.img-small.thumbnail }

<br>
**--Links and Instructions--**

- Eclipse code [LINK][eclipse-code]
- Android Studio code [LINK][android-code]
- Rodin code [LINK][rodin-code]
- APK installer [LINK][installer]

Download the eclipse code and export it as a project in Eclipse, right-click in its project entry to the left and select _Run as Android Application_. The project was compiled against Android API version 16 and 17 using OpenGL headers (they must be installed).

You can also download the logic module of the game and translate it to JML (not necessary to run the game from eclipse) using Rodin and the EventB2Jml tool. Just export it as a project in Rodin, install the EventB2Jml in Rodin, select the project entry to the left and click the menu bar entry called _EventB2Jml_ and select translate!

In case you don't want to deal with code, we provide an APK file for direct installation into the Android Device (with OS v2.3 or later).

**--Controls--**

All possible interactions with the application are touch screen events, the image below details their position:

[![][controls]][controls]{:.img-small.thumbnail.float-left} 

||**L:** | Lean the car to the left  | (Hold)
||**R:** | Lean the car to the right | (Hold)
||**H:** | High acceleration         | (Touch)
||**A:** | Low acceleration          | (Touch)
||**B:** | Break                     | (Touch)

{:.text-block}
<br>
**--Authors--**

_Salim Perchy:_ email yamil-salim dot perchy at inria dot fr

_Néstor Cataño:_ email nestor dot catano at gmail dot com

[game]:       http://en.wikipedia.org/wiki/Road_Fighter
[rodin]:      https://sourceforge.net/projects/rodin-b-sharp/
[eclipse]:    http://www.eclipse.org/
[eventb2jml]: https://arxiv.org/pdf/1309.2339.pdf
[eventb]:     http://wiki.event-b.org/
[jml]:        http://www.eecs.ucf.edu/~leavens/JML/

[article]:      ../assets/pdf/formal_game.pdf
[screenshot1]:  ../assets/img/racing-screenshot1.png
[screenshot2]:  ../assets/img/racing-screenshot2.png
[controls]:     ../assets/img/racing-controls.png
[eclipse-code]: ../assets/other/RoadFighter-Eclipse.zip
[android-code]: ../assets/other/RoadFighter-Android.zip
[rodin-code]:   ../assets/other/RoadFighter-EventB.zip
[installer]:    ../assets/other/RoadFighter-Android.apk
