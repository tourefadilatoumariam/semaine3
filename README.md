# semaine3
#exercices 
#  MonProjet - Gestionnaire de Tâches

MonProjet est une application web simple qui permet aux utilisateurs de créer, modifier et supprimer des tâches personnelles. Développée en PHP avec une base de données MySQL, elle permet une gestion efficace de vos tâches au quotidien.



## Fonctionnalités

-  Authentification utilisateur (connexion / inscription)
-  Ajout de tâches
-  Modification des tâches
-  Suppression des tâches
-  Affichage des tâches par utilisateur



## Aperçu

![Aperçu de l'application](./images/screenshot.png)


## Technologies utilisées

- PHP 8



##  Installation

### Pré-requis

- Serveur local (XAMPP, WAMP, MAMP…)
- PHP 
- Navigateur web moderne

### Étapes

```bash
# Clone le dépôt
git clone https://github.com/ton-utilisateur/MonProjet.git

# Place le dossier dans le répertoire htdocs (XAMPP)
cd MonProjet

# Importe la base de données
1. Ouvre phpMyAdmin
2. Crée une base de données nommée "monprojet_db"
3. Importe le fichier monprojet_db.sql

# Lance le projet depuis ton navigateur
http://localhost/MonProjet