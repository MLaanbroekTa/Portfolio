---
layout: post
author: Maurits Laanbroek
tags: [Tools, Personal]
permalink: /Personal/:title:output_ext
desc: A unfinished web comic reader.
logo: comicReader.png
title: Web comic reader
imgpath: assets/images/personal/
categories: nonWork
back: /Personal/personal.html

---

A large personal python based project I worked on and off over the years.
While not finished it is a good continues exercise in handling large code projects, experimenting with design philosophies and developing python skills.

The main idea is to be able read comics from all different types comic and manga websites in a single app.
The web crawling uses a custom crawler that uses separate XML files for each source to know how to correctly crawl them. This way if a page layout changes it's easy to update.
Each XML file has a large list of Regex and Xpaths to find and clean data the correct data.

The main loop and many of the components are working:
- Supporting multiple sources for a single comic
- Favourites
- Tracking which chapters are read
- Reading a comic
- Infinite scroll on library, async crawling of new entries
- Multiple screen layouts 
- Multiple comic types, left to right, right to left, vertical

It uses Python 3.7 and PySide5 together with other libraries for web crawling to XML file handling.
Developed skills:
- System design
- QT > PtSide
- Python
- Threading and services
- Web crawling
- Regex, XPath and XML

