SEMAINE 8
=========

VENDREDI 21 FEVRIER 2020
------------------------

**DE 9 H A 12 H 30**

- Feuille de route :
 	- Bootcamp : SQL, requêtes simples , filtres, fonctions, jointures, / Update Read The Doc (gr +sql pm : Ludovic)
	- Workshop : Manageo / Demande client, roadmap (3 p : Xavier, pm, Inès, Romain) / présentation, update note de cadrage : intrviews client (Yoann, pm, Ludovic, Djoumbé à 10 H : OK ==> Echanges par mail pour faire évoluer le projet ==> livrable : Google sheets, questionnaire/ Audit tech (Yacine, pmm, Hachem, Joshua) , livrable : Google sheets, questionnnaire
	- Veille: rgpd (Sabine, Sacha)  / Flask (Joshua, Lofti)  / Scrum (Inès, Romain)
	
- https://www.europeandataportal.eu/elearning/fr/module9/#/id/co-01

- Recherche de stages avec S

- Ltr de motivation générale envoyée à Sabine pour le mettre sur un tableau

**DE 13 H 30 A 15 H**

Envoi de demandes de stages via Internet ou par email : OK


JEUDI 20 FEVRIER 2020
---------------------

**DE 9 H A 12 H 30**

- Feuille de route :
 	- Bootcamp : SQL, requêtes simples , filtres, fonctions, jointures, / Update Read The Doc (gr +sql pm : Ludovic)
	- Workshop : Manageo / Demande client, roadmap (3 p : Xavier, pm, Inès, Romain) / présentation, update note de cadrage : intrviews client (Yoann, pm, Ludovic, Djoumbé à 10 H : OK ==> Echanges par mail pour faire évoluer le projet.oumbé) livrable : Google sheets, questionnaire/ Audit tech (Yacine, pmm, Hachem, Joshua) , livrable : Google sheets, questionnnaire
	- Veille: rgpd (Sabine, Sacha)  / Flask (Joshua, Lofti)  / Scrum (Inès, Romain)
	- Events : CSV jeudi 27/02 (Amaria et Xavier )/ Présentation des slides / mail Manageo

**DE 13 H 30 A 17 H 30**

- Préparation du meetup du jeudi 27/02 avec Samba

- Préparation CV et LM  et recherche d'entreprises ==> Envois d'email. OK


MERCREDI 19 FEVRIER 2020
------------------------

**DE 9 H A 12 H 30**

- Feuille de route :
 	- Bootcamp : SQL, requêtes simples , filtres, fonctions, jointures, / Update Read The Doc (gr +sql pm : Ludovic)
	- Workshop : Manageo / Demande client, roadmap (3 p : Xavier, pm, Inès, Romain) / présentation, update note de cadrage : inerviews client (Yoann, pm, Ludovic, DjCall à 10 H : OK ==> Echanges par mail pour faire évoluer le projet.oumbé) livrable : Google sheets, questionnaire/ Audit tech (Yacine, pmm, Hachem, Joshua) , livrable : Google sheets, questionnnaire
	- Veille: rgpd (Sabine, Sacha)  / Flask (Joshua, Lofti)  / Scrum (Inès, Romain)
	- Events : CSV jeudi 19/02 (Amaria)/ Présentation des slides

**DE 13 H 30 A 17 H 30**

- Bootcamp sur sql et python

- Préparation du meetup sur le fichier csv avec Samba



MARDI 18 FEVRIER 2020
---------------------

**DE 9 H A 12 H 30**

**DE 13 H 30 A 17 H 30**

- Evaluation de Rafik

from re import sub

Elus ='                                                                                                                                        '
Elus+='code (insee)    mode de scrutin    numliste    code (nuance de la liste)    numéro du candidat dans la liste    tour    nom    prénom    sexe    Date de naissance    code (profession)    libellé profession    nationalité'

def rnames(Elus):
    x=Elus.replace(' ','')
    x1=sub('[é,è]','e',x)
    x2=sub('[(,)]','',x1)
    x3=x2.split() # le x3 est le resultat des noms de colonnes en liste
    #x4='\n'.join(x3) # j'ai fait un join pour avoir un resultat propre
    return x3
print(r_names(Elus))


LUNDI 17 FEVRIER 2020
---------------------

**DE 9 H A 12 H 30**
**DE 13 H 30 A 17 H 30**

- Evaluation de Rafik

	* file:///home/utilisateur/Documents/PROJETS/Evaluation_170220/Projet_-_examen.pdf

	* PYTHON :
		- 1. Ecrire une fonction python r_names() qui admet pour entrer une de ces chaînes de caractères et qui retourne une liste de nom de colonnes 			Les espaces, les « ‘ » et les « . » doivent être remplacé par des « _ ».
		Les « é » et « è » doivent être remplacé par des « e ».
		Les « , », « ) » et « ( » doivent être supprimées.

