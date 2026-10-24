# Junsung Kim

**M.S. student, EECS @ GIST** · Vision–language models · Mixture of experts · Multimodal AI

[![Email](https://img.shields.io/badge/Email-wnstjd123%40gm.gist.ac.kr-EA4335?style=flat-square)](mailto:wnstjd123@gm.gist.ac.kr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ClementKim-0A66C2?style=flat-square)](https://www.linkedin.com/in/ClementKim)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square)](https://scholar.google.com/citations?user=7hg7QDEAAAAJ&hl=en)
<!-- Add when ready:
[![CV](https://img.shields.io/badge/CV-PDF-555555?style=flat-square)](YOUR_CV_URL)
-->

I'm a master's student in Prof. Heung-No Lee's INFONET Lab at GIST in Gwangju, South Korea. The thread running through my work is **interaction-conditioned computation**: learning how inputs (image and text, or pixels and features) should interact, and letting those interactions decide which experts do the work. I apply this mainly to vision–language models, and I've also worked on hyperspectral imaging for face anti-spoofing.

> **Open to Research Engineer roles** in multimodal and vision&ndash;language AI &mdash; graduating **February 2027**.

## Research interests

- **Vision–language learning and visual reasoning** &mdash; how image–text interactions shape what a model perceives and reasons about
- **Mixture of experts** &mdash; interaction-conditioned expert weighting, and what the routing actually learns
- **Hyperspectral imaging** &mdash; face anti-spoofing and identity recognition

## Selected research

### IP-MoE: spatial token–patch interactions with dense expert weighting
*First author&middot;under review* <!-- · [paper](ARXIV_URL) · [code](REPO_URL) -->

A vision&ndash;language connector in which bilinear token–patch interactions weight a dense mixture of six spatial experts and condition the language model.

- **Setup:** frozen CLIP vision encoder + Llama-3.2-3B-Instruct; two-stage distributed training on LLaVA-NeXT data (LoRA, BF16, 6× A100)
- **Evaluation:** seven multimodal benchmarks, plus routing-entropy and per-subtask analysis of what the routing learns
<!-- - **Result:** your headline number vs. baseline, e.g. "+X.X average over an MLP-projector connector" -->

### [cnn-moe-fas](https://github.com/ClementKim/cnn-moe-fas): hyperspectral face anti-spoofing with sparse MoE
*First author · KICS Winter Conference 2026*

A VGG-style CNN with four sparsely gated experts for face anti-spoofing and identification on hyperspectral images (4,374 images, 54 subjects). **Raises 4-class live/spoof accuracy from 82.8% to 93.7%** (+10.9 pts) over a CNN-only baseline.

### [InteractSeg](https://github.com/ClementKim/InteractSeg): bilinear interactions for material segmentation
*Computer Vision course project, GIST 2026*

Extends bilinear interaction learning to dense prediction: per-pixel material segmentation on MINC and OpenSurfaces with a ViT-S + ResNet-34 dual encoder and mixture-of-experts modules.
<!-- Add a result, e.g. mIoU or pixel accuracy vs. a single-encoder baseline -->

## Publications

**Under review**

- **J. Kim**, Y. Choi, M. Song, S. Kim, S. Lee, H.-N. Lee. *IP-MoE: Studying spatial token&mdash;patch interactions and dense expert weighting.*
- S. Lee, **J. Kim**, M. Song, S. Kim, H.-N. Lee. *Beyond answer preservation: Scientific evidence minimization for private LLM reasoning.*

**Conference and workshop papers**

- M. Song, S. Kim, **J. Kim**, Y. Lee, H.-N. Lee. *Retrieval-augmented generation for symbolic folk-art interpretation: Comparing dense and graph-based retrieval using Korean Minhwa.* **ORACLE Workshop @ EMNLP 2026.**
- **J. Kim**, Y. Choi, H.-N. Lee. *An HSI-based CNN-MoE framework for face anti-spoofing and identification.* KICS Winter Conference 2026. [[code](https://github.com/ClementKim/cnn-moe-fas)]
- M. Song, S. Kim, **J. Kim**, H.-N. Lee. *AI-assisted dataset creation pipeline for Korean Minhwa.* KICS Winter Conference 2026.
- Y. Lee, **J. Kim**, H.-N. Lee. *A prompt-based pipeline for generative game asset synthesis and evaluation.* KICS Winter Conference 2026.

## Other projects

- **[BCAI_A2A](https://github.com/paulmjsong/BCAI_A2A)** — proof-of-concept marketplace where AI agents trade services over the Agent-to-Agent (A2A) protocol, with payments verified on-chain by an EVM smart contract. *Course project, GIST 2025, with Minjun Song.* <!-- If this was your 2nd-place Academic Frontier entry, say so here. -->
- **[spectrometer](https://github.com/ClementKim/spectrometer)** — compressive-sensing spectrometer that reconstructs spectra via non-negative L1-regularized least squares.

## Skills

- **Research:** vision–language connector design and training, mixture of experts, parameter-efficient fine-tuning (LoRA), multimodal benchmark evaluation, routing analysis
- **Engineering:** Python, PyTorch, multi-GPU distributed training (BF16), Docker, Linux
<!-- Add libraries you actually used, e.g. Hugging Face Transformers, PEFT, DeepSpeed / FSDP, Accelerate, Weights & Biases, lmms-eval -->

## Education

- **M.S., Electrical Engineering and Computer Science**, GIST, 2025–2027 (expected Feb 2027). Korean Government Scholarship (full tuition and stipend).
- **B.A., Political Science and Diplomacy** and **B.S., Software and Computer Science** (double major), Ajou University, 2019–2025.


## Honors

- **2nd Place**, AI Agent & Blockchain Innovation Challenge, The Academic Frontier 2025.


## Leadership & outreach

- **Volunteer mentor**, GIST PIUM (2025–present) &mdash; teaching science and offering academic and career mentoring to school students.
- **Organizer and speaker**, AI Nights, Ajou University's on-campus AI conference (2024) &mdash; talk on K-means and DBSCAN.
- **Team leader**, Daesin-Learning, a university-supported ML/DL study group (2024).
