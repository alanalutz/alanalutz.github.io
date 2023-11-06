---
title: "Reproducing and Reanalyzing SoVI Validity"
last_modified_at: 2023-10-30T16:20:02-05:00
categories:
  - Blog
tags:
  - GIS
  - science
  - SoVI
  - validity
---

Our third reproduction was based on a SoVI validity study published by [Spielman et al in 2020](https://doi.org/10.1007/s11069-019-03820-z).
SoVI, the Social Vulnerability Index, was first developed by [Cutter, Boruff, and Shirley in 2003](https://doi.org/10.1111/1540-6237.8402002) to rank counties in the United States by their social vulnerability to environmental hazards using socioeconomic and demographic data.
Spielman et al reproduced the SoVI at various geographic extents (nationwide, FEMA subregions, and individual states) and evaluated its validity by comparing county vulnerability rankings between models of different extents.
They found that the SoVI is both internally and theoretically inconsistent, raising issues with the model's validity.\
\
We reproduced Spielman et al.'s original work, obtaining nearly identical results.
Further, we modified the analysis by reweighting the SoVI by the percent variance explained of each PCA component, rather than using a simple sum of the components.
(Find the code repository [here.](https://github.com/alanalutz/RPl-Spielman-2020))
The purpose of this modification was to evaluate whether this method of weighting improves the internal and/or theoretical consistency of the SoVI model.
In Spielman et al, internal consistency is assessed by comparing the county rankings of SoVI scores in a state between models with different geographic extents.
Theoretical consistency (construct validity) is assessed by comparing the directionality and ranked importance of input variables between models with different geographic extents.\
\
Overall, our weighting methodology had little obvious impact on the output of the model.
It did not improve the model's internal consistency, and improved some aspects of theoretical consistency but not others.
(For more information, read the full reproduction report [here.](https://alanalutz.github.io/RPl-Spielman-2020/))
From this analysis, we can infer that the SoVI's issues with internal and theoretical consistency are not a result of a failure to properly weight the index's components.
Perhaps the entire construct of the SoVI model must be reinterpreted to take into account geographic threats to validity arising from changes in scale.
As Spielman et al wrote, "it does not seem unreasonable that the meaning of social vulnerability would change with geographic context."
If vulnerability is highly contextual to location, and thus the importance of different variables will always change from place to place, could we ever expect a generalized national model of vulnerability to match a model that has been tailored to a more focused local context?\
\
Here is more information about the class I'm taking, [Open GIScience.](http://opengisci.github.io)

