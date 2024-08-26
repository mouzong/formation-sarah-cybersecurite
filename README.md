# Programme de montée en compétences de Sarah ()

Programme de formation structuré de manière logique et chronologique pour guider un débutant en Linux à partir de zéro, en intégrant l'installation des outils nécessaires comme Git, VirtualBox, et Vagrant.



### Semaine 1 : Installation et configuration de l’environnement de travail

**Objectif : Préparer l'environnement de travail en installant les outils nécessaires pour la virtualisation, le contrôle de version, et la gestion de VM.**

1. **Installation de Git**
   - **Qu'est-ce que Git ?**
     - Introduction au contrôle de version.
   - **Installation de Git :**
     - Pour Ubuntu/Debian : `sudo apt-get install git`.
     - Pour Windows : Téléchargez et installez Git depuis le site officiel.
   - **Configuration de Git :**
     - Configurer votre nom d'utilisateur et email : 
       ```bash
       git config --global user.name "Votre Nom"
       git config --global user.email "votre.email@example.com"
       ```

2. **Installation de VirtualBox**
   - **Qu'est-ce que VirtualBox ?**
     - Introduction à la virtualisation et aux hyperviseurs.
   - **Installation de VirtualBox :**
     - Pour Ubuntu/Debian : 
       ```bash
       sudo apt-get update
       sudo apt-get install virtualbox
       ```
     - Pour Windows/Mac : Téléchargez VirtualBox depuis le site officiel et suivez les instructions d'installation.
   - **Création d'une machine virtuelle :**
     - Configurer une VM avec Ubuntu.

3. **Installation de Vagrant**
   - **Qu'est-ce que Vagrant ?**
     - Introduction à Vagrant pour la gestion des environnements virtuels.
   - **Installation de Vagrant :**
     - Pour Ubuntu/Debian :
       ```bash
       sudo apt-get install vagrant
       ```
     - Pour Windows/Mac : Téléchargez Vagrant depuis le site officiel et installez-le.
   - **Premier projet Vagrant :**
     - Initialisation d'un environnement Vagrant :
       ```bash
       vagrant init ubuntu/bionic64
       vagrant up
       ```

4. **Travaux pratiques :**
   - Vérifier le bon fonctionnement de Git, VirtualBox, et Vagrant.
   - Créer et démarrer une VM via Vagrant.

### Semaine 2 : Introduction à Linux

**Objectif : Découvrir Linux, apprendre les commandes de base, et explorer l'organisation du système.**

1. **Les bases de Linux**
   - **Qu'est-ce que Linux ?**
     - Historique et présentation des distributions populaires.
   - **Interface en ligne de commande (CLI) :**
     - Présentation du terminal.

2. **Commandes de base**
   - **Navigation dans le système de fichiers :**
     - Commandes `ls`, `cd`, `pwd`.
   - **Gestion des fichiers et répertoires :**
     - Commandes `cp`, `mv`, `rm`, `mkdir`.
   - **Consultation des fichiers :**
     - Commandes `cat`, `less`, `head`, `tail`.
   - **Permissions et utilisateurs :**
     - Commandes `chmod`, `chown`.

3. **Gestion des paquets**
   - **Utilisation d'un gestionnaire de paquets :**
     - Commandes APT (`sudo apt-get install`, `sudo apt-get update`).

4. **Travaux pratiques :**
   - Naviguer dans le système de fichiers.
   - Installer et configurer un logiciel simple comme `curl`.

### Semaine 3 : Git et GitHub

**Objectif : Apprendre à utiliser Git pour le contrôle de version et GitHub pour la collaboration en ligne.**

1. **Commandes Git de base**
   - **Initialiser un dépôt Git :**
     - Commande `git init`.
   - **Ajouter et commiter des changements :**
     - Commandes `git add`, `git commit`.
   - **Gestion des branches :**
     - Créer et fusionner des branches avec `git branch`, `git merge`.

2. **Utilisation de GitHub**
   - **Création d’un compte GitHub.**
   - **Lier un dépôt local à GitHub :**
     - Commandes `git remote add`, `git push`.
   - **Cloner un dépôt :**
     - Commande `git clone`.

3. **Travaux pratiques :**
   - Créer un projet local, le versionner avec Git, et le pousser sur GitHub.
   - Collaborer sur un projet simple en utilisant des branches et en résolvant des conflits.

### Semaine 4 : Documentation

**Objectif : Comprendre l’importance de la documentation et apprendre à la rédiger efficacement.**

1. **Lire et utiliser la documentation**
   - **Pages man :** Utilisation de `man`.
   - **Fichiers README.md sur GitHub :** Les lire et comprendre leur structure.

2. **Rédiger de la documentation**
   - **Écriture d'un fichier README :**
     - Introduction à Markdown.
   - **Documenter des commandes et scripts :**
     - Ajouter des commentaires dans le code.

3. **Travaux pratiques :**
   - Rédiger un fichier README pour un projet GitHub.
   - Documenter un script Bash ou une procédure d’installation.

### Semaine 5 et au-delà : Projets et approfondissements

**Objectif : Consolider les connaissances en réalisant des projets pratiques.**

1. **Projets pratiques**
   - **Automatisation :** Créer un script Bash pour automatiser une tâche.
   - **Site web statique :** Créer et versionner un petit site web statique.
   - **Contribuer à un projet open-source sur GitHub.**

2. **Approfondissement**
   - **Commandes Linux avancées :** Exploration de commandes plus complexes.
   - **Containerisation avec Docker :** Introduction à Docker.
   - **Outils de documentation avancés :** Utilisation de Sphinx pour Python.
