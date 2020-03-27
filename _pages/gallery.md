---
layout: archive
title: "Gallery"
permalink: /Gallery/
author_profile: true
---
| ![image](/images/AK_eelgrass.jpg)(http://gis-yang.github.io) | ![image](/images/AK_eelgrass.jpg)(http://gis-yang.github.io) | 
| *AK_eelgrass1* |*AK_eelgrass2* |

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
