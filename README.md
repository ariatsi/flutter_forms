# flutter_forms

# TP Flutter - Application de Connexion avec Formulaire

Ce projet Flutter propose une application de connexion avec validation des champs, navigation conditionnelle et affichage des informations de l'utilisateur connecté.

## 🎯 Objectifs

- Créer une interface de connexion avec validation des champs email et mot de passe.
- Valider les identifiants à partir d'une base locale (Map).
- Naviguer vers une page de profil après une connexion réussie.
- Gérer la déconnexion pour revenir à l'écran de login.
- Structurer le code en plusieurs fichiers pour une meilleure lisibilité.

## 📁 Structure du Projet

- `main.dart` : Écran principal contenant l'écran de login.
- `screens/profile_screen.dart` : Écran du profil utilisateur.
- `widgets/` : Conteneur suggéré pour les composants réutilisables (non utilisé ici mais recommandé pour évoluer).

## ✨ Fonctionnalités

- Formulaire de connexion avec validation :
    - Email valide requis.
    - Mot de passe d'au moins 6 caractères.
- Authentification simulée avec une Map en mémoire.
- Navigation conditionnelle vers une page de profil.
- Données du profil affichées de manière structurée.
- Déconnexion avec retour à l'écran de connexion.

## ✅ Identifiants de Test

| Email               | Mot de passe | Prénom | Nom  | Rôle  |
|--------------------|--------------|--------|------|-------|
| user@example.com   | userpass     | Jane   | Doe  | User  |
| admin@example.com  | adminpass    | Admin  | User | Admin |

## 🛠️ Lancer le Projet

1. Ouvrir Android Studio.
2. Créer un projet Flutter nommé `login_app`.
3. Copier les fichiers `main.dart` et `profile_screen.dart` dans le répertoire `lib/`.
4. Exécuter l'application sur un simulateur ou un appareil physique.

## 🔐 Bonnes Pratiques

- Ne jamais stocker les mots de passe en clair en production.
- Séparer les écrans dans des fichiers distincts pour faciliter la maintenance.
- Ajouter des `CircularProgressIndicator` pour améliorer l'expérience utilisateur.
- Prévoir l'adaptation aux différentes tailles d’écran.

## 📚 Crédit

TP réalisé dans le cadre du cours de Programmation Flutter — Mise à jour 06/01/2025.

---

*Happy Fluttering!*
