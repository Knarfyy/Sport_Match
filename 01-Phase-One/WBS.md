# 🗺️ Structure de Décomposition du Travail (WBS) - Phase 1

## 1. Application Mobile (Front-End)
Ceci couvre tous les éléments visibles et interactifs de l'application, pensés pour le mobile.

### 1.1. Profil Utilisateur & Compte
* 1.1.1. Création / Connexion / Déconnexion (Auth JWT)
* 1.1.2. Affichage et Modification du Profil (Niveaux sportifs, préférences)
* 1.1.3. Gestion des Partenaires Réguliers

### 1.2. Gestion des Activités Sportives
* 1.2.1. Création d'une Nouvelle Activité (Sport, Lieu, Horaire, Niveau)
* 1.2.2. Recherche et Filtrage d'Activités Existantes (Proximité, Niveau)
* 1.2.3. Demande de Participation à une Activité

## 2. Infrastructure Back-End & Services (API)
Ceci représente le cœur du système, garantissant la logique, la sécurité et la qualité des données.

### 2.1. Architecture de Base
* 2.1.1. Mise en place de l'API (Java/Spring Boot)
* 2.1.2. Base de Données (PostgreSQL) et Modèle de Données
* 2.1.3. Sécurité de la Communication (HTTPS)

### 2.2. Services d'Authentification & Autorisation
* 2.2.1. Implémentation du token JWT
* 2.2.2. Gestion des Droits (Organisateur vs. Participant)

### 2.3. Algorithme de Matching
* 2.3.1. Logique de Compatibilité (Niveau, Localisation, Affinité)
* 2.3.2. Gestion de la Géolocalisation

## 3. Qualité, Gestion & Conformité
Ceci couvre les aspects non-fonctionnels, pédagogiques et de gestion de projet.

### 3.1. Démarche Qualité & CI/CD
* 3.1.1. Définition des Standards de Codage
* 3.1.2. Stratégie de Tests (Unitaires et Intégration)
* 3.1.3. Mise en place d'une chaîne CI/CD légère

### 3.2. Protection des Données & Éthique
* 3.2.1. Gestion de la Confidentialité (RGPD)
* 3.2.2. Code de Conduite (Non-Dating App, Anti-Harcèlement)

### 3.3. Gestion de Projet
* 3.3.1. Définition des Rôles (Front, Back, Data, PM)
* 3.3.2. Choix de la Méthodologie (Agile-ish, Sprints)
