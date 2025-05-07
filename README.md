# PPE-GLPI – Projet de Gestion des Interventions Informatiques

## 📌 Introduction

Le projet **PPE-GLPI** (Projet Personnel Encadré) est un système de gestion d'interventions techniques inspiré de l'outil GLPI. Il permet à une entreprise de gérer efficacement ses demandes d’interventions informatiques, les techniciens, les clients, les téléphones achetés, ainsi que les rapports d’interventions.

Ce projet a été réalisé dans le cadre d’un stage ou d’un projet académique, avec pour objectif la numérisation et l’optimisation de la gestion des événements et des interventions.

---

## 🚀 Fonctionnalités principales

- 🔐 **Authentification des utilisateurs**
  - Connexion sécurisée avec rôles (administrateur, technicien)
- 👤 **Gestion des clients**
  - Ajouter, modifier, supprimer, et consulter les fiches clients
- 🔧 **Gestion des techniciens**
  - Enregistrement, modification, et suppression des techniciens
- 📱 **Suivi des téléphones**
  - Association des téléphones achetés aux clients
- 🛠️ **Gestion des interventions**
  - Création, consultation et suivi des interventions
- 📊 **Statistiques et rapports**
  - Affichage des interventions en fonction de critères variés

---

## 🧰 Technologies utilisées

- **PHP** (POO avec PDO)
- **MySQL**
- **HTML5 / CSS3**
- **Bootstrap** (template QuickStart)
- **JavaScript (basique)**

---

## 🗂️ Arborescence du projet

```
/PPE-GLPI
├── index.php
├── /controleur
│   └── controleur.php
├── /modele
│   └── *.php (fichiers de modèle pour chaque entité)
├── /vue
│   ├── header.php
│   ├── footer.php
│   ├── page_connexion.php
│   ├── page_accueil.php
│   └── autres vues...
├── /css
│   └── style.css
└── /js
    └── script.js
```

---

## 🛠️ Installation et utilisation

### Prérequis

- Serveur Apache (ex: XAMPP, WAMP, Laragon)
- PHP ≥ 7.4
- MySQL

### Étapes d’installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/nom-utilisateur/PPE-GLPI.git
   ```
2. Copier le projet dans le dossier `htdocs` (si XAMPP).
3. Créer une base de données MySQL nommée `ppe_glpi`.
4. Importer le fichier SQL fourni dans la base de données.
5. Modifier les identifiants de connexion à la base de données dans le fichier `modele/connexion.php`.
6. Lancer le serveur Apache/MySQL.
7. Accéder au projet via `http://localhost/PPE-GLPI`.

---

## 🔐 Comptes de test

- **Administrateur**
  - Email : admin@glpi.fr
  - Mot de passe : admin123

- **Technicien**
  - Email : tech@glpi.fr
  - Mot de passe : tech123

---

## 🧪 Tests & Scénarios

- Connexion avec différents rôles
- Ajout d’un client et consultation
- Création d’un téléphone pour un client
- Saisie d’une intervention et affectation à un technicien
- Affichage des rapports dans la vue gestion

---

## 🔧 Maintenance et évolutivité

Le projet est conçu de manière modulaire :

- Il est facile d’ajouter de nouvelles entités (ex : matériel, tickets)
- Les vues et modèles sont séparés pour faciliter la maintenance
- L’interface peut être enrichie avec JavaScript pour plus de dynamisme
- Possibilité de migrer vers un framework (ex : Laravel) pour une version avancée

---

## 📄 Auteur

Projet réalisé par **Truong Son Vu**  
Dans le cadre de : **BTS SIO / BUT Informatique / Licence Pro**  
Année : **2024-2025**

---

## ✅ Licence

Ce projet est un exemple éducatif. Il peut être réutilisé et modifié dans le cadre d’un usage académique ou personnel.
