---
title: "Reproducing a Climate Vulnerability Model"
last_modified_at: 2023-10-22T16:20:02-05:00
categories:
  - Blog
tags:
  - GIS
  - science
  - COVID-19
---

For our second reproduction study, we looked at a climate vulnerability model published by [Malcomb et al in 2014](https://doi.org/10.1016/j.apgeog.2014.01.004).
This study developed a multi-criteria model that combined adaptive capacity, livelihood sensitivity, drought exposure, and flood risk to map overall climate vulnerability across Malawi.
(Find the code repository [here.](https://github.com/alanalutz/RPr-Malcomb-2014))\
\
Ultimately, the reproduction attempt failed to produce identical or even similar results to the original study, despite Malcomb et al’s intentions of reproducibility. (The full reproduction report can be found [here.](https://alanalutz.github.io/RPr-Malcomb-2014/))
This failure can be largely attributed to uncertainties in the data processing methodology, particularly the treatment of geometry errors and the scaling of indicators.
These results emphasize the necessity of improving the reproducibility and replicability of climate vulnerability research, which is essential to enhance the potential for this research to inform policy and reduce harm caused by climate change.\
\
To add further value to this reproduction, I modified the final raster aggregation methodology to test the effect of a geometric aggregation against the original additive aggregation.
The justification for this reanalysis is that additive aggregations assume that there is no interaction between indicators, which is often not the case with social vulnerability variables.
Additive aggregations may also increase compensability, in which a low value in one indicator can mask a high value in another.
Geometric aggregation can reduce issues with both interaction and compensability.\
\
When comparing vulnerability results between the additive and geometric aggregation methods, the geometric aggregation appears to identify more areas of Malawi with relatively greater vulnerability.
This result suggests that compensability may be involved in the additive aggregation, giving some areas an artificially low vulnerability score.
In the context of evaluating and allocating foreign aid, it is better to overestimate vulnerability than to underestimate.
Thus, I would argue that a geometric aggregation strategy is likely the better approach in this study.
Despite the failures in reproduction, a reanalysis like this one offers additional insight into sensitivity of parameters within a vulnerability model.\
\
Here is more information about the class I'm taking, [Open GIScience.](http://opengisci.github.io)

