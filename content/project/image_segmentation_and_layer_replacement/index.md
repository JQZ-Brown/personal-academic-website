---
title: Image segmentation and layer replacement
summary: The final project for CS1430 Computer Vision.
tags:
- Course
- Deep Learning
date: "2021-12-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Poster
  focal_point: Smart



url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This is the final project for *CS1430 Computer Vision*, collaborated with Cameron Fiore, Colin Jones, and Martin Gil del Real. We propose an automatic photo edit-
ing tool. This tool takes in visual data (i.e. a photo or a
video) and, using a deep-learning model, automatically seg-
ments the input by the different objects that it recognizes.
The system then separates the original input into ”layers”,
with each layers corresponding to a recognized object in
the input. The user can then select which object in the input
to modify, and our tool automatically replaces the selected
object with an image of user choice.
