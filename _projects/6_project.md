---
layout: page
title: Best-of-N Sampling in Tabular GANs
description: Improving GAN-generated tabular data quality via best-of-N selection
img: assets/img/akmol-masud-profile.png
importance: 6
category: work-in-progress
---

This project investigates applying **Best-of-N sampling** strategies to Generative Adversarial Networks for tabular data synthesis, improving the quality and utility of synthetic datasets.

### Motivation

Tabular GANs often produce low-quality synthetic data due to mode collapse and training instability. Best-of-N sampling selects the highest-quality samples from N generated candidates, improving downstream ML task performance.

### Approach

- Systematic evaluation of quality metrics (column-wise stats, ML efficacy) for best-of-N selection
- Benchmarking across CTGAN, TVAE, and CTAB-GAN on real-world tabular datasets

### Links

- [GitHub](https://github.com/masud1901/Best-of-N-Sampling-in-Tabular-GANs)
