# AI-ML-Assignment-6-Prompt-Engineering

**Name:** Mateusz Ozog  
**Course:** AD 331  
**Assignment:** Prompt Engineering  
**Environment:** Jupyter Notebook (Anaconda)  
**Model Used:** google/flan-t5-small (Hugging Face)

---

## Assignment Overview

The goal of this assignment is to demonstrate how prompt engineering techniques can significantly improve the quality and reliability of Large Language Model (LLM) outputs. The model and input text remain the same for every test. Only the prompt is changed.

The task used in this experiment is structured data extraction. The model is given several product reviews written in natural language and must extract the product name, price, and purchase date from each review.

---

## Input Data

The same input text is used for all prompt tests. The text is intentionally messy, with different date formats, informal prices, and one missing price, to make the task more challenging.

---

## Prompt Comparison Summary

| Prompt Version | Technique Used | Score (1–10) | Observation |
|---------------|---------------|--------------|-------------|
| Baseline | None | 3 | Output is incomplete and unstructured |
| Technique 1 | Role Prompting | 5 | Slightly more careful but still inconsistent |
| Technique 2 | Output Formatting (JSON) | 8 | Major improvement, structured and usable |
| Technique 3 | Step-by-Step Instructions | 8 | More consistent handling of edge cases |
| Final Prompt | Combined Techniques | 9 | Cleanest and most reliable output |

---

## Key Takeaway

This experiment shows that prompt engineering alone can significantly improve LLM performance. By adding clear instructions, format constraints, and simple reasoning steps, the model produces outputs that are more accurate, consistent, and usable without changing or retraining the model.

---

## Files Included

- `Assignment6_Prompt_Engineering.ipynb` – Jupyter Notebook with all prompt experiments  
- `README.md` – Assignment summary and results
