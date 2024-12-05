---
layout: archive
title: "GIS Maps"
permalink: /GIS-maps/
author_profile: true
---
**Welcome :)**

This site is an online portfolio to document my journey through the exciting world of Geographic Information Systems (GIS). I began this journey from 2018 since I started worked GIS and CAD tools in urban planning. Until now, I have already finished my master's degree in Geo-Information Science and am continue discovering the GIS world.

I hope you will enjoy following my progress towards completion of the project. In the meantime, explore some of the projects that I have worked on in the past few years.

---

### **Project 1: Fukusima map**

<video width="540" height="300" controls>
    <source src="../videos/fukushima.mp4" type="video/mp4">
  </video>

A dynamic maps that shows the evolution in the levels of radiation in the Fukushima area from 2010 to 2021.

### **Project 2: Immigration map**

### **Project 3: Amsterdam center monumental building maps**

### **Project 4: Biodiverse route**

### **Project 5: 3D root web map**

{% include base_path %}

{% for post in site.GIS-maps reversed %}
  {% include archive-single.html %}
{% endfor %}
