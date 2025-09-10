# Estimating the population with intellectual and developmental disabilities in the United States: A new model-based method

Accurate estimates of the adult population (ages 18-64) with intellectual and developmental disabilities (IDD) are crucial for developing policies and services that effectively support the well-being of this population. Although accurate estimates rely upon nationally representative data sources, in the United States, data that yield such estimates were last collected in 2018. Available survey data regarding cognitive functional limitation are not sufficient to identify and distinguish the population with IDD from populations with other disabilities related to cognition. State-level administrative records with measures of IDD only capture data from individuals participating in government programs, offering incomplete population insights. This article presents a model-based method utilizing existing nationally representative survey data functional limitations, activities of daily living limitations (ADL), and instrumental activities of daily living limitations (IADL) to provide an out-of-sample accurate estimate of the IDD population.
Proxy variables for IDD are first constructed utilizing National Health Interview Survey (NHIS) data from 2013 to 2017 by incorporating limitations associated with IDD along with factors like educational attainment. Resultant proxy variable estimates are then used to construct proxy proportion models, which are validated by comparing measures of agreement with available IDD information within the NHIS, for the same period. Model estimates are based on data from current nationally representative surveys to demonstrate capacity to generate national, state, and county-level estimates of the population with IDD. 
Estimates based on this model will provide stronger support to organizations and advocacy groups in their efforts to offer services and assistance to people with IDD. 

## Description

The purpose of this project is to provide the disability research community with a method of estimating the population of people with ID, DD, and IDD due to category exclusion in nationally representative surveys.

## Getting Started

### Dependencies

* Developed in R 4.5.1
* Packages: 

```{r}
library(haven)
library(tidyverse)
library(epiR)
library(survey)
library(caret)
library(pROC)
library(broom)
```

## Authors

Stacia Kingsbury, Nate Thomas, and Andrew Houtenville

## Funding Acknowledgment

The contents of this manuscript were developed under a grant from the National Institute on Disability, Independent Living, and Rehabilitation Research (NIDILRR grant number 90RTGE0005). NIDILRR is a Center within the Administration for Community Living (ACL), Department of Health and Human Services (HHS). The contents of this article do not necessarily represent the policy of NIDILRR, ACL, or HHS, and you should not assume endorsement by the Federal Government.