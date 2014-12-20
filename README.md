BattlePouic 
===========
Framapad: https://lite5.framapad.org/p/tOQJ2nQruv
===========
Battle Pouic: The Origin of the start of the very first Beggining of the Origin of the First Prequel of Battle Pouic

=========Gameplay=======

	Tour par tour rythmé (délai de jeu max)
	Unités diverses et équlibrées pour stratégie
	Favoritisme de la stratégie défensive
	Temps de tour par tour dépendant de la distance entre unités
	
	
	*****Unités*****
	
		Part de zéro et évolue naturellement au kill tel que:
				mastodonte-parasite-prédateur EVOLUTION DEPENDANTE (Evolution vers sa faiblesse progressive jusqu'à transformation totale)
				puissant<-résistant<-vif EVOLUTION INDEPENDANTE (vitesse, force, défense)
				point d'action et point de déplacement ("je pense qu'il va aller là donc je fais ça")
				
	*****Gestion des unités*****
	
		Nombre de slot de conservation limite et périodiquement croissant
		Gain d'unités aléatoirement au début du combat et choix de conservation. Ces premières unités sont basiques avec un pas d'évolution aléatoire.
		
		
	*****COMBAT******
		Bonus selon l'orientation de l'attaque (flanc, dos, embuscade...)
		Demi-tour perdant.
		Vie continue (non discrète) 	
			ex: proie survit au prédateur si bonnes stats mais en mauvais état...
		Brouillard de guerre.
		Chef
		Temps de décision proportionnel à la situation (proche de l'ennemi) et du nombre d'unité (genre 2sec par unités).
		
	*****Visuel*****
	
		Nom coloré selon la classe (prédateur etc) 
		
	*****Menu*****
	
		Chaque kill apporte des points d'évolution aux monstres. Les monstres peuvent à la fin du combat évoluer avec ces points ou les convertir en pognon.
		Le pognon peut servir à l'évolution de créatures mais dans les moindres limites. 
		Le nombre de slot initial est bloqué, on dépense le pognon pour agrandir son "coffre" et y conserver nos favoris. Les slots vides dans le choix des unités sont 
		automatiquement rempli par des unités au hasard.
		
	*****Musique*****
	
		Composition d'une musique de combat, une de déplacement (basique), une d'embuscade etc...
		Chaque phase de déplacement effective sera accompagné de la musique adéquat (guerre si combat prévu etc), phases de décision accompagné de morceaux de la musique de réflexion  
			(tendue si position mauvaise etc)
		
============

Mise au forme littéraire depuis Framasoft:

Game Design Document
BATTLE POUIC: The origin of the start of the very first Beggining of the origin of the First Prequel of Battle Pouic
Présentation du jeu
Battle Pouic est un jeu de stratégie au tour par tour musical.
Le joueur participe à des battailes contre une intelligence artificielle.
Chaque joueur possède une équipe de 5 Pouics.
Les Pouics
Ces 5 Pouics peuvent appartenir à trois grandes classes de Pouic: 

    Les mastodontes: Avantages sur les parasites et désavantages vis à vis des prédateurs

    Les parasites: Avantages sur les prédateurs et désavantages vis à vis des mastodontes

    Les prédateurs:Avantages sur les mastodontes et désavantages vis à vis des parasites 

Si un Pouic parvient à dominer un autre Pouic de classe oposée (un Pouic appartenant à une classe pour laquelle il est normalement désavantagé) alors il changera de classe: il gagnera l'avantage face à la classe qui était sa faiblesse et donc deviendra un membre de la classe ayant un avantage face à celle ci.
ex: un parasite qui tue beaucoup de mastodonte deviendra un prédateur (qui est la classe ayant un avantage sur les mastodontes).
 
 TODO: déterminer les conditions de domination ! (genre au bout de combient de kill/seconde sont nécessaire à la transformation ?) 
 IDEA: Je dirais jauge d'expérience qui croît avec le niveau du monster tué et sa spécialisation dans le rôle à pourvoir.
 
     
Chaque Pouic possède, en plus d'une classe, des caractéristiques propres lui permettant de se différencier des autres membre de sa classe: 

    sa vitesse (point de déplacement, rapidité d'action dans le tour, nombre d'attaque)

    sa défense (passif de protection des alliés) // Il manque quelque chose je touve

    son attaque(Zone d'attaque, nombre d'attaque

Ces caractéristiques sont déterminées par le type du Pouic.
Il existe en effet trois grands types de Pouic:

    Les puissants: Avantages sur les résistants et désavantages vis à vis des vifs

    Les résistants: Avantages sur les vifs et désavantages vis à vis des puissants

    Les vifs: Avantages sur les puissants et désavantages vis à vis des résistants

Déroulement d'un combat
les tours
Chaque pouics commencent le combat avec 100% de vie.
Les tours sont déterminés par un fond musical rythmé. A chaque signal un tour passe.
ex: dans un rythme du genre "tic-tic-tic-Tac-tic-tic-tic-Tac-tic-tic-tic-Tac-tic-tic-tic-Tac" le tour change à chaque "Tac"
Lorsque le tour du joueur arrive, il doit controler ses Pouics en rythmes.
L'ordre de controle est déterminé par la vitesse des Pouics: les plus rapides (donc les vifs) sont controlés en premier.
Le joueur à alors un temps déterminé par le rythme du jeu pour controler chaque Pouic.
Suivant sa position sur le plateau chaque Pouic peut effectuer différentes actions:

    s'il est en face d'un Pouic adverse il peut l'attaquer 

    s'il est en face d'un Pouic adverse il peut se défendre

    s'il est en face d'une case accessible il peut s'y rendre

Son nombre d'actions est directement déterminé par ses caractéristiques: en effet 

    plus un Pouics est rapide plus il possèdera de point de déplacement.

    plus il est fort en attaque et plus son nombre d'attaque et sa zone d'attaque grandit

     plus il est défensif plus il peut se défendre et améliorer la défense de ses voisins.

TODO: Trouver la méthode de calcul du nombre d'attaque/défense/déplacement en fonction de l'attaque/défense/vitesse d'un pouic
L'attaque
Suivant l'orientation de sa cible, un Pouic obtiendra des bonus supplémentaire suivant le schémas suivant:

    attaque de face: pas de bonus

    attaque de flanc: attaque x2

    attaque de dos: attaque x10


========Versionnage=====
****Version 0*******
	Affichage d'une map.
	Affichage d'une équipe
	
****Version 0.1*******
	Deplacement des unités	
	
****Version 0.2*******
	Intéraction des unités
	
****Version 0.3*******
	IA de la pitié
	
****Version 1*******
	Equipe aléatoire donnée entre 3 neutres
	Combat possible rythmé par un bip
	
****Version 0*******
	Menu de sélection
	
****Version 0*******
****Version 0*******

