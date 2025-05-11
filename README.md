# Analyse des Données sur les Victimes de Crimes  

Ce notebook présente une analyse exploratoire des données relatives aux victimes de crimes. L'objectif principal est de comprendre les caractéristiques démographiques et les circonstances entourant ces événements tragiques. En collaboration avec mes amis : Sewa Fumey et Alexandre Chevalier
Lien du POWER POINT ( format PDF ) : [Projet Alexandre Sewa Zakaria.pdf](https://github.com/user-attachments/files/20151522/Projet.Alexandre.Sewa.Zakaria.pdf)


## Résumé des Étapes Clés

1.  **Importation des Bibliothèques:**
    * Importation des bibliothèques essentielles telles que `pandas`, `matplotlib.pyplot` et `seaborn` pour la manipulation et la visualisation des données.
2.  **Chargement des Données:**
    * Chargement du dataset à partir d'un fichier CSV nommé "homicide-data.csv".
3.  **Nettoyage et Préparation des Données:**
    * Suppression des colonnes non pertinentes pour l'analyse.
    * Remplacement des valeurs manquantes dans la colonne 'age' par la médiane.
    * Création de la colonne 'ageBracket' pour catégoriser l'âge des victimes.
4.  **Analyse Exploratoire des Données (EDA):**
    * Visualisation de la distribution des victimes par genre à l'aide d'un diagramme circulaire.
    * Analyse de la répartition des tranches d'âge des victimes via un histogramme.
    * Examen des lieux de décès des victimes à travers un graphique à barres.
    * Étude de la relation entre l'âge et le lieu de décès des victimes à l'aide d'un graphique à barres.
5.  **Identification du Profil Type de la Victime:**
    * Détermination du profil type de la victime en regroupant les données par genre, tranche d'âge et lieu de décès, puis en identifiant le groupe le plus fréquent.

## Présentation

Ce notebook offre une vue d'ensemble des données sur les victimes de crimes, en mettant en lumière les tendances clés et les caractéristiques importantes. Les visualisations graphiques facilitent la compréhension des relations entre différentes variables, telles que l'âge, le genre et le lieu de décès des victimes. L'analyse aboutit à l'identification du profil type de la victime, ce qui peut être crucial pour orienter les efforts de prévention et de soutien aux communautés affectées
