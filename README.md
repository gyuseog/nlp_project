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
- **Evaluation Dataset**: PubMedQA (reasoning-required biomedical QA)
- **Knowledge Corpus for RAG**: PubMed abstracts
- **Personalization Source**: Simulated personal health records (PDF-based)

### Baselines
- Vanilla LLM with prompting
- Pretrained LLM without external retrieval

### Proposed Methods
- Local LLM + RAG (medical literature)
- Local LLM + LoRA (parameter-efficient specialization)
- RAG-based personalization using health records

---

## Evaluation

### Specialization
- Biomedical QA performance on PubMedQA
- Reasoning capability comparison across models
- Performance of small/local models with RAG

#### Results

### Personalization
- Question Answering (QA)
- Question Generation (QG)
- LLM-as-a-Judge evaluation (exploratory)

#### Results
---

## Key Idea

Rather than embedding all medical and personal knowledge into model parameters, this project explores **RAG as a flexible and lightweight alternative** that enables:

- Medical specialization without full fine-tuning
- Privacy-preserving personalization
- Practical deployment on local or embedded environments

---

## Limitations

- Limited computational resources prevented fully controlled comparisons.
- Lack of standardized evaluation metrics for personalization.
- Advanced RAG strategies and optimizations were not fully explored.

---

## Future Work

- Incorporate domain-specific embeddings (e.g., BioBERT, Bio-SBERT).
- Improve evaluation frameworks for personalization.
- Apply advanced RAG techniques and optimization strategies.
- Extend experiments to broader healthcare use cases.

---

## Conclusion

This project demonstrates that, with appropriate optimization and embedding strategies, **local LLMs combined with RAG show strong potential as specialized and personalized healthcare assistants**, without the cost and regulatory burden of fully fine-tuned medical LLMs.
