---
layout: archive
title: "Talks"
permalink: /Talks/
author_profile: true
---
## Invited Talks 
* “Drone Mapping for Coastal Seagrass Monitoring and Citizen Science” in Department of Geography colloquium, University of Florida, Gainesville, FL, October 10, 2019. [**View PDF**](/UF_Colloquium_Yang_20191009/)
*  “Multi-spectral drone mapping over Indian River Lagoon” in UCF research week kick-off event, University of Central Florida, Orlando, FL, 2018, April 5, 2019.
* “Spatio-temporal Cokriging Method for Blending and Downscaling Multi-scale Data” in UC geography colloquium series, University of Cincinnati, Cincinnati, OH, October 13, 2017

## Conference Talks
* High-resolution UAV mapping for investigating eelgrass wasting disease over the west coast of North America. In AGU Ocean Sciences Meeting. San Diego, CA, 2020
* A spatio-temporal geostatistical approach for sharpening multi-spectral satellite imagery using high-resolution UAV data. In, AAG Annual Meeting. Washington, D.C., 2019
* Analysis of impact of traffic regulation on spatial extent and intensity of urban heat islands with satellite thermal remote sensing. In, International Geographical Congress. Beijing, China, 2016
* Spatio-temporal Cokriging: A multi-scale assimilation method for downscaling, hindcasting, and forecasting. In, AAG Annual Meeting. San Francisco, CA, 2016
* Spatio-temporal Assimilation of Multi-scale Data Sets within a Cokriging Framework. In, AAG Annual Meeting Spatial Analysis and Modeling (SAM) paper competition. Chicago, IL, 2015
* Assimilation of multi-scale thermal remote sensing data using spatio-temporal cokriging method. In, AAG Annual Meeting. Tampa, FL, 2014
* Spatiotemporal (ST) cokriging to Fuse Images of Multi-Sensor Land Surface Temperature. In, Statistics 2013. Columbus, OH, 2013
* Spatiotemporal cokriging (ST) for multi-sensor images fusion of daily surface temperature over thaw lakes on north Alaska. In, AAG Annual Meeting. L. A., CA, 2013
* Derivation of daily surface temperature and emissivity measurements over the Maumee River watershed by integrating multi-scale thermal remote sensing data. In, AAG Annual Meeting. NYC, 2012





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
