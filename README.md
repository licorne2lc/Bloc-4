
#  Détection de spam SMS avec le Deep Learning

Ce projet consiste à classifier des messages SMS comme *spam* ou *ham* (non-spam) en utilisant différentes approches de Deep Learning, culminant avec un fine-tuning du modèle pré-entraîné **BERT** (via DistilBERT).

##  Fichiers utilisés

- `spam.csv` : jeu de données contenant les messages SMS et leurs labels.
- `projet AT&T.ipynb` : notebook principal .
- `01-AT&T_spam_detector.ipynb` : Ennoncé de l'exercice.

##  Méthodologie

Trois pipelines ont été testés :
1. **TF-IDF + Régression Logistique** (baseline)
2. **Réseau de neurones simple (RNN)** avec embedding + global pooling avec optimisation du seuil.
3. **Transfert Learning avec BERT (DistilBERT)** : fine-tuning sur les données avec optimisation du seuil.

Chaque modèle est évalué sur :
- Accuracy
- Rapport de classification (precision, recall, f1-score)
- Matrice de confusion

## Notebook : **projet AT&T.ipynb

##  Résultats

Le modèle DistilBERT fine-tuné fournit les meilleurs résultats avec un rappel (recall) élevé, crucial pour détecter les spams.

##  Auteurs

Projet réalisé par moulinier jerome dans le cadre de la formation Data Scientist — Bloc 4 : Deep Learning.
