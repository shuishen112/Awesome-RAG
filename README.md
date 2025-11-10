# Awesome-RAG
This is a repo to show the recent RAG approaches. There are several research line to RAGs. One is to finetuning the LLM to enhance the ability of LLM to use the external knowledge. For example, self-rag use some **reflection token** to teach LLM whether use the external knowledge or not.  DRAGIN is a dynamic RAG method to address the complex multi-step tasks. They develop an Real-time Information Needs Detection and Query Formulation based on Selfattention (QFS) methods. In the paper "Making Retrieval-Augmented Language Models Robust to Irrelevant Context", the author find that RALM are are now robust for the irrelevant documents, to address this, they train some examples to make models robust to irrelevant context and improve overall performance.


## Text-based RAG 

### Robust RAG

Retreival augment generation (RAG) enhance the LLMs by retrived relevant documents from external knowledge base. However, the external knowledge is not always reliable. Recent research indicates that RAG systems are vulnerable to adversarial manipulation at both input and corpus level. Attack strategies can be broadly categorized into two types: input-level attacks and corpus-level attacks. At the same time, a variety of defense strategies have been proposed to enhance the robustness of RAG systems. RobustRAG introduces an isolate-then-aggregate framework. 


| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [Making Retrieval-Augmented Language Models Robust to Irrelevant Context](https://arxiv.org/pdf/2310.01558) | 2023 | ICLR | no Run|
| [SELF-RAG: LEARNING TO RETRIEVE, GENERATE, ANDCRITIQUE THROUGH SELF-REFLECTION](https://arxiv.org/pdf/2310.11511) | 2024 |  ICLR | |
| [Certifiably robust rag against retrieval corruption(RobustRAG)](https://arxiv.org/pdf/2405.15556) | 2024 | Arxiv | no Run|
| [Large language models can be easily distracted by irrelevant context](http://proceedings.mlr.press/v119/guu20a/guu20a.pdf) | 2024 |  ICML | |
| [A THEORY FOR TOKEN-LEVEL HARMONIZATION IN RETRIEVAL-AUGMENTED GENERATION](https://arxiv.org/pdf/2406.00944) | 2025 |  ICLR | no Run|
| [Search-in-the-Chain: Interactively Enhancing Large Language Models with Search for Knowledge-intensive Tasks](https://arxiv.org/pdf/2304.14732) | 2025 | WWW | no Run|
| [Corrective Retrieval Augmented Generation(CRAG)](https://arxiv.org/pdf/2401.15884) | 2024 | Arxiv | no Run|
| [Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models](https://arxiv.org/abs/2311.09210) | 2024 | EMNLP | no Run|
| [RbFT: Robust Fine-tuning for Retrieval-Augmented Generation against Retrieval Defects](https://arxiv.org/pdf/2501.18365) | 2025 | Arxiv | no Run|
| [Astute rag: Overcoming imperfect retrieval augmentation and knowledge conflicts for large language models](https://arxiv.org/pdf/2410.07176) | 2024 | Arxiv | no Run|
| [Instructrag: Instructing retrieval-augmented generation with explicit denoising](https://arxiv.org/abs/2406.13629) | 2025 | ICLR | no Run|
| [TrustRAG: Enhancing Robustness and Trustworthiness in Retrieval-Augmented Generation](https://arxiv.org/pdf/2501.00879) | 2025 | Arxiv | no Run|
| [ReliabilityRAG: Effective and Provably Robust Defense for RAG-based Web-Search](https://arxiv.org/abs/2509.23519) | 2025 | NeurIPS | no Run|
| [SeCon-RAG: A Two-Stage Semantic Filtering and Conflict-Free Framework for Trustworthy RAG](https://arxiv.org/abs/2510.09710) | 2025 | NeurIPS | no Run|

#### attack the RAG system

| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [Attacking open-domain question answering by injecting misinformation](https://arxiv.org/pdf/2510.13217) | 2025 | Arxiv | no Run|
| [{PoisonedRAG}: Knowledge corruption attacks to {Retrieval-Augmented} generation of large language models](https://www.usenix.org/conference/usenixsecurity25/presentation/zou-poisonedrag) | 2023 | Arxiv | no Run|
| [Poisoning Retrieval Corpora by Injecting Adversarial Passages](https://arxiv.org/pdf/2310.19156) | 2023 | Arxiv | no Run|
| [Phantom: General Backdoor Attacks on Retrieval Augmented Language Generation](https://arxiv.org/pdf/2405.20485) | 2025 | Arxiv | no Run|
| [Trojanrag: Retrieval-augmented generation can be backdoor driver in large language models](https://arxiv.org/pdf/2405.13401) | 2024 | Arxiv | no Run|
| ["Glue pizza and eat rocks"--Exploiting Vulnerabilities in Retrieval-Augmented Generative Models](https://arxiv.org/pdf/2406.19417) | 2024 | Arxiv | no Run|
| [Badrag: Identifying vulnerabilities in retrieval augmented generation of large language models](https://arxiv.org/pdf/2406.00083) | 2024 | Arxiv | no Run|
| [TrojanRAG: Retrieval-Augmented Generation Can Be Backdoor Driver in Large Language Models](https://arxiv.org/abs/2405.13401) | 2025 | Arxiv | no Run|



#### Confidence score

| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [DRAGIN: Dynamic Retrieval Augmented Generation based on the Information Needs of Large Language Models ](https://arxiv.org/pdf/2403.10081#page=10.70) | 2024 | ACL oral | no Run|
| [Active Retrieval Augmented Generation](https://arxiv.org/pdf/2305.06983) | 2023 |  | no Run|
| [How can we know when language models know? on the calibration of language models for question answering](https://aclanthology.org/2021.tacl-1.57/) | 2021 | TACL | no Run|
| [Corrective Retrieval Augmented Generation](https://arxiv.org/pdf/2401.15884) | 2024 | Arxiv | no Run|
| [Confident Adaptive Language Modeling](https://arxiv.org/abs/2207.07061) | 2022 | NeurIPS | no Run|
| [Retrieval-Augmented Generation with Estimation of Source Reliability](https://arxiv.org/pdf/2410.22954) | 2025 | EMNLP | no Run|
| [REAR: A Relevance-Aware Retrieval-Augmented Framework for Open-Domain Question Answering](https://arxiv.org/pdf/2402.17497) | 2024 | EMNLP | no Run|

#### Retrieval-Augmented Language Model Pre-training
| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [Retrieval augmented language model pre-training](http://proceedings.mlr.press/v119/guu20a/guu20a.pdf) | 2024 |  ICML | |
| [LaSeR: Reinforcement Learning with Last-Token Self-Rewarding](https://www.arxiv.org/pdf/2510.14943) | 2025 |  Arxiv | [code](https://github.com/RUCBM/LaSeR)|



## Parametric RAG

| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [KNOWLEDGE CARD: FILLING LLMS’ KNOWLEDGE GAPS WITH PLUG-IN SPECIALIZED LANGUAGE MODELS](https://arxiv.org/pdf/2305.09955) | 2024 |  ICLR | |
| [DisentQA: Disentangling Parametric and Contextual Knowledge with Counterfactual Question Answering](https://arxiv.org/abs/2211.05655) | 2022 |  Arxiv | |
| [Training Plug-and-Play Knowledge Modules with Deep Context Distillation](https://arxiv.org/pdf/2503.08727) | 2025 | COLM | no Run|
| [Plug-and-Play Document Modules for Pre-trained Models](https://arxiv.org/pdf/2305.17660) | 2023 | ACL | [code](https://github.com/thunlp/Document-Plugin)|

## Benchmark
|
| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [LaRA: Benchmarking Retrieval-Augmented Generation and Long-Context LLMs - No Silver Bullet for LC or RAG Routing](https://arxiv.org/pdf/2502.09977) | 2025 |  ICML | [code](https://github.com/Alibaba-NLP/LaRA)|

## Application 

### medical RAG
| **Paper Title** | **Year** | **Conference/Journal** | **Remark** |
| --------------- | :----: | :----: | :----: |
| [Improving Retrieval-Augmented Generation in Medicine with Iterative Follow-up Questions](https://arxiv.org/pdf/2408.00727) | 2024 |  Arxiv |

## Novel methods

| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [LLM-GUIDED HIERARCHICAL RETRIEVAL](https://arxiv.org/pdf/2510.13217) | 2025 | Arxiv | no Run|

## Hallucination
| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [Selfcheckgpt: Zero-resource black-box hallucination detection for generative large language models](https://arxiv.org/pdf/2303.08896) | 2024 | Arxiv | no Run|
| [Detecting hallucinations in large language models using semantic entropy](https://www.nature.com/articles/s41586-024-07421-0.pdf) | 2024 | Arxiv | no Run|
