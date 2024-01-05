---
title: TalkingData AdTracking Fraud Detection
summary: |2-
  * Preprocessed 20 million data samples, built visualization to show distribution of predictors.
  * Conducted feature engineering generating new features by feature splitting and grouping operation.
  * Incorporated RandomForest and LightGBM methods to realize classification in Python, calculated AUC of testing set to evaluate both models, achieving a score of 0.95.
tags:
  - Fraud Detection
date: "2019-12-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Image may be subject to copyright.
#  focal_point: Smart
---

For companies advertising their application online, they would naturally expect that every click on their ad leads to a download of the application. However, click fraud can happen at an overwhelming volume, resulting in misleading click data and wasted money. The primary objective of this project is to develop an algorithm that can predict whether a user will download a mobile application after clicking on its ad.
{style="text-align: justify;"}

The provided dataset includes click information, such as IP address, device type, and click time, serving as predictors, with the app download status as the response variable. To address this challenge, I first expanded the set of predictors by feature splitting and grouping operations, since the number of original predictors is limited. Leveraging these new features, two machine learning approaches were implemented in Python: random forest and LightGBM. Both approaches aimed to construct a classification model which can efficiently predict whether a click will lead to a download. The performance of the methods was evaluated using the AUC metric. As a result, the random forest model achieved a score of 0.9, and the LightGBM model performed better with a score of 0.95, which successfully tackled the challenges posed by click fraud.
{style="text-align: justify;"}