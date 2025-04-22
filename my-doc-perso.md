
# ERPNext Docker Setup

## Description

Ce projet consiste à faire fonctionner **ERPNext** en local à l'aide de Docker. **ERPNext** est un ERP open-source complet permettant de gérer les opérations de votre entreprise. Ce guide vous permet de déployer rapidement une instance locale d'ERPNext grâce à Docker et Docker Compose.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants :

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Installation

1. Clonez le dépôt :

    ```bash
    git clone https://github.com/frappe/frappe_docker
    ```

2. Allez dans le répertoire `frappe_docker` :

    ```bash
    cd frappe_docker
    ```

3. Lancez les conteneurs Docker à l'aide de Docker Compose :

    ```bash
    docker-compose -f pwd.yml up -d
    ```

Cela téléchargera les images nécessaires et démarrera les conteneurs en mode détaché.

## Accéder à ERPNext

Une fois les conteneurs démarrés, vous pouvez accéder à ERPNext en local en vous rendant à l'adresse suivante :

[http://localhost:8080](http://localhost:8080)

### Identifiants par défaut :
- **Nom d'utilisateur** : Administrator
- **Mot de passe** : admin

## Motivation

### Contexte de l'évaluation - Examen J1 - Avril 25 - P16

Ce projet fait partie de l'évaluation de mon examen **J1 - Avril 25 - P16**. L'objectif est de télécharger le projet ERPNext depuis GitHub, de le faire fonctionner en local et de démontrer une bonne compréhension du système. Je vais également :

- Refait le MCD (Modèle Conceptuel de Données) pour mieux comprendre les relations dans le système.
- Créer une **todo list** pour structurer les tâches à venir.

### Tâches à venir

- **Modification sur un projet existant** : Améliorations et ajustements sur le code existant.
- **Création de nouvelles pages** sur une autre technologie, tout en étant lié au projet ERPNext existant.---

Cela correspond-il mieux à ce que tu voulais ?

### Fonctionnalités à préparer

- **Réinitialisation de données** : Ajouter une fonctionnalité pour réinitialiser les données dans l'application.
- **Import de fichiers** : Ajouter une fonctionnalité permettant d'importer des fichiers dans le projet ERPNext.

---

## Auteur

**RAZAFITSIALONINA Malala Ninah**




