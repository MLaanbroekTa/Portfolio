---
layout: post
author: NHTV
tags: [Education, Bachelor]
permalink: /Education/:title:output_ext
desc: Graduation project of my Bachelor 
logo: dungeonGen.png
title: Graduation project, Procedural dungeon gen
imgpath: assets/images/education/
categories: nonWork
back: school.html

youtubeId: 
    id0: uLiHWJP-GBg
    id1: DLXRJ8BdW4g
    id2: 5w2wr96WnAE
---
### Procedural dungeon generation
As graduation project I created procedural dungeon generator that enables users to rapidly prototype and tweak dungeons in both Houdini and Unity. The main goal was to create a working tool that is stable, fast, offer several levels of control while staying user friendly.
{% include youtubePlayer.html id=page.youtubeId.id0 %}

The generator for Houdini and Unity are separate tools, but both work in the same way. The Houdini version gives users more control over the design while the Unity version offers additional tools and options like, automatic collision meshed or tools that populate the dungeon with enemies and the player objects.  
  
For the generator I use the main principle of classical dungeon generators like the ones used in Roque and Roque likes for creating single floor 3d dungeons. While the dungeon is mostly generated automatically the user has control over the level flow, room density, location and more. Users can also add additional rooms and corridors to the design.  
  
> For more detail check the documentation:
> 	- [Graduation_Report_101110_Maurits_Laanbroek.pdf]({{ page.imgpath }}Graduation_Report_101110_Maurits_Laanbroek.pdf){:target="_blank"}

{% include youtubePlayer.html id=page.youtubeId.id1 %}
{% include youtubePlayer.html id=page.youtubeId.id2 %}