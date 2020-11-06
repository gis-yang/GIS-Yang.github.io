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
the University of Central Florida (UCF). I am co-leading with Dr. Timothy Hawthone for an NSF colaborative coastal mapping [project](https://www.citizensciencegis.org/nsfsmithosniandrones) supports [Citizen Science GIS](https://www.citizensciencegis.org/). This project is one of the earliest attempts to employ UAV mapping in coastal management and conservation across 23 degrees of latitude. 

I have multiple education backgrounds with a B.S. degree in applied mathematics, an M.S. in computer science, and an M.A. in GIS. I received my Ph.D. in geography at the University of Cincinnati (UC) advised by Dr. Hongxing Liu. 

My research interests are: **_GIScience, spatial statistics, UAV & drone mapping, citizen science, environmental and sociological modeling._**

I am an FAA part 107 remote pilot and NASBLA recognized boat driver. Besides of doing research and teaching, I like fiddling with tech gadgets, car mod, and playing basketball. I am maintaining an [open-access UAV/drone training course](https://gis-yang.github.io/DroneMapping/) for seagrass mapping. 

[*Curriculum Vitae -pdf-*](https://docs.google.com/document/d/1X4dQp722FGkrhZA4qp6Eu7vWaWDV-otF2zpRAI35AHI/edit?usp=sharing)

Pronouns: he/him/his

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

