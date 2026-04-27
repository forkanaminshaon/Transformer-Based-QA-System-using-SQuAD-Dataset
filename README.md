# BERT-Based Question Answering on SQuAD v1.1

This project demonstrates fine-tuning a transformer-based model for extractive question answering using the SQuAD v1.1 dataset. The model is trained to predict answer spans (start and end positions) from a given context in response to a question.

##  Features
- Fine-tuned BERT model for Question Answering
- Tokenization and preprocessing with Hugging Face Transformers
- Span-based prediction (start and end positions)
- Evaluation using Exact Match (EM) and F1 Score
- Custom question-answer testing

##  Model
- Pretrained Model: bert-base-uncased
- Framework: Hugging Face Transformers
- Training Strategy: Fine-tuning using Trainer API

## Results
- Exact Match (EM): 63.55%
- F1 Score: 72.10%

## Dataset
- Stanford Question Answering Dataset (SQuAD v1.1)

## Tech Stack
- Python
- Hugging Face Transformers
- Datasets
- Evaluate
- PyTorch

## Example

**Question:** Who developed the theory of relativity?  
**Answer:** Albert Einstein  

## Key Learning

- Difference between classification and extractive QA tasks
- Handling tokenization and answer span alignment
- Fine-tuning transformer models for NLP tasks
- Evaluating QA systems using EM and F1 metrics

## 🔗 Notebook
Google Colab notebook included for end-to-end execution.

https://colab.research.google.com/drive/1DuSlM6WBQ9FXr6s2GxumD-m90i05jRCW?usp=sharing
## 🔗 Notebook
Google Colab notebook included for end-to-end execution.
