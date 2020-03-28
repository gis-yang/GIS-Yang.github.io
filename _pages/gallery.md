---
layout: archive
title: "Gallery"
permalink: /Gallery/
author_profile: true
---
| [![image](/images/AK_eelgrass.jpg){:width = "400px"}](http://gis-yang.github.io) | ![image](/images/dronetraining.jpg){:width = "400px"} | 
| ![image](/images/dronetraining.jpg){:width = "300px"} |[![image](/images/AK_eelgrass.jpg){:width = "2500px"}](http://gis-yang.github.io)  |

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
