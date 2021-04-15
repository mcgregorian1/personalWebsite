---
title: Improving near real-time forest disturbance monitoring using multi-source satellite data
summary: Identifying deforestation quickly is key to mitigating forest loss around the world. We believe leveraging the availability of near-instantaneous satellite data can both help effectively monitor without being computationally instensive and be accessible to relevant stakeholders.
tags:
- Remote sensing
- Forest ecology
date: "2019 - present"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

As one of the main drivers of biodiversity loss, deforestation is a major issue in Myanmar and has been increasing since the democratization of the country in the 1990s. Enforcement of forest regulations is often impossible due to the temporal latency of available forest loss data. Some near real-time (NRT) monitoring methods can detect deforestation within a day of occurrence, but only for clearing events at least 6 ha in size. Illegal logging in Myanmar, and elsewhere, often takes the form of smaller scale, selective removals. For the purposes of this research, “disturbance” will be used in descriptions as it is inclusive of both selective logging and clear-cut deforestation. In order for remote sensing to be relevant for policy enforcement, NRT monitoring methods must be refined to detect disturbance sooner, and at finer spatial scales. The overarching goal of this project is to make progress by combining recent developments in data availability, high-performance computing, and advanced statistical methods. We propose to develop a continuously validated monitoring system that assimilates multi-source remotely sensed imagery to provide daily updated disturbance probabilities for two protected areas in Myanmar. This involves two main objectives:
- Objective 1: Use a Bayesian ensemble approach and multi-source imagery to reduce the latency and improve the spatial resolution of NRT deforestation monitoring.
    - Daily disturbance probability maps will be calculated for study sites within Myanmar. Training and validation data will be obtained from in-country partners via collaborators at the Smithsonian Conservation Biology Institute (SCBI).
    - Updated probabilities will be determined by computing the likelihood of disturbance given image evidence from a variety of complementary image records, combined with a prior probability of disturbance based on factors such as local topography and human population density.
- Objective 2: Create a continuously ground-validated application system using the probability maps.
    - The daily maps will be available via a Google Earth Engine (GEE) app with multi-source imagery, including MODIS/VIIRS, Landsat 8, and Sentinels 1 and 2
    - The application will incorporate user (forest manager) interactive feedback by refining the training data, which will fix the current data creator / data user paradigm by closing the loop between the two actors.
