---
layout: archive
title: "Gallery"
permalink: /Gallery/
author_profile: true
---
| [![image](/images/AK_eelgrass.jpg){width = "400px"}](http://gis-yang.github.io) | ![image](/images/dronetraining.jpg) | 
| [*AK eelgrass1*](http://gis-yang.github.io) |[*Drone training*](http://gis-yang.github.io) |

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
