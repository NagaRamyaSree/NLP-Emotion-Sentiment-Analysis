# NLP Emotion & Sentiment Analysis

An NLP-based project for analyzing emotions and sentiment from conversational text using the EmpatheticDialogues dataset and transformer-based models.

## Overview

Understanding emotions in text is an important part of Natural Language Processing, especially for applications such as conversational AI, customer support, and emotion-aware systems.

This project explores emotion and sentiment classification on conversational data. The workflow includes data preprocessing, emotion label processing, dataset balancing, text tokenization, transformer-based model training, and evaluation.

## Dataset

The project uses the **EmpatheticDialogues** dataset, which contains conversational examples associated with different emotional situations.

The dataset is not included in this repository. Users should obtain the dataset separately and provide the required files before running the notebook.

## Methodology

The overall workflow is:

1. Load and inspect the conversational dataset
2. Clean and preprocess the text data
3. Process and organize emotion labels
4. Map emotions into sentiment categories where required
5. Split the data into training, validation, and test sets
6. Handle class imbalance
7. Tokenize the text using a transformer tokenizer
8. Fine-tune a RoBERTa-based classification model
9. Evaluate the trained model
10. Analyze the classification results

## Model

The project uses **RoBERTa (Robustly Optimized BERT Pretraining Approach)** for transformer-based text classification.

RoBERTa is fine-tuned on the conversational dataset to learn patterns associated with different emotional and sentiment categories.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Sentence Transformers
- Matplotlib
- Seaborn
- Imbalanced-learn
- Jupyter Notebook

## Project Structure

```text
NLP-Emotion-Sentiment-Analysis/
│
├── emotion_sentiment_analysis.ipynb
├── requirements.txt
├── README.md
└── .gitignore
