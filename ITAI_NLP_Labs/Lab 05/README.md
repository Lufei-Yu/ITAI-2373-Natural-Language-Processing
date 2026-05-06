
# Lab 05 – Text Classification with Machine Learning

## Problem Statement
The goal of this lab is to build a machine learning model that can classify text into predefined categories. This lab demonstrates how feature extraction, preprocessing, and supervised learning techniques can be combined to solve real‑world NLP classification tasks.

## Approach
- Loaded and explored a labeled text dataset.
- Performed preprocessing:
  - Tokenization
  - Stop‑word removal
  - Lemmatization
  - Text normalization
- Converted text into numerical features using:
  - Bag‑of‑Words
  - TF‑IDF vectorization
- Trained multiple machine learning classifiers, such as:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machines (SVM)
- Evaluated models using accuracy, precision, recall, and F1‑score.
- Compared performance across different feature extraction and model choices.

## Results
- TF‑IDF features consistently outperformed Bag‑of‑Words.
- Logistic Regression or SVM typically produced the strongest classification performance.
- The confusion matrix revealed which classes were most frequently misclassified.

## Key Findings
- Text preprocessing has a major impact on classification accuracy.
- TF‑IDF provides richer information than simple word counts.
- Linear models (Logistic Regression, SVM) often outperform Naive Bayes on well‑structured datasets.
- Evaluating multiple metrics gives a more complete understanding of model performance.

## Technologies Used
- Python 3.x  
- NLTK / spaCy  
- Scikit‑learn  
- NumPy, Pandas  
- Matplotlib / Seaborn  
- Jupyter Notebook

## How to Run
1. Open the notebook in Jupyter or Google Colab.
2. Install dependencies:
   ```bash
   pip install nltk spacy scikit-learn pandas matplotlib
