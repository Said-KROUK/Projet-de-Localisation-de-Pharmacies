# Projet-de-Localisation-de-Pharmacies
Une Application de Recherche Géospatiale avec Python et Neo4j
Description du Projet
Ce projet fournit une solution pour localiser les pharmacies les plus proches en utilisant des outils géographiques modernes. Il combine l'extraction de données géographiques, le traitement des graphes et la recherche pour offrir une fonctionnalité de recherche efficace.

Les étapes principales incluent :

Extraction des Données : Utilisation de OSMnx pour extraire les données des réseaux routiers et des pharmacies depuis OpenStreetMap (OSM).
Gestion des Données : Importation des données extraites dans une base de données de graphes Neo4j, qui permet de gérer les relations et d'effectuer des recherches sur les données géographiques.
Recherche de Pharmacies : Développement d'une application Python qui calcule le chemin le plus court entre votre position actuelle et les pharmacies disponibles, en utilisant Neo4j pour trouver les itinéraires optimaux.
Le projet est conçu pour être modulaire et extensible, avec une architecture permettant d'ajouter facilement de nouvelles fonctionnalités ou d'adapter le système à d'autres types de points d'intérêt.
