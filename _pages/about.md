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
and the College of Sciences GIS Cluster at 
the University of Central Florida (UCF). I work with [Dr. Timothy L. Hawthone](https://sciences.ucf.edu/sociology/thawthorne/) co-lead an NSF colaborative coastal mapping [project](https://www.citizensciencegis.org/nsfsmithosniandrones) supports [Citizen Science GIS](https://www.citizensciencegis.org/). This project is one of the earliest attempts to employ UAV mapping in coastal management and conservation across 23 degrees of latitude. 

I have multiple education backgrounds with a B.S. degree in Applied Mathematics, an M.S. in Computer Science, and an M.A. in GIS. I received my Ph.D. in Geography advised by Dr. Hongxing Liu at University of Cincinnati (UC). 

My research interests are: **_GIScience, spatial statistics, UAV & drone mapping, citizen science, environmental and sociological modeling._**

I am an FAA part 107 remote pilot and NASBLA recognized boat driver. Besides of doing research and teaching, I like fiddling with tech gadgets and playing basketball. I am maintaining an [open-access UAV/drone training course](https://gis-yang.github.io/DroneMapping/) for seagrass mapping.

Pronouns: he/him/his 

[*Yang's Curriculum Vitae*](https://docs.google.com/document/d/1X4dQp722FGkrhZA4qp6Eu7vWaWDV-otF2zpRAI35AHI/edit?usp=sharing)



**Contact:**\
Bo Yang\
[Bo.Yang[a]ucf.edu](Bo.Yang@ucf.edu) \
(407) 823-4192\
4297 Andromeda Loop, Orlando, FL 32816\
University of Central Florida


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

