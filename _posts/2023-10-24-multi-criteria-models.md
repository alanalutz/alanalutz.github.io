---
title: "Multi-Criteria Model Validity"
last_modified_at: 2023-10-24T16:20:02-05:00
categories:
  - Blog
  - Response
tags:
  - vulnerability
  - validity
  - modeling
---
The original [Social Vulnerability Index (SoVI)](https://doi.org/10.1111/1540-6237.8402002) was developed in 2003 by Cutter, Boruff, and Shirley to evaluate county-level vulnerability to environmental hazards across the entire US.
This multi-criteria model uses an equal weighting approach “in the absence of a defensible method for assigning weights” to the 11 different factors used in the analysis.
However, I would argue that equal weighting is not a default option, but rather a meaningful decision, based on an unfounded assumption that each factor has an equal contribution to the county’s overall vulnerability.
Indeed, [Rufat et al (2018)](https://doi.org/10.1080/24694452.2018.1535887) compared the validity of SoVI to other social vulnerability models using real outcomes from Hurricane Sandy and found that a weighted index based on expert knowledge demonstrated greater validity and explanatory power for disaster impacts than the unweighted SoVI model.
The authors do acknowledge, however, that weighted indices are highly sensitive to the choice of weighting scheme.
It seems that justified weighting of factors is necessary for a valid model, but is fully dependent on the credibility of the expert knowledge used to create the weighting scheme.\
\
My own experience with multi-criteria models comes not from social vulnerability, but conservation planning.
Last semester, I [developed a model](https://drive.google.com/file/d/1ExbT47wo5-ezNi7tShup6tHS49cf35mr/view?usp=sharing) to prioritize the conservation value of unprotected grassland parcels in Middlebury, VT using factors including bird habitat size, soil quality, and parcel size.
In the process, I experimented with various parameters to test the sensitivity of the model to researcher decisions.
For example, I compared a simple binary threshold model to a more nuanced model with scored levels for each factor.
I also chose to weight the factors in my model, but realized that my weighting scheme felt rather arbitrary in the absence of expert opinion.
Reading about the validity of social vulnerability models has confirmed my suspicion that weighting and other such model parameters must be carefully considered when developing multi-criteria models.
Even though my personal research interests lie more in the realm of conservation planning than social vulnerability, the lessons we have learned from studying vulnerability indices are clearly relevant to other applications of multi-criteria modeling.\
\
Here is more information about the class I'm taking, [Open GIScience.](http://opengisci.github.io)\
\
**References:**
- Cutter, S. L., Boruff, B. J., & Shirley, W. L. (2003). Social vulnerability to environmental hazards. Social Science Quarterly, 84(2), 242–261. https://doi.org/10.1111/1540-6237.8402002
- Rufat, S., Tate, E., Emrich, C. T., & Antolini, F. (2019). How Valid Are Social Vulnerability Models? Annals of the American Association of Geographers, 109(4), 1131–1153. https://doi.org/10.1080/24694452.2018.1535887
