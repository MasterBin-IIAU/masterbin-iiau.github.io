---
layout: post
title:  "[5]  LightTrack: Finding Lightweight Neural Networks for Object Tracking via One-Shot Architecture Search"
date:   2021-04-29
image: /images/lighttrack.png
categories: research
authors: "<strong>Bin Yan*</strong>, Houwen Peng*, Kan Wu*, Dong Wang, Jianlong Fu, Huchuan Lu"
venue: "CVPR"
arxiv: https://arxiv.org/pdf/2104.14545.pdf
code: https://github.com/researchmm/LightTrack#lighttrack
---

We present LightTrack, which uses neural architecture search to design more lightweight and efficient object trackers. It can find trackers that achieve superior performance compared to handcrafted SOTA trackers, while using much fewer model Flops and parameters. On Snapdragon 845 Adreno GPU, LightTrack runs 12x faster than Ocean, while using 13x fewer parameters and 38x fewer Flops. 