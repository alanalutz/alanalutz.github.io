---
title: "A First Crack at Reproduction"
last_modified_at: 2023-10-05T16:20:02-05:00
categories:
  - Blog
tags:
  - GIS
  - science
  - COVID-19
---

This week, I tested the waters of what it's like to reproduce the work of other researchers by modifying the the [code](https://github.com/alanalutz/RPr-Chakraborty-2021) from [Chakraborty (2021)](https://doi.org/10.1016/j.dhjo.2020.101007), a study that analyzed county-level association of disability and COVID-19.
In the process, I learned that while reproduction is messy, often frustrating, and dependent on the incomplete documentation provided by the original researcher, it is a valuable way to improve on the work of others and build upon the existing body of scientific knowledge.
The numerous deviations, both planned and unplanned, of previous reproductions to this study demonstrated how slight changes in the computational environment or analytical decisions can affect results and test the robustness of the study's broader conclusions.\
\
I added my own deviation to this reproduction by modifying the spatial clusters of counties with higher relative risk of COVID-19.
Specifically, I chose not to create separate clusters for each state, removing the assumed state-level correlation from the clustering methodology.
(For more information, see the full [reproduction report.](http://alanalutz.github.io/RPr-Chakraborty-2021/))
Like the previous deviations, this modification confirmed that while some of the tested associations are more robust than others, the overall outcomes of the study remain largely unchanged.
Each deviation continues to improve the original study, offering nuance to the results while solidifying its broader conclusions.\
\
Here is more information about the class I'm taking, [Open GIScience.](http://opengisci.github.io)