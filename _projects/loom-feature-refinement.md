---
layout: page
published: false
title: LOOM Feature Refinement
description: A training-free method for improving person re-identification embeddings at inference time.
img: assets/img/4.jpg
importance: 3
category: research
---

LOOM is a lightweight feature refinement method for person re-identification that improves embedding quality without retraining the underlying model.

The method was designed to address common limitations in existing refinement pipelines, including identity mixing, instability, and added computational cost.

- Developed a plug-and-play approach based on leave-one-out mean centering.
- Proposed identity-aware and cluster-aware variants for supervised and label-free settings.
- Improved feature separability while reducing intra-class variance.
- Kept the method efficient enough for inference-time use without architecture changes.

This project sits at the intersection of representation learning, efficient adaptation, and reliable visual recognition.
