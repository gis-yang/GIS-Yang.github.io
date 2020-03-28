---
layout: archive
title: "Gallery"
permalink: /Gallery/
author_profile: true
---
| [![image](/images/AK_eelgrass.jpg){:height = "200px"}](http://gis-yang.github.io) | ![image](/images/dronetraining.jpg){:height = "200px"} | 
| ![image](/images/dronetraining.jpg){:height = "200px"} |[![image](/images/AK_eelgrass.jpg){:height = "200px"}](http://gis-yang.github.io)  |

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
