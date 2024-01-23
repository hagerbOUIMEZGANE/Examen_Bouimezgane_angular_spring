# Projet de Gestion des Produits et des Commandes

## Description du Projet

Ce projet est une solution complète de gestion de produits et de commandes, composée de plusieurs modules interconnectés. L'architecture repose sur des micro-services, une application frontend Angular, et une sécurité renforcée par OAuth2 et OpenID Connect (OIDC) via Keycloak.

### 1. Micro-service de Gestion des Produits (Inventory-service)

Le micro-service de gestion des produits offre des fonctionnalités exhaustives pour la manipulation des produits, y compris l'ajout, la modification, la suppression et la consultation. Il joue un rôle central dans la gestion du catalogue de produits.

### 2. Application Frontend Angular

L'interface utilisateur frontend, développée en Angular, offre une expérience utilisateur moderne et intuitive. Elle permet aux utilisateurs de visualiser, ajouter, modifier et supprimer des produits. De plus, elle intègre des fonctionnalités avancées pour la gestion des commandes.

### 3. Service de Gestion des Commandes

Un autre micro-service dédié à la gestion des commandes assure la traçabilité et la gestion efficace des commandes de produits. Les fonctionnalités incluent la création, la modification et la consultation des commandes.

## Sécurité de l'Application

La sécurité du système repose sur OAuth2 et OpenID Connect, avec la mise en œuvre de Keycloak. La gestion des rôles et des autorisations est centralisée via Keycloak, garantissant un contrôle d'accès robuste et fiable.

## Tâches à Réaliser

1. **Développement du Micro-service de Gestion des Produits (Inventory-service)**

   - Mise en œuvre des opérations CRUD pour la gestion des produits.

2. **Développement du Frontend Angular**

   - Création d'une interface utilisateur Angular permettant une interaction fluide avec le micro-service de gestion des produits.

3. **Sécurisation du Micro-service Inventory-service**

   - Configuration de la sécurité OAuth2 pour le micro-service Inventory-service.

4. **Sécurisation du Frontend Angular avec Adaptateur Keycloak**

   - Intégration d'un adaptateur Keycloak pour renforcer la sécurité de l'application frontend Angular.

5. **Développement d'un Micro-service Sécurisé pour la Gestion des Commandes**

   - Implémentation des fonctionnalités CRUD pour la gestion des commandes.
   - Sécurisation du nouveau micro-service en utilisant OAuth2 et Keycloak.

6. **Ajout des Fonctionnalités Frontend pour la Gestion des Commandes**

   - Intégration des fonctionnalités dans l'interface utilisateur Angular pour une gestion efficace des commandes.

7. **Intégration des Services Spring Cloud**
   - Intégration des services Spring Cloud suivants :
     - Spring Cloud Gateway
     - Eureka Discovery
     - Spring Cloud Config

## Captures d'écran

- **Clients:**
  ![Clients](ScreenShots/clients.png)

- **Produits:**
  ![Produits](ScreenShots/products.png)

- **Rôles:**
  ![Rôles](ScreenShots/Roles.png)

## Instructions d'Exécution

Suivez attentivement le guide d'installation et de configuration dans la documentation pour déployer et exécuter le projet avec succès.

## Auteur

[Bouimezgne Hager]
