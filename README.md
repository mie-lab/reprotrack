# 1st ACM SIGSPATIAL International Workshop on Reproducibility in tracking data analysis and mobility research

Co-located with SIGSPATIAL' 23, November 13th (Monday) 2023, Hamburg, Germany

![teaser](images/teaser.jpg?raw=True)

## Background and workshop goals

In 2015, a study estimated the rate of replicability of psychology studies published in top journals at about 40%, sending shock-waves through the community and starting what is called the replicability crises in psychology. Since then, subsequent studies showed that the problem of reproducible research is not limited to Psychology, but poses a systematic problem in all scientific disciplines. Very recently, researchers discussed the challenges of reproducibility in geoinformation science and spatial sciences and how to address them in practice. However, these best-practices are not yet adopted in all fields within GIScience.

Reproducibility is especially challenging in mobility analysis, a core area of research presented at ACM SIGSPATIAL. Here, our understanding of how people travel was greatly enhanced over the last years based on large-scale movement data such as call-detail record (CDR), check-in sequences from location-based social networks (LBSN) and GNSS tracking data sets. However, real-world data is often plagued by inaccuracies, such as GNSS noise, false labeling and limited tracking coverage, all of which require extensive preprocessing efforts. 
Preprocessing in movement data analysis is still not standardized and the processing steps and their outcomes are, therefore, often different across studies. Problematically, the results of studies based on mobility data strongly depend on the employed preprocessing methods. Thus, the variety of preprocessing methods hinders the comparability of research results in movement data analysis. They are further not documented comprehensively and prominently in many studies, limiting the reproducibility of mobility studies.

We aim to bring the community together in a workshop on reproducibility in tracking data analysis and mobility research to discuss and advance reproducibility and transparency in movement data analysis. The workshop will comprise an keynote talk, an interactive tutorial on standardizing tracking data analysis and a discussion section on necessary future efforts to improve the comparability of mobility research.

## Program

* Keynote on Reproducibility in Spatial Data Science
* Hands-on section: tracking data processing tutorials and interactive section
* Discussion on the future of reproducibility


## Hands-on tutorial with Trackintel

Our workshop is targeted at researchers working with tracking data who are interested to get to know new tools for standardized data preprocessing. The second part of the workshop will feature a specific tool developed to improve reproducibility, namely the open-source library [Trackintel](https://github.com/mie-lab/trackintel). Trackintel builds on an established data model for mobility data and aims to align preprocessing methods in a common framework. It is applicable to different types of tracking data and yields high-level representations such as locations, activity staypoints and trips, which are consistent with movement concepts in GIS and transport planning. The functionality of Trackintel will be shortly presented by the workshop organizers and demonstrated on a standard tracking dataset that is publicly available. Participants will then have the chance to work with their own tracking data. In the hands-on tutorial, participants will be asked to follow the preprocessing steps as well as to apply analysis tools yielding high-level information such as the length of trips, the data quality in terms of temporal tracking coverage, and transport mode split. With the tutorial, participants will gain a basic understanding of the procedures of reproducible mobility analysis and will be able to fairly compare the properties of their data with open-source datasets. 

## Organizers
- [Nina Wiedemann](https://baug.ethz.ch/en/department/people/staff/personen-detail.MjUzNzEy.TGlzdC82NzksLTU1NTc1NDEwMQ==.html), nwiedemann@ethz.ch
- [Henry Martin](https://n.ethz.ch/~martinhe/), martinhe@ethz.ch
- [Ye Hong](https://hongyeehh.github.io/), hongy@ethz.ch
- [Martin Raubal](https://www.raubal.ethz.ch/), mraubal@ethz.ch

[Mobility Information Engineering Lab, ETH Zürich](http://mie-lab.ethz.ch/)
