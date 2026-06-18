# 🗄️ Analyse de données avec SQL

## 🎯 Objectif

Concevoir une base de données relationnelle et exploiter SQL afin de répondre à des problématiques métier à travers des requêtes d'extraction, de filtrage et d'agrégation.

## 📌 Contexte

Projet réalisé dans le cadre de la formation **Data Analyst OpenClassrooms**.

L'objectif est de créer une base de données à partir de fichiers CSV, de modéliser les relations entre les différentes tables puis d'utiliser SQL pour produire des indicateurs exploitables.

## ❓ Problématique

Comment structurer une base de données relationnelle et utiliser SQL pour extraire efficacement des informations utiles à la prise de décision ?

## 🛠️ Méthodologie

### Création de la base de données

* Analyse des données sources
* Création des tables SQL
* Définition des clés primaires et étrangères
* Import des données CSV dans SQLite

### Modélisation

* Construction du schéma relationnel
* Mise en place des relations entre les tables `CONTRAT` et `REGION`
* Vérification de l'intégrité des données

### Requêtage SQL

Développement de requêtes permettant notamment de :

* Réaliser des jointures entre plusieurs tables
* Filtrer des données selon différents critères
* Calculer des moyennes et agrégations
* Identifier les contrats les plus importants
* Produire des indicateurs par région et département

## 📊 Analyses réalisées

Parmi les requêtes développées :

* Liste des contrats d'une commune spécifique
* Analyse des contrats par département
* Liste des régions de France
* Top 5 des contrats avec les plus grandes surfaces
* Calcul de la cotisation mensuelle moyenne
* Nombre de contrats par catégorie de biens
* Analyse régionale des contrats
* Classement des départements selon différents indicateurs

## 🧰 Technologies utilisées

* SQL
* SQLite
* SQLiteStudio
* Modélisation relationnelle

## 📂 Structure du projet

```text
sql/
│
├── creation_tables.sql
├── requetes.sql

schema/
│
├── schema_relationnel.png

docs/
│
├── documentation.pdf
├── presentation.pdf
```

## ✅ Compétences développées

* SQL avancé
* Jointures (JOIN)
* Agrégations (AVG, COUNT, GROUP BY)
* Filtrage des données
* Modélisation relationnelle
* Gestion des clés primaires et étrangères
* Analyse métier des données
* Documentation technique

## 👨‍💻 Auteur

**Mohamed Zaidi**
