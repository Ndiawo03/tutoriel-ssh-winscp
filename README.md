
Tutoriel SSH + WinSCP


1. Installation du serveur SSH sur Ubuntu

"sudo apt update
 sudo apt install openssh-server
 sudo systemctl status ssh"

Le service doit afficher active (running).

2. Connexion au réseau local

Utilise la commande suivante pour obtenir l’adresse IP de ta VM :

"ip a"

Note l’adresse IP affichée (exemple : 192.168.1.50)

3. Connexion avec WinSCP depuis Windows

Télécharger WinSCP : https://winscp.net

Ouvrir l'application

Choisir le protocole SFTP

Hôte : adresse IP de la VM Ubuntu

Identifiant : nom d’utilisateur Ubuntu

Mot de passe : mot de passe Ubuntu

4. Transfert de fichiers

Transfert de Windows vers Ubuntu :

Glisser un fichier du panneau gauche vers la droite

Transfert de Ubuntu vers Windows :

Glisser un fichier du panneau droit vers la gauche

5. Captures à inclure dans le rapport

Affichage de systemctl status ssh

Affichage de l’adresse IP de la VM (commande ip a)

Interface WinSCP avec connexion réussie

Exemple de transfert de fichier effectué

6. Résultat final

Ce tutoriel montre comment :

Installer et vérifier un serveur SSH

Se connecter à distance avec WinSCP

Effectuer des transferts de fichiers sécurisés entre deux systèmes
