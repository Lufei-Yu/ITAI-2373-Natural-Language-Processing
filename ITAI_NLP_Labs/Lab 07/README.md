# Lab 07 – Sentiment and Emotion Analysis in the Real World

## Problem Statement
The goal of this lab is to analyze real‑world text data to determine both sentiment (positive, negative, neutral) and emotional tone (e.g., joy, anger, fear, sadness). This lab demonstrates how NLP models can extract subjective meaning from human language.

## Approach
- Collected or loaded a dataset containing real‑world text samples.
- Performed preprocessing:
  - Tokenization
  - Lowercasing and normalization
  - Stop‑word removal
  - Lemmatization
- Applied sentiment analysis using:
  - Traditional ML models (e.g., Naive Bayes, Logistic Regression) **or**
  - Pretrained NLP models (e.g., VADER, TextBlob, transformer‑based models)
- Applied emotion classification using lexicon‑based or model‑based methods.
- Visualized results using bar charts, word clouds, and distribution plots.

## Results
- Achieved sentiment classification accuracy of **XX%** (replace with your actual result).
- Emotion detection successfully identified dominant emotional categories in the dataset.
- Visualizations revealed common emotional patterns and frequently used words.

## Key Findings
- Sentiment and emotion analysis provide deeper insight into user opinions and behaviors.
- Pretrained models often outperform traditional ML approaches on subjective text.
- Emotion classification is more nuanced than sentiment classification and may require richer models.
- Data quality and preprocessing strongly influence model performance.

## Technologies Used
- Python 3.x  
- NLTK / spaCy  
- Scikit‑learn  
- VADER / TextBlob / HuggingFace Transformers  
- Pandas, NumPy  
- Matplotlib / Seaborn / WordCloud  
- Jupyter Notebook

## How to Run
1. Open the notebook in Jupyter or Google Colab.
2. Install dependencies:
   ```bash
   pip install nltk spacy scikit-learn textblob vaderSentiment wordcloud matplotlib

