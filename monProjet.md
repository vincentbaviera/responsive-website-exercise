#ICOM - Cours HTML / CSS #

* Vincent Baviera * 

## Pourquoi mon projet est-il organisé de cette manière ?
	
	[J'ai répondu à la demande de créer un site responsive de manière simple, afin de mieux comprendre le code mis en oeuvre et ne pas m'arrêter sur l'aspect esthétique, ou peu.
	Mon projet est réparti en 3 parties, un fichier HTML, avec un fichier CSS qui concerne le style des éléments d'ensemble, avec un autre fichier qui répond à la demande d'avoir un site en responsive design et qui va définir mes éléments en fonction de celui ci.
	Mes balises sont organisées en fonction de leur place dans la page HTML, partant du haut pour aller en bas, les éléments numériques regroupés à la suite, tels que la colonne 1 est définie avant la colonne 2, même si elles apparaissent côte à côte.]

### _Avantages et inconvénients:
		
	[L'avantage est d'avoir un code qui est beaucoup plus lisible et plus rapidement parcourable, tandis que l'inconvénient serait d'avoir à devoir chercher parfois longtemps où doit se trouver la balise pour fonctionner correctement ou laquelle est buguée et doit être modifiée dans le CSS par exemple.]

## Comment en suis-je arrivé à ce résultat ?
	
	[J'en suis arrivé ici en me basant sur votre code de base afin d'avoir une base saine, puis je l'ai adapté afin de répondre à ce que j'avais en tête, l'agrémentant de balises au fur et à mesure.]

### _Différentes étapes, problématiques d'organisation:

	[J'ai tout d'abord écrit la structure HTML afin d'avoir tous mes éléments à mettre en forme, de manière d'abord simple puis je suis revenu dessus plus tard, une fois une première approche du CSS réalisée. L'inconvénient de cette méthode est de revenir souvent sur son code initial pour le modifier et l'adapter, ce qui fait perdre un certain temps. Une fois les premiers éléments HTML et CSS généraux mis en place, j'ai commencé alors mon approche du responsive design, gérant petit à petit les problèmes qui apparaissaient alors dans mon code.
	Une erreur dans l'écriture d'une balise dans le fichier mediaqueries m'a fait perdre un certain temps avant que j'arrive à trouver le problème. En effet, mes balises resp-section puis resp-grid n'était pas en relation (l'une avait un padding et l'autre compensait en utilisant margin) ce qui augmentait le non alignement de mes éléments au lieu de faire en sorte d'avoir un bloc visule bien organisé à verticalement à l'affichage.
	De la même manière, une première erreur dans l'organisation de la grille responsive m'a fait inverser au départ la répartition de la taille des colonnes, ce qui me faisait faire l'inverse de ce que je voulais à l'affichage. Une fois ce problème reglé, tout est allé beaucoup plus vite.
	Mon but était de visuellement ressembler le plus possible à la maquette que vous nous aviez fourni, tout en personnalisant le site un minimum afin de ne pas avoir une copie.
	J'ai laissé certaines balises (en particulier les liens) à complèter, afin de voir rapidement où sont les éléments à définir plutôt que de marquer un code n'ayant rien à voir et de devoir chercher par la suite les bons éléments à remplacer. De cette manière, les autres pages du site n'ayant pas été codées, je n'ai pas mis leurs liens dans les balises '<a>'' et le nom de mon site où la page d'accueil nétant pas définitive, je n'ai pas non plus mis les liens de la page d'accueil, sauf pour tester certaines balises, que j'ai ensuite enlevés. Cela me permet de ne pas avoir à chercher où sont les liens qui sont corrects et où sont ceux qui ne le sont pas.
	J'ai agrméenté mon code de commentaires pour les éléments majeurs à rajouter (comme un affichage des tweets en rapports avec le page) plus tard ou pour définir des parties organisées dans mon CSS. ]

	## Quelles sont les difficultés renconctrées durant ces 6 sessions ?

		[Les difficultés majeures que j'ai rencontrées sont surtout dues à mon inexpérience dans le domaine du codage, en effet j'ai mis un certain tempas au départ pour retrouver les différentes syntaxes, retrouver les balises, comment les organiser...
		Réaliser ce site m'a permis de récupérer mon niveau de l'année dernière et de beaucoup mieux comprendre plusieurs éléments, ce qui m'a fait progresser. 
		Un autre problème majeur à été l'utilisation de GitHub, que je n'ai pas réellement respecté, ce qui poserait problème dans le cas d'un site réalisé en  entreprise. L'interface logiciel n'étant pas très laire quant à son utilisation et aux différentes étapes à réaliser, c'est cependant le seul moyen que je connaisse pour envoyer mon travail sur github depuis un PC, travaillant à la fois sur Mac à la faculté et sur PC chez moi.]