# InterfaceRobotExplorateur

![Angular](https://img.shields.io/badge/built%20with-Angular-red)
![Status](https://img.shields.io/badge/status-terminé-green)

Interface Angular pour le contrôle d’un **robot explorateur autonome** dans le cadre du projet fil rouge de 1ère année à UPSSITECH (2023–2025).

Le robot doit :
- cartographier son environnement,
- comprendre des commandes vocales,
- suivre des balles colorées,
- être contrôlable manuellement depuis l’interface.

## ✨ Fonctionnalités principales

- ▪ Mode **Cartographie** : affichage temps réel des points détectés par le Lidar.
- ▪ Mode **Commande vocale** : enregistrement audio → envoi au backend Flask → interprétation → commande envoyée au robot.
- ▪ Mode **Pilotage manuel** : boutons de direction + retour vidéo en direct.
- ▪ Mode **Suivi de balle** : détection visuelle + choix dynamique de la couleur à suivre.

## 🔧 Stack technique

- **Frontend** : Angular v17.3.3
- **Backend (non inclus dans ce repo)** : Flask (Python)
- **Robot** : Raspberry Pi + Arduino

## 🎓 Ce que j’ai appris

- Développement Angular (modules, composants, routing).
- Communication avec un backend Flask via HTTP/REST.
- Intégration de retours capteurs (caméra, Lidar).

## ⚡ Statut

Projet **terminé** (2024). Utilisé lors de démonstrations pour valider les compétences transverses du projet.

## ⚙️ Lancer le projet en local

1. Cloner le repo :
   ```bash
   git clone https://github.com/Bebel19/interface_robot_explorateur.git
   cd interface_robot_explorateur
   ```

2. Installer les dépendances :
   ```bash
   npm install
   ```

3. Lancer le serveur de développement :
   ```bash
   ng serve
   ```
   Accéder à [http://localhost:4200](http://localhost:4200)

## 🎨 Demo

![Aperçu du robot explorateur](https://github.com/Bebel19/interface_robot_explorateur/blob/main/assets/image/robot_explorateur_demo.gif)



---

**Projet universitaire ✨** — UPSSITECH Toulouse
