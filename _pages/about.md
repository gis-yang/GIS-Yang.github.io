---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Yang's GIS page aims to share research progresses and resources of Geographical Information Science (GIS), UAV & Drone, and spatio-temporal geo-statistics. 

I am an interdisciplinary postdoc in the 
Department of Sociology
and the College of Sciences Geospatial Technologies Cluster at 
the University of Central Florida (UCF). I am co-leading with Dr. Timothy Hawthone for an NSF colaborative coastal mapping project supports Citizen Science GIS. This project is one of the earliest attempts to employ UAV mapping in coastal management and conservation across 23 degrees of latitude. 

I have multiple education backgrounds with a B.S. degree in applied mathematics, an M.S. in computer science, and an M.A. in GIS. I received my Ph.D. in geography at the University of Cincinnati (UC) in 2018 under the direction of Dr. Hongxing Liu. 

My research interests are: **_GIScience, spatial statistics, UAV & drone mapping, citizen science, environmental and sociological modeling._**

I am an FAA part 107 remote pilot and NASBLA recognized boat driver. Besides of doing research and teaching, I like fiddling with tech gadgets, car mod, and playing basketball.

Pronouns: he/him/his

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

