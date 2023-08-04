---
title: Improving near real-time forest disturbance monitoring using multi-source satellite data
summary: Identifying deforestation quickly is key to mitigating forest loss around the world. We believe leveraging the availability of near-instantaneous satellite data can both help effectively monitor without being computationally intensive and be accessible to relevant stakeholders.
tags:
- Remote sensing
- Forest ecology
date: "2019 - 2023"

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

The proliferation of satellite imagery has facilitated the analysis of deforestation trends using multi-source time series approaches. This combination of long-term data sources can be crucial for near real-time (NRT) deforestation monitoring in tropical regions with extensive cloud cover. Yet despite recent progress, methods in multi-source, NRT monitoring have experienced issues with trade-offs between accuracy and latency, the lack of external spatial data, and general inability to incorporate users into the workflow. To address these limitations, my dissertation focused on three main topics: first, a novel, NRT detection algorithm was created to explicitly assess multiple spectra of trade-offs; second, landscape processes were incorporated into the algorithm using a Bayesian approach; and finally, we expanded the methodology to develop a continuously-improving model by integrating input from *in-situ* users.
    
The majority of the analysis was conducted in R, including processing of satellite imagery, modelling with linear models and exponentially-weighted moving averages, and spatial analysis. Google Earth Engine was used for the initial formatting and downloading of training data, while PLANET imagery was used to manually identify training points. Other technical skills used for the project include Python, ArcGIS, and QGIS.
