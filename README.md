# Awesome-RAG
This is a repo to show the recent RAG approaches. There are several research line to RAGs. One is to finetuning the LLM to enhance the ability of LLM to use the external knowledge. For example, self-rag use some **reflection token** to teach LLM whether use the external knowledge or not.  DRAGIN is a dynamic RAG method to address the complex multi-step tasks. They develop an Real-time Information Needs Detection and Query Formulation based on Selfattention (QFS) methods. In the paper "Making Retrieval-Augmented Language Models Robust to Irrelevant Context", the author find that RALM are are now robust for the irrelevant documents, to address this, they train some examples to make models robust to irrelevant context and improve overall performance.


## Text-based RAG 

### Robust RAG

It have been proved that the LLM can be easily distracted by irrelevant context. To alleviate this, there are several methods to make the RAG more robust. 
| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [SELF-RAG: LEARNING TO RETRIEVE, GENERATE, ANDCRITIQUE THROUGH SELF-REFLECTION](https://arxiv.org/pdf/2310.11511) | 2024 |  ICLR | |
| [A THEORY FOR TOKEN-LEVEL HARMONIZATION IN RETRIEVAL-AUGMENTED GENERATION](https://arxiv.org/pdf/2406.00944) | 2025 |  ICLR | no Run|
| [Search-in-the-Chain: Interactively Enhancing Large Language Models with Search for Knowledge-intensive Tasks](https://arxiv.org/pdf/2304.14732) | 2025 | WWW | no Run|
| [Corrective Retrieval Augmented Generation](https://arxiv.org/pdf/2401.15884) | 2024 | Arxiv | no Run|
| [Making Retrieval-Augmented Language Models Robust to Irrelevant Context](https://arxiv.org/pdf/2310.01558) | 2023 | ICLR | no Run|
| [Large language models can be easily distracted by irrelevant context](http://proceedings.mlr.press/v119/guu20a/guu20a.pdf) | 2024 |  ICML | |
| [Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models](https://arxiv.org/abs/2311.09210) | 2024 | EMNLP | no Run|
| [RbFT: Robust Fine-tuning for Retrieval-Augmented Generation against Retrieval Defects](https://arxiv.org/pdf/2501.18365?) | 2025 | Arxiv | no Run|

#### attack the RAG system

| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [Attacking open-domain question answering by injecting misinformation](https://arxiv.org/pdf/2510.13217) | 2025 | Arxiv | no Run|
| [{PoisonedRAG}: Knowledge corruption attacks to {Retrieval-Augmented} generation of large language models](https://www.usenix.org/conference/usenixsecurity25/presentation/zou-poisonedrag) | 2023 | Arxiv | no Run|
| [Poisoning Retrieval Corpora by Injecting Adversarial Passages](https://arxiv.org/pdf/2310.19156) | 2023 | Arxiv | no Run|
| [Phantom: General Backdoor Attacks on Retrieval Augmented Language Generation](https://arxiv.org/pdf/2405.20485) | 2025 | Arxiv | no Run|
| [Trojanrag: Retrieval-augmented generation can be backdoor driver in large language models](https://arxiv.org/pdf/2405.13401) | 2024 | Arxiv | no Run|
| [" Glue pizza and eat rocks"--Exploiting Vulnerabilities in Retrieval-Augmented Generative Models](https://arxiv.org/pdf/2406.19417) | 2024 | Arxiv | no Run|
| [Badrag: Identifying vulnerabilities in retrieval augmented generation of large language models](https://arxiv.org/pdf/2406.00083) | 2024 | Arxiv | no Run|






#### Confidence score

| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [DRAGIN: Dynamic Retrieval Augmented Generation based on the Information Needs of Large Language Models ](https://arxiv.org/pdf/2403.10081#page=10.70) | 2024 | ACL oral | no Run|
| [Active Retrieval Augmented Generation](https://arxiv.org/pdf/2305.06983) | 2023 |  | no Run|
| [How can we know when language models know? on the calibration of language models for question answering](https://aclanthology.org/2021.tacl-1.57/) | 2021 | TACL | no Run|

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


## Application 

### medical RAG
| **Paper Title** | **Year** | **Conference/Journal** | **Remark** |
| --------------- | :----: | :----: | :----: |
| [Improving Retrieval-Augmented Generation in Medicine with Iterative Follow-up Questions](https://arxiv.org/pdf/2408.00727) | 2024 |  Arxiv |

## Novel methods

| **Paper Title** | **Year** | **Conference/Journal** | **Code** |
| --------------- | :----: | :----: | :----: |
| [LLM-GUIDED HIERARCHICAL RETRIEVAL](https://arxiv.org/pdf/2510.13217) | 2025 | Arxiv | no Run|