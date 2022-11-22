---
title: "STEm-Seg: Spatio-temporal Embeddings for Instance Segmentation in Videos"
collection: publications
permalink: /publication/ECCV2020_STEmSeg
excerpt: ''
date: 2020-09-05
venue: 'ECCV'
paperurl: 'https://arxiv.org/pdf/2003.08429.pdf'
---
Ali Athar\*, Sabarinath Mahadevan\*, Aljosa Osep, Laura Leal-Taixe, Bastian Leibe

Existing methods for instance segmentation in videos typically involve multi-stage pipelines that follow the tracking-by-detection paradigm and model a video clip as a sequence of images. Multiple networks are used to detect objects in individual frames, and then associate these detections over time. Hence, these methods are often non-end-to-end trainable and highly tailored to specific tasks. In this paper, we propose a different approach that is well-suited to a variety of tasks involving instance segmentation in videos. In particular, we model a video clip as a single 3D spatio-temporal volume, and propose a novel approach that segments and tracks instances across space and time in a single stage. Our  problem formulation is centered around the idea of spatio-temporal embeddings which are trained to cluster pixels belonging to a specific object instance over an entire video clip. To this end, we introduce (i) novel mixing functions that enhance the feature representation of spatio-temporal embeddings, and (ii) a single-stage, proposal-free network that can reason about temporal context. Our network is trained end-to-end to learn spatio-temporal embeddings as well as parameters required to cluster these embeddings, thus simplifying inference. Our method achieves state-of-the-art results across multiple datasets and tasks.

[PDF](https://arxiv.org/pdf/2003.08429.pdf) | [GitHub](https://github.com/sabarim/STEm-Seg) | [YouTube](https://www.youtube.com/watch?v=E2Z-1HNO934)
