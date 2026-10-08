# App covoiturage rugby

Application web en production, utilisée chaque semaine par les parents d'un groupe de jeunes pour organiser les trajets à l'entraînement et la rotation du goûter.

Ce dépôt contient la **version de démonstration**, avec des données fictives.

- Démo en ligne : [demo-covoiturage-rugby.blanloeil.com](https://demo-covoiturage-rugby.blanloeil.com/)
- Présentation du projet : [romain.blanloeil.com/projets/rugby-app.html](https://romain.blanloeil.com/projets/rugby-app.html)

## Fonctionnalités

- Gestion des trajets et des covoiturages pour les entraînements
- Rotation automatique des tours (goûter, trajets)
- Calcul de la semaine (`mondayIndex()`) qui saute les vacances scolaires
- Disponibilités saisies via un formulaire Google

## Technique

- HTML / CSS / JavaScript vanilla, sans framework
- Google Sheets utilisé comme base de données, lu via export CSV
- Hébergement sur Vercel

## Données

Tous les prénoms et toutes les données de cette démo sont fictifs.
