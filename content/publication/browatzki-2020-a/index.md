---
title: '3FabRec: Fast Few-Shot Face Alignment by Reconstruction'
authors:
- admin
- Christian Wallraven
date: '2020-06-01'
#publishDate: '2024-01-04T18:48:40.754651Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE Computer Society Conference on Computer Vision
  and Pattern Recognition*'
publication_short: '*CVPR 2020* *(Oral)*'
doi: 10.1109/CVPR42600.2020.00615
abstract: Current supervised methods for facial landmark detection require a large
  amount of training data and may suffer from overfitting to specific datasets due
  to the massive number of parameters. We introduce a semi-supervised method in which
  the crucial idea is to first generate implicit face knowledge from the large amounts
  of unlabeled images of faces available today. In a first, completely unsupervised
  stage, we train an adversarial autoencoder to reconstruct faces via a low-dimensional
  face embedding. In a second, supervised stage, we interleave the decoder with transfer
  layers to retask the generation of color images to the prediction of landmark heatmaps.
  Our framework (3FabRec) achieves state-of-the-art performance on several common
  benchmarks and, most importantly, is able to maintain impressive accuracy on extremely
  small training sets down to as few as 10 images. As the interleaved layers only
  add a low amount of parameters to the decoder, inference runs at several hundred
  FPS on a GPU.

summary:  Current supervised methods for facial landmark detection require a large
  amount of training data and may suffer from overfitting to specific datasets due
  to the massive number of parameters. [[...]](./publication/browatzki-2020-a/)

url_pdf: 'https://arxiv.org/pdf/1911.10448.pdf'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'
#url_video: '8601-oral.mp4'

links:
- name: arXiv
  url: https://arxiv.org/abs/1911.10448
- name: Video (1min)
  url: '8601-oral.mp4'
- name: Video (5min)
  url: '8601-oral.mp4'
    
featured: true

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - retinacorder


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "retinacorder"` references `content/slides/retinacorder/index.md`.
#   Otherwise, set `slides: ""`.
#slides: retinacorder
---
[//]: # (**Summary**)

<video controls autoplay muted>
  <source src="8601-1min.mp4" type="video/mp4">
</video>

****

**Conference Talk (5min)**

<video width="320" height="240" controls>
  <source src="8601-oral.mp4" type="video/mp4">
</video>

****

**A few examples**

Rows show the original, and the reconstruction itself, with predicted landmarks, with ground-truth landmarks, and with predicted landmark heatmaps, respectively.

The fifth column illustrates a failure case.

![examples](./featured__.png)

