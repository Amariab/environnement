SEMAINE 8
=========






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

