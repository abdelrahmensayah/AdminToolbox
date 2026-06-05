# 🛠️ AdminToolbox - Outils Réseau & Sécurité

## 📖 Présentation
AdminToolbox est une application web centralisée de type "couteau suisse", conçue pour faciliter le quotidien des administrateurs systèmes et réseaux. Elle regroupe plusieurs utilitaires permettant d'automatiser les calculs d'infrastructure et de manipuler des données de sécurité rapidement, sans nécessiter d'installation logicielle.

Ce projet a été développé dans le cadre d'un stage technique pour répondre à un besoin d'optimisation lors des déploiements d'infrastructures.

## ✨ Fonctionnalités principales

L'outil est divisé en trois modules interactifs :

1. **Calculatrice IP & Diagnostic** - Analyse complète d'une adresse IPv4 (Classe, Type : Publique/Privée/Loopback).
   - Calcul automatique de l'adresse réseau, du broadcast, et de la plage d'hôtes utilisables selon le CIDR.
   - Conversion en notation binaire.

2. **Découpage VLSM (Variable Length Subnet Mask)**
   - Génération d'un plan d'adressage optimisé à partir d'un réseau majeur.
   - Tri automatique et allocation des sous-réseaux pour éviter le gaspillage d'adresses IP.

3. **Utilitaires de Sécurité**
   - Génération d'empreintes numériques (Hash) : MD5, SHA-256, SHA-512.
   - Encodage et décodage de chaînes de caractères en Base64.

## 💻 Technologies utilisées

- **HTML5** : Structure de l'application.
- **JavaScript (Vanilla)** : Moteur algorithmique pour les calculs réseaux et la manipulation des données.
- **Tailwind CSS** (via CDN) : Interface utilisateur responsive et moderne.
- **CryptoJS** : Bibliothèque cryptographique pour la génération des hash.
- **Vercel** : Hébergement et déploiement continu.

## 🚀 Utilisation

L'application fonctionne entièrement côté client (dans le navigateur).
- **Version en ligne :** https://calculatrice-ip.vercel.app/
- **Version locale :** Téléchargez simplement le fichier `index.html` et ouvrez-le avec n'importe quel navigateur web moderne.
