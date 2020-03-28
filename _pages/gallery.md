---
layout: archive
title: "Gallery"
permalink: /Gallery/
author_profile: true
---
| [![image](/images/Gallery/dronetraining.jpg){:width="300px"}](https://doi.org/10.3390/drones3030060) | [![image](/images/Gallery/CarrieBow_GPSMap.jpg){:width="300px"}](http://www.citizensciencegis.org/capturing-the-beauty-of-belize-from-above-with-drones-to-support-science-and-discovery-with-smithsonian-marinegeo/) | 


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
