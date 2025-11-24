# About 6G-GOALS

<p>
  <img align="right" width="200" alt="6ggoals" src="https://github.com/user-attachments/assets/26d24283-2721-45d4-981c-f66070451005" />
  6G-GOALS aims to realize a sustainable wireless network ecosystem that relies on AI-empowered architecture to support semantic and goal-oriented communication protocols and services. 6G-GOALS will create a path towards building a sustainable 6G, featuring a drastic reduction in the number of unnecessary bits processed and sent and, consequently, enabling extreme energy and spectrum efficiency, reduction of EMF exposure, and massive machine-type communications.
</p>

<p>6G-GOALS project has received funding from the Smart Networks and Services Joint Undertaking (SNS JU) under the European Union’s Horizon Europe research and innovation program under Grant Agreement No 101139232.</p>

<img height="40" src="https://github.com/user-attachments/assets/7a65b0f2-3085-4a56-818d-28d0b17b9ebf" />
<img height="40" src="https://github.com/user-attachments/assets/08762888-1257-4a92-bc7c-e5dbb7557768" />

# Open-Source Code

### Table of Contents

- [EcoPull: Sustainable IoT Image Retrieval Empowered by TinyML Models](#ecopull-sustainable-iot-image-retrieval-empowered-by-tinyml-models)
- [Real-Time Inference for Distributed Multimodal Systems under Communication Delay Uncertainty](#real-time-inference-for-distributed-multimodal-systems-under-communication-delay-uncertainty)

<!--
# Template
## Publication Name

[![DOI](https://img.shields.io/badge/DOI-PAPERDOI)](PAPERLINK) [![arXiv](https://img.shields.io/badge/arXiv-ARXIVCODE.svg)](ARXVILINK)

:octocat: **Repository:** LINKTOREPOSITORY

**Authors:** AUTHORLIST

*Paper published in the PAPERSTATUS*

**Abstract:** ABSTRACT

-->

## EcoPull: Sustainable IoT Image Retrieval Empowered by TinyML Models

[![DOI](https://img.shields.io/badge/DOI-10.1109/GLOBECOM52923.2024.10901782-00629b)](https://ieeexplore.ieee.org/document/10901782) [![arXiv](https://img.shields.io/badge/arXiv-2404.14236-b31b1b.svg)](https://arxiv.org/abs/2404.14236)

:octocat: **Repository:** https://github.com/victorkreutzfeldt/ecopull

**Authors:** Mathias Thorsager, Victor Croisfelt, Junya Shiraishi, Petar Popovski

*Paper published in the proceedings of IEEE GLOBECOM 2024.*

**Abstract:** This paper introduces EcoPull, a sustainable Internet of Things (IoT) framework powered by Tiny Machine Learning (TinyML) models for efficient image retrieval from multiple devices. The devices are equipped with two types of TinyML models: i) a behavior model and ii) an image compressor model. The behavior model filters out irrelevant images based on the current task, minimizing unnecessary data transmission and reducing communication resource competition among devices. The image compressor model enables devices to communicate with the edge server (ES) using latent representations of images, thereby reducing communication bandwidth usage. While integrating TinyML models into IoT devices does increase energy consumption due to the inference process, this cost is carefully accounted for in our design. Numerical results show that the proposed framework can achieve over 77% and 43% energy savings compared to the simple offloading and a state-of-the-art baseline while still maintaining the quality of the retrieved images at the ES.

<div align="center"><img src="https://github.com/user-attachments/assets/60d92e89-1cf3-4a9b-a70b-a0ad9d73494a" width=60%></div>

## Real-Time Inference for Distributed Multimodal Systems under Communication Delay Uncertainty

[![arXiv](https://img.shields.io/badge/arXiv-2511.16225-b31b1b.svg)](https://arxiv.org/abs/2511.16225)

:octocat: **Repository:** https://github.com/victorkreutzfeldt/real-time-inference-distributed-multimodal-systems

**Authors:** Victor Croisfelt, João Henrique Inacio de Souza, Shashi Raj Pandey, Beatriz Soret, Petar Popovski

*Paper submitted to the IEEE ICC 2026.*

**Abstract:** Connected cyber-physical systems perform inference based on real-time inputs from multiple data streams. Uncertain communication delays across data streams challenge the temporal flow of the inference process. State-of-the-art (SotA) non-blocking inference methods rely on a reference-modality paradigm, requiring one modality input to be fully received before processing, while depending on costly offline profiling. We propose a novel, neuro-inspired non-blocking inference paradigm that primarily employs adaptive temporal windows of integration (TWIs) to dynamically adjust to stochastic delay patterns across heterogeneous streams while relaxing the reference-modality requirement. Our communication-delay-aware framework achieves robust real-time inference with finer-grained control over the accuracy-latency tradeoff. Experiments on the audio-visual event localization (AVEL) task demonstrate superior adaptability to network dynamics compared to SotA approaches.

<div align="center"><img src="https://github.com/user-attachments/assets/b0be82e7-c419-40b8-b88a-e50827381d74" width=55%></div>
