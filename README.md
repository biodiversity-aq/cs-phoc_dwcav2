# Mapping CS-PHOC dataset to DwCA v2

This repository is used to manage data transformation script and output for mapping exercise of a survey use case dataset into the DwCA v2.

## Repo structure

```         
.
├── LICENSE
├── README.md
├── _quarto.yml           : Quarto config
├── cs-phoc_dwcav2.Rproj  : R project file
├── docs                  : rendered Quarto files for GitHub Pages
├── index.qmd             : Quarto file wtih data transformation script
├── output                : mapped DwCAv2 tables
├── renv                  : renv files for dependencies
└── renv.lock             : describes the state of project's library
```

## Getting started

This project uses \[renv\](<https://rstudio.github.io/renv/>) to manage the dependencies in a virtual environment. Please try the following command to load the dependencies:

```{r}
renv::restore()
```

R version 4.4.2 was used the scripts in this repository.

## Acknowledgement

This work is part of the ADVANCE project funded by BELSPO (BELSPO project RT/23/ADVANCE).

## Bibliographic citation

The dataset used for this exercise:

Woodman S M, Borras-Chavez R, Goebel M E, Torres D, Aguayo A, Krause D J
(2024). CS-PHOC: weekly census counts of Southern Ocean phocids at Cape
Shirreff, Livingston Island. Version 2.2. SCAR - AntOBIS. Samplingevent
dataset. https://doi.org/10.48361/gklk1u accessed via GBIF.org on
2025-01-07.
