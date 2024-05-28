---
title: "Robust Depth Enhancement via Polarization Prompt Fusion Tuning"
collection: publications
permalink: 'https://arxiv.org/abs/2404.04318'
excerpt: "<img src='/images/pol.png' width='450' height='300'>"
date: 2024-01-01
venue: 'CVPR'
paperurl: 'https://arxiv.org/abs/2404.04318'
citation: 'Ikemura, K., Huang, Y., Heide, F., Zhang, Z., Chen, Q., & Lei, C. (2024). Robust Depth Enhancement via Polarization Prompt Fusion Tuning. In <i>Proceedings of the ieee/cvf conference on computer vision and pattern recognition</i>.'
---

Existing depth sensors are imperfect and may provide inaccurate depth values in challenging scenarios, such as in the presence of transparent or reflective objects. In this work, we present a general framework that leverages polarization imaging to improve inaccurate depth measurements from various depth sensors. Previous polarization-based depth enhancement methods focus on utilizing pure physics-based formulas for a single sensor. In contrast, our method first adopts a learning-based strategy where a neural network is trained to estimate a dense and complete depth map from polarization data and a sensor depth map from different sensors. To further improve the performance, we propose a Polarization Prompt Fusion Tuning (PPFT) strategy to effectively utilize RGB-based models pre-trained on large-scale datasets, as the size of the polarization dataset is limited to train a strong model from scratch. We conducted extensive experiments on a public dataset, and the results demonstrate that the proposed method performs favorably compared to existing depth enhancement baselines. Code and demos are available at https://lastbasket.github.io/PPFT/.
