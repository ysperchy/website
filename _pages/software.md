---
order: 1
layout: default
title: Software
permalink: /software/
exclude: false
---

**Software:**

- A small 3D game engine I coded:
  + {% for page in site.pages %} {% if page.exclude and page.categories contains 'engine' %} [LINK]({{ page.url }}) {% endif %} {% endfor %}
- A racing game developed for Android (Unpublished):
  + {% for page in site.pages %} {% if page.exclude and page.categories contains 'racing' %} [LINK]({{ page.url }}) {% endif %} {% endfor %}
- A C++11 library for simulating constraint systems (Published):
  + {% for page in site.pages %} {% if page.exclude and page.categories contains 'constraints' %} [LINK]({{ page.url }}) {% endif %} {% endfor %}
- Automatic Music Generation by Context-Free Grammars (Published):
  + [ZIP][music-gen]
- An implementation of the OSC protocol for Mozart (Published):
  + [LINK][osc-mozart]
- A model checker for the NTCC programming language (Published, with other authors):
  + [ZIP][ntcc-checker]
- A TCP multi-party self-competing AI (based in constraint programming) solver of randomly generated Sudominokus in the Mozart language:
  + [ZIP][sudo-solver]

[formal-racing]:    http://google.com
[constraints-lib]:  http://google.com
[music-gen]:        /assets/other/music_grammars.zip
[osc-mozart]:       http://cic.javerianacali.edu.co/wiki/doku.php?id=grupos:avispa:osc-oz
[ntcc-checker]:     /assets/other/ntccModelChecker.zip
[sudominoku]:       http://www.ludism.org/attachments/ppwiki/Sudominoku.pdf
[sudo-solver]:      /assets/other/sudominoku.zip
