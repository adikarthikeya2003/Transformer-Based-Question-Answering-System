# Transformer-Based-Question-Answering-System (SQuAD v2)
End-to-end NLP Question Answering system comparing BERT, RoBERTa, DeBERTa, and Flan-T5 on SQuAD v2 with EM, F1, and BERTScore evaluation.

## Overview
Built and evaluated an end-to-end NLP Question Answering system using transformer models on the SQuAD v2 dataset, focusing on both answerable and unanswerable questions.

## Models
- BERT
- RoBERTa
- DeBERTa
- Flan-T5 (Generative)

## Dataset
- SQuAD v2 (10,000-sample subset due to GPU constraints)

## Key Results
- Improved Exact Match from 34.9% → 75.3%
- Achieved F1 score up to 78.4%
- Unanswerable question detection accuracy up to 92.3%
- Best extractive model: DeBERTa
- Best generative model: Flan-T5

## Evaluation Metrics
- Exact Match (EM)
- F1 Score
- BERTScore
- Classification metrics (precision, recall, macro/micro F1)

## Features
- Multi-model training and comparison
- Visual diagnostics (loss curves, confusion matrices)
- Real-time QA inference interface

## Tech Stack
Python, PyTorch, Hugging Face Transformers, NLP, Google Colab (GPU)

## Demo
Includes an interactive interface for comparing model predictions in real time.

## Future Work
- Larger-scale training
- Model calibration for unanswerable detection
- Deployment via REST API
