# 📙 EngiBench Level 3 Dataset Field Descriptions

This document provides detailed descriptions of each field in the Level 3 dataset used in the EngiBench benchmark.  
Level 3 focuses on **open-ended, real-world engineering tasks**, evaluated using a **rubric-based system** across four core capabilities.

---

## 🧾 Field Descriptions

| Field Name                           | Description                                                                                               |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------|
| `question`                           | The translated version of the original question in English.                                               |
| `question_modified`                  | Semantically perturbed version of the original question.                                                  |
| `source_detail`                      | The original source of the question (e.g., MCM competition, course assignments, national exam).           |
| `official_scoring_standard`          | Translated version of the official rubric into English.                                                   |
| `subfield`                           | Engineering subfield (e.g., Systems & Control, Structural, Chemical & Biological).                        |
| `category`                           | Topical domain or context.                                                                                |
| `information_extraction_score`       | Score for the model's ability to identify and filter relevant information from complex inputs.            |
| `multi_objective_decision_score`     | Score for the model's ability to balance competing objectives and make trade-offs.                        |
| `redundant_information_filtering_score` | Score for the model's ability to reason under uncertainty or incomplete data.                             |
| `domain_specific_reasoning_score`    | Score for the model's ability to apply engineering knowledge and perform domain-specific reasoning.       |

---

## 📌 Notes

- 🏆 Level 3 problems assess **higher-order reasoning** and **realistic decision-making**.  
- 📑 Scoring is based on **rubrics** rather than binary correctness.  
- ⚖️ Each score reflects one of the **core capabilities**: Information Extraction, Domain-Specific Reasoning, Multi-Objective Decision-Making, and Uncertainty Handling.  
