# Hi! I'm Oliver (Xianyu Yuan) 👋

M.S. student in Security Informatics at **Johns Hopkins University** (ISI) · B.S. in Computer Science, **Case Western Reserve University**

## What I Work On 🔬

### 🤖 AI Security — making LLM systems trustworthy when their outputs drive real decisions
I'm interested in what happens when LLMs are put in charge of high-stakes judgments: where they fail, how to contain those failures, and how to verify them honestly. My view is that an LLM should reason inside hard boundaries, not hold the final say. Its claims should be checked against ground truth rather than against another model's opinion.

### 📈 NQ100 Market-Analysis System — built solo, running live
A hybrid Python–LLM system for intraday futures analysis that applies these ideas in production.
- **Containment architecture**: a deterministic Python engine performs all quantitative computation (key levels, market structure, anomaly signals), the LLM is confined to structured reasoning through a multi-round prompt chain, and programmatic hard overrides enforce every safety-critical constraint
- **Failure-driven iteration**: 4+ major versions, each driven by failure cases found in live evaluation
- **Honest evaluation**: every claim is checked against objective forward prices with day-clustered bootstrap and permutation tests (Westfall–Young maxT). LLM judges serve as an independent cross-check, never as ground truth. One result: the classifier's *state* calls carry real signal and its *direction* calls do not, so the direction layer was demoted rather than tuned
- Live real-time dashboard; now trading micro futures (MNQ, MES, MGC, …)

### ⛓️ Blockchain Security — transaction ordering and MEV
- **Ordering auctions on Arbitrum TimeBoost**: what public auction data does and doesn't establish about revenue and concentration, and the limits of in-protocol fixes (advised by Prof. Matthew Green)
- **MEV detection on Layer 2**: which L1 detection heuristics carry over to rollups, and why some fail structurally

### 📰 LLMs as Measurement Instruments
Using LLMs to turn news into structured, auditable signals, such as a policy shock index from 90k+ headlines, and testing their effect on commodity and equity markets (with Prof. Wenwen Zhang, Sun Yat-sen University).

## Tech Stack 💻

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Dune](https://img.shields.io/badge/Dune_Analytics-F4603E?style=for-the-badge&logoColor=white)

## Connect With Me 📫

Open to research conversations and collaborations.

[![Email](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:ooliveryuan@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OliverYuan-git)
