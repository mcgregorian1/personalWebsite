---
title: Improving near real-time forest disturbance monitoring using multi-source satellite data
summary: Identifying deforestation quickly is key to mitigating forest loss around the world. We believe leveraging the availability of near-instantaneous satellite data can both help effectively monitor without being computationally intensive and be accessible to relevant stakeholders.
tags:
- Remote sensing
- Forest ecology
date: "2019 - present"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

As one of the main drivers of biodiversity loss, deforestation is a major issue in Myanmar and has been increasing since the democratization of the country in the 1990s. Enforcement of forest regulations is often impossible due to the temporal latency of available forest loss data. Some near real-time (NRT) monitoring methods can detect deforestation within a day of occurrence, but only for clearing events at least 6 ha in size. Illegal logging in Myanmar, and elsewhere, often takes the form of smaller scale, selective removals. For the purposes of this research, “disturbance” will be used in descriptions as it is inclusive of both selective logging and clear-cut deforestation. In order for remote sensing to be relevant for policy enforcement, NRT monitoring methods must be refined to detect disturbance sooner, and at finer spatial scales. The overarching goal of this project is to make progress by combining recent developments in data availability, high-performance computing, and advanced statistical methods. We propose to develop a continuously validated monitoring system that assimilates multi-source remotely sensed imagery to provide daily updated disturbance probabilities for two protected areas in Myanmar. 

My original idea for the research involved three distinct chapters:
- Chapter 1: Build a multi-source, NRT monitoring algorithm that uses a novel, efficient aggregation method to explore the trade-offs between decreasing temporal latencies while improving spatial accuracy. Ideally this could be easily turned into a monitoring tool for stakeholders to use.
- Chapter 2: Integrate a Bayesian approach to incorporate biogeographical characteristics of the study area as prior predictors of disturbance to understand how much that would help improve the results of Chapter 1. This required in-depth knowledge of the local, human side of deforestation.
- Chapter 3: At first, we were going to use the output of Chapter 1 to predict elephant presence in Gabon, since we had anecdotal knowledge they were attracted to recent disturbances. This became unfeasible due to data, thus the focus changed to predicting vulture presence near illegal gold mining in Peru because, similar to the elephants, it was suggested that they were attracted to the disturbances. This could lead to chemical poisoning of the animals.
    
The majority of the analysis takes place in R, including processing of satellite imagery, modelling with linear models and exponentially-weighted moving averages, and spatial analysis. Google Earth Engine was used for the initial formatting and downloading of training data, while PLANET's imagery and API was used to manually identify training points. Other technical skills used for the project include Python, ArcGIS, and QGIS.
