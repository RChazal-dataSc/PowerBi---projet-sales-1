📊 Power BI – Dashboard de Suivi des Ventes

Projet complet : Data cleaning, modélisation, DAX, data visualisation et publication.

🚀 Présentation

Ce projet Power BI propose un tableau de bord interactif basé sur un fichier de ventes (sales_2.csv).
L’objectif : construire un rapport professionnel en passant par toutes les étapes clés — préparation, modélisation, visualisation, navigation et sécurité.

🧹 1. Préparation des données

Analyse de la qualité des données (qualité / distribution / profil).

Correction des types et nettoyage : suppression de 2 lignes contenant des valeurs manquantes.

Vérification d'absence d’outliers via histogrammes.

Renommage complet des colonnes pour plus de clarté.

🗂️ 2. Modèle de données (Architecture en étoile)

Normalisation de la table brute en créant :

Clients, Produits, Régions (tables de dimensions).

Ventes (table de faits).

Suppression des redondances, tri des identifiants, vérifications d’intégrité.

Création et ajustement manuel des relations dans Power BI.

📐 3. Mesures & DAX

Création d’une table dédiée aux mesures, incluant notamment :

Total ventes

Nombre de commandes

Quantité vendue

Commande moyenne
Mais aussi des mesures spécifiques pour l’analyse des commandes annulées.

🎨 4. Personnalisation & Data Viz

Import d’un thème JSON personnalisé (ex : Loomy Lime).

Mise en page complète : couleurs, briques, structure (2000px).

Création de visuels variés :

KPI

Courbes & Aires

Barres horizontales

Donut

Treemap

Ruban

Tableaux détaillés

🔍 5. Filtres, Segments & Navigation

Filtres : date, région, statut commande.

Menu de navigation personnalisé (icônes + actions).

Info-bulles avancées via pages dédiées.

Signets pour filtrage rapide (mobiles, bureautique, reset).

🛡️ 6. Sécurité & Version mobile

Row-Level Security (RLS) :

Rôle 1 : AI Systems / TechCorp

Rôle 2 : Région South

Version mobile optimisée du tableau de bord.

☁️ 7. Publication

Publication finale du rapport sur Power BI Service.

📁 Contenu du dépôt

dashboard.pbix – rapport Power BI complet

sales_2.csv – dataset source

README (présent document)

💡 Objectifs pédagogiques

Appliquer un processus analytique complet.

Construire un modèle étoile propre et optimisé.

Utiliser DAX pour créer des indicateurs métier.

Concevoir un dashboard professionnel, interactif et sécurisé.
