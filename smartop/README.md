# SmartOp - Application de Gestion des Opérations Programmées

## Description

SmartOp est une application web développée pour la gestion des opérations programmées au sein d'une organisation. Elle permet de planifier, suivre et gérer efficacement les opérations ainsi que les comptes-rendus associés.

Le projet a été réalisé avec **Spring Boot** pour le back-end et **Angular** pour le front-end, en suivant la méthodologie agile **SCRUM**.

## Contexte

Ce projet a été développé pour répondre aux besoins métier d'Intelcia IT Solutions. Il a permis de mettre en pratique les compétences en génie logiciel, développement web full-stack et gestion de projet agile.

## Fonctionnalités

### Gestion des utilisateurs
- Création des utilisateurs
- Modification des informations utilisateur
- Suppression des utilisateurs
- Gestion des rôles et permissions

### Gestion des opérations
- Création d'opérations programmées
- Planification des opérations
- Suivi de l'avancement
- Consultation des opérations

### Gestion des comptes-rendus (CR)
- Création de comptes-rendus
- Modification des comptes-rendus
- Consultation de l'historique des comptes-rendus

## Technologies utilisées

### Back-end
- Java
- Spring Boot
- Spring Data JPA
- Spring Security
- Hibernate
- Maven

### Front-end
- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap

### Base de données
- MySQL

### Outils
- Git
- GitHub
- Postman
- IntelliJ IDEA
- Visual Studio Code

## Architecture du projet

```text
smartop/
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── ...
│
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
│
└── README.md
```

## Installation

### Prérequis

- Java 17 ou supérieur
- Maven
- Node.js
- Angular CLI
- MySQL

### Cloner le projet

```bash
git clone https://github.com/imane1banzi/smartopgit2.git
cd smartopgit2/smartop
```

## Configuration du Back-end

Se placer dans le dossier du back-end :

```bash
cd backend
```

Configurer la connexion à la base de données dans :

```properties
src/main/resources/application.properties
```

Exemple :

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/smartop
spring.datasource.username=root
spring.datasource.password=password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Lancer le serveur :

```bash
mvn spring-boot:run
```

Le back-end sera accessible sur :

```text
http://localhost:8080
```

## Configuration du Front-end

Se placer dans le dossier du front-end :

```bash
cd frontend
```

Installer les dépendances :

```bash
npm install
```

Lancer l'application Angular :

```bash
ng serve
```

L'application sera accessible sur :

```text
http://localhost:4200
```

## Méthodologie

Le projet a été réalisé selon la méthodologie Agile SCRUM :

- Gestion du backlog
- Planification des sprints
- Réunions de suivi
- Livraison incrémentale des fonctionnalités

## Compétences développées

- Développement Full-Stack
- Architecture REST
- Gestion des utilisateurs et des rôles
- Développement d'API sécurisées
- Développement d'interfaces web modernes
- Gestion de base de données relationnelle
- Travail en environnement Agile

## Captures d'écran

- Page de connexion :
<img width="945" height="663" alt="image" src="https://github.com/user-attachments/assets/9df122b8-7e0b-41ad-b751-aeb5f56e3f04" />

- Gestion des opérations :
<img width="727" height="332" alt="image" src="https://github.com/user-attachments/assets/56489e9b-81d6-461b-bf2f-b21a950d9825" />

- Gestion des utilisateurs : 
<img width="769" height="235" alt="image" src="https://github.com/user-attachments/assets/5ce6d259-4a89-4202-a461-eece3174fdcc" />

- Gestion des comptes-rendus
<img width="688" height="256" alt="image" src="https://github.com/user-attachments/assets/b53d59ec-210d-458e-b2e1-7ae8d87d5f98" />

## Perspectives d'amélioration

- Notifications par e-mail
- Tableau de bord statistique avancé
- Gestion documentaire
- Export PDF des comptes-rendus
- Historisation complète des opérations

## Auteur

**Imane Banzi**

Développeuse Full-Stack Java / Spring Boot / Angular

GitHub : https://github.com/imane1banzi

## Licence

Projet réalisé dans un cadre professionnel et éducatif.
