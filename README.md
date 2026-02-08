# Analyse de la santé mentale étudiante — Projet d'exploration de données (In French)

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

---

# Student Mental Health Analysis — Exploratory Data Project (English)

## Introduction

This project explores self-reported data on student mental health. The goal is to identify observable patterns and correlations (not diagnoses) and to propose data-driven recommendations for institutions and student support teams. The project also serves as a technical exercise to improve data skills.

## Why this is useful

- Understand the distribution of issues (stress, anxiety, depression) within student samples.
- Highlight potential correlations (e.g., sleep and anxiety) to inform preventive actions.
- Demonstrate skills in data cleaning, EDA, visualization, and simple analyses (clustering, correlations).

## Data source

- File: `data/raw/Student Mental health.csv` (original dataset available on [Kaggle](https://www.kaggle.com/datasets/aminasalamat/mental-health-of-students-dataset?resource=download)).
- Type: CSV.

## Dataset content

- Key variables: indicators of anxiety/depression/stress, sleep habits, workload, gender, age, student status.
- Types: mixture of categorical variables, Likert scales, and numeric fields.

## Summary of analyses (expected insights)

- Notable correlation between sleep deprivation and anxiety levels (correlation, not causation).
- High academic workload correlates with higher stress scores.
- Student profiles identified via clustering: (1) high stress / low support, (2) moderate stress / good sleep, (3) low stress / sufficient support.
- Identified biases: self-reporting, non-representative sample, cultural biases.

## Potential factors (cautious wording)

Potential factors identified through correlation include academic overload, lack of psychological support, social isolation and financial pressure. These hypotheses require further professional and clinical study before any causal claim.

## Data-driven recommendations

- Strengthen and promote anonymous student support services.
- Implement sleep-hygiene awareness programmes and practical workshops.
- Establish regular anonymous statistical monitoring at the institutional level to detect trends.
- Develop simple indicators (e.g., frequent insufficient sleep) to trigger early alerts.

## How to use this repository

1. Install dependencies listed in `requirements.txt`.
2. Open `notebook.ipynb` and execute the cells in order.
3. The notebook loads `data/raw/Student Mental health.csv` and produces the visualizations and analyses described.

## Demonstrated skills

- Data cleaning and preprocessing
- Exploratory data analysis (EDA) and visualization
- Descriptive statistics and correlation analysis (Spearman)
- Clustering and profile detection
- Clear communication of limitations and biases