# Analyse-Netflix
# 🎬 Netflix Data Analysis Project

## 📌 Description du projet
Ce projet consiste en une analyse exploratoire (EDA) du dataset **Netflix Titles**.  
L’objectif est de comprendre la répartition du catalogue Netflix, son évolution dans le temps, les types de contenus proposés ainsi que les tendances par pays et par genre.

---

## 🧰 Technologies utilisées
- Python 🐍
- Pandas (manipulation des données)
- Matplotlib (visualisation)
- Seaborn (visualisation avancée)

---

## 📂 Dataset
Le dataset utilisé contient des informations sur les films et séries disponibles sur Netflix :
- Type (Movie / TV Show)
- Titre
- Pays
- Date d’ajout sur Netflix
- Année de sortie
- Durée
- Genre
- Description

---

## 🧹 Préparation et nettoyage des données
Les étapes réalisées :
- Suppression des valeurs manquantes (country, date_added)
- Conversion de `date_added` en format date
- Extraction de l’année d’ajout (`year_added`)
- Extraction de la durée numérique (`duration_value`)
- Normalisation des pays (`main_country`)
<img width="1355" height="616" alt="image" src="https://github.com/user-attachments/assets/876e5d63-5e1e-4744-bc53-45e2b31f8925" />

---

## 📊 Analyses et visualisations réalisées

### 1. 📈 Évolution des contenus ajoutés sur Netflix
- Graphique en ligne (line plot)
- Montre le nombre de films et séries ajoutés par année
- Permet de visualiser la croissance de Netflix dans le temps

---

### 2. 🌍 Top 10 des pays producteurs de contenu
- Graphique en bar chart
- Identifie les pays les plus présents sur la plateforme
- Met en évidence la domination de certains marchés

---

### 3. 🎭 Répartition des types de contenus
- Diagramme en camembert (pie chart)
- Compare :
  - Films (Movies)
  - Séries (TV Shows)

📌 Résultat : les films représentent la majorité du catalogue

---

### 4. 🎬 Analyse des genres les plus populaires
- Bar chart des genres les plus fréquents
- Extraction via `listed_in`
- Permet d’identifier les catégories dominantes (Drame, Comédie, etc.)

---

### 5. ⏱️ Analyse des durées
- Films : durée en minutes
- Séries : nombre de saisons
- Calcul des moyennes et médianes

---

### 6. 📊 Dashboard global
Un dashboard combinant plusieurs visualisations :
- Évolution des ajouts par année
- Répartition Movies / TV Shows
- Top pays
- Top genres

---

## 💡 Insights clés
- Netflix a connu une forte accélération des ajouts entre 2016 et 2020
- Les films dominent largement le catalogue
- Quelques pays concentrent une grande partie de la production
- Les genres Drame et Comédie sont les plus présents

---

## 🚀 Objectif du projet
Ce projet permet de :
- Pratiquer le nettoyage de données réelles
- Réaliser des visualisations professionnelles
- Construire un dashboard analytique
- Préparer un projet portfolio pour GitHub / LinkedIn

---

## 📁 Structure du projet
