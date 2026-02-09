# nlp_project

Introduction to NLP Project, Feb 2026

Gyuseog Hong   
LG electronics

## About This Project

This project investigates the **feasibility of building a specialized and personalized healthcare Large Language Model (LLM)** using a **local small-scale LLM combined with Retrieval-Augmented Generation (RAG)**.

Instead of relying solely on prompt engineering or fully fine-tuned medical LLMs, this work explores whether **RAG-based knowledge injection** can provide sufficient medical specialization and personalization while preserving privacy and reducing operational costs.

---

## Motivation

As expectations for LLMs continue to rise, users increasingly seek **specialized and personalized feedback**, particularly in healthcare. However, existing approaches face several critical limitations:

- **Prompt-based personalization requires large context inputs**, leading to high token costs and slower inference.
- **Medical data privacy and security regulations** restrict sending personal health data to cloud-based LLM services.
- **Specialized medical LLMs** are often limited to institutional use due to regulatory and approval barriers.
- Consequently, **general users have limited access to personalized medical AI systems**.

This project is motivated by the hypothesis that a **locally deployed LLM**, augmented with medical knowledge and personal health records via RAG, can provide meaningful personalization without violating privacy constraints.

---

## Project Goal

Rather than focusing purely on academic novelty, this project aims to serve as a **hands-on, industry-oriented feasibility study**:

- Evaluate how well **RAG-based LLMs** perform compared to vanilla prompting and pretrained baselines.
- Examine whether **medical specialization** can be achieved without full model fine-tuning.
- Explore **privacy-preserving personalization** using personal health records (e.g., check-up reports).

---

## Approach

### Data
- **Evaluation Dataset**: PubMedQA (reasoning-required biomedical QA) https://pubmedqa.github.io/
<img width="299" height="49" alt="image" src="https://github.com/user-attachments/assets/f461a441-5874-4806-ac00-2b91e02f12a6" />

- **Knowledge Corpus for RAG**: PubMed abstracts
- **Personalization Sou**

