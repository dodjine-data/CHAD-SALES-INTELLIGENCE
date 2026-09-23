# 📊 CHAD SALES INTELLIGENCE

## Analyse des ventes, de la rentabilité et des créances d'une PME tchadienne

**CHAD SALES INTELLIGENCE** est un projet de Business Intelligence réalisé avec **Microsoft Power BI** autour d'une PME tchadienne fictive : **TCHAD DISTRIBUTION SARL**.

L'objectif du projet est de transformer des données commerciales en informations utiles à la prise de décision à travers l'analyse des ventes, de la rentabilité, des clients, des créances, des produits, des villes et des commerciaux.

> ⚠️ **Important :** les données utilisées dans ce projet sont simulées à des fins pédagogiques et de portfolio. Elles ne représentent pas les données réelles d'une entreprise.

---

## 🎯 Objectifs du projet

Ce projet vise à :

- analyser le chiffre d'affaires ;
- mesurer la rentabilité et les marges ;
- suivre les créances clients ;
- analyser les ventes par ville ;
- comparer la performance des commerciaux ;
- identifier les produits et catégories les plus performants ;
- analyser les modes de paiement ;
- suivre l'évolution mensuelle des principaux indicateurs ;
- construire un dashboard Power BI interactif ;
- transformer les données commerciales en informations utiles à la décision.

---

## 🏢 Contexte

**Entreprise :** TCHAD DISTRIBUTION SARL  
**Secteur :** Distribution de produits alimentaires et ménagers  
**Pays :** Tchad  
**Période analysée :** 2025

Le dataset simulé représente des transactions commerciales réalisées dans plusieurs villes tchadiennes.

L'entreprise fictive vend différents produits alimentaires et ménagers à plusieurs types de clients, avec plusieurs commerciaux et différents modes de paiement.

---

## 🗂️ Données utilisées

Le modèle de données est composé de **6 tables**.

### Table de faits

#### `Fact_Ventes`

Cette table contient les transactions commerciales :

- Vente_ID
- Date_ID
- Date
- Client_ID
- Produit_ID
- Commercial_ID
- Ville_ID
- Quantite
- Prix_Unitaire
- Montant_Vente
- Cout_Total
- Benefice
- Montant_Paye
- Creance
- Mode_Paiement

### Tables de dimensions

#### `Dim_Date`

- Date_ID
- Date
- Annee
- Mois_Numero
- Mois
- Trimestre
- Jour
- Jour_Semaine

#### `Dim_Client`

- Client_ID
- Client
- Ville_ID
- Type_Client

#### `Dim_Produit`

- Produit_ID
- Produit
- Categorie
- Prix_Unitaire
- Cout_Unitaire

#### `Dim_Commercial`

- Commercial_ID
- Commercial
- Ville_Principale

#### `Dim_Ville`

- Ville_ID
- Ville
- Province
- Zone

---

## ⭐ Modèle de données

Le projet utilise une architecture en étoile (**Star Schema**).

`Fact_Ventes` constitue la table centrale et les différentes tables de dimensions permettent d'analyser les transactions selon plusieurs axes.

```text
                         Dim_Date
                            │
                            │
Dim_Client ─────────── Fact_Ventes ─────────── Dim_Produit
                            │
                            │
                    Dim_Commercial
                            │
                            │
                        Dim_Ville


### 4. Analyse de la rentabilité

Analyse du chiffre d'affaires, des coûts, du bénéfice et des marges par produit, catégorie, ville et commercial.

![Rentabilité](./Screenshots/rentabilite.png)
