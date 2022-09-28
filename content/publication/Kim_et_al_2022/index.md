---
title: "Using GitHub Actions continuous integration to automate quality assurance and control of data on ecological dynamics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Albert Y. Kim
- Valentine Herrmann
- Ross Bareto
- Brianna Calkins
- Erika B. Gonzalez-Akre
- Daniel J. Johnson
- Jennifer Jordan
- Lukas Magee
- admin
- Nicolle Montero
- Karl Novak
- Teagan Rogers
- Jessica Shue
- Kristina J. Anderson-Teixeira

date: "2022-09-28"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-06"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Methods in Ecology and Evolution
publication_short:

abstract: In an era of rapid environmental change, accurate data on ecological dynamics are essential to understanding the resistance and resilience of ecological systems, and the services they provide, to multiple global change drivers. Field data collection errors are common, and researchers often struggle to keep up with data checking until months or even years after data have been collected, at which point many errors can no longer be corrected. The lag between data collection and analysis can also result in slow detection of anomalous dynamics. Needed is a system in which data quality assurance and control (QA/QC), along with basic data summaries, can be automatically conducted immediately following data collection. Here, we implement and test a cyberinfrastructure system to accomplish this. We used GitHub Actions continuous integration (CI) to automate 1) data QA/QC, in particular error checking and naive anomaly detection and 2) the running of routine scripts for data wrangling to produce cleaned data sets ready for analysis. We implemented and tested this system on two annual tree mortality censuses and a dendrometer band survey at two ForestGEO large forest dynamics plots':' Smithsonian Conservation Biology Institute and Harvard Forest. This system automation had numerous benefits. It produced a dashboard providing near real-time information on data collection status and errors requiring correction, resulting in final data sets free of detectable errors. Second, it produced an apparent learning effect among field technicians':' original error rates in field data collection declined significantly following implementation of the system. By implementing CI schemes, researchers can ensure that data sets are free of any errors for which a test can be coded. The result is dramatically improved data quality, increased skill among technicians, and reduced need for expert oversight. Furthermore, CI implementation can reveal anomalous ecological trends as they occur, allowing researchers to adjust sampling to capture unexpected dynamics. Thus, by reducing the time between data collection and analysis, CI stands to accelerate the pace of ecological field research.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.13982'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Winter in the Forest-GEO plot at SCBI.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- scbi-forestgeo

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
