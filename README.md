# Java Hibernate & H2

Ce projet est une application Java basée sur **Hibernate ORM** et la base de données **H2**. Il permet de gérer des produits et de réaliser différentes opérations sur les données, notamment l’insertion, l’affichage et la recherche d’un produit par son identifiant.

## 1. Création de la table Produit

<img width="546" height="198" alt="Capture d'écran 2026-10-06 204614" src="https://github.com/user-attachments/assets/0dfa288f-6348-46e7-8fda-2a463462014c" />

Projet Java utilisant Hibernate et une base de données H2. L’application permet de gérer des produits avec leurs informations principales : identifiant, nom et prix. Hibernate est utilisé pour la création et la gestion automatique des tables dans la base de données.

## 2. Insertion de produits avec Hibernate

<img width="1228" height="498" alt="Capture d'écran 2026-10-06 205040" src="https://github.com/user-attachments/assets/8f953b11-267c-4b04-9089-e05e56729d01" />

Hibernate génère automatiquement les requêtes SQL `INSERT` afin d’ajouter les produits dans la table `Produit`. Après l’exécution des requêtes, le message « Produits insérés avec succès ! » confirme que les données ont été enregistrées correctement dans la base de données.

## 3. Récupération des produits avec Hibernate

<img width="652" height="343" alt="Capture d'écran 2026-10-06 205237" src="https://github.com/user-attachments/assets/7a92830b-754e-4b90-b268-7a847a160e49" />

Hibernate génère automatiquement une requête SQL `SELECT` pour récupérer les informations des produits enregistrés dans la table `Produit`, notamment leur identifiant, leur nom et leur prix.

## 4. Affichage et recherche des produits

<img width="1013" height="417" alt="image" src="https://github.com/user-attachments/assets/2d22d0ae-3d3c-42ab-9116-0fabac1d8f13" />



L’application récupère la liste des produits enregistrés dans la base de données et affiche leurs informations : identifiant, nom et prix. Elle permet également de rechercher un produit spécifique à partir de son identifiant. Dans cet exemple, le produit ayant l’ID 1 est correctement retrouvé et affiché.

## 5. Connexion à la base de données H2

<img width="1357" height="547" alt="db1" src="https://github.com/user-attachments/assets/c21f96cb-4c42-4ca6-a0a6-24905707121c" />


Cette étape permet de configurer une connexion à la base de données H2 en utilisant le driver `org.h2.Driver` et l’URL JDBC `jdbc:h2:mem:testdb`. La base de données est utilisée en mode mémoire pour stocker temporairement les données de l’application.

## 6. Interface H2 Database

<img width="1357" height="547" alt="db1" src="https://github.com/user-attachments/assets/81233b10-682e-4d97-bace-0601c2357a43" />

Cette interface permet de consulter et de manipuler la base de données `jdbc:h2:mem:testdb`. Elle permet notamment d’exécuter des requêtes SQL pour créer, insérer, consulter, modifier et supprimer des données dans les tables. Ici, la table `PRODUIT` est visible dans la base de données.

## 7. Consultation de la base de données H2

<img width="1362" height="640" alt="Capture d'écran 2026-10-06 194459" src="https://github.com/user-attachments/assets/7b90d37e-ffc2-4916-959f-1d2d613e1a74" />

L’interface H2 permet de se connecter à la base `jdbc:h2:mem:testdb` et d’exécuter des requêtes SQL. Elle permet de consulter la table `PRODUIT` et de réaliser différentes opérations comme la création, l’insertion, la consultation, la modification et la suppression des données.

<img width="1362" height="642" alt="Capture d'écran 2026-10-06 194538" src="https://github.com/user-attachments/assets/dc1cbc3f-81f2-4bff-9ada-a3054342a6b4" />
