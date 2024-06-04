---
title: "An online semantic mapping system for extending and enhancing visual SLAM"
authors:
- admin
- Ayoub Al-Hamadi
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-05-01T00:00:00Z"
doi: "10.1016/j.engappai.2022.104830"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Engineering Applications of Artificial Intelligence"
publication_short: ""

abstract: We present a real-time semantic mapping approach for mobile vision systems with a 2D to 3D object detection pipeline and rapid data association for generated landmarks. Besides the semantic map enrichment the associated detections are further introduced as semantic constraints into a simultaneous localization and mapping (SLAM) system for pose correction purposes. This way, we are able generate additional meaningful information that allows to achieve higher-level tasks, while simultaneously leveraging the view-invariance of object detections to improve the accuracy and the robustness of the odometry estimation. We propose tracklets of locally associated object observations to handle ambiguous and false predictions and an uncertainty-based greedy association scheme for an accelerated processing time. Our system reaches real-time capabilities with an average iteration duration of 65 ms and is able to improve the pose estimation of a state-of-the-art SLAM by up to 68% on a public dataset. Additionally, we implemented our approach as a modular ROS package that makes it straightforward for integration in arbitrary graph-based SLAM methods.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- SLAM, Semantic Mapping
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S095219762200094X'
url_code: 
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

{{< rawhtml >}} 

<video width=100% controls autoplay>
    <source src="/videos/semanticslam.mp4" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}