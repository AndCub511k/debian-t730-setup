# 🧱 Étape 2 – Installation de Debian via la clé bootable et configuration initiale

## 🎯 Objectif
Démarrer le HP T730 depuis la clé USB bootable et installer Debian Server avec les bons réglages de base.

---

## 🧰 Prérequis

- ✅ Clé USB bootable créée (voir [Étape 1 – Préparation de l'installation de Debian Server](https://github.com/AndCub511k/debian-t730-setup/blob/01-prep-install-debian/%C3%89tape%201%20%E2%80%93%20Pr%C3%A9paration%20de%20l'installation%20de%20Debian%20Server.md))

- ⚙️ BIOS prêt à booter sur USB (mode UEFI ou Legacy)
- 🌐 Connexion Internet disponible (Ethernet recommandé)

---

## 🖥️ Démarrage sur la clé USB

Le HP T730 a automatiquement démarré sur la clé USB, **aucun réglage dans le BIOS n’a été nécessaire**.

> ⚠️ *Remarque :* Si ce n’est pas le cas sur une autre machine :
> - Redémarrer l’ordinateur
> - Appuyer sur la touche `SUPPR` (ou `DEL`) dès l’allumage pour accéder au BIOS/UEFI
> - Vérifier ou modifier l’ordre de démarrage pour placer la **clé USB en premier**

---

## ⚙️ Installation Debian – Étapes principales

### 1. Lancement de l’installation
- Choix de la langue : `Français`
- Configuration du clavier : `Français`
- Fuseau horaire : `Europe/Paris`

### 2. Réseau
- Connexion automatique via DHCP (Ethernet)
- Nom d’hôte défini (ex: `debian-t730`)
- Optionnel : Nom de domaine (laissé vide)
- Mot de passe `root` défini (ou laissé vide pour un système avec `sudo`)
- Création d’un utilisateur standard (`ousmane` par ex.)

### 3. Disque
- Choix du disque (ex: `sda`)
- Partitionnement **automatique recommandé**
- Formatage du disque

### 4. Sélection des paquets
- ✅ Utilitaires usuels du système
- ✅ Serveur SSH
- ❌ Pas d’environnement de bureau (option décochée)

### 5. GRUB
- Installation du chargeur d’amorçage GRUB
- Choix du disque pour l’installer (ex: `/dev/sda`)
- Fin de l’installation → Retirer la clé USB → Redémarrage

---

## ✅ Résultat attendu

- Debian est installé et démarre depuis le disque dur.
- Un terminal (`tty`) s’affiche avec l’invite de connexion :
  
  ```bash
  Debian GNU/Linux 12 debian-t730 tty1

  debian-t730 login:
