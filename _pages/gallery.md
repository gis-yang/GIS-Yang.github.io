---
layout: archive
title: "Gallery"
permalink: /Gallery/
author_profile: true
---
| ![image](/images/AK_eelgrass.jpg) | ![image](/images/AK_eelgrass.jpg) | 
| [*AK_eelgrass1*](http://gis-yang.github.io) |[*AK_eelgrass2*](http://gis-yang.github.io) |

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
