---
layout: post
title:  "Alpha-Refine: Boosting Tracking Performance by Precise Bounding Box Estimation"
date:   2021-04-28
image: /images/alpharefine.png
categories: research
authors: "<strong>Bin Yan*</strong>, Xinyu Zhang*, Dong Wang, Huchuan Lu, Xiaoyun Yang"
venue: "CVPR"
arxiv: https://arxiv.org/pdf/2012.06815.pdf
code: https://github.com/MasterBin-IIAU/AlphaRefine#alpharefine
---

We present Alpha-Refine, a flexible and accurate refinement module, which can significantly improve the base trackers’ box estimation quality. Alpha-Refine adopts a pixel-wise correlation, a corner prediction head, and an auxiliary mask head as the core components. Comprehensive experiments on TrackingNet, LaSOT, GOT-10K, and VOT2020 benchmarks with multiple base trackers show that our approach significantly improves the base tracker’s performance with little extra latency. 