---
title: The Lottery Ticket Hypothesis for Object Recognition
summary: To appear in IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2021
authors:
- admin
- Shishira R Maiya
- Kamal Gupta
- Hao Chen
- Larry Davis
- Abhinav Shrivastava
author_notes:
- "Equal contribution"
- "Equal contribution"
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
url_pdf: "https://arxiv.org/abs/2012.04643"
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

- Showed that lottery tickets obtained from ImageNet training don’t transfer when it comes to object recognition challenges in case of COCO. There are no universal tickets in pre-trained ImageNet models that can be used for downstream tasks without a drop in performance.

- With direct pruning, we find “task-specific” tickets  with  up  to  80%  sparsity  for  each  of  the  datasets and backbones.

- Analysed the behavior of tickets obtained for object recognition tasks,  with respect to various task attributes such as object size, frequency, and difficulty of detection.
