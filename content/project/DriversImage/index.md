---
title: Detecting Distracted Drivers through Camera Image Recognition
summary: |2-
    Responsibilities include:
  * Adopted two convolutional neural networks (CNN), ResNet50 and AlexNet, employing PyTorch to construct multiclassification models for drivers’ image processing and recognition.
  * Executed fine-tuning to prevent overfitting, and calculated confusion matrices for detailed comparison.
  * Attained an accuracy rate of 99%, validated through the percentage of correctly classified images.
tags:
  - Computer Vision
date: '2020-12-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Yingyu
  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Distracted driving poses a constant and significant threat, contributing to a striking number of traffic accidents. To enhance driver safety, the automatic detection of distracted behaviors becomes crucial. Therefore, the primary objective of this project is to develop a model capable of both detecting the presence of distracted behavior and identifying the specific class of the behavior on a given dataset of driver images.
{style="text-align: justify;"}

The dataset comprises numerous images capturing various driver behaviors, categorized into 10 classes, including safe driving and distracted behaviors like drinking, talking on the phone, talking to passenger, and so on. To address this image classification challenge, I implemented two convolutional neural networks, ResNet50 and AlexNet, to build multiclassification models using PyTorch in Python. I evaluated the model performance through accuracy, representing the percentage of correctly classified images. As a result, AlexNet achieved a 99% accuracy rate on both training set and validation set, demonstrating superior performance in solving this problem.
{style="text-align: justify;"}

To provide a clearer insight, I also computed a confusion matrix, detailing the probabilities of each class being predicted as any of the ten classes. This analysis helps in identifying the most challenging classes to classify, and areas for potential model improvement. A possible appealing improvement is to incorporate temporal context in the recognition and classification. By considering temporal sequences of actions, we may gain a better understanding of the driver's current behavior by examining their preceding actions, thereby enhancing the model's overall accuracy and effectiveness.
{style="text-align: justify;"}

