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

![Dashboard Filtered by Midfield](/images/Dashboard_Midfielder.png)

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

## 🎯 Objectif du Projet
Ce projet vise à mettre en pratique l'ensemble du processus de Business Intelligence avec Power BI, du nettoyage des données à la visualisation. L'objectif était de répondre à des questions clés telles que la répartition de la valeur marchande par club, nation et poste.

## 🛠️ Compétences Mises en Œuvre

1.  **Collecte et Nettoyage (Power Query) :**
    *   Importation et nettoyage du jeu de données (Kaggle).
    *   Gestion des valeurs nulles et typage des données.
    *   Création de colonnes calculées (âge, catégories).

2.  **Modélisation et DAX :**
    *   Création de mesures DAX optimisées pour les calculs clés.

3.  **Visualisation :**
    *   Conception d'un rapport dynamique avec filtres interactifs.

*(Les captures d'écran ci-dessus illustrent le fonctionnement des filtres dynamiques sur les positions et les nationalités).*

