Base de données Topographiques du sytème karstique de l'Aulp du Seuil (Isère, 38, France)
===============================================================================================

Overview
--------

Ce dépôt contient les données topographiques et les dessins associés des cavités du massif karstique de l'Aulp du Seuil (Isère, 38, France). 
Elles ont été majoritairement produites par les spéléologues du Spéléo club de Vienne, du Spéléo club de Savoie, du Groupe Catamaran, des Furets Jaunes de Seyssins, du Cave diving group et University of Leeds Speleological Association (Guiers vif 91/92) et du Spéléo club des Comminges (Trou des flammes 2004/2006).

Aujourd'hui ces différents explorateurs se rassembent sous le nom de _Collectif de l'Aulp du Seuil_ afin de mutualiser l'energie et les explorations.

Ce dépôt est mis à jour à chaque fois qu'une nouvelle topographie est rajoutée au système décrit dans cette base de données.

Description
-----------

Ce dépôt sauvegarde les données topographiques et de dessin. Ces fichiers sont pour le logiciel Therion (data + dessins).

Uniquement les fichiers sources sont sauvegardés pour des raisons de taille, bien que certians pdf puissent être présents à des fin de travail.
	
	* .thc, .th, .th2 et .thconfig pour le logiciel Therion
    * .zip pour les exports des séances topo de l'appli Topodroid
	
Pour obtenir les topographies en plan, coupe et/ou 3D, il faut compiler les fichiers Therion.

Il est possible de produire un export à l'échelle du massif ou bien de chaque cavité.


Travail sous Therion
-----------

Une convention a été mise en place pour la gestion des points d'interrogation, et donc des différents départs possibles, avec la définition de différents champs.
S'utilise de la façon suivante dans Therion, pour le point "Continuation" : 
    
    -attr Code "" -attr cavite "" -attr Reseau "" -attr CA "" -text ""

	* le champ "Code" qui décrit le type de terminus. Il peut prendre les valeurs : 
	
		* A : il suffit d'y aller et de continuer, pas d'obstacles
		
		* D1 : Désobstruction de petite ampleur, 

        * D2 : Désobstruction de moyenne ampleur,
		
		* E : Escalade nécessaire, 
		
		* P : Puits non descendu,
		
		* Q : non renseigné sur la topographie, c'est à voir/vérifier,
		
		* S : Siphon à plonger, 
		
		* T : Trémie à désobstruer
	
	* le champ "Cavite" qui donne le nom de la cavité en question,
	
	* le champ "Reseau" qui indique la partie de la cavité où se situe le point d'interrogation (pour pouvoir le retrouver plus rapidement sur les topographies),
	
	* le champ "CA" qui est rempli si présence de courant d'air, avec éventuellement des remarques/commentaires. Il est facultatif.

Licence
-------

L'ensemble de ces données est publié sous la licence libre Creative Commons Attribution-ShareAlike-NonCommercial (Attribution, partage à l'identique et non commerciale) :
	http://creativecommons.org/licenses/by-nc-sa/4.0/

Auteurs de la base de donnée 
-------

L'élaboration et la mise à jour de cette synthèse topographique sous Therion est le fruit d'un travail de : 

_Vincent Franzi ; Xavier Robert ; David Parot ; Théophile Cailhol ; Martin Kern_ (2026)


Contact
-------

Contacter l'auteur du dépot Git ou aulpduseuilsouterrainAROBASEgmailPOINTcom
