
# 📱 Détection de spam SMS avec le Deep Learning

Ce projet consiste à classifier des messages SMS comme *spam* ou *ham* (non-spam) en utilisant différentes approches de Deep Learning, culminant avec un fine-tuning du modèle pré-entraîné **BERT** (via DistilBERT).

## 📁 Fichiers utilisés

- `spam.csv` : jeu de données contenant les messages SMS et leurs étiquettes.
- `projet AT&T.ipynb` : notebook principal de développement.
- `01-AT&T_spam_detector.ipynb` : version d'origine de l'exercice.

## 🔧 Méthodologie

Trois pipelines ont été testés :
1. **TF-IDF + Régression Logistique** (baseline)
2. **Réseau de neurones simple (RNN-like)** avec embedding + global pooling
3. **Transfert Learning avec BERT (DistilBERT)** : fine-tuning sur les données.

Chaque modèle est évalué sur :
- Accuracy
- Rapport de classification (precision, recall, f1-score)
- Matrice de confusion

## 🚀 Démarrage

Installer les dépendances :
```bash
pip install -r requirements.txt
```

## 📊 Résultats

Le modèle DistilBERT fine-tuné fournit les meilleurs résultats avec un rappel (recall) élevé, crucial pour détecter les spams.

## 🧠 Auteurs

Projet réalisé dans le cadre de la formation Data Scientist — Bloc 4 : Deep Learning.
