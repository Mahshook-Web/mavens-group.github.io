---
title: Materials Informatics
show_date: false
profile: false
---

Designing functional materials with novel properties lies at the heart of modern technological innovation. Traditional approaches to identifying these materials through trail and error experimentation are time- and resource-intensive. Although ab-initio computational techniques can offer some speed up, materials discovery remain constrained by the sheer complexity of material systems and the vast pool of possible candidates. Machine learning opens the door to a paradigm shift by applying data-driven methods enabling accelerated materials discovery. Materials Informatics aims to accelerate materials discovery using data-driven machine learning solutions. At MAVENs, we use machine learning as a tool to design materials for various applications including Quantum Information Science and Magnetocaloric Refregeration.
## Research Areas

### 1. Designing Qubits for Quantum Information Processing:
A fault-tolerant quantum computer could challenge the limits of what's computationally tractable. Unlike traditional computers that work using boolean logic, Quantum computers rely on quantum mechanical phenomena like superposition and entanglement to perform computations long thought impossible using even supercomputers. To perform quantum computation, such devices rely on binary information stored in two-level quantum systems. The so-called qubits demand materials that could exhibit long coherence times, efficient state manipulation and high-fidelity read-out. Deep level defects in semiconductors offer themselves as promising candidates exhibiting the above-mentioned criteria, notably the NV-center in diamond. But fabricating diamond defects is a technologically challenging task. Our research aims to use machine learning models to scan through the vast expanse of semiconducting materials space to identify host-defect systems with improved quantum compatible properties that can be synthesized using existing fabrication techniques.

### 2. Named Entity Recognition for Efficient Data Retrieval:
Structured data stored in databases are the primary source of information for material properties. A vast amount of information is hidden in the form of unstructured texts in articles, books, etc... Traditional Data mining methods have relied on manual curation or keyword-based searches, which are both time-consuming and prone to missing critical information. Named Entity Recognition (NER), a core concept in Natural Language Processing could automate the process of information retrieval thanks to rapid developments in the capabilities of Large Language Models (LLMs) implementing them. Our research aims to develop APIs for information retrieval from scientific texts using LLMs fine tuned on domain specific tasks. By fine-tuning LLMs on domain-specific corpora, these LLMs could identify, extract, and organize material properties such as band gaps, elastic constants, thermal conductivities, and defect formation energies directly from scientific literature. These models not only improve the speed and scalability of data extraction but also capture contextually relevant insights, such as experimental conditions or theoretical methods used in the reported studies.

### 3. Fine-tuning Large Language Models for Materials Discovery:
In the words of Andrej Karpathy, a founding member of OpenAI, *Large Language Models have little to do with language; they are highly general-purpose technology for statistical modeling of token streams*. The predictive capabilities of LLMs are often overshadowed by their impact on NLP. These models are capable of learning intricate details that even the most sophisticated machine learning models would struggle with, their primary limitation being the vast amount of data required for training. In conventional machine learning, developing representations of materials that capture all the invariants in their structure and composition often compromises predictive accuracy. LLMs, however, can learn these invariants and representations directly from natural language texts, making them a versatile tool for materials discovery. Despite this potential, the use of LLMs for material property prediction remains underexplored. Our research focuses on leveraging textual representations of materials data to fine-tune LLMs for downstream material property predictions. Additionally, we aim to address challenges such as mitigating hallucinations in model predictions. By developing, comparing, and contrasting these models with traditional machine learning approaches, we seek to evaluate their effectiveness and unlock new possibilities for materials informatics.

## Methodologies
For statistical modelling we use open source python libraries scikit-learn, tensorflow and pytorch
to develop machine learning models, and pymatgen, DScribe, and matminer libraries for feature
engineering.
To train large language models, we use pytorch and tranformers API.