# 📊 Dashboard de Performance Commerciale - Global Superstore

## 📝 Description du Projet
Ce projet consiste en une analyse approfondie des performances de vente mondiales pour une entreprise de grande distribution. L'objectif est de transformer des données brutes en un outil d'aide à la décision interactif permettant d'identifier les leviers de croissance et les points de perte de rentabilité.

## 🚀 Fonctionnalités Clés
* **Analyse de la Rentabilité** : Visualisation dynamique des marges via des indicateurs couleurs (Vert/Rouge) pour un diagnostic immédiat.
* **Analyse Géographique** : Cartographie mondiale des ventes avec bulles de profitabilité par pays.
* **Suivi Temporel** : Graphique de tendances comparant le CA et le Profit (2011-2014) pour détecter la saisonnalité.
* **Interactivité Avancée** : Filtres (Slicers) par **Région**, **Année** et **Segment de clientèle** (Consumer, Corporate, Home Office).

## 💡 Storytelling & Aide à la Décision

### 1. Le Constat (Le "Quoi")
Bien que le Chiffre d'Affaires global soit en forte croissance, la **rentabilité ne suit pas la même courbe**. L'analyse montre que l'augmentation du volume de ventes ne garantit pas automatiquement une hausse des profits.

### 2. Les Insights Business (Le "Pourquoi")
* **Le Tueur de Marge :** La catégorie **Furniture** (Ameublement) génère un volume de ventes important mais un profit dérisoire, voire négatif dans certaines zones. Cela suggère des coûts logistiques ou des taux de retour trop élevés.
* **Le Moteur de Croissance :** La catégorie **Technology** est le segment le plus sain, affichant la marge bénéficiaire la plus élevée.
* **Alerte Géographique :** Certaines régions d'Amérique Latine et d'Afrique présentent des "bulles rouges", indiquant des ventes à perte qu'il faut auditer.

### 3. Recommandations Stratégiques (L'Aide à la Décision)
* **Optimisation Logistique :** Auditer la chaîne d'approvisionnement du segment "Furniture" pour réduire les coûts fixes.
* **Focus Marketing :** Réallouer le budget publicitaire vers les produits "Technology" et les segments "Office Supplies" à haute marge.
* **Politique de Prix :** Réviser les tarifs dans les zones géographiques déficitaires pour stabiliser la marge globale.

## 🛠️ Outils & Compétences Techniques
* **Power BI Desktop** : Conception des visuels et du dashboard.
* **Power Query (ETL)** : Nettoyage, transformation des données et gestion des formats de dates complexes.
* **DAX (Data Analysis Expressions)** : 
    * `CA Total = SUM(Sales)`
    * `Profit Total = SUM(Profit)`
    * `Marge % = DIVIDE([Profit Total], [CA Total])`

## 📁 Structure du Dépôt
* `Global_Superstore_Analysis.pbix` : Fichier source Power BI.
* `Global_Superstore2.csv` : Jeu de données source.
* `image_d077d7.png` : Capture d'écran du rapport final.
* `README.md` : Présentation et analyse du projet.

---
