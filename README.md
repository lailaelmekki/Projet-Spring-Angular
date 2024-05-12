part 1: backend 
Fonctionnalités
Créer un projet Spring Boot : Le projet est configuré avec Spring Boot pour une mise en place rapide et une gestion efficace des dépendances.

Entités JPA : Les entités JPA suivantes ont été créées :

Customer
BankAccount
Saving Account
CurrentAccount
AccountOperation
Interfaces JPA Repository : Des interfaces JPA Repository basées sur Spring Data ont été créées pour chaque entité afin de faciliter les opérations de base de données.

Test de la Couche DAO : Des tests unitaires ont été écrits pour tester la couche DAO afin de garantir le bon fonctionnement des opérations de base de données.

Couche Service et DTOs : La couche service a été mise en place pour la logique métier et des objets de transfert de données (DTOs) ont été utilisés pour transférer les données entre les couches.

RestController : Des contrôleurs REST ont été mis en place pour exposer les services à travers des points de terminaison RESTful.

Test des Web Services RESTful :Pour tester les web services RESTful, Swagger a été intégré à l'application. Swagger fournit une interface utilisateur conviviale pour tester et explorer les points de terminaison RESTful.

Exécution du Projet
Exécuter la classe principale GestionBanqueApplication.java.
Accéder à l'application via l'URL : http://localhost:8081
part 2 frontend :





