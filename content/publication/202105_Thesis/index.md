---
abstract: 'Surveillance systems of communicable diseases encompass monitoring a variety of goals such as eradication and elimination, measuring the impact of prevention and control programmes, trends in endemic diseases and progress towards programmatic targets. Disease mapping can support all stages of the monitoring tasks from planning to implementation, evaluation of control efforts and early warning. Modern disease cartography is strongly supported by the use of geographical information systems, remote sensing and geostatistics. It is able to provide insights into the epidemiology and ecology of diseases at various spatio-temporal scales. For diseases linked to the climate, such as malaria and neglected tropical diseases (NTDs), remotely sensed environmental data has proved to predict spatial distributions of transmission patterns with good precision. For emerging infectious diseases, where our understanding of the mechanisms underlying the emergence remains rudimentary, maps serve as the primary tool of contemporary surveillance. The geospatial component of the monitoring has been recognised as crucial for the surveillance of vector-borne diseases especially at the elimination stage.


Multiple efforts of controlling malaria led to retraction of the disease and many areas are transitioning from high transmission to low transmission and elimination phases. Few countries are running surveillance systems capturing malaria cases at individual household level. This data collection procedure gives rise to the point pattern data constituted by random number of random case locations. Models of point pattern data is an underdeveloped field in comparison to other spatial models, such as conditional auto-regressive model for areal data and geostatistical model for point-referenced data. Log-Gaussian Cox process (LGCP) is a sound tool, allowing to model point pattern disease case data via spatially and temporally varying intensity function, make inference about the determinants of the ongoing transmission and produce disease incidence maps. However, in its Bayesian formulation and on fine spatio-temporal scale, LGCP exhibits prohibitively long computation times and high storage requirements, which prevents its wide application and further model development. LGCP is often approximated in the literature via a Poisson process. The consequence of such approximation remained unclear for computation time and amount of uncertainty in the estimates. Point patterns can be extended to the so called marked point patterns when each data point is enriched with an extra coordinate, e.g. a discrete tag, but the same computational issues emerge as for LGCP.


Smooth maps, produced by geostatistical and point pattern models, are capable of displaying disease patterns, but can not highlight hotspot areas as regions statistically elevated as compared to their immediate neighbours. Therefore, a methodology is needed to be able to determine hotpospts boundaries.
Geospatial distribution of many human infectious diseases, and in particular vector-borne diseases, can be well predicted by environmental factors due to the strong relation of climate and environment to the survival of vectors and pathogen replication rate. This link can be used to harness transmission and design efficient intervention strategies. Remote sensing (RS) imagery is a powerful tool to produce environmental data. The quality of the RS data, however, varies across products. Missing values can be present in the images due to satellite failures or due to the presence of clouds. Gaps in the data hamper the usage of RS images and need to be filled either prior to the analysis or as a part of it. Modern techniques of predicting missing values in RS data sets lag behind the advancements in model-based geostatistics.


This thesis aims to address the above gaps. The specific methodological objectives of this research are: (i) to evaluate exact and approximate likelihood formulations for LGCP, to expand the Poisson distributional assumption to model Negative Binomial counts, to exploit parsimonious computational strategies and investigate the effect of the spatial resolution on statistical inference (Chapter 2), (ii). to develop methodology for detecting burden hotpots on disease gridded surfaces derived by Bayesian point pattern and geostatistical models (Chapters 3 and 4), (iii). to develop a well-scalable method for filling missing values in remote sensing environmental proxies, accounting for uncertainty and spatio-temporal structure of the data (Chapter 5), (iv). to extend LGCP models for marked point patterns with Negative Binomial count distributions and introduce Bayesian variable selection in LGCP modelling (Chapter 6). Objectives from the applied perspective are to: (i). assess the association of imported malaria cases and environmental factors with the local malaria incidence in Eswatini (Chapters 2 and 5), (ii). identify malaria burden hotspots based on point pattern surveillance data in Eswatini and survey geostatistical data in Togo (Chapter 3), (iii). detect S. mansoni and S. haematobium risk hotspots from schistosomiasis data in Togo (Chapter 4), (iv). estimate missing values in NDVI images derived from MODIS satellite data (Chapter 5). Finally, in Chapter 6 we summarise the work presented herein and discuss potential paths for future research.' 

authors:
- admin

date: "2019-05-08T00:00:00Z"
doi: "https://doi.org/10.5451/unibas-ep82190"
featured: true
image:
  caption: 
  focal_point: ""
  preview_only: false
projects:
- example
publication: University of Basel
publication_short:
publication_types:
- "7"
publishDate: "2022-07-29T00:00:00Z"
#slides: example
summary:
tags: []
title: 'Bayesian modelling of large spatio-temporal disease surveillance and environmental data.'
share: false
url_code: 
url_dataset: ""
url_pdf: "https://edoc.unibas.ch/82190/"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

