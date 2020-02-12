SEMAINE 7
=========

MERCREDI 12 FEVRIER 2020
------------------------

**DE 9 H A 12 H 30**


- Feuille de route :
	- Bootcamp : Python, type de données, instructions, fonctions, structures conditionnelles, itératives / Update Read The Doc -Section Python (4 groupes  + Python pm Hachem)
 	- Bootcamp : SQL, requêtes simples
	-


- GitHub : push "Semaine_7.md" : OK

- Etude **MANAGEO**




MARDI 11 FEVRIER 2020
---------------------



- ATELIER : Recherche de stage avec Cécile.

- Tentatives de connection sur Simplonline : NOK
  Adresse mail sur Discord : amaria.boualam@gmail.com
  Adresse mail sur Simpblonline : amaria.boualam.data@gmail.com


**DE 13 H 30 A 17 H 30**

- Cours : les fonctions d'agrégation

- Mise en pratique :

Afficher le nb de films dans lesquels a jouer "Johnny LOLLOBRIGIDA" regroupé par catégorie.

_________________________________________________________________________________________________________________________________________________________

LUNDI 10 FEVRIER 2020
---------------------

**DE 9 H A 12 H 30**


- **Sebastien BORIES** cma/cgm Développeur data

Il existe 4 environnements : La Dev, les UAT, la pré-prod et la prod. Pour les UAT, il s'agit de quelques utilisateurs chargés de tester les nouvelles procédures, qu'ils testeront ensuite en pré-prod. A la fin, les nouveautés seront introduites en Prod.

- Prévention d'approvisionnement financier grâce à toutes les infos dispo (==> estimation de la facture)

- Les sgbd : 
	stockage :	
			- Modéliser un métier
			- stocker des données de façon typée et structurée
			- Gérer les écritures multiples et concurrentes

	Intégrité :	
			- garantir la qualité des données
			- garantir l'application de rèbles métiers

	Restitution : 
			- Récupérer et afficher des données sous une forme souhaitée
			- arantir la justesse des données renvoyées

- Les principaux objets: 
			les tables
			les contraintes (clés primaires, clés étrangères, contraintes perso)
			les vues et vues matériélisées ==> tables
			les index (ordonnés en arbres ==> tables index)
			les triggers (et séquences): pour créer des id 
			les packages (procédures stockées : fonctions stockées) regroupés selon un domaine fonctionnel
			les types : on peut créer ses propres types (autres que chaîne,...=
			les db links (database link) requêtes pour joindre des tables distantes, sur des serveurs différents.

- Le SQL (langage de 4ème génération) mais n'est pas un langage objet

C'est un **langage serveur**.
Il permet de manipuler des objets BD avec ds prédicats (égalités, inégalités), des opératures logiques et math

de manipuler de lois ensemblistes 'union, intersection, différence, produit cartésien)

d'agreger les données
de transformer des données (règles conditionnelles, pivots, opérations mathématiques)


- Les jointures : 

- La requête SELECT

C'est une boucle, avec des projections conditionnées (CASE WHEN)
On peut faire du SELECT FROM SELCTE (sous-requêtes)(bloc with)
Le tri (ORDER BY)

- Les fonctions d'agrégation

La somme (SUM)
Les moyennes (AVG)
Le minimum (MIN)
Le maximum (MAX)
La Concaténation


Une fonction d'agrégation oblige toujours à utilier le regroupement (GROUP BY)

Prédicats sur le résultat d'agrégation (HAVING)

Attention aux doublons !

- **Bonnes pratiques** :

Ecrire les requêtes en colonnes

Indenter chaque sous-requêtes

Utiliser les alias

WHERE 1+1 Pourquoi faire ?


- ORACLE **(Oracle Xe gratuit tant que ce n'est pas commercial)**

le fenêtrage (windowing)

optimisation et plan d'exécution

Data statistics

Les "Hint" spécifique à Oracle. Ca ressemble à un commentaire, + et des mots clés /*+......*/ pour orienter le moteur sql ==> optimisation

Le cache serveur

Les langages SGBD (**PL/SQL**)

Les métadonnées : rajouter une colonne sur toutes les tables après les avoir interrogé

Schedulers / jobs ==> tâches planifiées. Ex : maj journalière

**DE 13 H 30 A 17 H 30**


- ATELIER SUR LA BD sakila
https://datamastery.gitlab.io/exercises/sakila-queries.html
https://github.com/adesai25/MySQL-Exercises-with-Sakila-DB-/commit/6dd87581b1b26c544eb203cfb1b04aaafa0d0159
https://github.com/sschadt/sakila/commit/615a05ab9c3625ecff8aada5ea80c2333d1adca8
https://www.w3resource.com/sql-exercises/movie-database-exercise/joins-exercises-on-movie-database.php



**Donner la liste des acteurs qui ont joué dans 19 films.**


**L'acteur que l'on trouve dans le plus de film ?**


**les films qui n'ont jamais été loués ?**


