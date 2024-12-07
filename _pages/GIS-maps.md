---
layout: archive
title: "GIS Maps"
permalink: /GIS-maps/
author_profile: true
---
**Welcome :)**

This site is an online portfolio to document my journey through the exciting world of **Geographic Information Systems (GIS)**. I began this journey from 2018 since I started worked GIS and CAD tools in urban planning. Until now, I have already finished my master's degree in Geo-Information Science and am continue discovering the GIS world.

I hope you will enjoy following my progress towards completion of the project. In the meantime, explore some of the projects that I have worked on in the past few years.

---

### **Project 1: Fukusima map**

<video width="540" height="300" controls>
  <source src="{{site.url}}/videos/fukushima.mp4" type="video/mp4">
</video>

A dynamic maps that shows the evolution in the levels of radiation in the Fukushima area from 2010 to 2021.

### **Project 2: Iberian Ibex Immigration map**

<img src="{{site.url}}/images/GIS-maps/Immigration_map.png" alt="Iberian Ibex immigration map" align="left" width=240 height=350 style="margin-right: 50px;">

The immigration map shows the corridor zones and movement paths of Iberian Ibex in the study area based on the the metadata.
It is a significant reference which significantly establishing an ecological corridor for the protection of Ibex.

<br clear="left"/>

### **Project 3: Amsterdam center monumental building map**

<video id="myVideo" width="540" height="300" controls>
  <source src="{{site.url}}/videos/monu-building.mp4" type="video/mp4">
</video>

This interactive map retrieves information about the monumental state of Dutch buildings on a national and municipal level and specifies whether a given building is positioned within the protected cityscape area.
Based on the year of construction retrieved from the Key Register of Adresses and Buildings, the repository assigns information about whether installation of a heating pump is allowed and/or recommended.

<script>
document.getElementById('myVideo').defaultPlaybackRate = 2.0;
</script>

### **Project 4: Biodiverse route map**

<video width="540" height="300" controls>
  <source src="../videos/biodiversity-route-app.mp4" type="video/mp4">
</video>

The video shows a interactive map with a mobilized form. The demostration provides an application which showcase the possible walking route with highest biodiversity rate. The route is in an interested area: Groenlo, where situated in the eastern part of the Netherlands, on the German border.

### **Project 5: 3D root web map**

<video width="540" height="300" controls>
  <source src="../videos/cesium-map.mp4" type="video/mp4">
</video>

This demo indicates a interactive map using Cesium platform to illustrate the underground 3D tree root models with surrounding buildings and terrain model. Users could visualize the tree roots with traslucent terrain texture.

{% include base_path %}

{% for post in site.GIS-maps reversed %}
  {% include archive-single.html %}
{% endfor %}
