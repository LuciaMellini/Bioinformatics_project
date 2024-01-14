# Disease subtype discovery using multi-omics data integration
This project has the aim of clustering  samples regarding Pancreatic adenocarcinoma coming from a dataset of The Cancer Genome Atlas. In particular we want to partition the samples into disease subtypes, and compare the solutions with the one proposed in[^1].
The main document is a report that goes into detail about:
* data pre-processing
* used data integration methods for the multi-omics data
* chosen clustering methods
* comparison of the results with respect to iCluster method

This repository also contains the R code used for all the computation needed in the sections outlined in the report.

## Contents
* `project.Rmd` is the R notebook that contains the code and step-by-step description of the 
* `report.tex` contains the $\LaTeX$ source code

For the rendering of the R notebook in `html` and the pdf version of the report, refer to release.

[^1]Adam Abeshouse, Jaeil Ahn, Rehan Akbani, Adrian Ally, Samirkumar Amin, Christopher D
Andry, Matti Annala, Armen Aprikian, Joshua Armenia, Arshi Arora, et al. _The molecular
taxonomy of primary prostate cancer_. Cell, 163(4):1011–1025, 2015