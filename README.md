Mini Projet B3 - Node.JS - YNOV
===================

###Objective 
Créer un chat d'équipe "Slack-like" en temps réel.

----------


Cas d'usages utilisateur
-------------
> - Un utilisateur doit être capable de se connecter à l'aide de Facebook, Twitter et d'un compte Google. *Si un utilisateur se connecte avec Facebook, il devra choisir un pseudo d'usage.*
> - Un utilisateur doit pouvoir créer/rejoindre/quitter un ou plusieurs canaux.
> - Un utilisateur doit pouvoir parler au sein de l'un des canaux et en utilisant du texte normal ou la syntaxe Markdown mettre du gras, italique etc *(Utiliser une bibliothèque à cet effet)*.
> - Un utilisateur peut être admin ou simple user sur le canal.
> - Un utlisateur peut laisser une "emotion" sur un message d'un utilisateur.

Cas d'usages administrateur
-------------
>- Un administrateur peut supprimer, censurer, kicker, bannir et transformer un utilisateur en admin.
	- Un message censuré ou supprimer, devra être affiché comme tel

Cas d'usages superadmin
-------------
> - Un superadmin peut supprimer un canal même s'il n'est pas admin de celui-ci.

BONUS
-------------
> - Un effort a été fait sur l'UI
> - Il est possible de définir un photo de profil pour l'user
> - Il est possible d'uploader des fichiers ou d'embed des vidéos YouTube
> - Votre application est responsive.


NOTE :
-------------
Votre application doit conserver les sessions après redémarrage et a travers les clusters. Car, oui votre application doit utiliser les clusters !!
