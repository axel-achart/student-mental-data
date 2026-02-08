# Analyse de la santé mentale étudiante — Projet d'exploration de données

## Introduction

Ce projet explore des données auto-déclarées (self-report) portant sur la santé mentale des étudiants. L'objectif est d'identifier des motifs et des corrélations observables, afin de proposer des pistes d'action basées sur la data pour les établissements et les équipes support.
Vous l'avez bien compris, ce projet a pour but de m'entraîner et à perfectionner mes compétences techniques.

## Pourquoi c'est utile

- Comprendre la répartition des enjeux (stress, anxiété, dépression) au sein d'échantillons d'étudiants.
- Mettre en lumière des corrélations potentielles (par ex : sommeil et anxiété) pour orienter des actions de prévention.
- Montrer des compétences en data cleaning, EDA, visualisation et analyses simples (clustering, corrélations).
## Source des données

- Fichier : `data/raw/Student Mental health.csv` ([disponible sur Kaggle](https://www.kaggle.com/datasets/aminasalamat/mental-health-of-students-dataset?resource=download)).
- Type : CSV.
## Contenu du dataset

- Variables clés : indicateurs d'anxiété/dépression/stress, habitudes de sommeil, charge de travail, genre, âge, statut étudiant.
- Types : mix de variables catégorielles, Likert, et numériques.
## Résumé des analyses (insights attendus)

- X% des étudiants déclarent des niveaux élevés de stress.
- Corrélation notable entre privation de sommeil et niveaux d'anxiété (corrélation, non causalité).
- Charge académique élevée corrélée avec des scores de stress plus élevés.
- Profils étudiants identifiés via clustering : (1) stress élevé / faible soutien, (2) stress modéré / bon sommeil, (3) faible stress / soutiens présents.
- Biais identifiés : auto-déclaration, échantillon non représentatif, biais culturels.
## Causes potentielles (formulation prudente)

Les facteurs potentiels identifiés par corrélation comprennent : surcharge académique, manque de soutien psychologique, isolement social et pression financière. Ces pistes sont hypothétiques et requièrent des études complémentaires (professionnelles) pour toute interprétation clinique.

## Pistes d'action basées sur la data

- Renforcement des services de soutien étudiant et communication anonyme.
- Programmes de sensibilisation à l'hygiène du sommeil et ateliers pratiques.
- Mise en place d'un suivi statistique anonyme régulier dans les universités pour détecter des tendances.
- Développement d'indicateurs simples (ex : fréquence de sommeil insuffisant) pour des alertes précoces.
## Utilisation du repository

1. Installer les dépendances listées dans `requirements.txt`.
2. Ouvrir `notebook.ipynb` et exécuter les cellules dans l'ordre.
3. Le notebook charge `data/raw/Student Mental health.csv` et produit des visualisations et analyses décrites.
## Compétences démontrées

- Nettoyage et prétraitement de données
- Analyse exploratoire (EDA) et visualisation
- Analyse statistique descriptive et corrélations (Spearman)
- Clustering et détection de profils
- Communication claire des limites et biais