---
layout: page
title: DP-FL on Human Activity Recognition
description: Differentially Private Federated Learning for HAR
img: assets/img/akmol-masud-profile.png
importance: 7
category: work-in-progress
---

This project applies **Differentially Private Federated Learning (DP-FL)** to Human Activity Recognition (HAR) using wearable sensor data, exploring the privacy-utility tradeoff in a cross-device FL setting.

### Research Questions

- How does DP noise (Gaussian mechanism, ε-δ privacy) impact HAR model accuracy across heterogeneous clients?
- Can adaptive clipping strategies reduce accuracy loss while preserving privacy guarantees?

### Setting

- Dataset: UCI HAR (accelerometer + gyroscope, 6 activities, 30 subjects)
- Federated setup: heterogeneous data partitions per client, FedAvg with DP-SGD
