# Analyse-Netflix
# Netflix Data Analysis Project

## Description du projet
Ce projet consiste en une analyse exploratoire (EDA) du dataset **Netflix Titles**.  
L’objectif est de comprendre la répartition du catalogue Netflix, son évolution dans le temps, les types de contenus proposés ainsi que les tendances par pays et par genre.

---

## Technologies utilisées
- Python 
- Pandas (manipulation des données)
- Matplotlib (visualisation)
- Seaborn (visualisation avancée)

---

## Dataset
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

## Préparation et nettoyage des données
Les étapes réalisées :
- Suppression des valeurs manquantes (country, date_added)
- Conversion de `date_added` en format date
- Extraction de l’année d’ajout (`year_added`)
- Extraction de la durée numérique (`duration_value`)
- Normalisation des pays (`main_country`)
<img width="1355" height="616" alt="image" src="https://github.com/user-attachments/assets/876e5d63-5e1e-4744-bc53-45e2b31f8925" />

---

## Analyses et visualisations réalisées

### 1. 📈 Évolution des contenus ajoutés sur Netflix
- Graphique en ligne (line plot)
- Montre le nombre de films et séries ajoutés par année
- Permet de visualiser la croissance de Netflix dans le temps
<img width="1373" height="556" alt="image" src="https://github.com/user-attachments/assets/dfa3935f-60b0-421a-a9af-2444adb91d81" />

---

### 2. Top 10 des pays producteurs de contenu
- Graphique en bar chart
- Identifie les pays les plus présents sur la plateforme
- Met en évidence la domination de certains marchés
<img width="1294" height="722" alt="image" src="https://github.com/user-attachments/assets/612c0a9f-141c-46bd-8e84-4c64589b2fb0" />

---

### 3. Répartition des types de contenus
- Diagramme en camembert (pie chart)
- Compare :
  - Films (Movies)
  - Séries (TV Shows)
<img width="746" height="665" alt="image" src="https://github.com/user-attachments/assets/6cfc524f-e410-4c7e-8c7d-e2e309224c26" />

-> Résultat : les films représentent la majorité du catalogue

---

### 4. Analyse des genres les plus populaires
- Bar chart des genres les plus fréquents
- Extraction via `listed_in`
- Permet d’identifier les catégories dominantes (Drame, Comédie, etc.)
<img width="1164" height="757" alt="image" src="https://github.com/user-attachments/assets/bc8afeda-6201-4bfa-9009-8ad591cb9715" />

---

### 5. Analyse des durées
- Films : durée en minutes
- Séries : nombre de saisons
- Calcul des moyennes et médianes
<img width="1153" height="538" alt="image" src="https://github.com/user-attachments/assets/31fbf447-436e-42e0-9a28-7f292febf0d3" />

---

### 6. Dashboard global
Un dashboard combinant plusieurs visualisations :
- Évolution des ajouts par année
- Répartition Movies / TV Shows
- Top pays
- Top genres
<img width="1110" height="764" alt="image" src="https://github.com/user-attachments/assets/b4edd6d1-bfbd-4b3b-a3e5-f1a277dda922" />

---

## Insights clés
- Netflix a connu une forte accélération des ajouts entre 2016 et 2020
- Les films dominent largement le catalogue
- Quelques pays concentrent une grande partie de la production
- Les genres Drame et Comédie sont les plus présents
<img width="417" height="354" alt="image" src="https://github.com/user-attachments/assets/d6cd574b-6434-4631-8523-1276d8ca56af" />

---

## Objectif du projet
Ce projet permet de :
- Pratiquer le nettoyage de données réelles
- Réaliser des visualisations professionnelles
- Construire un dashboard analytique
- Préparer un projet portfolio pour GitHub / LinkedIn

