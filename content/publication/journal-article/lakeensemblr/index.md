---
title: "LakeEnsemblR: An R package that facilitates ensemble modelling of lakes"
authors:
- Tadhg Moore
- Jorrit P. Mesman
- Robert Ladwig
- Johannes Feldbauer
- Freya Olsson
- Rachel M. Pilla
- Tom Shatwell
- Jason J. Venkiteswaran
- Austin D. Delany
- Hilary Dugan
- Kevin C. Rose
- Jordan S. Read
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2021-05-29T00:00:00Z"
doi: "10.1016/J.ENVSOFT.2021.105101"
slug: "LakeEnsemblR"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Environmental Modelling & Software* (143)"
publication_short: ""

abstract: Model ensembles have several benefits compared to single-model applications but are not frequently used within the lake modelling community. Setting up and running multiple lake models can be challenging and time consuming, despite the many similarities between the existing models (forcing data, hypsograph, etc.). Here we present an R package, LakeEnsemblR, that facilitates running ensembles of five different vertical one-dimensional hydrodynamic lake models (FLake, GLM, GOTM, Simstrat, MyLake). The package requires input in a standardised format and a single configuration file. LakeEnsemblR formats these files to the input required by each model, and provides functions to run and calibrate the models. The outputs of the different models are compiled into a single file, and several post-processing operations are supported. LakeEnsemblR's workflow standardisation can simplify model benchmarking and uncertainty quantification, and improve collaborations between scientists. We showcase the successful application of LakeEnsemblR for two different lakes.

# Summary. An optional shortened abstract.
summary: Here we present an R package, LakeEnsemblR, that facilitates running ensembles of five different vertical one-dimensional hydrodynamic lake models (FLake, GLM, GOTM, Simstrat, MyLake). The package requires input in a standardised format and a single configuration file. LakeEnsemblR formats these files to the input required by each model, and provides functions to run and calibrate the models. The outputs of the different models are compiled into a single file, and several post-processing operations are supported.

tags:
- Calibration
- Ensemble Modelling
- Hydrodynamics
- R Package
- Lake Modelling
- LakeEnsemblR
- Open-source software

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://reader.elsevier.com/reader/sd/pii/S1364815221001444?token=15D653A113A32FF85B5B7BBBB1C1A98EC37CE9C7DA9E6E52B4E49DAB5D6744BE78E7D09AA5A6D7B4A05B33DAED68DE11&originRegion=eu-west-1&originCreation=20221103115946
url_code: 'https://github.com/aemon-j/LakeEnsemblR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Conceptual overview of the LakeEnsemblR package showing the main folder structure and important functions.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [lakeensemblr]
networks: [aemon-j]

---

Download and install LakeEnsemblR from [here](https://github.com/aemon-j/LakeEnsemblR).

