# Lab 02 Basic NLP Preprocessing Techniques

## Problem Statement
This lab focuses on the foundational preprocessing steps required for Natural Language Processing tasks. The goal is to clean, normalize, and transform raw text into structured representations that machine learning models can understand.

## Approach
- Loaded and explored a raw text dataset.
- Applied essential preprocessing techniques:
  - Lowercasing and normalization
  - Removing punctuation and special characters
  - Stop‑word removal
  - Tokenization
  - Stemming and lemmatization
- Compared different preprocessing strategies and observed their impact on downstream tasks.
- Converted text into numerical representations such as Bag‑of‑Words or TF‑IDF.

## Results
- Successfully transformed raw text into clean, tokenized, and vectorized data.
- Demonstrated how preprocessing choices affect vocabulary size and feature quality.
- Observed improvements in text clarity and structure after applying normalization steps.

## Key Findings
- Text preprocessing is a critical first step in any NLP pipeline.
- Tokenization and lemmatization significantly influence model performance.
- Removing noise (punctuation, stop words) improves feature quality but must be done carefully, depending on the task.
- Different preprocessing methods can lead to very different model outcomes.

## Technologies Used
- Python 3.x  
- NLTK / spaCy  
- Scikit‑learn  
- NumPy, Pandas  
- Jupyter Notebook

## How to Run
1. Open the notebook in Jupyter or Google Colab.
2. Install dependencies:
   ```bash
   pip install nltk spacy scikit-learn pandas
