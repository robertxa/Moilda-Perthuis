Base de données Topographiques du système karstique Moilda - Perthuis dans le massif karstique du Bugey (01, France)
=====================================================================================================================================================

Overview
--------

Ce dépôt contient les données topographiques et les dessins associés des cavités du système Moilda - Perthuis dans le massif du Bugey (01, France). Pour l'instant, pour des raisons de choix d'accès des auteurs respectifs, seules les données produites par le club Vulcain sont accessibles en open-source. 
Pour pouvoir construire l'ensemble de la base de données topographiques, soit commenter l'appel aux cavités sans les données open-sources dans `Data/Moilda-System-Total.th` et dans `Data/Maps.th` les demander à l'auteur au cas par cas.

Ce dépôt est mis à jour à chaque fois qu'une nouvelle topographie est ajoutée à l'un des systèmes décrit dans cette base de données.

Si besoin, des templates pour Therion sont disponibles sur https://github.com/robertxa/Th-Config-Xav .

Description
-----------

Ce dépôt sauvegarde les données topographiques et de dessins. Ces fichiers sont pour les logiciels Visual Topo (données) et/ou Therion (data + dessins).

Uniquement les fichiers sources sont sauvegardés pour des raisons de taille ; j'ai aussi choisi de ne pas uploader les dessins dessinés à la main sur papier :

	* les anciens fichiers .tro pour le logiciel Visual Topo
	
	* .thc, .th, .th2 et .thconfig pour le logiciel Therion
	
Pour obtenir les topographies en plan, coupe et/ou 3D, il faut compiler les fichiers Therion.

Une convention a été mise en place pour la gestion des points d'interrogation, avec la définition de différents champs :

	* le champ "Code" qui décrit le type de terminus. Il peut prendre les valeurs : 
	
		* A : il suffit d'y aller et de continuer, pas d'obstacles
		
		* D : Désobstruction nécessaire, 
		
		* E : Escalade nécessaire, 
		
		* P : Puits non descendu,
		
		* Q : non renseigné sur les topographie anciennes, c'est à voir/vérifier,
		
		* S : Siphon à plonger, 
		
		* T : Trémie à désobstruer
	
	* le champ "Cavite" qui donne le nom de la cavité en question,
	
	* le champ "CA" qui est rempli si présence de courant d'air, avec éventuellement des remarques/commentaires.

Licence
-------

L'ensemble de ces données est publié sous la licence libre Creative Commons Attribution-ShareAlike-NonCommercial (Attribution, partage à l'identique et non commerciale) :
	http://creativecommons.org/licenses/by-nc-sa/4.0/

Auteur de la base de données
----------------------------

Cette base de données est actuellement gérée par Xavier Robert (xavier.robert@ird.fr), mais elle ne peut exister que grâce au partage des données des autres clubs et topographes, notamment d'Yvan Robin, du GUS. 

How to cite
-----------

En fonction des apports à cette base de données, les auteurs associés à la citation sont susceptibles de changer, afin de créditer les différents apports.

Robert, X., Base de données Topographiques du système karstiques Moilda - Perthuis (Bugey, 01, France), https://github.com/robertxa/Moilda-Perthuis, 2021. 

Contact
-------

Pour plus d'informations, demandes de corrections, rajout de données ou demandes de données complémentaires sous copyright non libre, contacter l'auteur ou le club Vulcain (https://www.groupe-speleo-vulcain.com/contacts/)
