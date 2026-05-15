# InterfaceRobotExplorateur - Projet Fil Rouge 1A SRI 2023/2024

Français | [English](README.md)

![Angular](https://img.shields.io/badge/built%20with-Angular-red)
![Status](https://img.shields.io/badge/status-terminé-green)

Interface Angular pour le contrôle d’un **robot explorateur autonome** dans le cadre du projet fil rouge de 1ère année à UPSSITECH (2023–2025).

Le robot doit :
- cartographier son environnement,
- comprendre des commandes vocales,
- suivre des balles colorées,
- être contrôlable manuellement depuis l’interface.

## Fonctionnalités principales

- Mode **Cartographie** : affichage temps réel des points détectés par le Lidar.
- Mode **Commande vocale** : enregistrement audio → envoi au backend Flask → interprétation → commande envoyée au robot.
- Mode **Pilotage manuel** : boutons de direction + retour vidéo en direct.
- Mode **Suivi de balle** : détection visuelle + choix dynamique de la couleur à suivre.

## Stack technique

- **Frontend** : Angular v17.3.3
- **Backend ([dans ce repo](https://github.com/MaelaViguier/mobile_robot_backend))** : Flask (Python)
- **Robot** : Raspberry Pi + Arduino

## Ce que j’ai appris

- Développement Angular (modules, composants, routing).
- Communication avec un backend Flask via HTTP/REST.
- Intégration de retours capteurs (caméra, Lidar).

## Statut

Projet **terminé** (2024). Utilisé lors de démonstrations pour valider les compétences transverses du projet.
Ce projet a été utilisé comme plateforme de développement lors du **[HackaTAL 2024](https://hackatal.github.io/2024/)**, un hackathon autour du TAL et des IA génératives appliquées à la conversion audio en commandes.

## Lancer le projet en local

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

## Demo

<div align="center">
  <img src="https://github.com/Bebel19/interface_robot_explorateur/blob/master/src/assets/image/20240512_195038.jpg?raw=true" alt="Robot explorateur" width="400"/>
  <br/>
  <img src="https://github.com/Bebel19/interface_robot_explorateur/blob/master/src/assets/video/robot_explorateur.gif?raw=true" alt="Robot explorateur GIF" width="800"/>
</div>




---

**Projet universitaire** — UPSSITECH Toulouse
