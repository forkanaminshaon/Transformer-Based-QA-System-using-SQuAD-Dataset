#  BERT-Based Question Answering on SQuAD v1.1

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red)
![Dataset](https://img.shields.io/badge/Dataset-SQuAD_v1.1-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

##  Overview

This project demonstrates fine-tuning a transformer-based model (**BERT**) for extractive Question Answering (QA) using the **SQuAD v1.1 dataset**.

Unlike traditional classification tasks, this model predicts **answer spans (start and end positions)** from a given context in response to a question.

---

##  Model Architecture

- **Model:** bert-base-uncased  
- **Task:** Extractive Question Answering  
- **Approach:** Fine-tuning pre-trained transformer  
- **Framework:** Hugging Face Transformers + PyTorch  

---

##  Tech Stack

- Python  
- Hugging Face Transformers  
- Datasets  
- Evaluate  
- PyTorch  

---

## Results

| Metric        | Score   |
|--------------|--------|
| Exact Match  | 63.55% |
| F1 Score     | 72.10% |

> The higher F1 score indicates the model captures partial answer spans effectively even when exact matches are not perfect.

---

##  Dataset

- 📌 Stanford Question Answering Dataset (**SQuAD v1.1**)  
- ~87K training samples  
- Extractive QA format (context + question → answer span)

---

## 🔄 Pipeline

```text
Raw Data → Tokenization → Span Alignment → Model Fine-Tuning → Evaluation → Prediction

```
## Tech Stack
- Python
- Hugging Face Transformers
- Datasets
- Evaluate
- PyTorch

## Example Predictions

Example 1

Question: Who developed the theory of relativity?
Answer: Albert Einstein

Example 2

Question: Where is the Eiffel Tower located?
Answer: Paris, France

## Key Learning

- Difference between classification and extractive QA tasks
- Handling tokenization and answer span alignment
- Fine-tuning transformer models for NLP tasks
- Evaluating QA systems using EM and F1 metrics

## 🔗 Notebook
Google Colab notebook included for end-to-end execution.

https://colab.research.google.com/drive/1DuSlM6WBQ9FXr6s2GxumD-m90i05jRCW?usp=sharing

## Future Improvements

Train on full dataset (no sampling)
Use larger models (RoBERTa, DeBERTa)
Implement advanced post-processing
Deploy as a QA API

##  Contact

👤 **Forkan Amin**  

💻 GitHub: https://github.com/forkanaminshaon  
🔗 LinkedIn: https://www.linkedin.com/in/forkan-amin-shaon/  

Passionate about Data Science, Machine Learning, and building real-world AI solutions.
