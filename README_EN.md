
# 📱 SMS Spam Detection with Deep Learning

This project aims to classify SMS messages as *spam* or *ham* using various Deep Learning approaches, culminating in the fine-tuning of the **BERT** model (DistilBERT variant).

## 📁 Files Used

- `spam.csv`: Dataset containing labeled SMS messages.
- `projet AT&T.ipynb`: Main development notebook.
- `01-AT&T_spam_detector.ipynb`: Original exercise version.

## 🔧 Methodology

Three pipelines were implemented:
1. **TF-IDF + Logistic Regression** (baseline)
2. **Simple Neural Network (RNN-like)** with embedding + global pooling
3. **Transfer Learning with BERT (DistilBERT)**: fine-tuned on our dataset.

Each model is evaluated on:
- Accuracy
- Classification report (precision, recall, f1-score)
- Confusion matrix

## 🚀 Getting Started

Install dependencies:
```bash
pip install -r requirements.txt
```

## 📊 Results

The fine-tuned DistilBERT model delivered the best performance, with a strong recall score—critical for spam detection.

## 🧠 Authors

Project conducted during the Data Scientist training — Module 4: Deep Learning.
