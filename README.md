# A Survey of Large Language Models for Time-Series Anomaly Detection

This repository accompanies the survey paper:

**Kunqi Li, Bin Liang.**  
*A Survey of Large Language Models for Time-Series Anomaly Detection: Methods, Challenges, and Opportunities* (2025).  

We provide resources, taxonomy figures, and a curated list of papers related to large language models (LLMs) for anomaly detection in time-series data and related tasks such as **fault detection, failure diagnosis, fraud detection, and intrusion detection**.  

---

## 📑 Paper
- [Survey PDF](paper/survey.pdf) *(preprint version, if sharing is allowed)*  
- [Taxonomy Diagram](taxonomy-diagram.png)  

---

## 📚 Resources
We aim to keep this repository up to date with new research.  
- [Papers](resources/papers.md) – curated list of works on LLMs + TSAD  
- [Datasets](resources/datasets.md) – benchmark datasets for anomaly and fault detection  
- [Methods](resources/methods.md) – implementations and GitHub repositories  

---

## 🧩 Taxonomy
Our survey introduces a taxonomy of LLM-based approaches for TSAD:
1. **Prompting-based inference**  
   Using zero-shot, few-shot, or chain-of-thought prompting for anomaly reasoning.  
2. **Backbone adaptation**  
   Leveraging LLMs as core sequence models for temporal representation learning.  
3. **Knowledge-injection frameworks**  
   Integrating domain knowledge (rules, graphs, causal priors) with LLM-driven models.  

---

## ✨ Highlights
- First systematic survey of LLMs for time-series anomaly detection (TSAD).  
- Comparative analysis across **prompting**, **backbone**, and **knowledge-injection** paradigms.  
- Discussion of challenges: scalability, interpretability, numeric representation, context length, resource efficiency.  
- Outlook on opportunities: multimodal anomaly detection, retrieval-augmented reasoning, domain-specific prompting.  

---

## 🔎 Citation
If you find this survey useful, please cite:

```bibtex
@article{li2025llm-tsad-survey,
  title={A Survey of Large Language Models for Time-Series Anomaly Detection: Methods, Challenges, and Opportunities},
  author={Kunqi Li and Bin Liang},
  journal={Preprint},
  year={2025}
}
