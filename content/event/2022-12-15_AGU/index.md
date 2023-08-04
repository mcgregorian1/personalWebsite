---
title: ASAP or AAAP? The Importance of Tradeoffs Between Detection Time and Accuracy for Multisource Deforestation Monitoring. 

event: American Geophysical Union (AGU) Annual Meeting 2022
event_url:

location: Chicago, IL
address:
  street:
  city: Chicago
  region: IL
  postcode: ''
  country: United States

summary: Poster presentation for AGU 2022
abstract: Detecting deforestation quickly and accurately has long been a focus of remote sensing, and with the large availability of satellite data, methods have continuously advanced. To lower temporal latency and increase accuracy, a growing number of studies have pursued multi-source approaches. For instance, in areas of persistent cloud cover, using synthetic aperture radar (SAR) may be the only source of observations. Typically, near real-time (NRT) monitoring approaches have used retrospective change detection methods to maximize an accuracy metric like the F1 score. Much less attention has been paid to potential parameter tradeoffs: Can faster detections be achieved with alternative inputs, and at what cost to accuracy? We developed a novel NRT approach that monitors Landsat-8, Sentinel-2, and Sentinel-1 SAR time series in order to calculate a daily probability of disturbance. After combining standardized residuals of sensor-specific models, we converted an exponentially-weighted moving average (EWMA) to a disturbance probability. We explored how altering the EWMA sensitivity affected detection accuracy (F1) and latency (days until detection) using training data manually identified from PlanetScope in northern Myanmar. For a moderate parameterization, the algorithm detected disturbances within a median of 1-2 observations (mean of 3.3-9.5 days), with an overall F1 score of greater than 90%. We found two main trade-offs. The most sensitive inputs detected quickly (average of 3.3-9.5 days) compared to the conservative inputs (9.5-15.6 days) at the expense of accuracy, with overall F1 scores of above 91% and 95%, respectively. Even though including S1 increased time series density, it did not result in lower latency or higher accuracy detections, primarily because of its lower signal-to-noise ratio. Once understood and accounted for, the tradeoffs can allow for applications in a variety of contexts. Plus, we anticipate that as more data becomes available (e.g. NISAR L-band SAR), the method will give faster detections. Overall, our novel, multi-source approach clearly advances NRT deforestation monitoring by providing a quick, simple, and effective way of combining multi-source satellite data. **NB**: This poster is a slightly-updated version of the one used for the conference in Germany in September. To see this poster in full detail, please see the event for the NCSU Graduate Research Symposium


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-12-12"
date_end: "2022-12-17"
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
