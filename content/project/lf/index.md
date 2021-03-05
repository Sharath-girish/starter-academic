---
title: A Unified Learning-Based Framework for Light Field Reconstruction From Coded Projections
summary: IEEE Transactions on Computational Imaging (TCI), 2019
weight: 69
authors: 
- Anil Kumar Vadathya
- admin
- Kaushik Mitra
# tags:
# - Deep Learning
date: "2021-03-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: ""

#image:
#  caption: Photo
#  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
url_pdf: "https://ieeexplore.ieee.org/abstract/document/8878019"
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

- Proposed a unified deep learning based framework for LF reconstruction from coded measurements. Our main
step is the disparity estimation network DisparityNet, which we train using indirect supervision from viewsynthesis.

- Using our reconstruction algorithm analyzed three different LF reconstruction frameworks 1) compressive light field (CLF) 2) coded aperture (CA) and 3) focus-defocus (FocDef) image pair.

- Showed that with our unified LF reconstruction pipeline, we are on par with the state-of-the-art techniques
in all the multiplexing schemes. Our FocDef approach with no additional hardware requirement performs better than hardware intensive CLF and CA. 

- Demonstrated that we can reconstruct high resolution light field from real focus-defocus image pair captured using a DSLR.
