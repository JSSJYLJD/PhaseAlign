# PhaseAlign: Complex Phase Alignment for Stable Open-Vocabulary Semantic Segmentation

This repository is the official PyTorch implementation of the ICML 2026 (Poster) paper: *PhaseAlign: Complex Phase Alignment for Stable Open-Vocabulary Semantic Segmentation* , authored by Jiankang Wang, Dingding Jia, Shuopeng Zhou and Xuan Wang. The source code will be available soon.

**Abstract:**

Open-Vocabulary Segmentation(OVS) aims to achieve pixel-level semantic recognition from arbitrary text queries. Existing large-scale visual-linguistic models, such as CLIP, perform well in zero-shot generalization, but their image-level training objectives and real-valued cross-modal alignment mix amplitude and phase information, limiting fine-grained segmentation and often causing blurred boundaries and fragmented structures. Inspired by the ability of electromagnetic wave phase to control interference independently of amplitude, we propose PhaseAlign, an OVS framework based on Complex Phase Alignment (CPA). CPA explicitly decouples the magnitude and phase of visual and textual embeddings in the complex domain, refining effective features for stable cross-modal alignment. To further enhance structural awareness, we introduce spatial-aware cross-modal projection, which models local neighborhood relations via multi-scale spatial contrast normalization, and attention-guided affinity modeling, which leverages pre-trained ViT self-attention to propagate category activations, improving boundary clarity and region integrity. Experiments show that PhaseAlign achieves state-of-the-art performance on multiple OVS benchmarks.

<img width="2562" height="1098" alt="figure1 - 副本" src="https://github.com/user-attachments/assets/bd76a1a2-60a3-4f76-9799-64e48570bf8c" />
