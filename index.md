---
layout: single
author_profile: true
permalink: /
title: "About Me"
---

Hello! I'm Hanting Chen.

I am currently a Researcher at **Huawei Technologies** (Beijing). I received my Ph.D. degree from the School of Intelligence Science and Technology, **Peking University (PKU)** in 2022, under the supervision of Prof. Chao Xu. My research focuses on **efficient AI** and **LLM**, bridging the gap between powerful models and resource-constrained devices. 
* **Large Language Models (Post-2023):** I am working on efficient and effective LLM architectures, model compression (quantization, pruning), and inference acceleration.
* **Computer Vision (Pre-2023):** I worked extensively on neural network architecture design (e.g., IPT and AdderNet series).

I have published **50+ papers** in top-tier conferences and journals (NeurIPS, CVPR, ICML, ICCV, TPAMI, etc.) with **10,000+ citations**. I also serve as an **Area Chair for NeurIPS**. 

---

## 🔥 News

* **[2025.12]** 📄 New paper: **Nexus**! We propose **Higher-Order Attention** to break the low-rank bottleneck of standard Transformers. By dynamically refining Queries/Keys via nested attention loops, it captures intricate multi-hop dependencies with **nearly zero additional parameters**. [[PDF]](https://arxiv.org/abs/2512.03377)
* **[2025.11]** 🚀 Released **openPangu-R-7B-Diffusion**! It is a 7B diffusion-based LLM (context-causal block diffusion). It achieves **2.5x inference speedup** over autoregressive models and SOTA performance (e.g., **91.9% on GSM8K**, **87.8% on HumanEval**), surpassing LLaDA and SDAR. [[Model]](https://ai.gitcode.com/ascend-tribe/openPangu-R-7B-Diffusion)
* **[2025.11]** 📄 New paper: **ROOT (Robust Orthogonalized Optimizer)**. We propose a robust optimizer that outperforms Muon and Adam by introducing adaptive Newton iterations and proximal optimization, solving the instability issues in large-scale LLM training. [[PDF]](https://arxiv.org/abs/2511.20626)

---

## 📝 Selected Publications

*(Full list available on [Google Scholar](https://scholar.google.com/citations?hl=en&user=wZ9N88gAAAAJ))*

### 🚀 Efficient & On-Device LLMs (2023 - Present)

#### Edge LLMs

**[1] Pangu Embedded: An Efficient Dual-system LLM Reasoner with Metacognition**

***Hanting Chen**, Yasheng Wang, Kai Han, ... Yunhe Wang*

> **TL;DR:** We present a reasoning-optimized LLM featuring "Fast & Slow" thinking modes. It utilizes a two-stage training (Distillation & RL with MARS) and a dynamic complexity-aware mode selection to balance latency and reasoning depth.
> [[PDF]](https://arxiv.org/pdf/2505.22375) [[Model]](https://gitcode.com/ascend-tribe/openPangu-Embedded-7B-V1.1.git)

**[2] Revealing the Power of Post-Training for Small Language Models via Knowledge Distillation**

*Miao Rang, Zhenni Bi, Hang Zhou, **Hanting Chen**, ... Yunhe Wang*

> **TL;DR:** A systematic post-training pipeline (Curriculum SFT + Offline On-policy KD) that enables 1B-parameter models to achieve SOTA performance. This solution is tailored for deploying high-performance LLMs on resource-constrained edge devices.
> [[PDF]](https://arxiv.org/pdf/2509.26497) [[Model]](https://gitcode.com/ascend-tribe/openPangu-Embedded-1B-V1.1.git)

**[3] Enhancing Large Language Models through Adaptive Tokenizers**

*M Zheng, **Hanting Chen**, T Guo, C Zhu, B Zheng, C Xu, Y Wang*

*NeurIPS 2024*
> **TL;DR:** We propose a model-driven tokenizer construction scheme that optimizes the vocabulary specifically for the target LLM, improving encoding efficiency and model performance.
> [[PDF]](https://proceedings.neurips.cc/paper_files/paper/2024/file/cdf00c97c0cb2cc35179f03363da6c4f-Paper-Conference.pdf)

#### LLM Compression

**[4] Rethinking 1-bit Optimization Leveraging Pre-trained Large Language Models**

*Zhijun Tu, **Hanting Chen**, Siqi Liu, ... Yunhe Wang*

> **TL;DR:** Unlike existing methods that train 1-bit LLMs from scratch, we enable 1-bit quantization from pre-trained models. By using consistent progressive training and binary-aware initialization, we significantly reduce training costs while maintaining high accuracy.
> [[PDF]](https://arxiv.org/pdf/2508.06974)

**[5] Pangu Light: Weight Re-Initialization for Pruning and Accelerating LLMs**

***Hanting Chen**, Jiarui Qin, Jialong Guo, ... Yunhe Wang*

> **TL;DR:** A structured pruning framework for LLMs that solves the "aggressive pruning" degradation problem via novel Weight Re-Initialization techniques. It outperforms Nemotron and Qwen3 series in accuracy-efficiency trade-offs on Ascend NPUs.
> [[PDF]](https://arxiv.org/pdf/2505.20155)

---

### 👁️ Computer Vision (2018 - 2023)

#### The Image Processing Transformer (IPT) Series

**[6] Pre-Trained Image Processing Transformer**

***Hanting Chen**, Yunhe Wang, Tianyu Guo, Chang Xu, ... Wen Gao*

*CVPR 2021* <span style="color:red">**(2,600+ Citations)**</span>
> **TL;DR:** The first Transformer model tailored for low-level vision tasks. By introducing a pre-training strategy on large-scale datasets, **IPT** achieved SOTA performance across multiple tasks (denoising, super-resolution, deraining).
> [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Pre-Trained_Image_Processing_Transformer_CVPR_2021_paper.pdf)

**[7] Image Processing GNN: Breaking Rigidity in Super-Resolution**

*Y Tian, **Hanting Chen**, C Xu, Y Wang*

*CVPR 2024* <span style="color:red">**(Best Student Paper Runner-up)**</span> 🏆
> **TL;DR:** We introduce Graph Neural Networks (GNN) into image restoration to break the grid rigidity of CNNs/Transformers, allowing for more flexible long-range dependency modeling.
> [[PDF]](https://openaccess.thecvf.com/content/CVPR2024/papers/Tian_Image_Processing_GNN_Breaking_Rigidity_in_Super-Resolution_CVPR_2024_paper.pdf)

**[8] IPT-V2: Efficient Image Processing Transformer using Hierarchical Attentions**

*Z Tu, K Du, **Hanting Chen**, ... Y Wang*

<span style="color:red">**NTIRE 2023 Challenge Winner**</span>🏆
> **TL;DR:** An evolved version of IPT using hierarchical attention mechanisms, which won the **Champion** of the NTIRE 2023 Image Denoising Challenge.
> [[PDF]](https://arxiv.org/pdf/2404.00633)

#### The AdderNet Series

**[9] AdderNet: Do we really need multiplications in deep learning?**

***Hanting Chen**, Yunhe Wang, C Xu, B Shi, C Xu, Q Tian, C Xu*

*CVPR 2020* <span style="color:red">**(Oral Presentation)**</span>
> **TL;DR:** A pioneering work that replaces massive multiplications in CNNs with cheaper additions (L1-norm distance), significantly reducing energy consumption on hardware while maintaining comparable accuracy.
> [[PDF]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_AdderNet_Do_We_Really_Need_Multiplications_in_Deep_Learning_CVPR_2020_paper.pdf)

