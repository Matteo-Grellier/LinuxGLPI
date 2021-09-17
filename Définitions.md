# Définitions

- ## SSH

SSH veut dire Secured Shell est un protocole de communication sécurisée qui permet de contrôler à distance des appareils,  
c'est un outil très utile pour pouvoir faire des copier coller ou installer des packages sur un appareil à partir d'un autre,  
ici il est utile car sur ma vm Debian je ne peut pas faire de copier coller donc j'utilise le ssh pour pour pouvoir en faire à partir d'un autre appareil.

- ## PHP  

PHP est un langage de programmation qui sert pour produire des pages Web dynamiques via un serveur HTTP, il va être utile pour l'interface web GLPI

- ## Mariadb

Mariadb est un gestionnaire de base de donnée, il nous est utile pour la création d'un GLPI, il contiendrat les données des différents utilisateurs.

pour installer MariaDB, taper les commandes `apt-get install mariadb-server` et `mysql_secure_installation`  
Repondez Y à toutes les questions  

MariaDB est installé !!!

- ## Apache2

Apache2 C'est un serveur http qui permettra d'héberger ``l'interface web GLPI``, il permet d'envoyer des contenus statiques(page HTML, CSS, Images) 

- ## FusionInventory

- ## GLPI
  
GLPI ca veut dire ``Gestionnaire Libre de Parc Informatique``, c'est une application web qui permet d'aider les entreprises dans la gestion du matériel en créant un inventaire des ressources de l'entreprise.

- ## VM

- ## CRON