# Car Price Prediction
Ce projet consiste à prédire le prix des voitures en utilisant un modèle d'apprentissage automatique basé sur un Decision Tree Regressor. Les données utilisées proviennent du fichier avito_car_dataset_ALL.csv, qui contient des informations détaillées sur les voitures, telles que leur marque, modèle, kilométrage, type de carburant, boîte de vitesses, et bien plus.
## Objectifs
Préparer les données de manière à les rendre adaptées au modèle de régression.
Utiliser un modèle de régression pour prédire les prix des voitures.
Évaluer les performances du modèle avec des métriques standard.
## Données

Fichier source : avito_car_dataset_ALL.csv.
Le dataset contient des colonnes comme :
   Marque
   Modèle
   Kilométrage
   Type de carburant
   Boîte de vitesses
   Prix (cible à prédire)
## Prétraitement des Données
Les étapes suivantes ont été réalisées pour préparer les données :

1-Conversion des colonnes non numériques en type catégoriel.
2-Suppression des colonnes non pertinentes comme Lien.
3-Imputation des valeurs manquantes :
  Médiane pour les colonnes numériques.
  Mode pour les colonnes catégorielles.
4-Encodage One-Hot pour les colonnes catégorielles (Ville, Origine, etc.).
5-Fusion des colonnes Marque et Modèle en une seule : Marque_Modele.
6-Séparation des données en features et target (Prix).
## Modèle
Algorithme utilisé : Decision Tree Regressor.
Bibliothèque : scikit-learn.

## Dépendances
Pour exécuter ce projet, vous aurez besoin des bibliothèques suivantes :

### pandas
### numpy
### scikit-learn
Installez les dépendances avec la commande suivante :

    pip install pandas numpy scikit-learn
