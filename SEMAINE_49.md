# MARDI 3 DECEMBRE 2019

## 9 H A 12 H 30



### STAND A LA CITE DES METIERS DE MARSEILLLE

Il s'agissait de présenter la formation Dev Data et d'animer des ateliers sur Python avec des exemples (les librairies Plotlib, FETECADO) + les commandes sur Linux.

## 13 H 30 A 17 H 30

### PROBLEMATIQUE WORKBENCH

Après la résolution du problème avec MySql, j'ai réinstallé Workbench mais le problème est revenu.
Problème accès à MySQL, essayer :
  sudo service mysql stop
  sudo mkdir -p /var/run/mysqld
  sudo chown mysql:mysql /var/run/mysqld
  sudo /usr/sbin/mysqld --skip-grant-tables --skip-networking &

#### DESINSTALLATION ET REINSTALLATION DE MYSQL
https://replay-sdk.com/2017/03/comment-desinstaller-completement-mysql-sur-linux-ubuntu-16-04-pour-le-reinstaller-de-zero/

Désinstallation complète (remove –purge)
sudo apt-get remove --purge mysql-server mysql-client mysql-common
sudo apt-get autoremove
sudo apt-get autoclean

Vérification des fichiers de données – et effacement si nécessaire
ls /var/lib/mysql
rm -rf /var/lib/mysql

Réinstallation
sudo apt-get install mysql-server
Réinstallation de Workbench


1ERE METHODE
sudo mysql -u root -p 
mysql: USE MySQL;
SELECT User, Host, plugin FROM mysql.user;
mysql: UPDATE user SET plugin='mysql_native_password' WHERE User='root';
mysql: FLUSH PRIVILEGES;
mysql: exit;
$ service mysql restart
Le plugin reste "auth_socket" et ne devient pas : "mysql_native_password"

2EME METHODE : (replace YOUR_SYSTEM_USER with the username you have)
$ sudo mysql -u root # I had to use "sudo" since is new installation
mysql> USE mysql;
mysql> CREATE USER 'ROOT2'@'localhost' IDENTIFIED BY '';
mysql> GRANT ALL PRIVILEGES ON *.* TO 'ROOT2'@'localhost';
mysql> UPDATE user SET plugin='auth_socket' WHERE User='ROOT2';
mysql> FLUSH PRIVILEGES;
mysql> exit;
$ service mysql restart

15 H 25
Connection OK avec ROOT2

### INSTALLATION DE VISUAL STUDIO

https://linuxize.com/post/how-to-install-visual-studio-code-on-ubuntu-18-04/
test d'ouverture sur le terminal : code : A

### PRISE EN MAIN DE WORKBENCH
https://www.youtube.com/watch?v=pZKrznZymMg&t=135s

SCHEMA ET DATABASE : Un schéma est une unité logique de placement des objets de la base. Une base peut comporter autant de schéma qu'on le souhaite. Il existe toujours un schéma par défaut. Celui de la base, comme celui de l'utilisateur SQL.
Le seul SGBDR a ne pas se conformer à la notion de schéma est MySQL.


#### LES FCT

##### LES FCT RECURSIVES
Elles s'appellent elles-mêmes 
Avantage : elles font des boucles.


# LUNDI 2 DECEMBRE 2019

## 9 H A 12 H 30

### OBJECTIF

#### LE MODELE RELATIONNEL DES DONNEES

	* Remémoration de ce qui a été fait la semaine dernière : Explications à partir des pdf de Rafik
	* Le modèle relationnel des données
	* Recherche d'infos sur le MRD

		* Les dépendabces fonctionnelles : 
https://www.youtube.com/watch?v=R0QOca7OQS0
Ce sont des relations entre les propriétés.

Propriété B d'une entité E2 dépend fonctionnellemen d'une ou plusieurs propriétés A d'une autre entité E1
Si chaque valeur de A détermine une et une valeur de B

Ex : 
N° d'immatriculation 
la marque d'un véhicule 
N0 détermine la marque

Ex : 
ID
Client
ID client


		* Identifiant :
		* Matrice des dépendances fonctionnellles :
		* les relations :
		* Les formes normales :

## 13 H 30 A 17 H 30

### SUITE DE L'EXERCICE

Exercice de l'exo : l'entrepreneur en informatique 

Exercie de l'exo : les fédérations de sport


