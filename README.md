# 🇰🇷 Korean Island – Apprentissage du Coréen

> Plateforme mobile interactive pour l'apprentissage du coréen, conçue pour les francophones.

<!-- Badges (Placeholders) -->
[![Licence MIT](https://img.shields.io/badge/License-MIT-blue.svg )](LICENSE)
[![Plateforme](https://img.shields.io/badge/Platform-Android-green.svg )](https://developer.android.com/ )
[![Langage](https://img.shields.io/badge/Language-Java-orange.svg )](https://www.java.com/ )
[![Statut du Projet](https://img.shields.io/badge/Status-En%20D%C3%A9veloppement-yellow.svg )]()

## Table des Matières
1. [Description du Projet](#description-du-projet)
2. [✨ Fonctionnalités Clés](#-fonctionnalités-clés)
3. [Technologies Utilisées](#technologies-utilisées)
4. [Architecture du Projet](#architecture-du-projet)
5. [Installation et Démarrage](#installation-et-démarrage)
6. [Aperçu (Screenshots)](#aperçu-screenshots)
7. [Contribution](#contribution)
8. [📄 Licence](#-licence)

---

## Description du Projet

**Korean Island** est une application mobile Android dédiée à l'apprentissage du coréen. Notre objectif est de rendre l'acquisition de cette langue accessible, **interactive et motivante** pour la communauté francophone.

L'application propose un parcours complet, allant de l'apprentissage du vocabulaire de base et du Hangeul à la maîtrise de la prononciation avancée et des structures grammaticales. L'utilisateur évolue dans un **univers gamifié** inspiré de la culture coréenne, débloquant des niveaux et des récompenses pour un suivi de progression intuitif.

## ✨ Fonctionnalités Clés

| Catégorie | Fonctionnalité | Description |
| :--- | :--- | :--- |
| **Apprentissage** | Parcours Immersif | Zones thématiques inspirées de la culture coréenne, avec défis et leçons adaptées au niveau. |
| | Leçons Modulaires | Modules progressifs couvrant le vocabulaire, la grammaire et la prononciation. |
| **Pratique** | Exercices Interactifs | QCM, associations de mots et mini-jeux pour une mémorisation active. |
| | Évaluation Continue | Tests réguliers pour valider les connaissances et débloquer le contenu suivant. |
| **Motivation** | Gamification | Accumulation de points, badges et récompenses pour maintenir l'engagement. |
| | Suivi Personnalisé | Profil utilisateur avec statistiques, leçons terminées et badges obtenus. |
| **Culture** | Contenus Culturels | Articles et vidéos pour enrichir l'expérience d'apprentissage avec l'histoire et les traditions coréennes. |

## Technologies Utilisées

| Composant | Technologie | Version / Note |
| :--- | :--- | :--- |
| **Plateforme** | Android | SDK 34 (Min SDK 21) |
| **Langage** | Java | JDK 1.8 |
| **Base de Données** | Room | Couche d'abstraction SQLite pour la persistance locale. |
| **Interface Utilisateur** | Material Design | Composants AndroidX pour une UI moderne et cohérente. |
| **Build** | Gradle | Système de construction standard pour Android. |

## Architecture du Projet

Le projet suit une architecture modulaire, favorisant la séparation des préoccupations (SoC) et facilitant l'évolution. La structure est conçue pour une transition potentielle vers des architectures plus modernes comme **MVVM (Model-View-ViewModel)**.

## Installation et Démarrage

Ces instructions vous guideront pour obtenir une copie du projet et le faire fonctionner sur votre machine locale à des fins de développement et de test.

### Prérequis

*   **Android Studio** (version stable recommandée)
*   **JDK 1.8** ou supérieur

### Étapes de Démarrage

1.  **Cloner le dépôt :**
    ```bash
    git clone [URL_DU_DEPOT]
    cd KoreanIsland
    ```

2.  **Ouvrir dans Android Studio :**
    *   Lancez Android Studio.
    *   Sélectionnez `File > Open` et naviguez jusqu'au dossier `KoreanIsland`.

3.  **Synchronisation Gradle :**
    *   Android Studio devrait automatiquement synchroniser le projet et télécharger toutes les dépendances nécessaires. Si ce n'est pas le cas, cliquez sur l'icône **Sync Project with Gradle Files** (éléphant).

4.  **Exécuter l'application :**
    *   Sélectionnez un émulateur ou un appareil Android connecté.
    *   Cliquez sur le bouton **Run (▶)** pour compiler et lancer l'application.

## Aperçu (Screenshots)

*(Ajoutez ici vos captures d’écran pour présenter l'application : écran d’accueil, leçons interactives, carte des îles, profil utilisateur.)*

## Contribution

Nous accueillons avec plaisir toutes les contributions ! Si vous souhaitez améliorer **Korean Island**, veuillez suivre les étapes ci-dessous :

1.  **Fork** du projet.
2.  Créez une nouvelle branche pour votre fonctionnalité ou correction :
    ```bash
    git checkout -b feature/nom-de-votre-fonctionnalite
    ```
3.  Committez vos changements avec un message clair (respectez la convention **Conventional Commits** si possible) :
    ```bash
    git commit -m "feat: Ajout de la fonctionnalité X"
    ```
4.  Poussez la branche vers votre Fork :
    ```bash
    git push origin feature/nom-de-votre-fonctionnalite
    ```
5.  Ouvrez une **Pull Request** vers la branche `main` du dépôt original pour révision.

## 📄 Licence

Ce projet est distribué sous la **Licence MIT**. Pour plus de détails, consultez le fichier `LICENSE` à la racine du dépôt.

---

**Développé avec 💖 pour l'apprentissage du Coréen.**
