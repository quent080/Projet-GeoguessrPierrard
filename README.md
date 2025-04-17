# **Projet-GeoguessrPierrard**
projet du cours de systèmes intelligents

## **1. Descritpion du projet**

Dans le cadre du cours de systèmes intelligents, nous avons décidé de réaliser un projet inspiré de GeoGuessr, en essayant de le reproduire de la manière la plus fidèle possible. Pour cela, nous allons utiliser des images provenant du monde entier récupérées via Google Street View. L'objectif est de permettre à notre algorithme de reconnaître l'endroit montré sur l'image et de prédire les coordonnées géographiques (longitude et latitude) correspondant selon lui à cet endroit.

## **2. Nos objectifs**



## **3. Comment allons nous procéder ?**

Première étape nous allons récuperer des données grâce à l'API de google street view associées à leurs coordonnées (longitude et latitude).
Deuxième étape on va redimensionner les images en 240x240 pour avoir le même modèle d'image dans toute notre base de données.
Troisème étape on va utiliser le principe de l’augmentation des données qui consiste à générer de nouvelles données à partir de données existantes. On va tourner, zoomer, éclaircir nos images existantes de notre base de données.

