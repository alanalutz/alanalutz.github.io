---
title: "Improving a Study of COVID-19 Spatial Accessibility"
last_modified_at: 2023-11-13T16:20:02-05:00
categories:
  - Reproduction
tags:
  - GIS
  - science
  - COVID-19
  - accessibility
---

This week's reproduction was based on a spatial accessibility study published by [Kang et al](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x) in the midst of the COVID-19 pandemic.
The purpose of the original study was to develop a methodology to rapidly measure the accessibility of healthcare resources in the state of Illinois. The authors performed a network analysis of road systems to determine catchment areas for each hospital, then used an enhanced two-step floating catchment area (E2SFCA) method to calculate the ratios of healthcare resources to at-risk populations in each residential location. The final output maps the spatial accessibility of ICU beds and ventilators for people at risk (over 50 years old) and COVID-19 patients, demonstrating areas of need for further resource allocation.\
\
We modified the study's original methodology by using the osmnx.speed module to set speed limits, rather than setting all unknown speed limits to a default of 35 mph.
(Find the code repository [here.](https://github.com/alanalutz/RPr-Kang-2020))
This adjustment improved the validity of the study by increasing the accuracy of speed limit data.
In particular, the modified network analysis better represents the slower speed limits of Chicago's residential areas. The modification noticeably affected the study's final spatial accessibility results for the vulnerable population over 50, producing a zone of highest accessibility that is smaller and does not extend as far to the northwest.
Thus, we should interpret the original study results with caution, knowing that they may erroneously inflate accessibility with higher default speed limits.\
\
For more information, read the full reproduction report [here.](https://alanalutz.github.io/RPr-Kang-2020/)\
\
Here is more information about the class I'm taking, [Open GIScience.](http://opengisci.github.io)

