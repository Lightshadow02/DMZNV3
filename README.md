# 🛡️ Mise en place d'une DMZ à différents niveaux 🛡️

Ce projet a pour objectif de créer une DMZ (zone démilitarisée) à plusieurs niveaux afin de sécuriser les différents segments du réseau. Il inclut la configuration de pare-feux avec Pfsense et l'intégration de serveurs dans un environnement virtualisé via Proxmox.

## 📑 Table des matières 📑

- [Aperçu du Projet](#-aperçu-du-projet)
- [Fonctionnalités Principales](#-fonctionnalités-principales)
- [Technologies Utilisées](#-technologies-utilisées)
- [Configuration](#-configuration)
- [Problèmes Rencontrés et Solutions](#-problèmes-rencontrés-et-solutions)
- [Remerciements](#-remerciements)

## 🔍 Aperçu du Projet 🔍

Le projet s'articule autour de plusieurs étapes pour la mise en place d'une DMZ à plusieurs niveaux :

1. **Ajout dans Proxmox** : Création de nouvelles machines virtuelles et configuration de leurs interfaces réseau.
2. **Paramétrage des pare-feux** : Attribution des adresses IP et configuration des règles de sécurité.
3. **Configuration Pfsense** : Gestion des règles NAT et désactivation de certaines fonctionnalités par défaut pour renforcer la sécurité.
4. **Accès Web sécurisé** : Installation d'un serveur Apache2 avec redirection de trafic pour sécuriser l'accès aux ressources.

## 🌟 Fonctionnalités Principales 🌟

- **DMZ multi-niveaux** : Séparation des différents niveaux de sécurité pour une meilleure protection des ressources.
- **Gestion des pare-feux avec Pfsense** : Contrôle des accès réseau et protection des segments.
- **Hébergement sécurisé avec Apache2** : Configuration du serveur web Apache2 pour une gestion sécurisée du trafic.

## 🛠️ Technologies Utilisées 🛠️

- **Proxmox** : Plateforme de virtualisation pour héberger et gérer les machines virtuelles.
- **Pfsense** : Pare-feu open-source pour segmenter le réseau et contrôler les accès.
- **Apache2** : Serveur web pour héberger les services accessibles via la DMZ.

## ⚙️ Configuration ⚙️

- **Pfsense** : Configuration des interfaces WAN et LAN, avec désactivation de certains protocoles et mise en place de règles NAT.
- **Apache2** : Paramétrage des redirections de trafic et configuration du serveur pour l'accès sécurisé aux ressources.

## 🔧 Problèmes Rencontrés et Solutions 🔧

Des défis liés à la configuration des pare-feux et aux contraintes réseau ont été résolus en ajustant les règles de sécurité et en optimisant les paramètres de chaque segment de la DMZ.

## 🙏 Remerciements 🙏

Merci à mes enseignants et collègues du lycée Pergaud pour leur soutien et leurs conseils dans la réalisation de ce projet.



![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/PfSense_logo.png/799px-PfSense_logo.png)
        
