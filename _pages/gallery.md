---
layout: archive
title: "Gallery"
permalink: /Gallery/
author_profile: true
---
| [![image](/images/Gallery/dronetraining.jpg){:width="480px"}](https://doi.org/10.3390/drones3030060) | [![image](/images/Gallery/CarrieBow_GPSMap.jpg){:width="480px"}](http://www.citizensciencegis.org/capturing-the-beauty-of-belize-from-above-with-drones-to-support-science-and-discovery-with-smithsonian-marinegeo/) | 
| [![image](/images/Gallery/Anderson.jpg){:width="480px"}](https://doi.org/10.1016/j.jag.2019.03.010) |[![image](/images/Gallery/Crime.jpg){:width="480px"}](https://doi.org/10.1080/13658816.2020.1737701)| 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
