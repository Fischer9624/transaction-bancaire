📊 Projet d’Analyse Descriptive – Banque de détail

📌 Contexte
Ce projet vise à analyser un dataset de transactions bancaires (2024, 3000 lignes, 200 clients) afin d’extraire des indicateurs clés (KPI) et de fournir des insights métiers utiles pour la gestion des clients et la prévention des risques.

🎯 Objectifs
Compréhension du dataset : identifier les variables clés (montant, type, canal, ville, solde).

Nettoyage et préparation : suppression des colonnes inutiles, gestion des valeurs manquantes.

Analyse descriptive : répondre aux questions métiers par des KPI et des visualisations.

Segmentation clients : classification en Normal, Fragile, À risque, Critique.

Règles métiers : détection des découverts, dépenses excessives, incohérences, saisonnalité.

🛠️ Technologies utilisées
Python 3.x

pandas : manipulation et agrégation des données

matplotlib / seaborn : visualisations statiques

plotly : visualisations interactives

Jupyter Notebook : exploration et documentation

📊 Analyses réalisées
Catégories de dépenses dominantes

Clients à risque de découvert

Saisonnalité des dépenses

Panier moyen Débit vs Crédit

Canaux de paiement utilisés

Répartition par ville

Segmentation clients

🚀 Résultats clés
Les dépenses quotidiennes dominent en volume, les revenus en montant.

Décembre et août sont des pics saisonniers.

Carte bancaire et mobile sont les canaux dominants.

Les clients sont segmentés en 4 profils : Normal, Fragile, À risque, Critique.

Mise en place de règles métiers pour détecter les anomalies et anticiper les risques.

📌 Recommandations pour la banque
Prévention : alertes automatiques pour les découverts.

Offres ciblées : micro-crédit pour fragiles, consolidation pour critiques.

Optimisation : investir dans mobile et carte bancaire.

Anticipation : préparer les campagnes marketing en décembre et août.

📂 Organisation du projet
Code
├── data/                # Dataset brut et nettoyé
├── notebooks/           # Jupyter Notebooks d’analyse
├── scripts/             # Scripts Python (KPI, règles métiers)
├── visuals/             # Graphiques matplotlib/plotly
└── README.md            # Documentation du projet