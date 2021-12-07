---
title: We Can’t Have It Both Ways - Accepting the Trade-off of Detection Time and Accuracy in Multi-source, Near Real-time Deforestation Monitoring
event: American Geophysical Union (AGU) Annual Meeting 2021
event_url:

location: New Orleans, LA
address:
  street:
  city: 
  region: 
  postcode: ''
  country: United States

summary: Oral presentation for AGU 2021
abstract: Monitoring deforestation in near real-time continues to be a high priority for remote sensing science. The proliferation of Earth-observing satellites, and the emergence of time series approaches, promises higher accuracy detections with lower latency. But the potential trade-off between optimizing detection accuracy and time has been underexplored, and combining disparate information from multiple sensors remains challenging. We devised a straightforward approach to monitoring deforestation using multiple satellite image time series, and used multiobjective optimization to answer the following questions: Do multi-source approaches give higher accuracy, lower latency change detections compared to single-source? And, can a single approach optimize detection time and accuracy, or are there trade-offs? We used PlanetScope image sequences to create a validation set of deforestation events with high temporal accuracy in north-central Myanmar (n=159). Similar to CCDC, we estimated time series models from Landsat 8 and Sentinel-2 NDVI time series, and VV and VH backscatter from Sentinel-1. Standardized residuals were combined across sensors, and aggregated using a temporal weighting scheme before converting to a deforestation probability using logistic regression. We optimized for detection time, alongside Type 1 and II errors across a range of weighting parameters. Multi-source approaches were superior to any single-source approach, with both detection times and error rates being twice as good. We also show clear trade-offs between detection time and error rate: weighting scenarios with the fastest detections (median value of 2 days) had higher false positive (0.015) and false negative rates (0.23). Thus, we recommend that further developments focus on using multi-source time series to increase accuracy and reduce detection time. Users should also be aware of the inherent trade-offs in detection latency and accuracy, and be able to prioritize these differently across applications.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-12-12"
date_end: "2021-12-17"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: ""

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption:
  focal_point: Right

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["dissertation"]
---
