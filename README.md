
# Telecom Customer Churn Prediction

Prédiction du départ des clients (Churn) dans le secteur des télécommunications à l’aide du Machine Learning.

---

## Objectif du projet

L’objectif est d’identifier **les clients susceptibles de quitter l’entreprise** afin d’aider les équipes métier à mettre en place des actions de rétention ciblées.

Ce projet couvre **tout le pipeline Data Science** :  
De l’analyse exploratoire des données (EDA) jusqu’à la construction et l’évaluation d’un modèle prédictif prêt à être déployé.

---

## Dataset

- **7043 clients**
- **20 variables explicatives**
- Variables numériques et catégorielles (contrat, services, facturation, ancienneté, etc.)
- Variable cible : **Churn (Yes / No)**

---

## Étapes réalisées

###  Analyse Exploratoire (EDA)

- Analyse de la distribution des variables
- Étude du lien entre chaque feature et le churn
- Visualisations : boxplots, countplots, heatmap de corrélation
- Détection des outliers sur les variables numériques
- Analyse du déséquilibre de la target

###  Data Preprocessing

- Encodage des variables catégorielles
- Normalisation des variables numériques
- Feature Engineering basé sur l’analyse métier
- Séparation Train / Test
- Gestion du déséquilibre des classes

###  Modélisation

- Modèle utilisé : **Régression Logistique**
- Entraînement sur les données d’entraînement
- Prédiction sur le jeu de test

###  Évaluation du modèle

| Métrique | Score |
|----------|-------|
| Accuracy | **83.82 %** |
| Precision | **83.87 %** |
| Recall | **84.27 %** |
| F1-Score | **84.07 %** |
| AUC | **0.9209** |

L’AUC très élevée montre une excellente capacité du modèle à distinguer les clients churn / non churn.

---

## Variables les plus influentes sur le churn

Les facteurs principaux identifiés :

- Type de contrat (Month-to-month)
- Ancienneté du client (tenure)
- Montant mensuel (MonthlyCharges)
- Services souscrits (Internet, TechSupport, OnlineSecurity)
- Mode de paiement

---

## Technologies utilisées

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Utilisation du modèle (Prédiction)

Le modèle peut être utilisé pour prédire le churn sur **de nouvelles données clients** en respectant :

- Les mêmes colonnes que le dataset d’entraînement
- Le même encodage
- Le même pipeline de preprocessing

---

## Structure du projet


---

## Compétences démontrées

- Analyse de données réelles
- Feature Engineering
- Machine Learning appliqué
- Évaluation avancée de modèles
- Préparation d’un modèle pour déploiement (API FastAPI)

---

## Auteur

**Ayoub Berhili**  
Master Cybersécurité & Science des Données — Université Paris 8  
Futur Data Analyst / Data Scientist
