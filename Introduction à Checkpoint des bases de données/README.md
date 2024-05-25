SLIDE 1 : Introduction
Titre : Comparaison des bases de données MongoDB et SQL
Aperçu:
Introduction aux types de bases de données : SQL (Structured Query Language) vs NoSQL (Not Only SQL).
Objectif : Comparez MongoDB (une base de données NoSQL leader) avec les bases de données SQL traditionnelles.
SLIDE 2 : Bases de données SQL
Titre : Bases de données SQL
Définition:
Les bases de données SQL sont des bases de données relationnelles qui utilisent le langage de requête structuré pour la gestion des données.
Les exemples incluent MySQL, PostgreSQL, Oracle Database et SQL Server.
Principales caractéristiques:
Basé sur un schéma : schéma fixe avec des tables et des colonnes prédéfinies.
Conformité ACID : garantit l'atomicité, la cohérence, l'isolement et la durabilité des transactions.
Basé sur un tableau : les données sont organisées en lignes et en colonnes.
Forte cohérence : garantit une cohérence immédiate dans la base de données.

SLIDE 3 : MongoDB
Titre : MongoDB
Définition:
MongoDB est une base de données NoSQL qui stocke les données dans des documents flexibles de type JSON.
Il s'agit d'une base de données orientée document conçue pour une évolutivité et des performances élevées.
Principales caractéristiques:
Sans schéma : schéma flexible permettant des structures de données dynamiques.
Orienté document : stocke les données au format BSON (Binary JSON).
Évolutivité horizontale : facilement évolutive sur plusieurs serveurs (sharding).
Haute performance : optimisé pour gérer de gros volumes de données.
Requêtes riches : prend en charge les requêtes complexes et l'indexation.
SLIDE 4 : Comparaison
veTitre : MongoDB vs bases de données SQL
Modèle de données:
SQL : structuré, basé sur des tables, avec un schéma fixe.
MongoDB : flexible, basé sur des documents, avec un schéma dynamique.
Langage de requête:
SQL : utilise SQL pour interroger et gérer les données.
MongoDB : utilise le langage de requête MongoDB (MQL) avec des méthodes telles que find() et Aggregate().
Évolutivité :
SQL : évolue généralement verticalement (ajoutant plus de puissance au matériel existant).
MongoDB : évolue horizontalement (en ajoutant plus de serveurs ou de nœuds).
Transactions:
SQL : prise en charge renforcée des transactions ACID, garantissant l'intégrité des données.
MongoDB : prend en charge les transactions ACID multidocuments (depuis la version 4.0), en mettant l'accent sur les performances.
Cas d'utilisation :
SQL : idéal pour les applications nécessitant des requêtes complexes, des données structurées et un support transactionnel solide (par exemple, services bancaires, systèmes ERP).
MongoDB : Idéal pour les applications avec des données non structurées, des analyses en temps réel et des architectures évolutives.

SLIDE 5 : Conclusion
Titre : Conclusion

Choisir la bonne base de données :

Bases de données SQL :
Adapté aux données structurées, aux requêtes complexes et aux besoins de transactions importants.
Idéal pour les applications traditionnelles nécessitant l’intégrité et la cohérence des données.
MongoDB :
Adapté aux données et applications non structurées ou semi-structurées nécessitant de la flexibilité.
Idéal pour les applications évolutives et hautes performances avec des cycles de développement rapides.
Dernières pensées:

Le choix entre les bases de données MongoDB et SQL dépend des exigences spécifiques du projet.
Les deux bases de données ont des atouts distincts et la décision doit être basée sur la structure des données, l'évolutivité et les besoins transactionnels.
Ces diapositives fournissent une comparaison structurée des bases de données MongoDB et SQL, mettant en évidence leurs fonctionnalités, leurs différences et les cas d'utilisation appropriés.
