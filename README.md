📊 Sales & Risk Analytics Dashboard
🚀 À propos du projet
Ce projet de Business Intelligence consiste en la conception et le développement d'un tableau de bord analytique complet sous Power BI. L'objectif est de transformer un flux de données brutes des ventes en un outil d'aide à la décision stratégique, permettant de piloter la performance commerciale et d'analyser les risques opérationnels liés aux commandes annulées.

🛠️ Stack Technique & Outils
Outil principal : Power BI Desktop, Power BI Service

ETL & Préparation : Power Query (M)

Modélisation : Modèle en étoile (Star Schema)

Langage de calcul : DAX (Data Analysis Expressions)

Gouvernance & Sécurité : RLS (Row-Level Security), Bookmarks, Tooltips dynamiques

📈 Fonctionnalités Clés & Architecture
Pipeline ETL & Modélisation :

Nettoyage des données, gestion des types et normalisation de la table brute en tables de dimensions (Clients, Produits, Régions) et de faits (Ventes).

Mesures DAX Avancées :

Calculs dynamiques pour le suivi du Chiffre d'Affaires, du Panier Moyen, du Taux d'Annulation et de la ventilation par région/produit.

Analyse des Risques (Commandes Annulées) :

Second onglet dédié à l'identification des frictions opérationnelles (analyse temporelle par ruban, ventilation des pertes par catégorie de produits).

Expérience Utilisateur & Sécurité :

Menu de navigation par icônes, info-bulles contextuelles (tooltips), signets de filtrage rapide, version mobile optimisée et mise en place de la sécurité par rôles (RLS).

📂 Structure du Rapport
Onglet 1 : Suivi des Ventes (KPIs globaux, évolution temporelle CA/volumes, répartition par région et catégorie, tableau détaillé).

Onglet 2 : Commandes Annulées (KPIs d'annulation, courbe d'évolution, histogramme régional, treemap par catégorie).
