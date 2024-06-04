---
title: "6D Rotation Representation For Unconstrained Head Pose Estimation"
authors:
- admin
- Ahmed A. Abdelrahman 
- Ayoub Al-Hamadi
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-10-18T00:00:00Z"
doi: "10.1109/ICIP46576.2022.9897219"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-conference"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE International Conference on Image Processing (ICIP)"
publication_short: ""

abstract: In this paper, we present a method for unconstrained end-to-end head pose estimation. We address the problem of ambiguous rotation labels by introducing the rotation matrix formalism for our ground truth data and propose a continuous 6D rotation matrix representation for efficient and robust direct regression. This way, our method can learn the full rotation appearance which exceeds the capabilities of previous approaches that restrict the pose prediction to a narrow-angle for satisfactory results. In addition, we propose a geodesic distance-based loss to penalize our network with respect to the SO(3) manifold geometry. Experiments on the public AFLW2000 and BIWI datasets demonstrate that our proposed method significantly outperforms other state-of-the-art methods by up to 20%. We open-source our training and testing code along with our trained models - https://github.com/thohemp/6DRepNet.

# Summary. An optional shortened abstract.
summary: In this paper, we present an advanced method for unconstrained end-to-end head pose estimation using a continuous 6D rotation matrix representation and geodesic distance-based loss, achieving superior performance on AFLW2000 and BIWI datasets by up to 20% over previous approaches.

tags:
- Head pose estimation, Facial analysis
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9897219
url_code: 'https://github.com/thohemp/6drepnet'
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
projects: [RoboAssist, AutoKoWaT]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" # example
---
