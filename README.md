# SmartBike 

## Description

SmartBike est une application dédiée aux amateurs de vélos électriques. Cette plateforme intuitive vous permet de découvrir, commander et en savoir plus sur une gamme exclusive de vélos électriques. 


## Structure du projet

- **controllers:** Contient les classes des contrôleurs.
- **models:** Contient la classe du modèle SmartbikeModel.
- **views:** Contient les fichiers de vue pour chaque page.
- **css:** Contient les fichiers de style CSS.

## Fonctionnalités

- **Page d'Accueil:**
  - Affiche les détails du dernier vélo ajouté.
  - Possibilité de commander le dernier vélo.
  
- **Vélos:**
  - Liste tous les vélos disponibles à l'achat.
  - Affiche un bouton "Commander" pour chaque vélo.
  - Affiche un bouton "Plus d'infos" pour chaque vélo.

- **Produit:**
  - Affiche les détails d'un vélo spécifique.
  - Affiche un bouton "Commander" pour le vélo sélectionné.
  
- **Commande:**
  - Permet aux utilisateurs de passer une commande pour un vélo.
  - Formulaire avec champs pour le nom, prénom, email et message.
  - Bouton "Envoyer" pour soumettre la commande.

- **Contact:**
  - Formulaire de contact pour les utilisateurs.
  - Formulaire avec champs pour le nom, prénom, email et message.
  - Bouton "Envoyer" pour soumettre le message.

## Configuration

### Base de Donnée

Informations de connexion a la base de donnée MySQL :

 ```php
    <?php

    define('DB_HOST', 'localhost:3306');
    define('DB_NAME', 'db-dk');
    define('DB_USER', 'root');
    define('DB_PASSWORD', 'password');
 ```

## Utilisation

1. Clonez le dépôt : `git clone https://github.com/battlcall/smartbike.git`
2. Configurez le serveur web pour pointer vers le répertoire du projet.
3. Assurez-vous que PHP est configuré correctement.
4. Accédez au site via votre navigateur.
