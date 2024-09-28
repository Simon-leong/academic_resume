---
title: "Few-shot face sketch-to-photo synthesis via global-local asymmetric image-to-image translation"
authors:
- Yongkang Li
- admin
author_notes:
- "First Author"
- "Second Author"
date: "2024-07-13T00:00:00Z"
doi: "https://dl.acm.org/doi/10.1145/3672400"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-13T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*ACM Transactions on Multimedia Computing, Communications, and Applications*"
publication_short: ""

abstract: Face sketch-to-photo synthesis is widely used in law enforcement and digital entertainment, which can be achieved by image-to-image (I2I) translation. Traditional I2I translation algorithms usually regard the bidirectional translation of two image domains as two symmetric processes, so the two translation networks adopt the same structure. However, due to the scarcity of face sketches and the abundance of face photos, the sketch-to-photo and photo-to-sketch processes are asymmetric. Considering this issue, we propose a few-shot face sketch-to-photo synthesis model based on asymmetric I2I translation, where the sketch-to-photo process uses a feature-embedded generating network, while the photo-to-sketch process uses a style transfer network. On this basis, a three-stage asymmetric training strategy with style transfer as the trigger is proposed to optimize the proposed model by utilizing the advantage that the style transfer network only needs few-shot face sketches for training. Additionally, we discover that stylistic differences between the global and local sketch faces lead to inconsistencies between the global and local sketch-to-photo processes. Thus, a dual branch of the global face and local face is adopted in the sketch-to-photo synthesis model to learn the specific transformation processes for global structure and local details. Finally, the high-quality synthetic face photo can be generated through the global-local face fusion sub-network. Extensive experimental results demonstrate that the proposed Global-Local ASymmetric image-to-image translation algorithm (GLAS) compared to SOTA methods, at least improves FSIM by 0.0126, and reduces LPIPS (alex), LPIPS (squeeze), and LPIPS (vgg) by 0.0610, 0.0883, and 0.0719, respectively.

# Summary. An optional shortened abstract.
summary: Developing a three-stage asymmetric neural network training strategy for solving information scarcity in few shot contexts.

tags:

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: 'https://github.com/Simon-leong/Few-shot-Face-Sketch-to-Photo-Synthesis-via-Global-Local-Asymmetric-Image-to-Image-Translation'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

