---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Yang's GIS page aims to share research progresses and resources of Geographical Information Science, Remote Sensing, and Environmental Science. 

Currenlty, I am an postdoctral research scholar in the Department of Sociology and Geospatial Cluster in the College of Sciences at University of Central Florida (UCF). I work with Dr. Timothy Hawthone co-leading an NSF colaborative coastal mapping [project](https://gis-yang.github.io//Projects/) supports [Citizen Science GIS](https://www.citizensciencegis.org/). This project is one of the earliest attempts to employ UAV mapping in coastal management and conservation across 23 degrees of latitude. 


I have multiple education backgrounds with a B.S. degree in Applied Mathematics, an M.S. in Computer Science. I received my Ph.D. in Geography advised by Dr. Hongxing Liu at University of Cincinnati (UC). For my doctoral dissertation, I developed and implemented a novel geo-statistical (ST-Cokriging) method to assimilate multi-source and multi-scale data for forecasting and hindcasting spatio-temporal environmental processes, such as urban heat island effects measured with remote sensing.Compared with previous data assimilation algorithms, this new method is more accurate with its additional capability in filling missing data. 

My research interests are: **_GIScience, Remote Sensing, Spatial Statistics, Unmanned Aerial Vehicle (UAV), Citizen Science, Environmental and Societal Modeling_**. 

I am an FAA part 107 remote pilot and NASBLA recognized boat driver. I am maintaining an [open-access UAV/drone training course](https://gis-yang.github.io/DroneMapping/) for coastal UAV mapping. Besides of doing research and teaching, I like fiddling with tech gadgets and playing basketball. 

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

