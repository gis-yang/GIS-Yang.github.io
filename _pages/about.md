---
permalink: /
title: ""
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
 <img align="center"  src="/images/DJI_0894.JPG">
 
Yang's GIS page aims to share research progresses and resources of Geographical Information Science, Remote Sensing, and Environmental Science. 

I am an post-doctoral research scholar in the Department of Sociology and Geospatial Cluster in the College of Sciences at University of Central Florida (UCF). I work with Dr. Timothy Hawthone co-leading an NSF colaborative coastal mapping project supports [Citizen Science GIS](https://www.citizensciencegis.org/). This [project](https://gis-yang.github.io//Projects/) is one of the earliest attempts to employ UAV remote sensing in coastal management and conservation across 23 degrees of latitude. 

I have interdisciplinary education background with a B.S. degree in Applied Mathematics, an M.S. in Computer Science. I received my Ph.D. in Geography advised by Dr. Hongxing Liu at University of Cincinnati (UC). My research interests are: **_GIScience, Remote Sensing, Spatial Statistics, Unmanned Aerial Vehicle (UAV), Human-environment Interactions, and Citizen Science_**. 

For my doctoral dissertation, I developed and implemented a new geo-statistical ([ST-Cokriging](https://doi.org/10.1016/j.rse.2020.112190)) method to assimilate multi-scale data for forecasting and hindcasting spatio-temporal environmental & societal processes, such as urban heat island effects measured with remote sensing. Compared with previous data assimilation algorithms, this machine learning method is more accurate with its additional capabilities in filling missing data and uncertainty estimates. 

I am an FAA part 107 remote pilot maintaining an open-access UAV/drone training [course](https://gis-yang.github.io/DroneMapping/) for coastal UAV mapping. Besides of doing research and teaching, I like fiddling with tech gadgets and playing basketball. 

Pronouns: he/him/his 

[*Yang's Curriculum Vitae*](https://docs.google.com/document/d/1nT3W5MqYg02pN3GBTEk82azSgIICLYM18z3yoXPlEDU/edit?usp=sharing)



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

