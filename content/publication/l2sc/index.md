---
title: "L2CS-Net : Fine-Grained Gaze Estimation in Unconstrained Environments"
authors:
- Ahmed A. Abdelrahman 
- admin
- Aly Khalifa
- Ayoub Al-Hamadi
- Laslo Dinges
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-10-23T00:00:00Z"
doi: "10.1109/ICFSP59764.2023.10372944"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-conference"]

# Publication name and optional abbreviated publication name.
publication: "2023 8th International Conference on Frontiers of Signal Processing (ICFSP)"
publication_short: ""

abstract: Human gaze is a crucial cue used in various applications such as human-robot interaction and virtual reality. Recently, convolution neural network (CNN) approaches have made notable progress in predicting gaze direction. The performance of existing appearance-based gaze methods remains unsatisfactory due to the uniqueness of eye appearance, lightning conditions, and the diversity of head pose and gaze directions. In this paper, we propose a novel multi-loss two-branch CNN architecture (L2CS-Net) to explicitly learn the discriminative features for each gaze angle by predicting each gaze angle using a separate fully connected layer and loss function. In addition, we introduce a new multi-loss gaze function that consists of combined classification and regression losses to further enhance the model performance. We perform gaze classification utilizing a softmax layer along with cross-entropy loss. To obtain fine-grained predictions, we calculate the expectation of the gaze-class probabilities followed by a Mean Squared Error (MSE) loss. We evaluated our model with two popular datasets collected with unconstrained settings. Our proposed model achieves state-of-the-art performance on the MPIIGaze and Gaze360 datasets, respectively. We make our code open source at https://github.com/Ahmednull/L2CS-Net.

# Summary. An optional shortened abstract.
summary: In this paper, we present an new method for gaze estimation using a multi loss approach.

tags:
- Gaze estimation, Facial analysis
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10372944
url_code: 'https://github.com/Ahmednull/L2CS-Net'
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
