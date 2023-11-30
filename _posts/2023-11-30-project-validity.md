---
title: "Project Validity"
last_modified_at: 2023-11-30T16:20:02-05:00
categories:
  - Blog
tags:
  - validity
  - replication
---
For my independent project to culminate this class, I will be replicating part of a wildlife corridor analysis.
The original study evaluated the connectivity of Makuyuni Wildlife Corridor, a stretch of unprotected land between Tarangire National Park and Essmingor National Forest Reserve in Tanzania.
I will be reproducing the first part of the study, a multifactor analysis model that approximates cost of movement through the corridor based on least cost pathway analysis.
The study was originally conducted using the QGIS Model Builder, and I will be replicating the workflow in R.
The output I am attempting to replicate is a map displaying the minimum cost of movement through each point in the study area.\
\
There are several possible geographic threats to validity in a wildlife corridor analysis.
The first is scale dependency.
Species of different sizes and behavioral characteristics show on-the-ground movement patterns of different scales.
If the spatial resolution of analysis does not align with the movement patterns of the species of interest, the study may not accurately represent movement costs.
It will be important to confirm that the spatial resolution of the model is appropriate for the species of interest.\
\
A second threat is space-time interactions.
Wildlife movement patterns can change over time, especially over the course of a year due to seasonal variations.
Corridor analyses that do not take into account temporal considerations may not capture these dynamics.
If the data is available, a potential solution is to incorporate seasonal data that accounts for changing movement behaviors or landscape characteristics.\
\
A final geographic threat to validity in this study could be boundary distortions.
If the extent of the study area is not based on ecologically sound data that indicates wildlife movement patterns, it may not accurately represent movement pathways within the study area.
It will be important to confirm that the study area is a reasonable wildlife corridor through with animals move from one protected area to another.
**References:**
- Schmitt, R. R. (1978). Threats to validity involving geographic space. Socio-Economic Planning Sciences, 12(4), 191–195. https://doi.org/10.1016/0038-0121(78)90044-7
