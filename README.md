# Hi, I'm Junsung Kim 👋

I'm an M.S. student in Electrical Engineering and Computer Science at **GIST** in Gwangju, South Korea, working in the INFONET Lab with Prof. Heung-No Lee. I build and analyze **vision&ndash;language models** and **mixture of experts** architectures, and I've also worked on **hyperspectral imaging** for face anti-spoofing.

> 🔎 **Open to Research Engineer roles** in multimodal and vision–language AI &mdash; graduating **February 2027**.

[![Email](https://img.shields.io/badge/Email-wnstjd123%40gm.gist.ac.kr-EA4335?style=flat-square)](mailto:wnstjd123@gm.gist.ac.kr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ClementKim-0A66C2?style=flat-square)](https://www.linkedin.com/in/ClementKim)

---

### 🔬 Research interests

- **Vision&ndash;language learning and visual reasoning** &mdash; how image&ndash;text interactions shape what a model perceives and reasons about
- **Interaction-conditioned mixture of experts** &mdash; learned expert weighting, and what the routing actually learns
- **Hyperspectral imaging** &mdash; face anti-spoofing and identity recognition

### 🛠️ Selected projects

- **IP-MoE** &middot; *first-author paper, under review* &mdash; A vision&ndash;language connector in which bilinear token&ndash;patch interactions weight a dense mixture of six spatial experts and condition the language model (frozen CLIP + Llama-3.2-3B-Instruct). Two-stage distributed training on LLaVA-NeXT data (LoRA, BF16, 6× A100), evaluated on seven benchmarks with routing-entropy and per-subtask analysis.
- **[cnn-moe-fas](https://github.com/ClementKim/cnn-moe-fas)** &middot; *KICS Winter Conference 2026* &mdash; A VGG-style CNN with four sparsely gated experts for hyperspectral face anti-spoofing and identification, on a dataset of 4,374 images from 54 subjects. Raises 4-class live/spoof accuracy from 82.8% to 93.7% over a CNN-only baseline.
- **[InteractSeg](https://github.com/ClementKim/InteractSeg)** &middot; *Computer Vision course project, GIST 2026* &mdash; Bilinear interaction learning for per-pixel material segmentation on MINC and OpenSurfaces, using a ViT-S + ResNet-34 dual encoder with mixture-of-experts modules.
- **[BCAI_A2A](https://github.com/paulmjsong/BCAI_A2A)** &middot; *course project, GIST 2025, with Minjun Song* &mdash; A proof-of-concept marketplace where AI agents exchange services over the Agent-to-Agent (A2A) protocol, with payments verified on-chain by an EVM smart contract.
- **[spectrometer](https://github.com/ClementKim/spectrometer)** &mdash; A compressive-sensing spectrometer that reconstructs spectra with non-negative L1-regularized least squares.

### 📄 Publications

- **J. Kim**, Y. Choi, M. Song, S. Kim, S. Lee, H.-N. Lee. *IP-MoE: Studying spatial token–patch interactions and dense expert weighting.* Under review.
- S. Lee, **J. Kim**, M. Song, S. Kim, H.-N. Lee. *Beyond answer preservation: Scientific evidence minimization for private LLM reasoning.* Under review.
- M. Song, S. Kim, **J. Kim**, Y. Lee, H.-N. Lee. *Retrieval-augmented generation for symbolic folk-art interpretation: Comparing dense and graph-based retrieval using Korean Minhwa.* ORACLE Workshop at EMNLP 2026.
- **J. Kim**, Y. Choi, H.-N. Lee. *An HSI-based CNN-MoE framework for face anti-spoofing and identification.* KICS Winter Conference 2026. [[code](https://github.com/ClementKim/cnn-moe-fas)]

<details>
<summary>Two more KICS Winter Conference 2026 papers</summary>

- M. Song, S. Kim, **J. Kim**, H.-N. Lee. *AI-assisted dataset creation pipeline for Korean Minhwa.*
- Y. Lee, **J. Kim**, H.-N. Lee. *A prompt-based pipeline for generative game asset synthesis and evaluation.*

</details>

### 🎓 Education & honors

- **M.S., Electrical Engineering and Computer Science** &mdash; GIST, 2025&ndash;2027 (expected Feb 2027). Korean Government Scholarship (full tuition and stipend).
- **B.A., Political Science and Diplomacy** &mdash; Ajou University, 2019&ndash;2025.
- **B.S., Software and Computer Science (double major)** &mdash; Ajou University, 2019&ndash;2025
- **2nd Place**, AI Agent & Blockchain Innovation Challenge &mdash; The Academic Frontier 2025.

### 🧰 Tools

Python &middot; PyTorch &middot; distributed multi-GPU training (LoRA, BF16) &middot; Docker &middot; Ubuntu/Linux

### 🌱 Beyond the lab

- Volunteer mentor at **GIST PIUM**, teaching science and giving academic and career mentoring to school students (2025–present)
- Organizer and speaker at **AI Nights**, Ajou University's on-campus AI conference — talk on K-means and DBSCAN (2024)
- Team leader of **Daesin-Learning**, a university-supported machine-learning and deep-learning study group (2024)
