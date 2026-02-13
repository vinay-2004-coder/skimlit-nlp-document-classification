# SkimLit — PubMed Abstract Sentence Classification

## Overview
This project builds an NLP model to classify sentences from PubMed abstracts into
section labels (e.g., BACKGROUND, OBJECTIVE, METHODS, RESULTS, CONCLUSION).

## Task
Given a sentence from an abstract (and optionally context features such as line number),
predict its section label.

## Approach
- Text preprocessing and tokenization
- Neural network model in TensorFlow/Keras
- Evaluation using accuracy and classification metrics

## How to Run
### Google Colab
Upload the notebook (and any required helper files) and run top-to-bottom.

### Local
```bash
pip install -r requirements.txt
jupyter notebook
