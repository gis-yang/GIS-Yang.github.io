---
layout: archive
title: "Talks"
permalink: /Talks/
author_profile: true
---
## Invited Talks 
* “Drone Mapping for Coastal Seagrass Monitoring and Citizen Science” in Department of Geography colloquium, University of Florida, Gainesville, FL, October 10, 2019. [**View PDF**](/UF_Colloquium_Yang_20191009/)
*  “Multi-spectral drone mapping over Indian River Lagoon” in UCF research week kick-off event, University of Central Florida, Orlando, FL, 2018, April 5, 2019.[**View PDF**](/UCF_Poster_Yang/)
* “Spatio-temporal Cokriging Method for Blending and Downscaling Multi-scale Data” in UC geography colloquium series, University of Cincinnati, Cincinnati, OH, October 13, 2017 [**View PDF**](/UC_Seminar2017_Yang/)

## Conference Presentations
* Bo Yang, Timothy Hawthorne, Michael Feinman, Hunter Searson, (2020) High-resolution UAV mapping for investigating eelgrass wasting disease over the west coast of North America. In AGU Ocean Sciences Meeting. San Diego, CA
* Bo Yang, Timothy Hawthorne (2019) A spatio-temporal geostatistical approach for sharpening multi-spectral satellite imagery using high-resolution UAV data. In, AAG Annual Meeting. Washington, D.C.
* Hongjie Yu, Lin Liu, Bo Yang (2019) Crime Prediction with Historical Crime and Potential Offender Data Using a Spatio-temporal Cokriging Method. In, AAG Annual Meeting. Washington, D.C.
* Bo Yang, Hongxing Liu, Emily Kang, Bailang Yu, Changchun Feng, Min Liu, Jianping Wu (2016) Analysis of impact of traffic regulation on spatial extent and intensity of urban heat islands with satellite thermal remote sensing. In, International Geographical Congress. Beijing, China
* Bo Yang, Hongxing Liu, Emily Kang, Richard A. Beck, Kenneth M. Hinkel, Lei Wang (2016) Spatio-temporal Cokriging: A multi-scale assimilation method for downscaling, hindcasting, and forecasting. In, AAG Annual Meeting. San Francisco, CA
* Bo Yang, Hongxing Liu, Emily Kang (2015) Spatio-temporal Assimilation of Multi-scale Data Sets within a Cokriging Framework. In, AAG Annual Meeting Spatial Analysis and Modeling (SAM) paper competition. Chicago, IL
* Heather Barrett, Mark Krekeler, Josh Crumbaker, Bo Yang, Angie Bittner (2015) Preliminary materials investigations to support search and recovery using hyperspectral remote sensing: Initial geomaterials and clothing results. In Geological Society of America (GSA) Annual Meeting in Baltimore, MD
* Bo Yang, Hongxing Liu, Emily Kang (2014) Assimilation of multi-scale thermal remote sensing data using spatio-temporal cokriging method. In, AAG Annual Meeting. Tampa, FL
* Bo Yang, Emily Kang, Hongxing Liu (2013) Spatiotemporal (ST) cokriging to Fuse Images of Multi-Sensor Land Surface Temperature. In, Statistics 2013. Columbus, OH
* Hongxing Liu, Bo Yang, Song, Shu, K KM Hinkel, RA Beck, EL Kang, (2013). Spatio-temporal analysis of surface temperature and water level variability of thermokarst lakes on the Arctic Coastal Plain of northern Alaska using multiscale satellite thermal images and ICESat laser altimetry. In AGU Fall Meeting. San Francisco, CA
* Bo Yang, Hongxing Liu, Emily Kang, Qiusheng Wu (2013). Spatiotemporal cokriging (ST) for multi-sensor images fusion of daily surface temperature over thaw lakes on north Alaska. In, AAG Annual Meeting. L. A., CA
* Bo Yang, Hongxing Liu, Qiusheng Wu, Richard Beck, Ken Hinkel, Emily Kang (2012). Derivation of daily surface temperature and emissivity measurements over the Maumee River watershed by integrating multi-scale thermal remote sensing data. In, AAG Annual Meeting. NYC
* Richard Beck, Hongxing Liu, Bo Yang, Qiusheng Wu (2012). Aircraft Sensing of Microcystis In, Workshop for Remote Sensing of Coastal and Inland Waters. University of Wisconsin-Madison






{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
