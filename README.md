![npm badge](https://img.shields.io/badge/npm-v11.9.0-purple)
![node badge](https://img.shields.io/badge/node-v25.6.1-black)
![javascript badge](https://img.shields.io/badge/javascript-beige)


# Mon API nodejs

# Table des Matières 

- [DOCUMENT DE SPECIFICATIONS FONCTIONNELLES][1]
- [DOCUMENTATION][2]

[1]: ./functional_documentation.md

## Description du projet 

Il s'agit d'une API REST pour la gestion centralisé d'un forum

## A qui s'adresse ce projet ? 

Ce projet est destiné à des developpeurs qui souhaite avoir un back qui communique differents plateformes 

## Dépendandes du projet 

```JSON
"dependencies": {
    "bcrypt": "^6.0.0",
    "dotenv": "^17.3.1",
    "express": "^5.2.1",
    "jsonwebtoken": "^9.0.3",
    "mongodb": "^7.1.0",
    "mongoose": "^9.2.3",
    "morgan": "^1.10.1",
    "nodemon": "^3.1.14",
    "redis": "^5.11.0"
  },
  "devDependencies": {
    "@eslint/js": "^10.0.1",
    "@faker-js/faker": "^10.3.0",
    "eslint": "^10.0.2",
    "globals": "^17.4.0"
```

## Instruction d'utilisation
> Pour commencer à utiliser l'api, vous devez créer un repository en amont sur votre github.

1. Cloner le répository
    ```BASH
    git clone https://github.com/Jboum7/mon-api-nodejs.git
    ```

2. Changer le Remote
    ```BASH
    cd mon-dossier-projet/
    git add remote origin 
    git push -u origin nom-branch
    ```

3. Installer les dépendances
    ``` BASH 
    npm install 
    ```

## Exécuter l'API 
```BASH 
npm run start 
```