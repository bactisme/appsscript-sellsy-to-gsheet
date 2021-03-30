# Google Sheet Apps Script For Calling SellSy API

Ce script est un exemple de l'utilisation de l'API SellSy pour mettre à jour une feuille dans google sheet avec les données SellSy.

La configuration d'exemple exporte toute les dernières factures pour une période donnée (exemple sur 2021) dans une feuille google sheet.

Le lancement de la mise à jour se fait via un menu ajouté.

<img width="229" alt="Capture d’écran 2021-03-30 à 14 39 51" src="https://user-images.githubusercontent.com/369622/112989995-d834de80-9165-11eb-9d7a-8a43633d801c.png">

# Installation

- Copier le contenu de Code.gs dans l'éditeur de script.
- Installer la [bibliothèque oAuth1 pour Google Apps Script](https://github.com/googleworkspace/apps-script-oauth1). 
- Définir les clés
- Créé la feuille de résultat
- Vérifier la section CUSTOM pour les paramètres

# TODO 

- Utilisation de la pagination (seulement les 1000 dernières par défaut)
- Mise à jour ligne par ligne en gardant l'ID du document.
