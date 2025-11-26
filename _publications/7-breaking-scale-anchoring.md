---
title: "Breaking Scale Anchoring: Frequency Representation Learning for Accurate High-Resolution Inference from Low-Resolution Training"
collection: publications
permalink: /publication/breaking-scale-anchoring
date: 2025-11-01
venue: "preprint"
# 如果以后有 arXiv 或 OpenReview 链接，可以填在下面
# paperurl: "https://arxiv.org/abs/xxxx.xxxxx"
---

**Wenshuo Wang**, Fan Zhang† († Corresponding Author)

- When deep learning models perform spatiotemporal forecasting at higher resolutions, they do not exhibit the power-law error decay characteristic of numerical solvers. Instead, their accuracy remains almost unchanged. We regard this long-accepted behavior as a problem, which we term **Scale Anchoring**.
- We identify the core limitation behind Scale Anchoring as the Nyquist frequency of the training data. Based on this insight, we propose **Frequency Representation Learning** to induce frequency-domain extrapolation with only minor computational overhead, enabling the model to mitigate this issue.
