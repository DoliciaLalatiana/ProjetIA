# Projet IA — Classification Sonar

## 1️⃣ Définition du problème

Les sous-marins utilisent des systèmes sonar pour détecter les objets présents sous l’eau.
Cependant, lorsqu’un objet est détecté, il est difficile de déterminer automatiquement s’il s’agit d’une roche (Rock) ou d’une mine sous-marine (Mine).

L’objectif de ce projet est de développer un modèle d’intelligence artificielle capable de classifier les objets détectés par sonar en deux catégories :

- **R (Rock)** : roche
- **M (Mine)** : mine sous-marine

Pour cela, nous utilisons un dataset appelé **sonar.all-data.csv**, qui contient des mesures de signaux sonar.

Chaque observation du dataset contient :
- **60 valeurs numériques** représentant les intensités du signal sonar
- **1 label final** indiquant si l’objet est une roche (R) ou une mine (M)

Le modèle de machine learning va apprendre à partir de ces données afin de pouvoir prédire correctement la nature d’un objet détecté.

### Type de problème

Ce problème appartient à la catégorie :

**Classification supervisée**

Car :
- nous avons des données d’entrée (les signaux sonar)
- nous avons une réponse attendue (Rock ou Mine)

L’objectif final est de créer un modèle capable de faire une **prédiction automatique** sur de nouvelles données sonar.