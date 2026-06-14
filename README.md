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

- Page de connexion
<img width="945" height="663" alt="image" src="https://github.com/user-attachments/assets/945d4c0b-020d-46a7-b067-df537cd4a1d8" />

- Gestion des opérations
<img width="717" height="341" alt="image" src="https://github.com/user-attachments/assets/a42864b0-aaa5-4414-a163-b4c23663bee6" />

- Gestion des utilisateurs
<img width="799" height="275" alt="image" src="https://github.com/user-attachments/assets/9eff78de-0e34-41d9-a96b-40a5a575e389" />

- Gestion des comptes-rendus
<img width="688" height="256" alt="image" src="https://github.com/user-attachments/assets/d3eb13f1-b45b-462f-8d47-6a63e78da732" />


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
