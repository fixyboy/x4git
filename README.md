# README du Cours GitHub

## Introduction

Bienvenue dans le cours GitHub! Ce cours est conçu pour vous aider à comprendre les bases de GitHub, une plateforme web utilisée pour le contrôle de version et le développement logiciel collaboratif. Que vous soyez un débutant cherchant à démarrer avec le contrôle de version ou un développeur expérimenté cherchant à améliorer votre flux de travail, ce cours couvre les sujets essentiels que vous devez connaître.

## Plan du Cours

1. **Introduction au Contrôle de Version**
   - Qu'est-ce que le contrôle de version ?
   - Avantages de l'utilisation des systèmes de contrôle de version
   - Vue d'ensemble de Git

2. **Commencer avec GitHub**
   - Création d'un compte GitHub
   - Configuration de Git sur votre machine locale
   - Commandes Git de base

3. **Référentiels**
   - Création d'un nouveau référentiel
   - Clonage d'un référentiel
   - Comprendre la structure du référentiel

4. **Travailler avec les Branches**
   - Qu'est-ce qu'une branche ?
   - Création et gestion des branches
   - Fusion des branches

5. **Collaborer sur GitHub**
   - Forker des référentiels
   - Pull requests
   - Revues de code

6. **Fonctionnalités Avancées de GitHub**
   - Problèmes et tableaux de projet
   - GitHub Actions
   - GitHub Pages

7. **Bonnes Pratiques**
   - Écrire de bons messages de commit
   - Maintenir un historique de commit propre
   - Utiliser efficacement les fichiers .gitignore

## Prérequis

- Compréhension de base de l'interface en ligne de commande
- Familiarité avec les concepts de programmation (optionnel mais utile)

## Installation et Configuration

### Installer Git

Avant de commencer, vous devez avoir Git installé sur votre machine locale. Suivez les instructions ci-dessous pour votre système d'exploitation :

#### Windows
1. Téléchargez Git depuis [git-scm.com](https://git-scm.com/download/win).
2. Exécutez l'installateur et suivez les instructions à l'écran.

#### macOS
1. Installez Homebrew si vous ne l'avez pas déjà :
   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Installez Git avec Homebrew :
   ```sh
   brew install git
   ```

#### Linux
1. Installez Git en utilisant votre gestionnaire de paquets. Par exemple, sur Ubuntu :
   ```sh
   sudo apt-get update
   sudo apt-get install git
   ```

### Configuration de Git

Après avoir installé Git, configurez-le avec les détails de votre compte GitHub :

```sh
git config --global user.name "Votre Nom"
git config --global user.email "votremail@example.com"
```

## Instructions du Cours

1. **Cloner le Référentiel du Cours**
   - Ouvrez votre terminal et exécutez la commande suivante :
     ```sh
     git clone https://github.com/yourusername/github-course.git
     ```
   - Accédez au répertoire du cours :
     ```sh
     cd github-course
     ```

2. **Suivre les Modules**
   - Chaque module est situé dans son propre répertoire.
   - Commencez par le répertoire `00-Introduction` et suivez les instructions.