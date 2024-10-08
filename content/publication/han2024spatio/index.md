---
title: "Spatio-Temporal Road Traffic Prediction using Real-time Regional Knowledge"
authors:
- admin
- Jisun An
- Dongman Lee
date: 2021-08-23
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-23

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: For traffic prediction in transportation services such as car-sharing and ride-hailing, mid-term road traffic prediction (within a few hours) is considered essential. However, the existing road-level traffic prediction has mainly studied how significantly micro traffic events propagate to the adjacent roads in terms of short-term prediction. On the other hand, recent attempts have been made to incorporate regional knowledge such as POIs, road characteristics, and real-time social events to help traffic prediction. However, these studies lack in understandings of different modalities of road-level and region-level spatio-temporal correlations and how to combine such knowledge. This paper proposes a novel method that embeds real-time region-level knowledge using POIs, satellite images, and real-time LTE access traces via a regional spatio-temporal module that consists of dynamic convolution and temporal attention, and conducts bipartite spatial transform attention to convert into road-level knowledge. Then the model ingests this embedded knowledge into a road-level attention-based prediction model. Experimental results on real-world road traffic prediction show that our model outperforms the baselines.


# Summary. An optional shortened abstract.
summary: Proposes a method for mid-term traffic prediction using region-level data, improving road-level prediction accuracy over baselines.

tags:
- Multi-modal Dataset
- Floating Population
- Human Activity

featured: true

links:
- name: Custom Link
  url: https://www.arxiv.org/abs/2408.12882
url_pdf: https://www.arxiv.org/pdf/2408.12882
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
