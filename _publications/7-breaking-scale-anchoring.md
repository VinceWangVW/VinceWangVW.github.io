---
title: "Breaking Scale Anchoring: Frequency Representation Learning for Accurate High-Resolution Inference from Low-Resolution Training"
collection: publications
category: manuscripts
permalink: /publication/breaking-scale-anchoring
excerpt: "We identify Scale Anchoring in zero-shot super-resolution spatiotemporal forecasting and propose Frequency Representation Learning to enable frequency-domain extrapolation from low-resolution training data."
date: 2025-11-01
venue: "preprint"
# 有 arxiv / openreview 链接的话，可以在这里填：
# paperurl: "https://openreview.net/..."
# 下面这个 citation 只用于 CV 等地方的完整引用格式
citation: "Wenshuo Wang, Fan Zhang. \"Breaking Scale Anchoring: Frequency Representation Learning for Accurate High-Resolution Inference from Low-Resolution Training.\" preprint, 2025."
---

**Wenshuo Wang**, Fan Zhang† († Corresponding Author)

- When deep learning models perform spatiotemporal forecasting at higher resolutions, they do not exhibit the power-law error decay characteristic of numerical solvers. Instead, their accuracy remains almost unchanged. We regard this long-accepted behavior as a problem, which we term Scale Anchoring.
- We identify the core limitation behind Scale Anchoring as the Nyquist frequency of the training data. Based on this insight, we propose Frequency Representation Learning to induce frequency-domain extrapolation with only minor computational overhead, enabling the model to mitigate this issue.
