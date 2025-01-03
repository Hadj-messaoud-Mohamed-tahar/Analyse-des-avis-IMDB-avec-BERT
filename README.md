# Analyse des Sentiments IMDB avec Fine-Tuning de BERT

Ce projet utilise le fine-tuning du modèle BERT pré-entraîné pour classifier les avis du jeu de données IMDB comme positifs ou négatifs. Il comprend des étapes de prétraitement des données, de fine-tuning, et d'évaluation.

## **Fonctionnalités**
- Nettoyage et prétraitement des avis textuels avec NLTK.
- Tokenisation et encodage des données textuelles avec HuggingFace Transformers.
- Fine-tuning de BERT pour la classification binaire des sentiments.
- Évaluation des performances avec des métriques standard et une matrice de confusion.
- Sauvegarde du modèle fine-tuné pour des prédictions futures.

## **Technologies utilisées**
- **Python** : Langage principal.
- **NLTK** : Prétraitement des textes.
- **PyTorch**: Framework principal pour l'entraînement et l'utilisation des modèles de deep learning, comme BERT
- **HuggingFace Transformers** : Tokenisation et fine-tuning du modèle BERT.
- **Scikit-learn** : Calcul des métriques et matrice de confusion.
- **Seaborn et Matplotlib** : Visualisation des résultats.

## **Prérequis**
1. Python 3.8 ou version ultérieure.
2. Bibliothèques nécessaires listées dans `requirements.txt`.

## **Installation**
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Hadj-messaoud-Mohamed-tahar/Analyse-des-avis-IMDB-avec-BERT.git
