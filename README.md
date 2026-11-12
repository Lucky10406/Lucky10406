
<div align="center">

# Hi, I'm Mayuresh Sharma

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3500&pause=1000&color=8B5CF6&center=true&vCenter=true&width=750&lines=AI+Researcher+%26+Technology+Builder;Efficient+AI+%7C+LLM+Compression+%7C+Green+AI;Building+Privacy-First+Digital+Systems;Exploring+Ideas.+Running+Experiments.+Building+Things." alt="Typing SVG" />

**Computer Science Student · Independent AI Researcher · Entrepreneur**

<p>
  <a href="https://github.com/Lucky10406">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/mayuresh-sharma-a08526315">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:mayureshsharma10406@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=Lucky10406&label=Profile%20Views&color=8b5cf6&style=flat" />
<img src="https://img.shields.io/github/followers/Lucky10406?label=Followers&style=social" />

</div>

---

## About Me

I'm a Computer Science and Engineering undergraduate at **Guru Gobind Singh Indraprastha University (GGSIPU), New Delhi**, exploring the intersection of artificial intelligence, computational efficiency, and real-world technology.

My work focuses on understanding how intelligent systems can become more efficient, accessible, and practical without compromising their capabilities.

Beyond research, I enjoy building products, experimenting with new technologies, and exploring ideas that connect software, hardware, and entrepreneurship.

- Researching **LLM compression, efficient inference, and hardware-aware machine learning**.
- Exploring quantization, pruning, knowledge distillation, and parameter-efficient fine-tuning.
- Building independent search infrastructure and privacy-first applications.
- Co-founder of **Aeson** and former co-founder of **CodeQuity**.
- Interested in AI for fintech, blockchain, cybersecurity, and emerging technologies.
- Open to research collaborations, internships, and challenging engineering problems.

---

## Research Focus

<div align="center">

![LLMs](https://img.shields.io/badge/Large_Language_Models-111827?style=for-the-badge)
![Green AI](https://img.shields.io/badge/Green_AI-059669?style=for-the-badge)
![Quantization](https://img.shields.io/badge/Quantization-7C3AED?style=for-the-badge)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-DC2626?style=for-the-badge)
![Hardware Aware ML](https://img.shields.io/badge/Hardware_Aware_ML-2563EB?style=for-the-badge)

</div>

| Research Area | What I'm Exploring |
|---|---|
| Efficient AI & Green AI | Reducing computational cost, memory consumption, and energy requirements |
| LLM Compression | Quantization, pruning, knowledge distillation, and model efficiency |
| Hardware-aware ML | Understanding model performance across different computational environments |
| Multilingual AI | Model compression across languages and its effects on performance |
| Responsible AI | Fairness, robustness, and reliability of compressed language models |
| Retrieval & Multimodal AI | Visual retrieval, geolocation, and retrieval-augmented systems |
| Neurosymbolic AI | Exploring the intersection of neural models and symbolic knowledge |

---

## Featured Research

### 01 — Green AI Compression for Disaster-Tweet Classification

[![Repository](https://img.shields.io/badge/Explore_Research-GitHub-181717?style=flat-square&logo=github)](https://github.com/Lucky10406/LLM-compression-study)
[![Paper](https://img.shields.io/badge/Read_Research_Paper-8B5CF6?style=flat-square)](https://github.com/Lucky10406/LLM-compression-study/blob/main/report/final_research_paper.pdf)

An empirical investigation into the quality-efficiency trade-offs of compressing large language models for disaster-related text classification.

The research compares quantization, magnitude pruning, and knowledge distillation using a QLoRA-fine-tuned **Qwen2.5-3B-Instruct** model and DistilBERT classifiers.

**Research highlights:**

- Evaluated FP16, INT8, and INT4 NF4 model configurations.
- Investigated 30%, 50%, and 70% unstructured magnitude pruning.
- Compared task-specific knowledge distillation against a hard-label control.
- Measured classification quality, latency, throughput, GPU memory, and estimated energy consumption.

| Experimental Result | Value |
|---|---:|
| INT4 NF4 Macro F1 | 0.7497 |
| INT4 Peak GPU Memory Reduction | 65.77% |
| Distilled DistilBERT Macro F1 | 0.7630 |
| Distilled Student Median Latency | 4.38 ms |

> Results are specific to the reported HumAID benchmark and execution environment. Energy measurements are estimates, and the distilled classifier represents a separate task-specific architecture.

<p align="center">
  <img src="https://raw.githubusercontent.com/Lucky10406/LLM-compression-study/main/outreach/hero_figure.png" width="850" alt="Research quality-efficiency Pareto comparison" />
</p>

**Research status:** Experimental study and research report completed.

**Tools and methods:** PyTorch · Hugging Face · QLoRA · bitsandbytes · DistilBERT · CodeCarbon

---

### 02 — PixelRAG for GeoGuessr

[![Repository](https://img.shields.io/badge/Explore_Research-GitHub-181717?style=flat-square&logo=github)](https://github.com/Lucky10406/PixelRAG-for-GeoGuessr-Research-)

An exploratory research project studying whether PixelRAG-style visual retrieval can support image geolocation using real-world visual evidence.

The study evaluates an image-only retrieval baseline and a conservative OCR-based extension across a frozen benchmark of **150 images from 30 countries**.

**Research highlights:**

- Evaluated country-level retrieval and prediction.
- Investigated the relationship between retrieved evidence and prediction reliability.
- Explored OCR-based geographical clues.
- Analyzed unsuccessful retrieval cases and abstention behavior.

| Evaluation | Result |
|---|---:|
| Benchmark size | 150 images |
| Countries | 30 |
| Correct country evidence in Top-5 | 17.3% |
| Selective prediction accuracy | 51.0% |

> This is an exploratory benchmark, not a state-of-the-art geolocation claim. The OCR extension showed limited coverage and requires further investigation.

**Research status:** Exploratory evaluation completed.

---

## My Research Library

<a href="https://github.com/Lucky10406/AI-Research-Library">
  <img src="https://img.shields.io/badge/AI_Research_Library-Explore_Papers-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white" />
</a>

A continuously growing collection of research papers, study questions, reading notes, and resources that support my research journey.

The library is designed to help students, researchers, and developers discover relevant work without navigating through an unorganized collection of PDFs.

| Topic | Explore |
|---|---|
| AI & Machine Learning Foundations | [Browse papers](https://github.com/Lucky10406/AI-Research-Library/tree/main/papers/foundations) |
| LLM Compression & Adaptation | [Browse papers](https://github.com/Lucky10406/AI-Research-Library/tree/main/papers/llm-compression) |
| Multilingual AI | [Browse papers](https://github.com/Lucky10406/AI-Research-Library/tree/main/papers/multilingual-ai) |
| Responsible AI & Safety | [Browse papers](https://github.com/Lucky10406/AI-Research-Library/tree/main/papers/responsible-ai) |
| Data-Centric AI | [Browse papers](https://github.com/Lucky10406/AI-Research-Library/tree/main/papers/data-centric-ai) |
| Neurosymbolic NLP | [Browse papers](https://github.com/Lucky10406/AI-Research-Library/tree/main/papers/neurosymbolic-nlp) |
| Efficient AI & Green AI | [Browse papers](https://github.com/Lucky10406/AI-Research-Library/tree/main/papers/efficient-ai) |

[Browse the complete research library](https://github.com/Lucky10406/AI-Research-Library) · [Explore reading paths](https://github.com/Lucky10406/AI-Research-Library/tree/main/reading-lists)

---

## Projects & Experiments

I enjoy working on projects that combine research, engineering, and product development.

| Project | Description | Status |
|---|---|---|
| **Sparrow Browser** | Privacy-first browser and independently developed search infrastructure, including crawling, indexing, ranking, and search interfaces. | In development |
| [LLM Compression Study](https://github.com/Lucky10406/LLM-compression-study) | Empirical research on efficient AI and disaster-tweet classification. | Research completed |
| [PixelRAG for GeoGuessr](https://github.com/Lucky10406/PixelRAG-for-GeoGuessr-Research-) | Experimental visual retrieval and image geolocation research. | Evaluation completed |
| [AI Research Library](https://github.com/Lucky10406/AI-Research-Library) | Curated research knowledge base with categorized papers and reading resources. | Growing |
| [Aeson](https://github.com/Lucky10406/Aeson) | Entrepreneurial and technology development initiative. | Project |
| [imAgIne](https://github.com/Lucky10406/imAgIne) | Web application development project. | Project |
| [Delivery Disaster](https://github.com/Lucky10406/Delivery-Disaster-Game) | Game development experiment. | Project |
| [The Last Walk](https://github.com/Lucky10406/the-last-walk-game) | Another exploration of game development and interactive experiences. | Project |

### Currently Building — Sparrow

Sparrow is an independent browser and search infrastructure project built around privacy, transparency, and greater control over the browsing experience.

Areas of development include:

- Web crawling and document discovery.
- Search indexing and ranking.
- Browser interface and navigation.
- Privacy-oriented architecture.
- Independent search infrastructure.

---

## Technical Toolkit

### AI, Machine Learning & Research

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
</p>

### Web Development & Software Engineering

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,nodejs,vite&theme=dark" />
</p>

### Databases, Infrastructure & Development Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,sqlite,firebase,supabase,cloudflare,vercel,git,github,vscode&theme=dark" />
</p>

---

## My Learning Roadmap

I'm continuously developing my understanding of:

- Transformer architectures and language model internals.
- Quantization algorithms and efficient inference.
- GPU memory optimization and hardware-aware AI.
- Multilingual model evaluation and calibration.
- Retrieval systems, information retrieval, and search ranking.
- Research methodology, experimental design, and reproducibility.
- Distributed systems and scalable software architecture.

---

## Books, Papers & Resources Worth Exploring

<details>
<summary><b>Foundational AI & Deep Learning</b></summary>

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [Understanding Deep Learning](https://udlbook.github.io/udlbook/)
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- [Transformer Explainer](https://poloclub.github.io/transformer-explainer/)
- [Dive into Deep Learning](https://d2l.ai/)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/)

</details>

<details>
<summary><b>LLM Compression & Efficient AI</b></summary>

- [Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)
- [LLM.int8()](https://arxiv.org/abs/2208.07339)
- [GPTQ](https://arxiv.org/abs/2210.17323)
- [LoRA](https://arxiv.org/abs/2106.09685)
- [QLoRA](https://arxiv.org/abs/2305.14314)
- [Green AI](https://arxiv.org/abs/1907.10597)

</details>

<details>
<summary><b>Multilingual AI, Fairness & Responsible Research</b></summary>

- [How Does Quantization Affect Multilingual LLMs?](https://aclanthology.org/2024.findings-emnlp.935/)
- [Calibrating Beyond English](https://aclanthology.org/2026.eacl-long.223/)
- [How Quantization Shapes Bias in Large Language Models](https://aclanthology.org/2026.eacl-long.17/)
- [Preserving Fairness and Safety in Quantized LLMs Through Critical Weight Protection](https://aclanthology.org/2026.findings-acl.993/)
- [Datasheets for Datasets](https://arxiv.org/abs/1803.09010)

</details>

<details>
<summary><b>Research Discovery & Open Science</b></summary>

- [arXiv](https://arxiv.org/) — Research preprints
- [Semantic Scholar](https://www.semanticscholar.org/) — Scientific literature discovery
- [OpenReview](https://openreview.net/) — Research submissions and open peer review
- [ACL Anthology](https://aclanthology.org/) — Computational linguistics research
- [Hugging Face Papers](https://huggingface.co/papers) — Machine learning papers
- [Google Scholar](https://scholar.google.com/) — Academic literature search
- [Connected Papers](https://www.connectedpapers.com/) — Research relationship visualization

</details>

<details>
<summary><b>Engineering, Systems & Search</b></summary>

- [Introduction to Information Retrieval](https://nlp.stanford.edu/IR-book/)
- [The Architecture of Open Source Applications](https://aosabook.org/)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Cloudflare Developer Documentation](https://developers.cloudflare.com/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)

</details>

<details>
<summary><b>Beyond AI — Things I'm Curious About</b></summary>

- [Our World in Data](https://ourworldindata.org/) — Global trends and statistics
- [MIT OpenCourseWare](https://ocw.mit.edu/) — Open educational resources
- [Neal.fun](https://neal.fun/) — Interactive explorations
- [OWASP](https://owasp.org/) — Cybersecurity knowledge
- [Ethereum Developer Resources](https://ethereum.org/developers/) — Blockchain and decentralized systems
- [Internet Archive](https://archive.org/) — Digital knowledge and history

</details>


## Open to Collaborate

I'm interested in connecting with researchers, engineers, students, and people building ambitious technology.

I'm particularly interested in:

- Research internships in AI and machine learning.
- Efficient AI, LLM compression, and hardware-aware ML research.
- Collaborative experiments and research reproducibility.
- Open-source software and independent digital infrastructure.
- Interesting ideas at the intersection of AI, finance, and decentralized technology.

If you're working on a related problem or have an idea worth exploring, feel free to reach out.

<div align="center">

<a href="mailto:mayureshsharma10406@gmail.com">
  <img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/mayuresh-sharma-a08526315">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://www.instagram.com/lucky_10406/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>

---

**Explore ideas. Question assumptions. Build what matters.**

<sub>Always learning, always experimenting.</sub>

</div>
