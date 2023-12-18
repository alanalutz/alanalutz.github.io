---
title: "Reproducing a Wildlife Corridor Analysis"
last_modified_at: 2023-12-18T16:20:02-05:00
categories:
  - Blog
  - Reproduction
tags:
  - GIS
  - science
  - wildlife corridor
---

For my culminating project in this class, I worked with Andy Atallah to reproduce a multi-criteria movement cost surface of Makayuni Corridor, a wildlife corridor in Tanzania.
This cost surface analysis was originally conducted by Justin Lucas using QGIS Model Builder as part of an unpublished study by Lyimo et al, and we reproduced the analysis by converting the QGIS model into an R script.
(Find the code repository [here.](https://github.com/alanalutz/Makayuni-Corridor))\
\
Overall, the reproduction was relatively successful.
The primary source of error was an unresolvable difference in computational environment that resulted in some buildings failing to rasterize properly at the resolution of analysis, creating isolated “bubbles” of error in proximity to these buildings.
This discrepancy demonstrates the impacts of partition distortion, in particular the Modifiable Areal Unit Problem, on reproduction analyses in different computational environments.
Otherwise, we found the original study to be relatively simple to follow, illustrating the reproducibility of a QGIS model given the proper documentation and metadata.\
\
For more information, read the full reproduction report [here.](https://alanalutz.github.io/Makayuni-Corridor/)\
\
Here is more information about the class I'm taking, [Open GIScience.](http://opengisci.github.io)

