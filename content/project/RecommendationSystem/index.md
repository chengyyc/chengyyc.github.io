---
title: Santander Bank Product Recommendation
summary: |2-
  * Imputed missings of 14 million samples, performed EDA to demonstrate data patterns.
  * Implemented two methods in Python to do recommending: applied SVD to decompose the user-item matrix to establish a rating system, and utilized XGBoost to build a multiclass classification model.
  * Evaluated the two models by MAP@7, and output feature importance to obtain most significant variables.
tags:
  - Recommender System
date: "2020-05-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Picture by Yingyu
#  focal_point: Smart
---

In any business scenario where a company offers a diverse range of products and serves a broad customer base, the accuracy of product recommendations is crucial for both the company and its customers. The primary objective of this project is to construct a recommendation system for Santander Bank, ensuring the most suitable bank products suggestions. With a more effective recommendation system in place, Santander Bank can better meet the individual needs of all customers, ultimately enhancing overall customer satisfaction.
{style="text-align: justify;"}

The dataset contains information of 956 thousand virtual customers at Santander Bank, including both demographic details and their product purchase history. To tackle this recommendation challenge, I implemented two methods in Python: XGBoost and singular value decomposition (SVD). XGBoost is a scalable tree boosting system, which took customers’ information as input and bank product choices as output to build a robust multiclass classification model. Meanwhile, SVD is an efficient matrix factorization approach, which established a rating system based on customers’ purchase history. The performance of both methods was evaluated using mean average precision @ 7 (MAP@7), which demonstrated their effectiveness in generating accurate product recommendations. To further interpret the most influential features in determining customer product preferences, I used the XGBoost method to generate feature importance plots. This analysis revealed that the gross income of the household, customer seniority, and customer age are the potential significant features.
{style="text-align: justify;"}

Through the application of XGBoost and SVD methods, this project not only addresses the immediate goal of enhancing Santander Bank's recommendation system, but also contributes to a deeper understanding of the critical factors shaping customer preferences for more targeted and personalized recommendations.
{style="text-align: justify;"}







