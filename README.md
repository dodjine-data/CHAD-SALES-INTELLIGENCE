📊 CHAD SALES INTELLIGENCE

Analyse des ventes, de la rentabilité et des créances d'une PME tchadienne

CHAD SALES INTELLIGENCE est un projet de Business Intelligence
réalisé avec Microsoft Power BI autour d'une PME tchadienne fictive
: TCHAD DISTRIBUTION SARL.

L'objectif du projet est de transformer des données commerciales en
informations utiles à la prise de décision à travers l'analyse des
ventes, de la rentabilité, des clients, des créances, des produits, des
villes et des commerciaux.

⚠️ Important : les données utilisées dans ce projet sont simulées
à des fins pédagogiques et de portfolio. Elles ne représentent pas les
données réelles d'une entreprise.

🎯 Objectif du projet

L'objectif de CHAD SALES INTELLIGENCE est de construire un tableau
de bord permettant de :

suivre le chiffre d'affaires ;

analyser la rentabilité et les marges ;

suivre les ventes et les quantités vendues ;

analyser les performances commerciales ;

identifier les clients et les créances ;

analyser les modes de paiement ;

comparer les performances par ville ;

identifier les produits et catégories les plus performants ;

fournir des informations utiles à la prise de décision.

🏢 Contexte

TCHAD DISTRIBUTION SARL est une PME fictive spécialisée dans la
distribution de produits alimentaires et de grande consommation dans
plusieurs villes du Tchad.

Le projet reproduit une situation proche d'un besoin réel d'entreprise :
transformer des données opérationnelles en informations permettant de
mieux comprendre l'activité commerciale.

📂 Données utilisées

Le projet repose sur une architecture en étoile composée d'une table de
faits et de plusieurs tables de dimensions.

Table de faits

Fact_Ventes

Elle contient les transactions commerciales :

Vente_ID

Date_ID

Date

Client_ID

Produit_ID

Commercial_ID

Ville_ID

Quantite

Prix_Unitaire

Montant_Vente

Cout_Total

Benefice

Montant_Paye

Creance

Mode_Paiement

Tables de dimensions

Dim_Client --- informations sur les clients

Dim_Produit --- produits et catégories

Dim_Commercial --- commerciaux

Dim_Ville --- villes, provinces et zones

Dim_Date --- calendrier et informations temporelles

🧩 Modèle de données

Le modèle de données utilise une architecture en étoile (Star
Schema).

La table Fact_Ventes se trouve au centre et est reliée aux
différentes tables de dimensions :

Dim_Client

Dim_Produit

Dim_Commercial

Dim_Ville

Dim_Date

Cette modélisation permet de faciliter l'analyse et la création des
mesures DAX dans Power BI.

🛠️ Technologies utilisées

Microsoft Power BI

Power Query

DAX

Microsoft Excel

CSV

Data Visualization

Business Intelligence

Data Analytics

🔄 Préparation et transformation des données

Les principales étapes réalisées sont :

Importation des fichiers CSV dans Power BI.

Vérification des colonnes et des en-têtes.

Correction des types de données.

Conversion des données numériques.

Gestion des formats décimaux.

Vérification des valeurs manquantes.

Création des relations entre les tables.

Mise en place du modèle en étoile.

Création des mesures DAX.

Création des visualisations et du dashboard.

📈 KPI principaux

KPI                             Valeur

Chiffre d'affaires     58 171 661 FCFA
Bénéfice               14 928 785 FCFA
Créances                6 970 781 FCFA
Quantité vendue          11 750 unités
Nombre de clients                   20
Marge globale                ≈ 25,66 %
Ventes à crédit                39,20 %

📊 Dashboard Power BI

Le dashboard est organisé en quatre pages principales.

1. Executive Overview

Vue globale de l'activité commerciale avec les principaux KPI,
l'évolution du chiffre d'affaires, les performances par ville, les
produits et les catégories.



2. Analyse commerciale

Analyse des performances des commerciaux, du chiffre d'affaires par
ville, des quantités vendues par produit et de la répartition du chiffre
d'affaires par catégorie.



3. Clients & Créances

Suivi des créances clients, des paiements, des ventes à crédit et de la
répartition des créances par client, ville et commercial.



4. Analyse de la rentabilité

Analyse du chiffre d'affaires, des coûts, du bénéfice et des marges par
produit, catégorie, ville et commercial.



📊 Principales visualisations

Le dashboard comprend notamment :

évolution mensuelle du chiffre d'affaires ;

chiffre d'affaires par ville ;

Top 5 des produits par chiffre d'affaires ;

chiffre d'affaires par catégorie ;

chiffre d'affaires par commercial ;

marge par commercial ;

quantité vendue par produit ;

évolution mensuelle du bénéfice ;

créances par client ;

créances par ville ;

créances par commercial ;

évolution mensuelle des créances ;

répartition du chiffre d'affaires par mode de paiement ;

bénéfice par produit ;

marge par catégorie ;

bénéfice par ville ;

marge par commercial.

🔎 Principaux insights

L'analyse du jeu de données simulé fait ressortir notamment :

N'Djamena représente environ 28,82 % du chiffre d'affaires
total.

Sucre 25 kg est le produit ayant le chiffre d'affaires le plus
élevé.

Sucre 25 kg arrive également en tête pour le bénéfice.

La catégorie Hygiène présente la marge la plus élevée.

N'Djamena concentre le niveau de créances le plus élevé parmi
les villes.

Supermarché Chari présente le niveau de créances le plus élevé
parmi les clients.

Ali Hassan présente la marge la plus élevée parmi les
commerciaux.

Ces résultats sont issus d'un jeu de données simulé et servent
uniquement à démontrer les capacités d'analyse du projet.

💡 Recommandations issues de l'analyse

À partir des résultats obtenus, plusieurs pistes d'action peuvent être
envisagées :

renforcer le suivi des clients présentant des créances importantes ;

analyser les pratiques commerciales associées aux meilleures marges
;

surveiller les produits à forte contribution ;

comparer régulièrement les performances par ville ;

suivre l'évolution des ventes à crédit ;

intégrer un suivi régulier des coûts et des marges.

🧠 Compétences démontrées

Analyse de données

Business Intelligence

Power BI

Power Query

DAX

Data Cleaning

Data Modeling

Star Schema

Data Visualization

Analyse commerciale

Analyse de rentabilité

Analyse des créances

Storytelling avec les données

📋 Méthodologie

Collecte → Nettoyage → Transformation → Modélisation → Analyse →
Visualisation → Interprétation → Recommandations

⚠️ Limites du projet

Les données sont entièrement simulées.

Elles ne proviennent pas d'une entreprise réelle.

Les résultats sont destinés à un usage pédagogique et de portfolio.

Les recommandations devraient être approfondies avec des données
réelles et davantage de contexte métier.

📁 Structure du projet

CHAD-SALES-INTELLIGENCE/ ├── README.md ├── PowerBI/ │ └──
CHAD_SALES_INTELLIGENCE.pbix ├── Data/ │ ├── Fact_Ventes.csv │ ├──
Dim_Client.csv │ ├── Dim_Produit.csv │ ├── Dim_Commercial.csv │ ├──
Dim_Ville.csv │ └── Dim_Date.csv └── Screenshots/ ├──
executive_overview.png ├── analyse_commerciale.png ├──
clients_creances.png └── rentabilite.png

🚀 Valeur du projet

CHAD SALES INTELLIGENCE constitue un projet de portfolio permettant
de démontrer la capacité à transformer des données commerciales brutes
en informations exploitables à travers un processus complet d'analyse de
données et de Business Intelligence.

Le projet met particulièrement en avant la capacité à construire un
modèle de données, créer des mesures DAX, concevoir un dashboard Power
BI et traduire les résultats en insights métier.

👤 Auteur

Dodjine Henock

Data Analyst Junior | Économie | Business Intelligence

Compétences principales

Excel • SQL • Python • Power BI • DAX • Analyse de données • Économie •
Business Intelligence

⭐ Projet réalisé à des fins pédagogiques et de portfolio.
