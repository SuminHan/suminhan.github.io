---
title: 'Urban Vibrancy Embedding and Application on Traffic Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yeji Lee
  - Jisun An
  - Dongman Lee

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: 2025-02-09
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE BigComp 2025
publication_short: IEEE BigComp 2025


abstract: "Urban vibrancy reflects the dynamic human activity within urban spaces and is often measured using mobile data that captures floating population trends. This study proposes a novel approach to derive Urban Vibrancy embeddings from real-time floating population data to enhance traffic prediction models. Specifically, we utilize variational autoencoders (VAE) to compress this data into actionable embeddings, which are then integrated with long short-term memory (LSTM) networks to predict future embeddings. These are subsequently applied in a sequence-to-sequence framework for traffic forecasting. Our contributions are threefold: (1) We use principal component analysis (PCA) to interpret the embeddings, revealing temporal patterns such as weekday versus weekend distinctions and seasonal patterns; (2) We propose a method that combines VAE and LSTM, enabling forecasting dynamic urban knowledge embedding; and (3) Our approach improves accuracy and responsiveness in traffic prediction models, including RNN, DCRNN, GTS, and GMAN. This study demonstrates the potential of Urban Vibrancy embeddings to advance traffic prediction and offer a more nuanced analysis of urban mobility."

# Summary. An optional shortened abstract.
summary: Urban Vibrancy embeddings from real-time data improve traffic prediction via VAE and LSTM.

tags:
  - Urban Vibrancy
  - Floating Population
  - Traffic Forecasting

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'IEEEBigComp25_Urban_Vibrancy_Embedding_and_Application_on_Traffic_Prediction.pdf'
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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: han2023enhancing
---

For the floating population visualization, refer to <a href="https://render-seoul-population-viz.onrender.com/">https://render-seoul-population-viz.onrender.com/</a>.

<iframe width="685" height="1217" src="https://www.youtube.com/embed/gMXvLWcDBXc" title="서울의 심장박동 (LTE생활인구)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
