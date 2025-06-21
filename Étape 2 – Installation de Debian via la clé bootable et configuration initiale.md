# Étape 2 – Installation de Debian via la clé bootable et configuration initiale

## 🎯 Objectif
Démarrer le PC depuis la clé USB bootable et installer Debian Server avec les bons réglages.

## 🧰 Prérequis
- Une clé USB bootable créée (voir Étape 1)
- Le BIOS configuré pour booter sur USB (mode UEFI ou Legacy selon le cas)
- Une connexion internet disponible (Ethernet de préférence)

## 🖥️ Étapes réalisées

1. Accéder au BIOS/UEFI :
   - Redémarrer le PC
   - Appuyer sur la touche `DEL`, `F2`, `F12`, ou `ESC` selon le constructeur

2. Modifier l’ordre de boot :
   - Mettre la clé USB en premier dans l’ordre de démarrage

3. Lancer l’installation Debian :
   - Choix de la langue, du fuseau horaire
   - Sélection du disque pour l’installation
   - Type d’installation : serveur sans interface graphique

4. Configuration réseau :
   - Configuration automatique via DHCP
   - Nom de machine (`hostname`) défini
   - Ajout du mot de passe `root` et création d’un utilisateur standard

5. Configuration du disque :
   - Partitionnement automatique (ou manuel si besoin)
   - Formatage du disque

6. Installation de GRUB :
   - Installation du chargeur d’amorçage (GRUB) sur le disque principal

## ✅ Résultat attendu

- Debian est installé et peut démarrer depuis le disque dur du PC.
- Accès à un terminal (`tty`) prêt à recevoir des commandes en tant que `root` ou utilisateur standard.

## 📝 Remarques

- Si la clé ne boote pas : vérifier qu’elle a bien été créée, et que le BIOS autorise le boot USB.
- Bien garder une sauvegarde de la configuration réseau ou de la partition si besoin.

