# Location

Location est une application Symfony dédiée à la gestion d'une agence de location de véhicules. Elle permet de gérer les utilisateurs, les véhicules, les réservations et les avis des clients.

## 📌 Description
L'application offre une interface utilisateur simple et intuitive permettant aux clients de réserver des véhicules, de consulter leurs réservations, et aux administrateurs de gérer l'ensemble des véhicules disponibles.

## 🚀 Fonctionnalités principales
- **Gestion des utilisateurs** : Inscription, connexion, rôles (administrateur, client).
- **Gestion des véhicules** : Ajout, modification, suppression, consultation des véhicules disponibles.
- **Réservation de véhicules** : Réservation, consultation, modification ou annulation.
- **Commentaires et avis** : Les clients peuvent laisser un avis sur les véhicules loués.
- **Dashboard utilisateur** : Interface personnalisée pour les clients et les administrateurs.

## 📂 Structure du projet
```
.
├── config/           # Configuration de l'application Symfony
├── migrations/       # Fichiers de migration de la base de données
├── public/           # Dossier public contenant l'index.php
├── src/              # Code source de l'application (Controllers, Entities, Repositories)
├── templates/        # Vues Twig pour l'affichage
├── .env              # Configuration de l'environnement
├── composer.json     # Dépendances PHP
├── README.md         # Documentation du projet
```

## 🔧 Prérequis
- PHP >= 8.0
- Composer
- Symfony CLI
- MariaDB ou MySQL

## 📥 Installation
1. Clonez ce dépôt :
```bash
$ git clone https://github.com/Lcs-93/Location.git
```
2. Rendez-vous dans le répertoire cloné :
```bash
$ cd Location
```
3. Installez les dépendances PHP avec Composer :
```bash
$ composer install
```
4. Configurez votre base de données dans le fichier `.env` :
```
DATABASE_URL="mysql://root:@127.0.0.1:3306/location?serverVersion=10.4.32-MariaDB&charset=utf8mb4"
```
5. Effectuez les migrations :
```bash
$ php bin/console doctrine:migrations:migrate
```
6. Lancez le serveur Symfony :
```bash
$ symfony server:start
```

## 📌 Utilisation
Accédez à l'application via votre navigateur à l'adresse suivante :
```
http://127.0.0.1:8000
```

## 🛠️ Technologies utilisées
- **Symfony** (PHP framework)
- **Twig** (Moteur de templates)
- **MariaDB / MySQL** (Base de données)
- **HTML / CSS / JavaScript** (Frontend)

## 📄 Licence
Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 📣 Auteur
Projet créé par **Lcs-93**. N'hésitez pas à me contacter pour toute suggestion ou amélioration !

---

🔥 Bon développement !

