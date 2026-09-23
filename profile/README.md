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
- [Topological Dictionary Learning](#topological-dictionary-learning)
- [Causal Abstraction Learning based on the Semantic Embedding Principle](#causal-abstraction-learning-based-on-the-semantic-embedding-principle)
- [Latent Space Alignment for AI-Native MIMO Semantic Communications](#latent-space-alignment-for-ai-native-mimo-semantic-communications)
- [Semantic Channel Equalization Strategies for Deep Joint Source-Channel Coding](#semantic-channel-equalization-strategies-for-deep-joint-source-channel-coding)
- [Real-Time Inference for Distributed Multimodal Systems under Communication Delay Uncertainty](#real-time-inference-for-distributed-multimodal-systems-under-communication-delay-uncertainty)
- [Learning Network Sheaves for AI-native Semantic Communication](#learning-network-sheaves-for-ai-native-semantic-communication)
- [Over-the-Air Semantic Alignment with Stacked Intelligent Metasurfaces](#over-the-air-semantic-alignment-with-stacked-intelligent-metasurfaces)
- [Federated Latent Space Alignment for Multi-user Semantic Communications](#federated-latent-space-alignment-for-multi-user-semantic-communications)
- [SEMASIA: A Large-Scale Dataset of Semantically Structured Latent Representations](#semasia-a-large-scale-dataset-of-semantically-structured-latent-representations)
- [Low-Latency Task-Oriented Image Transmission with Opportunistic Spectrum Access](#low-latency-task-oriented-image-transmission-with-opportunistic-spectrum-access)

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

## Topological Dictionary Learning

[![DOI](https://img.shields.io/badge/DOI-10.1109/TSP.2025.3646587-00629b)](https://ieeexplore.ieee.org/document/11306316) [![arXiv](https://img.shields.io/badge/arXiv-2503.11470-b31b1b.svg)](https://arxiv.org/abs/2503.11470)

:octocat: **Repository:** https://github.com/SPAICOM/topological-dictionary-learning

**Authors:** Enrico Grimaldi, Claudio Battiloro, Paolo Di Lorenzo

*Paper published in IEEE Transactions on Signal Processing.*

**Abstract:** The aim of this paper is to introduce a novel dictionary learning algorithm for sparse representation of signals defined over combinatorial topological spaces, specifically, regular cell complexes. Leveraging Hodge theory, we embed topology into the dictionary structure via concatenated sub-dictionaries, each as a polynomial of Hodge Laplacians, yielding localized spectral topological filter frames. The learning problem is cast to jointly infer the underlying cell complex and optimize the dictionary coefficients and the sparse signal representation. We efficiently solve the problem via iterative alternating algorithms. Numerical results on both synthetic and real data show the effectiveness of the proposed procedure in jointly learning the sparse representations and the underlying relational structure of topological signals.

<div align="center"><img src="https://github.com/user-attachments/assets/e1e108ad-6b14-432b-a818-e4a831e898b3" width=60%></div>

## Causal Abstraction Learning based on the Semantic Embedding Principle

[![OpenReview](https://img.shields.io/badge/OpenReview-12647-8c1b13)](https://openreview.net/forum?id=J16AIOkjjY)

:octocat: **Repository:** https://github.com/SPAICOM/calsep

**Authors:** Gabriele D'Acunto, Fabio Massimo Zennaro, Yorgos Felekis, Paolo Di Lorenzo

*Paper published in the proceedings of ICML'25.*

**Abstract:** Structural causal models (SCMs) allow us to investigate complex systems at multiple levels of resolution. The causal abstraction (CA) framework formalizes the mapping between high- and low-level SCMs. We address CA learning in a challenging and realistic setting, where SCMs are inaccessible, interventional data is unavailable, and sample data is misaligned. A key principle of our framework is semantic embedding, formalized as the high-level distribution lying on a subspace of the low-level one. This principle naturally links linear CA to the geometry of the Stiefel manifold. We present a category-theoretic approach to SCMs that enables the learning of a CA by finding a morphism between the low- and high-level probability measures, adhering to the semantic embedding principle. Consequently, we formulate a general CA learning problem. As an application, we solve the latter problem for linear CA; considering Gaussian measures and the Kullback-Leibler divergence as an objective. Given the nonconvexity of the learning task, we develop three algorithms building upon existing paradigms for Riemannian optimization. We demonstrate that the proposed methods succeed on both synthetic and real-world brain data with different degrees of prior information about the structure of CA.

<div align="center"><img src="https://github.com/user-attachments/assets/991d1d1e-3378-49d4-80de-aa085359ad9b" width=40%></div>

## Latent Space Alignment for AI-Native MIMO Semantic Communications

[![DOI](https://img.shields.io/badge/DOI-10.1109/IJCNN64981.2025.11228893-00629b)](https://ieeexplore.ieee.org/document/11228893) [![arXiv](https://img.shields.io/badge/arXiv-2507.16680-b31b1b.svg)](https://arxiv.org/abs/2507.16680)

:octocat: **Repository:** https://github.com/SPAICOM/semantic-alignment-mimo

**Authors:** Mario Edoardo Pandolfo, Simone Fiorellino, Emilio Calvanese Strinati, Paolo Di Lorenzo

*Paper published in the proceedings of IJCNN 2025.*

**Abstract:** Semantic communications focus on prioritizing the understanding of the meaning behind transmitted data and ensuring the successful completion of tasks that motivate the exchange of information. However, when devices rely on different languages, logic, or internal representations, semantic mismatches may occur, potentially hindering mutual understanding. This paper introduces a novel approach to addressing latent space misalignment in semantic communications, exploiting multiple-input multiple-output (MIMO) communications. Specifically, our method learns a MIMO precoder/decoder pair that jointly performs latent space compression and semantic channel equalization, mitigating both semantic mismatches and physical channel impairments. We explore two solutions: (i) a linear model, optimized by solving a biconvex optimization problem via the alternating direction method of multipliers (ADMM); (ii) a neural network-based model, which learns semantic MIMO precoder/decoder under transmission power budget and complexity constraints. Numerical results demonstrate the effectiveness of the proposed approach in a goal-oriented semantic communication scenario, illustrating the main trade-offs between accuracy, communication burden, and complexity of the solutions.

<div align="center"><img src="https://github.com/user-attachments/assets/98a9ddee-8a6a-45c2-afc0-cd5fb56803a8" width=60%></div>

## Semantic Channel Equalization Strategies for Deep Joint Source-Channel Coding

[![DOI](https://img.shields.io/badge/DOI-10.1109/GCWkshps68340.2025.11591060-00629b)](https://ieeexplore.ieee.org/abstract/document/11591060) [![arXiv](https://img.shields.io/badge/arXiv-2510.04674-b31b1b.svg)](https://arxiv.org/abs/2510.04674)

:octocat: **Repository:** https://github.com/SPAICOM/DJSCC-Semantic-Equalization

**Authors:** Lorenzo Pannacci, Simone Fiorellino, Mario Edoardo Pandolfo, Emilio Calvanese Strinati, Paolo Di Lorenzo

*Paper published in the proceedings of IEEE GLOBECOM Workshops 2025.*

**Abstract:**  Deep joint source-channel coding (DeepJSCC) has emerged as a powerful paradigm for end-to-end semantic communications, jointly learning to compress and protect task-relevant features over noisy channels. However, existing DeepJSCC schemes assume a shared latent space at transmitter (TX) and receiver (RX) - an assumption that fails in multi-vendor deployments where encoders and decoders cannot be co-trained. This mismatch introduces "semantic noise", degrading reconstruction quality and downstream task performance. In this paper, we systematize and evaluate methods for semantic channel equalization for DeepJSCC, introducing an additional processing stage that aligns heterogeneous latent spaces under both physical and semantic impairments. We investigate three classes of aligners: (i) linear maps, which admit closed-form solutions; (ii) lightweight neural networks, offering greater expressiveness; and (iii) a Parseval-frame equalizer, which operates in zero-shot mode without the need for training. Through extensive experiments on image reconstruction over AWGN and fading channels, we quantify trade-offs among complexity, data efficiency, and fidelity, providing guidelines for deploying DeepJSCC in heterogeneous AI-native wireless networks. 

<div align="center"><img src="https://github.com/user-attachments/assets/ea26d96a-d26f-4ee4-a9ce-a662e2123684" width=60%></div>

## Real-Time Inference for Distributed Multimodal Systems under Communication Delay Uncertainty

[![DOI](https://img.shields.io/badge/DOI-10.1109/ICC59461.2026.11586817-00629b)](https://ieeexplore.ieee.org/document/11586817) [![arXiv](https://img.shields.io/badge/arXiv-2511.16225-b31b1b.svg)](https://arxiv.org/abs/2511.16225)

:octocat: **Repository:** https://github.com/victorkreutzfeldt/real-time-inference-distributed-multimodal-systems

**Authors:** Victor Croisfelt, João Henrique Inacio de Souza, Shashi Raj Pandey, Beatriz Soret, Petar Popovski

*Paper published in the proceedings of IEEE ICC 2026.*

**Abstract:** Connected cyber-physical systems perform inference based on real-time inputs from multiple data streams. Uncertain communication delays across data streams challenge the temporal flow of the inference process. State-of-the-art (SotA) non-blocking inference methods rely on a reference-modality paradigm, requiring one modality input to be fully received before processing, while depending on costly offline profiling. We propose a novel, neuro-inspired non-blocking inference paradigm that primarily employs adaptive temporal windows of integration (TWIs) to dynamically adjust to stochastic delay patterns across heterogeneous streams while relaxing the reference-modality requirement. Our communication-delay-aware framework achieves robust real-time inference with finer-grained control over the accuracy-latency tradeoff. Experiments on the audio-visual event localization (AVEL) task demonstrate superior adaptability to network dynamics compared to SotA approaches.

<div align="center"><img src="https://github.com/user-attachments/assets/b0be82e7-c419-40b8-b88a-e50827381d74" width=55%></div>

## Learning Network Sheaves for AI-native Semantic Communication

[![DOI](https://img.shields.io/badge/DOI-10.1109/IEEECONF67917.2025.11443785>-00629b)](https://ieeexplore.ieee.org/document/11443785) [![arXiv](https://img.shields.io/badge/arXiv-2512.03248-b31b1b.svg)](https://arxiv.org/abs/2512.03248)

:octocat: **Repository:** https://github.com/SPAICOM/semantic-dict-sheaf

**Authors:** Enrico Grimaldi, Mario Edoardo Pandolfo, Gabriele D'Acunto, Sergio Barbarossa, Paolo Di Lorenzo

*Paper published in the proceedings of the 2025 59th Asilomar Conference on Signals, Systems, and Computers.*

**Abstract:** Recent advances in AI call for a paradigm shift from bit-centric communication to goal- and semantics-oriented architectures, paving the way for AI-native 6G networks. In this context, we address a key open challenge: enabling heterogeneous AI agents to exchange compressed latent-space representations while mitigating semantic noise and preserving task-relevant meaning. We cast this challenge as learning both the communication topology and the alignment maps that govern information exchange among agents, yielding a learned network sheaf equipped with orthogonal maps. This learning process is further supported by a semantic denoising and compression module that constructs a shared global semantic space and derives sparse, structured representations of each agent’s latent space. This corresponds to a nonconvex dictionary learning problem solved iteratively with closed-form updates. Experiments with multiple AI agents pretrained on real image data show that the semantic denoising and compression facilitates AI agents alignment and the extraction of semantic clusters, while preserving high accuracy in downstream task. The resulting communication network provides new insights about semantic heterogeneity across agents, highlighting the interpretability of our methodology.

<div align="center"><img src="https://github.com/user-attachments/assets/5268274e-b95c-4da0-9cb2-b683ca683ab1" width=60%></div>

## Over-the-Air Semantic Alignment with Stacked Intelligent Metasurfaces

[![arXiv](https://img.shields.io/badge/arXiv-2512.05657-b31b1b.svg)](https://arxiv.org/abs/2512.05657)

:octocat: **Repository:** https://github.com/SPAICOM/semantic-alignment-via-sim

**Authors:** Mario Edoardo Pandolfo, Kyriakos Stylianopoulos, George C. Alexandropoulos, Paolo Di Lorenzo

*Paper submitted for publication.*

**Abstract:**  Semantic communication systems aim to transmit task-relevant information between devices capable of artificial intelligence, but their performance can degrade when heterogeneous transmitter-receiver models produce misaligned latent representations. Existing semantic alignment methods typically rely on additional digital processing at the transmitter or receiver, increasing overall device complexity. In this work, we introduce the first over-the-air semantic alignment framework based on stacked intelligent metasurfaces (SIM), which enables latent-space alignment directly in the wave domain, reducing substantially the computational burden at the device level. We model SIMs as trainable linear operators capable of emulating both supervised linear aligners and zero-shot Parseval-frame-based equalizers. To realize these operators physically, we develop a gradient-based optimization procedure that tailors the metasurface transfer function to a desired semantic mapping. Experiments with heterogeneous vision transformer (ViT) encoders show that SIMs can accurately reproduce both supervised and zero-shot semantic equalizers, achieving up to 90% task accuracy in regimes with high signal-to-noise ratio (SNR), while maintaining strong robustness even at low SNR values. 

<div align="center"><img src="https://github.com/user-attachments/assets/d74e3f0d-2b5a-43f0-bd4d-206608f7c37b" width=60%></div>

## Federated Latent Space Alignment for Multi-user Semantic Communications

[![DOI](https://img.shields.io/badge/DOI-10.1109/SPAWC66079.2025.11143294-00629b)](https://ieeexplore.ieee.org/document/11143294) [![arXiv](https://img.shields.io/badge/arXiv-2602.17271-b31b1b.svg)](https://arxiv.org/abs/2602.17271)

:octocat: **Repository:** https://github.com/SPAICOM/multi-agent-semantic-alignment

**Authors:** Giuseppe Di Poce, Mario Edoardo Pandolfo, Emilio Calvanese Strinati, Paolo Di Lorenzo

*Paper published in the proceedings of IEEE SPAWC 2025.*

**Abstract:** Semantic communication aims to convey meaning for effective task execution, but differing latent representations in AI-native devices can cause semantic mismatches that hinder mutual understanding. This paper introduces a novel approach to mitigating latent space misalignment in multi-agent AInative semantic communications. In a downlink scenario, we consider an access point (AP) communicating with multiple users to accomplish a specific AI-driven task. Our method implements a protocol that shares a semantic pre-equalizer at the AP and local semantic equalizers at user devices, fostering mutual understanding and task-oriented communication while considering power and complexity constraints. To achieve this, we employ a federated optimization for the decentralized training of the semantic equalizers at the AP and user sides. Numerical results validate the proposed approach in goal-oriented semantic communication, revealing key trade-offs among accuracy, communication overhead, complexity, and the semantic proximity of AI-native communication devices.

<div align="center"><img src="https://github.com/user-attachments/assets/246ff010-b009-416d-9f4c-43974ee43f07" width=60%></div>

## SEMASIA: A Large-Scale Dataset of Semantically Structured Latent Representations

[![arXiv](https://img.shields.io/badge/arXiv-2605.09485-b31b1b.svg)](https://arxiv.org/abs/2605.09485)

:octocat: **Repository:** https://github.com/SPAICOM/semantic-alignment-via-sim

**Authors:** Mario Edoardo Pandolfo, Enrico Grimaldi, Lorenzo Marinucci, Leonardo Di Nino, Simone Fiorellino, Sergio Barbarossa, Paolo Di Lorenzo

*Paper submitted for publication.*

**Abstract:** Latent representations learned by neural networks often exhibit semantic structure, where concept similarity is reflected by geometric proximity in embedding space. However, comparing such spaces across models remains difficult: changes in architecture, pretraining data, objective, or random seed can yield embeddings with similar content but incompatible geometry. This latent space alignment problem is central to interpretability, transfer and multimodal learning, federated systems, and semantic communication; however, progress remains limited by the lack of large-scale, model-diverse, and metadata-rich benchmarks. To address this gap, we introduce SEMASIA, a large-scale collection of latent representations extracted from approximately 1,700 pretrained vision models across eight standard image-classification benchmarks. SEMASIA pairs embeddings with structured metadata describing architectures, training regimes, pretraining sources, and model scale. We demonstrate three applications of the resource. First, we analyze the conceptual organization of individual latent spaces, showing consistent prototype-like clustering and hierarchical semantic neighborhoods across models and datasets. Second, we benchmark supervised alignment mappings between latent spaces using reconstruction error and downstream task performance. Third, we perform a large-scale regression analysis of how pretraining-data complexity, specialization, transfer learning, augmentation, and model scale relate to geometric and probing properties of embeddings. By coupling representational scale with standardized metadata, SEMASIA provides a reproducible foundation for studying latent geometry, evaluating alignment methods, and developing next-generation heterogeneous and interoperable AI systems. 

<div align="center"><img src="https://github.com/user-attachments/assets/01ae3463-993a-4b58-bd4f-5408b6fc1cec" width=60%></div>

## Low-Latency Task-Oriented Image Transmission with Opportunistic Spectrum Access

[![arXiv](https://img.shields.io/badge/arXiv-2607.01921-b31b1b.svg)](https://arxiv.org/abs/2607.01921)

:octocat: **Repository:** https://github.com/joaohis/SemCR

**Authors:** João Henrique Inacio de Souza, Mattia Merluzzi, Mateus P. Mota, Beatriz Soret, Petar Popovski

*Paper presented at IEEE SPAWC 2026.*

**Abstract:** Communication systems designed for reliable data reconstruction, rather than task-oriented communication, typically rely on separate source and channel coding and incur high latency under limited spectrum availability and fading channels. To address this, we propose a transmission framework with opportunistic spectrum access, in which the transmitter sends discrete latent representations learned via a vector-quantized variational autoencoder (VQ-VAE) over idle licensed channels using standard digital modulation. The AI-powered receiver is still able to reconstruct task-related information from the heavily compressed data. We develop a cross-layer latency model that accounts for compression, block errors, retransmissions, and stochastic channel access. Results on latency-accuracy trade-offs show that the proposed scheme achieves at least 79- and 3.3-fold latency reductions with only 5.7% and 2.4% drops in classification accuracy compared to benchmarks using conventional source and channel coding. The framework enables low-latency communication and reliable task execution even under limited spectrum availability and challenging channel conditions.

<div align="center"><img max-width="2115" src="https://github.com/user-attachments/assets/d325234d-e7f1-4523-a476-88d6e55f90a8" /></div>
