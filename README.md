# Processus de Classification de Texte Multi-Classe avec PySpark

Ce projet implémente le processus de classification de texte multi-classe en utilisant PySpark. Le processus suit les étapes génériques de classification de texte et met en œuvre diverses techniques pour le prétraitement des données, l'extraction de caractéristiques, la création du modèle de régression logistique, et l'évaluation du modèle.

## 1. Prétraitement des Données

Le prétraitement des données est une étape cruciale dans laquelle la tokenisation est effectuée pour transformer le texte brut en une séquence de "tokens" ou de "jetons". Cela nettoie les données en supprimant les caractères spéciaux, les stop-words et les mots peu fréquents.

## 2. Extraction de Caractéristiques

Après la tokenisation, chaque token est représenté par un vecteur de nombres à l'aide de CountVectorizer. L'importance des mots est évaluée en utilisant la méthode TF-IDF (Term Frequency-Inverse Document Frequency).

## 3. Création du Modèle : Régression Logistique

La régression logistique, basée sur le principe "one versus all," est utilisée pour la classification multi-classe. Ce modèle découpe le problème de classification multi-classe en plusieurs problèmes de classification binaire.

## 4. Évaluation du Modèle

L'évaluation du modèle comprend l'utilisation de la matrice de confusion, de la précision (accuracy), de la précision positive (precision), du F1 Score, etc.

