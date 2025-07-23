---
layout: post
author: Ubisoft Mtl
tags: [Ubisoft, Tools, Professional]
permalink: /Professional/:title:output_ext
desc: Cliff generation and terrain stitching
logo: Cliffs_2.jpg
title: Cliff generation
imgpath: assets/images/ubisoft/
categories: work
back: /Professional/ubisoft.html
---

Automatically place cliff and rocks on steep terrain areas based on user defined cliff sets. Making sure they don't trap players but also look nice. This is followed by blending the terrain with the procedural and manual placed rocks for a better transition between terrain and rocks.

- Some constraints were to avoid roads and rivers.
- Follow the sloped area. 
- Blend terrain with rocks for smooth transition
- Only rotate along the vertical axis for game play.

![Stiching]({{ page.imgpath | relative_url }}CLiffs_jeryce-dianingana-09.jpg)
-- *Terrain blending in to cliffs with stitching. Img By Jeryce Dianingana*
![Cliff]({{ page.imgpath | relative_url }}Cliffs_2.jpg)
-- *World example of generated cliffs*