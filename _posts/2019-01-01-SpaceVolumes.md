---
layout: post
author: Ubisoft Mtl
tags: [Ubisoft, Tools, Professional]
permalink: /Professional/:title:output_ext
desc: Create valumes inside of buildings for sound distortion
logo: Space_sections_1.jpg
title: Space volumes detection
imgpath: assets/images/ubisoft/
categories: work
back: /Professional/ubisoft.html
---

The sounds team uses volumes to modify the sounds. Making a stone room sound different then a wooden one, etc. These volumes where originally placed by hand trough a clunky interface. The request was to have a tool that could be run on an entity and generate volumes for them.  These did not have to be perfect but the closer the better. This way they only had to check and make small tweaks, speeding up their work.

The algorithm takes the entity and tries to detect the rough interior shapes. afterwards it tries to place the best fitting geometric shape before trying to merge similar shapes into bigger ones.
- 2 cubes next to each other get fused into one.
Afterwards it detects portals, like windows and doors and places special volumes there.

![Volumes]({{ page.imgpath | relative_url }}Space_sections_1.jpg)
-- *House model*
![Mesh]({{ page.imgpath | relative_url }}Space_sections_2.jpg)
-- *Interior volume results*