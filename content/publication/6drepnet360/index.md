---
title: "Towards Robust and Unconstrained Full Range of Rotation Head Pose Estimation"
authors:
- admin
- Ahmed A. Abdelrahman 
- Ayoub Al-Hamadi
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-03-21T00:00:00Z"
doi: "10.1109/TIP.2024.3378180"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing"
publication_short: ""

abstract: Estimating the head pose of a person is a crucial problem for numerous applications that is yet mainly addressed as a subtask of frontal pose prediction. We present a novel method for unconstrained end-to-end head pose estimation to tackle the challenging task of full range of orientation head pose prediction. We address the issue of ambiguous rotation labels by introducing the rotation matrix formalism for our ground truth data and propose a continuous 6D rotation matrix representation for efficient and robust direct regression. This allows to efficiently learn full rotation appearance and to overcome the limitations of the current state-of-the-art. Together with new accumulated training data that provides full head pose rotation data and a geodesic loss approach for stable learning, we design an advanced model that is able to predict an extended range of head orientations. An extensive evaluation on public datasets demonstrates that our method significantly outperforms other state-of-the-art methods in an efficient and robust manner, while its advanced prediction range allows the expansion of the application area. We open-source our training and testing code along with our trained models - https://github.com/thohemp/6DRepNet360.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Head pose estimation, Facial analysis
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/10477888
url_code: 'https://github.com/thohemp/6drepnet360'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{< pdfReader "/home/thorsten/Projects/thohemp.github.io/content/publication/6drepnet360/10477888.pdf" >}}