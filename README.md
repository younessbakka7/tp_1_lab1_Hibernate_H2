# Java Hibernate & H2

Ce projet est une application Java basée sur **Hibernate ORM** et la base de données **H2**. Il permet de gérer des produits et de réaliser différentes opérations sur les données, notamment l’insertion, l’affichage et la recherche d’un produit par son identifiant.

<img width="546" height="198" alt="Création de la table Produit" src="https://github.com/user-attachments/assets/0dfa288f-6348-46e7-8fda-2a463462014c" />

### Gestion des produits

Projet Java utilisant **Hibernate** et une base de données **H2**. L’application permet de gérer des produits avec leurs informations principales : identifiant, nom et prix. Hibernate est utilisé pour la création et la gestion automatique des tables dans la base de données.

<img width="1228" height="498" alt="Insertion des produits" src="https://github.com/user-attachments/assets/8f953b11-267c-4b04-9089-e05e56729d01" />

### Insertion de produits avec Hibernate

Hibernate génère automatiquement les requêtes SQL `INSERT` afin d’ajouter les produits dans la table `Produit`. Après l’exécution des requêtes, le message **« Produits insérés avec succès ! »** confirme que les données ont été enregistrées correctement dans la base de données.

<img width="652" height="343" alt="Récupération des produits" src="https://github.com/user-attachments/assets/7a92830b-754e-4b90-b268-7a847a160e49" />

### Récupération des produits avec Hibernate

Hibernate génère automatiquement une requête SQL `SELECT` pour récupérer les informations des produits enregistrés dans la table `Produit`, notamment leur identifiant, leur nom et leur prix.

<img width="458" height="177" alt="Affichage et recherche des produits" src="https://github.com/user-attachments/assets/400b5f96-5439-4274-bc62-087c7ec244d7" />

### Affichage et recherche des produits

L’application récupère la liste des produits enregistrés dans la base de données et affiche leurs informations : identifiant, nom et prix. Elle permet également de rechercher un produit spécifique à partir de son identifiant. Dans cet exemple, le produit ayant l’ID **1** est correctement retrouvé et affiché.

<img width="1139" height="287" alt="Connexion à la base de données H2" src="https://github.com/user-attachments/assets/b72652d0-e51f-4afa-9b7e-0c8308e84793" />

### Connexion à la base de données H2

Cette étape permet de configurer une connexion à la base de données H2 en utilisant le driver `org.h2.Driver` et l’URL JDBC `jdbc:h2:mem:testdb`. La base de données est utilisée en mode mémoire pour stocker temporairement les données de l’application.

<img width="1357" height="547" alt="Interface H2 Database" src="https://github.com/user-attachments/assets/0ad58031-bf0a-475b-8f40-f8dd1000f0" />

### Interface H2 Database

Cette interface permet de consulter et de manipuler la base de données `jdbc:h2:mem:testdb`. Elle permet notamment d’exécuter des requêtes SQL pour créer, insérer, consulter, modifier et supprimer des données dans les tables. Ici, la table `PRODUIT` est visible dans la base de données.

<img width="1362" height="640" alt="Consultation de la base de données H2" src="https://github.com/user-attachments/assets/7b90d37e-ffc2-4916-959f-1d2d613e1a74" />

### Consultation de la base de données H2

L’interface H2 permet de se connecter à la base `jdbc:h2:mem:testdb` et d’exécuter des requêtes SQL. Elle permet de consulter la table `PRODUIT` et de réaliser différentes opérations comme la création, l’insertion, la consultation, la modification et la suppression des données.

<img width="1362" height="642" alt="Table Produit" src="https://github.com/user-attachments/assets/dc1cbc3f-81f2-4bff-9ada-a3054342a6b4" />
