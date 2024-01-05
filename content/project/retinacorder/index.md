---
title: eye2you Retinacorder
summary: A handheld, smartphone-based fundus camera for early detection of retinal and systemic diseases.
tags:
  - Medical AI
  - Retinal Images
  - Android
  - eye2you
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
#  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
#url_code: ''
#url_pdf: ''
#url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "retinacorder-slides"` references `content/slides/retinacorder-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
The main product of eye2you: A medical device to examining the retina for different diseases and anatomical anomalies and to be used by non-expert medical personnel. 

Recording and analysis are powered by an artificial intelligence which provides feedback on the quality of the recorded image and the sufficiency of the covered retinal area. 

The recorded images are stitched to a panoramic retina image by taking the anatomical structure of the retina into account. The panoramic image can then be analyzed for specific diseases, anatomical anomalies, or measure anatomical features like cup-to-disc ratio of the optic nerve.

All computations are done on the smartphone using OpenCV, PyTorch, C++ and Kotlin. Models were optimized and ran in real time (<1s per model). 

****

**Example of stitching process**
![panorama](./panos_with_inputs.png)

