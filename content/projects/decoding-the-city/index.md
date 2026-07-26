---
title: "Decoding the City"
summary: "Spatial Data Science and Explainable AI for Urban Accessibility"
date: 2026-07-26

weight: 2

type: project

tags:
  - Spatial Data Science
  - GIScience
  - Urban Analytics
  - Explainable AI
  - Urban Accessibility
  - Python

featured: true

image:
  filename: featured.png
  preview_only: true
---

## Spatial Data Science for Urban Accessibility

**Decoding the City** is an open research project that explores how **Spatial Data Science**, **Geographic Information Science (GIScience)** and **Explainable Artificial Intelligence (XAI)** can improve the understanding of urban accessibility and support evidence-based territorial planning.

The project combines open geospatial data, pedestrian network analysis, unsupervised machine learning, explainable artificial intelligence and interactive visualisation within a reproducible Python workflow.

Originally developed using the municipality of Porto, Portugal, as a case study, the analytical framework was designed to be transferable to other cities and territorial contexts.

---

## Key Features

- Building-level accessibility analysis
- Pedestrian network modelling
- Open geospatial data integration
- Spatial clustering
- Explainable Artificial Intelligence
- Interactive data visualisation
- Reproducible Python workflows
- Open Science

---

## Research Objectives

The project aims to:

- develop reproducible methods for analysing urban accessibility;
- identify spatial inequalities through building-level indicators;
- integrate machine learning with Geographic Information Science;
- improve model interpretability using Explainable AI;
- support transparent and evidence-based territorial decision-making.

---

## Methodological Workflow

The analytical workflow integrates seven main stages:

1. Data integration
2. Spatial data preparation
3. Pedestrian network analysis
4. Accessibility indicator construction
5. Spatial clustering
6. Explainable Artificial Intelligence
7. Interactive visualisation and interpretation

---

## 1. Data Integration

The project combines heterogeneous geographic and statistical datasets, including:

- OpenStreetMap building footprints;
- pedestrian street networks;
- population census data;
- administrative boundaries;
- public and commercial service locations;
- urban infrastructure data.

The datasets are integrated within a common spatial analytical environment.

---

## 2. Data Preparation

Spatial preprocessing includes:

- geometry and topology correction;
- coordinate reference system harmonisation;
- spatial data validation;
- filtering of residential buildings;
- spatial joins;
- feature engineering;
- data quality control.

These procedures ensure consistency between datasets obtained from different sources and formats.

---

## 3. Pedestrian Network Analysis

Urban accessibility is modelled through pedestrian networks rather than straight-line distance.

Buildings and service locations are connected to their nearest network nodes. Shortest pedestrian routes are then calculated to evaluate access to essential urban services.

The workflow includes:

- pedestrian network construction;
- building-to-network connection;
- service-to-network connection;
- shortest-path calculation;
- walking-distance measurement;
- service-accessibility indicators.

This network-based approach provides a more realistic representation of pedestrian movement through the urban environment.

---

## 4. Building-Level Accessibility

Accessibility is evaluated at the individual-building level.

The analysis considers:

- average pedestrian distance to services;
- number of accessible services;
- diversity of service categories;
- distribution of residents aged 65 years and over;
- spatial differences between central and peripheral urban areas.

Working at the building level helps reveal local inequalities that may be concealed when data are aggregated into larger administrative units.

---

## 5. Spatial Data Science and Clustering

The project applies exploratory analysis and unsupervised machine-learning algorithms to identify latent patterns in urban accessibility.

Implemented algorithms include:

- K-Means;
- Agglomerative Clustering;
- Gaussian Mixture Models.

Cluster quality is assessed using:

- Silhouette Score;
- Calinski–Harabasz Index;
- Davies–Bouldin Index;
- Akaike Information Criterion;
- Bayesian Information Criterion.

The comparison between algorithms supports the selection of spatially coherent and analytically interpretable urban clusters.

---

## 6. Explainable Artificial Intelligence

Explainable Artificial Intelligence is used to identify the variables that most strongly influence cluster membership and accessibility patterns.

Implemented methods include:

- SHAP;
- LIME;
- Decision Trees;
- Random Forests.

These techniques provide complementary forms of interpretation:

- **Decision Trees** represent model behaviour through transparent decision rules.
- **Random Forests** estimate the overall importance of the analytical variables.
- **SHAP** explains global and individual model outputs.
- **LIME** provides local explanations for selected buildings or observations.

The interpretability layer helps translate complex analytical outputs into information that can be understood by researchers, planners and territorial decision-makers.

---

## 7. Interactive Visualisation

The results are explored through interactive visual components developed in Python.

These include:

- accessibility maps;
- service-distribution maps;
- building-level population maps;
- cluster maps;
- statistical summaries;
- correlation matrices;
- feature-importance charts;
- SHAP visualisations;
- local model explanations.

Interactive visualisation supports the exploration of spatial patterns and strengthens communication between technical analysis and territorial interpretation.

---

## Technologies

The analytical workflow was developed using open-source software.

### Programming and data processing

- Python
- Pandas
- NumPy

### Geographic data processing

- GeoPandas
- Shapely
- PyProj

### Network analysis

- OSMnx
- NetworkX

### Machine learning and Explainable AI

- Scikit-learn
- SHAP
- LIME

### Visualisation

- Plotly
- Dash
- Matplotlib

---

## Case Study: Porto

The project was initially applied to the municipality of Porto, Portugal.

Porto provides a relevant case study because of its:

- dense and heterogeneous urban structure;
- differences between central and peripheral areas;
- uneven distribution of essential services;
- ageing population;
- availability of open geographic and statistical data.

The analysis revealed a marked spatial contrast between areas with high service accessibility and peripheral areas where lower accessibility coincides with greater concentrations of older residents.

---

## Scientific Contributions

The project demonstrates how Spatial Data Science can strengthen urban geographic analysis through:

- reproducible analytical workflows;
- building-level accessibility assessment;
- pedestrian network modelling;
- unsupervised spatial segmentation;
- explainable machine learning;
- transparent territorial indicators;
- interactive visual analytics;
- evidence-based urban planning.

It also provides a technical framework that can be adapted to other cities and spatial contexts.

---

## Open Science

**Decoding the City** follows Open Science principles by promoting:

- transparent analytical methods;
- reproducible computational workflows;
- public source code;
- methodological reuse;
- accessible documentation;
- open geographic information;
- collaborative research.

The public repository contains the analytical code and supporting project materials.

---

## Related Publication

The project supports the following scientific publication:

> **Machado, R.** *Decoding the City: Data Science and AI for Understanding Urban Accessibility.* Communications in Computer and Information Science, Springer.

The publication presents the Porto case study, including the accessibility indicators, clustering algorithms, model-evaluation procedures and Explainable AI techniques that form the scientific basis of the project.

---

## Future Development

Planned developments include:

- additional urban accessibility indicators;
- sensitivity analysis across walking thresholds;
- spatial autocorrelation analysis;
- local spatial cluster identification;
- comparison between buildings and aggregated spatial units;
- multi-city comparative analysis;
- expanded interactive web applications;
- decision-support tools;
- integration with GEOInsightLab.

---

## Source Code

The source code and analytical materials are available in the public GitHub repository:

[View Decoding the City on GitHub](https://github.com/RobertoOlivetree/decoding-the-city)
