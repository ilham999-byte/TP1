Objectif
Ce projet a pour but de maîtriser l'insertion et la récupération de données dans une base de données MySQL à l'aide de l'API JDBC en Java. Le projet met en œuvre les objets Connection, Statement, et ResultSet, et aborde la gestion des erreurs potentielles.

Fonctionnalités
Insertion des Données
La classe Site permet d'insérer un site (nom) dans la base de données à l'aide de la méthode save(Site s).

Récupération des Données
La méthode load() récupère et affiche les données stockées dans la table Site.

Instructions
Créer la Base de Données :

CREATE DATABASE db;
USE db;
CREATE TABLE `site` (
  `id` int(11) primary key auto_increment,
  `nom` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
Configurer la Connexion JDBC : Ajustez les informations de connexion dans la méthode save() (nom d'utilisateur, mot de passe, URL de la base de données).

Exécuter le Projet : Lancez le programme Java pour insérer et afficher les sites.

Liens vers le Code Source
Lien vers le dépôt GitHub
Démo Vidéo
Lien vers la démo vidéo
