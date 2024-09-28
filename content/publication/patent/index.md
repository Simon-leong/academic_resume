---
title: "Method for Smoke Removal in Fire Images Based on Improved Cycle-Dehaze Neural Network"
authors:
- admin
- Qingxiang meng
- Jinchun Liu
- Tonghe Zhang
author_notes:
- "First Author"
- "Second Author"
- "Third Author"
- "Forth Author"
date: "2023-07-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract:  The present invention introduces a fire image smoke removal method based on an enhanced Cycle-Dehaze neural network. It utilizes two luminance conversion functions to create a virtual exposure image for overexposed and underexposed pixel values in the input image. A multi-exposure image fusion is then performed using high- and low-frequency information, effectively addressing issues in fire background imaging, such as uneven illumination and ghosting. Additionally, the invention improves the traditional Cycle-Dehaze neural network by incorporating a dynamic dense residual block for smoke feature enhancement and introducing the CBAM attention mechanism, which boosts classification accuracy between relevant and irrelevant domains. To further tackle color distortion and texture blurring in current neural network-based smoke removal, a color loss function is added to the original loss function. This enhances color recognition in the SF-Cycle-Dehaze generator and discriminator, significantly improving the performance of mainstream de-smoking image reconstruction models.

# Summary. An optional shortened abstract.
summary: The present invention introduces a fire image smoke removal method based on an enhanced Cycle-Dehaze neural network.

tags:

featured: true

links:
- name: Custom Link
  url: 
url_pdf: 
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
