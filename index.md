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

* **[2025.11]** 🚀 Released **openPangu-R-7B-Diffusion**! It is a 7B diffusion-based LLM (context-causal block diffusion). It achieves **2.5x inference speedup** over autoregressive models and SOTA performance (e.g., **91.9% on GSM8K**, **87.8% on HumanEval**), surpassing LLaDA and SDAR. [[Code]](https://ai.gitcode.com/ascend-tribe/openPangu-R-7B-Diffusion)
* **[2025.11]** 📄 New paper: **ROOT (Robust Orthogonalized Optimizer)**. We propose a robust optimizer that outperforms Muon and Adam by introducing adaptive Newton iterations and proximal optimization, solving the instability issues in large-scale LLM training. [[PDF]](https://arxiv.org/abs/2511.20626)

---
## 📝 Selected Publications

*(Full list available on [Google Scholar](https://scholar.google.com/citations?hl=en&user=wZ9N88gAAAAJ))*

### 🚀 Efficient & On-Device LLMs (2023 - Present)

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [1] Pangu Embedded: An Efficient Dual-system LLM Reasoner with Metacognition
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    <strong>Hanting Chen</strong>, Yasheng Wang, Kai Han, ... Yunhe Wang
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    arXiv Preprint 2025
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> We present <strong>Pangu Embedded</strong>, a reasoning-optimized LLM for Ascend NPUs featuring "Fast & Slow" thinking modes. It utilizes a two-stage training (Distillation & RL with MARS) and a dynamic complexity-aware mode selection.
    <br>
    <a href="https://arxiv.org/pdf/2505.22375" style="text-decoration: none;">[PDF]</a> 
    <a href="https://gitcode.com/ascend-tribe/openPangu-Embedded-7B-V1.1.git" style="text-decoration: none;">[Model]</a>
  </div>
</div>

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [2] Revealing the Power of Post-Training for Small Language Models via Knowledge Distillation
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    Miao Rang, Zhenni Bi, Hang Zhou, <strong>Hanting Chen</strong>, ... Yunhe Wang
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    arXiv Preprint 2025
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> A systematic post-training pipeline (Curriculum SFT + Offline On-policy KD) enabling 1B-parameter models to achieve SOTA performance on <strong>edge devices</strong>.
    <br>
    <a href="https://arxiv.org/pdf/2509.26497" style="text-decoration: none;">[PDF]</a> 
    <a href="https://gitcode.com/ascend-tribe/openPangu-Embedded-1B-V1.1.git" style="text-decoration: none;">[Model]</a>
  </div>
</div>

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [3] Enhancing Large Language Models through Adaptive Tokenizers
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    M Zheng, <strong>Hanting Chen</strong>, T Guo, C Zhu, B Zheng, C Xu, Y Wang
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    NeurIPS 2024
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> A model-driven tokenizer construction scheme that optimizes the vocabulary specifically for the target LLM.
    <br>
    <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/cdf00c97c0cb2cc35179f03363da6c4f-Paper-Conference.pdf" style="text-decoration: none;">[PDF]</a>
  </div>
</div>

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [4] Rethinking 1-bit Optimization Leveraging Pre-trained Large Language Models
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    Zhijun Tu, <strong>Hanting Chen</strong>, Siqi Liu, ... Yunhe Wang
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    arXiv Preprint 2025
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> Enabling <strong>1-bit quantization from pre-trained models</strong> directly, significantly reducing training costs while maintaining accuracy.
    <br>
    <a href="https://arxiv.org/pdf/2508.06974" style="text-decoration: none;">[PDF]</a>
  </div>
</div>

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [5] Pangu Light: Weight Re-Initialization for Pruning and Accelerating LLMs
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    <strong>Hanting Chen</strong>, Jiarui Qin, Jialong Guo, ... Yunhe Wang
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    arXiv Preprint 2025
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> Solving the "aggressive pruning" degradation problem via novel <strong>Weight Re-Initialization</strong> techniques (CLAP & SLNP).
    <br>
    <a href="https://arxiv.org/pdf/2505.20155" style="text-decoration: none;">[PDF]</a>
  </div>
</div>

---

### 👁️ Computer Vision (2018 - 2023)

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [6] Pre-Trained Image Processing Transformer
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    <strong>Hanting Chen</strong>, Yunhe Wang, Tianyu Guo, ... Wen Gao
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    CVPR 2021 <span style="color:#c90000; font-weight:bold; margin-left:5px;">(2,600+ Citations)</span>
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> The first Transformer tailored for low-level vision, achieving SOTA across multiple tasks via pre-training.
    <br>
    <a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Pre-Trained_Image_Processing_Transformer_CVPR_2021_paper.pdf" style="text-decoration: none;">[PDF]</a>
  </div>
</div>

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [7] Image Processing GNN: Breaking Rigidity in Super-Resolution
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    Y Tian, <strong>Hanting Chen</strong>, C Xu, Y Wang
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    CVPR 2024 <span style="color:#c90000; font-weight:bold; margin-left:5px;">(Best Student Paper Runner-up)</span> 🏆
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> Introducing GNNs into image restoration to break the grid rigidity of CNNs/Transformers.
    <br>
    <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Tian_Image_Processing_GNN_Breaking_Rigidity_in_Super-Resolution_CVPR_2024_paper.pdf" style="text-decoration: none;">[PDF]</a>
  </div>
</div>

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [8] IPT-V2: Efficient Image Processing Transformer using Hierarchical Attentions
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    Z Tu, K Du, <strong>Hanting Chen</strong>, ... Y Wang
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    NTIRE 2023 Challenge Winner
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> An evolved IPT with hierarchical attention, winning the NTIRE 2023 Image Denoising Challenge.
    <br>
    <a href="https://arxiv.org/pdf/2404.00633" style="text-decoration: none;">[PDF]</a>
  </div>
</div>

<div style="margin-bottom: 1.5em;">
  <div style="font-size: 1.15rem; font-weight: 700; color: #111; line-height: 1.4;">
    [9] AdderNet: Do we really need multiplications in deep learning?
  </div>
  <div style="font-size: 0.9rem; color: #666; margin-top: 4px;">
    <strong>Hanting Chen</strong>, Yunhe Wang, ... C Xu
  </div>
  <div style="font-size: 0.9rem; font-style: italic; color: #444;">
    CVPR 2020 <span style="color:#c90000; font-weight:bold; margin-left:5px;">(Oral Presentation)</span>
  </div>
  <div style="margin-top: 6px; font-size: 0.95rem; color: #333; border-left: 3px solid #ddd; padding-left: 10px;">
    <strong>TL;DR:</strong> Replacing multiplications with additions (L1-norm) to reduce energy consumption while maintaining accuracy.
    <br>
    <a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_AdderNet_Do_We_Really_Need_Multiplications_in_Deep_Learning_CVPR_2020_paper.pdf" style="text-decoration: none;">[PDF]</a>
  </div>
</div>
