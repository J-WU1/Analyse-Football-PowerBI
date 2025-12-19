# ⚽ Football Market Value Analysis (Power BI)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-Language-blue?style=for-the-badge) ![Power Query](https://img.shields.io/badge/Power_Query-Transformation-green?style=for-the-badge)

🇺🇸 **English Version**

## 📌 Project Overview
This interactive dashboard analyzes football player data from Transfermarkt to predict and visualize market values. This project demonstrates my ability to handle the **full Business Intelligence lifecycle**, from raw data ingestion to actionable insights using **Power BI**.

*(Note: This project was developed locally using Power BI Desktop. The screenshots below demonstrate the dashboard's features and insights.)*

---

## 📸 Main Dashboard View
![Main Dashboard Preview](/images/Dashboard_Football_Transfermarkt.png)

---

## 🎯 Objectives
The goal was to answer key business questions using data:
*   Which clubs and nations hold the highest total market value?
*   Who are the most valuable players on the market?
*   How is market value distributed across different positions and age groups?

## 🛠️ Technical Implementation

1.  **ETL & Data Cleaning (Power Query):**
    *   Ingested raw CSV data from Kaggle.
    *   Performed data transformation: handling null values, type casting, and column selection.
    *   Created calculated columns (e.g., dynamic Age calculation from birthdate).

2.  **Modeling & DAX:**
    *   Designed a Star Schema data model.
    *   Wrote complex **DAX measures** for key metrics (Total Market Value, Player Count, Average Value).

3.  **Visualization & Storytelling:**
    *   Designed a dynamic report using Treemaps, Bar Charts, and KPIs.
    *   Implemented **Slicers and Filters** for interactive exploration (by Club, Nationality, Position).

---

## ✨ Interactivity Examples

### 1. Focus on "Midfielders"
Here is the report filtered to show only players in the **"Midfield"** position. The KPIs and charts update dynamically.

![Dashboard Filtered by Midfield](/images/Dashboard_Millieux.png)

### 2. Focus on "France"
Here is the report filtered to show only players with **"France"** as their nationality.

![Dashboard Filtered by France](/images/Dashboard_France.png)

---

## 📂 Repository Contents
*   **`DataFootTransfertmarkt.pbix`**: The source Power BI file.
*   **`players.csv`**: Raw dataset used for analysis.
*   **`/images`**: Folder containing dashboard screenshots.

---
---

🇫🇷 **Version Française**

# Analyse de Joueurs de Football avec Power BI

Un dashboard interactif pour analyser les données de joueurs de football issues de Transfermarkt, développé dans le cadre de mon auto-formation sur Power BI.

*(Note : Ce projet a été développé en local avec Power BI Desktop. Les images ci-dessous présentent les fonctionnalités et les conclusions du dashboard.)*

---

## 📸 Aperçu du Dashboard Principal
![Aperçu du Dashboard Football](/images/Dashboard_Football_Transfermarkt.png)

---

## 🎯 Objectif du Projet

Ce projet vise à mettre en pratique l'ensemble du processus de Business Intelligence avec Power BI, du nettoyage des données à la visualisation. L'objectif était de répondre à des questions clés telles que :

*   Quels sont les clubs et les nations avec la plus grande valeur marchande ?
*   Qui sont les joueurs les plus chers du marché ?
*   Comment la valeur se répartit-elle selon les postes et l'âge des joueurs ?

---

## 🛠️ Étapes Réalisées et Compétences Mises en Œuvre

1.  **Collecte et Nettoyage des Données (Power Query) :**
    *   Importation du jeu de données CSV depuis Kaggle.
    *   Gestion des valeurs nulles, correction des types de données et sélection des colonnes pertinentes.
    *   Création de colonnes calculées (ex: calcul de l'âge à partir de la date de naissance).

2.  **Modélisation et DAX :**
    *   Création de mesures DAX claires et réutilisables pour les calculs clés (Valeur Marchande Totale, Nombre de Joueurs, etc.).

3.  **Visualisation et Storytelling :**
    *   Conception d'un rapport dynamique avec des histogrammes, des treemaps et des tableaux.
    *   Mise en place de filtres et de segments pour permettre une exploration interactive des données. **(Voir exemple ci-dessous)**

---

## ✨ Exemple d'interactivité : Focus sur les "Millieux de terrains"

Pour démontrer les capacités de filtrage du dashboard, voici une vue du rapport lorsqu'il est filtré pour n'afficher que les joueurs en position "Midfield".

![Dashboard filtré sur les millieux](/images/Dashboard_Millieux.png)

*(Cette image montre comment tous les visuels (Top Clubs, Nationalités, Tableau des joueurs) se mettent à jour dynamiquement pour ne refléter que les données relatives aux millieux de terrain.)*

---
✨ Autre Exemple d'interactivité : Focus sur les "Français"

Voici une vue du rapport lorsqu'il est filtré pour n'afficher que les joueurs qui ont pour nationalité "France".

![Dashboard filtré sur les français](/images/Dashboard_France.png)

*(Cette image montre comment tous les visuels (Top Clubs, Nationalités, Tableau des joueurs) se mettent à jour dynamiquement pour ne refléter que les données relatives aux millieux de terrain.)*

---

## 📂 Contenu du Dépôt

*   **`DataFootTransfertmarkt.pbix`** : Le fichier source du projet Power BI (nécessite Power BI Desktop pour être ouvert).
*   **`players.csv`** : Le jeu de données brut utilisé comme source pour l'analyse.
*   **`/images`** : Un dossier contenant les captures d'écran du dashboard.
*   **`README.md`** : Ce fichier de présentation.
