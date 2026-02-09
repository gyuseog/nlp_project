# nlp_project

Introduction to NLP Project, Feb 2026

Gyuseog Hong
LG electronics

This project explores the feasibility of building a specialized and personalized healthcare LLM using a local small-scale language model combined with Retrieval-Augmented Generation (RAG), rather than relying solely on prompt engineering or fully fine-tuned medical LLMs.

Motivation

As user expectations for Large Language Models (LLMs) increase, there is growing demand for more specialized and personalized feedback, especially in the healthcare domain. However, current approaches face several limitations:

Personalization via prompting requires large context inputs, leading to high token costs and slower response times.

Medical data privacy and regulatory constraints make it difficult to send personal health records to cloud-based LLM services.

Specialized medical LLMs are often restricted to institutional use and face high regulatory and approval barriers.

As a result, general users have limited access to personalized medical AI systems.

This project is motivated by the hypothesis that a locally deployed LLM, augmented with medical knowledge and personal health data via RAG, can provide meaningful specialization and personalization without violating privacy constraints.

Project Goal

Rather than pursuing purely academic benchmarks, this project aims to be a hands-on, industry-relevant feasibility study:

How well can a RAG-based approach approximate the performance of medically fine-tuned models?

Can personal health records (e.g., check-up reports) be integrated safely to improve personalization?

How does RAG compare to vanilla prompting and pretrained LLM baselines?

Approach

Dataset: PubMedQA (reasoning-required biomedical QA)

Knowledge Source for RAG: PubMed abstracts

Baselines:

Vanilla LLM with prompting

Pretrained LLM without external knowledge

Proposed Models:

Local LLM + RAG (medical literature)

Local LLM + LoRA (specialization)

RAG with simulated personal health records (PDF-based)

Evaluation:

Specialization: QA accuracy and reasoning performance on PubMedQA

Personalization: QA/QG-based evaluation and LLM-as-a-Judge methodology
