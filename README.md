# AInimus

## Principe

AI.nimus est un projet réalisé par des étudiants du DUT Métier du Multimédia et de l’Internet de L’IUT Bordeaux Montaigne. Il s’agit d’un site internet à visée pédagogique, qui veut proposer une nouvelle approche du sujet des Intelligences Artificielles, en se basant sur le contenu du programme de philosophie de Terminale, tout en permettant de créer et de générer des débats formateurs au sein des classes.

La cible principale de notre projet étant les professeurs de philosophie, auxquels nous souhaitons donner un nouvel outil pédagogique libre de droit et facile d’utilisation

## Dev
Twine est un [logiciel libre](https://fr.wikipedia.org/wiki/Logiciel_libre "Logiciel libre") disponible pour [Windows](https://fr.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows"), [Linux](https://fr.wikipedia.org/wiki/Linux "Linux") et [macOS](https://fr.wikipedia.org/wiki/MacOS "MacOS"). Son interface graphique est basée sur l'interface en ligne de commande nommée twee

Le logiciel Twine fournit une représentation visuelle de la structure hypertexte, à l'aide d'une "_node map_" (carte de nœuds). Un jeu se compose de "passages", blocs de texte reliés entre eux par des liens hypertextes.

Chris Klimas travaille actuellement sur une seconde version de Twine, qui disposera d'une interface web.

## Syntaxe
''Bold''
//Italics//
__Underlined__
Pour faire du random entre deux valeurs : <<print either("heads","tails")>>
<[img] src="the URL of your image" width="500" height="300" alt="Two foxes">
<video src="the URL of your video" width="640" height="480"></video>
<audio src="the URL of your sound effect" autoplay>





Selector	Description
.passage	All the passages on the page. In Sugarcane, unlike Jonah, there's only ever one such passage. Note that this element fades in whenever you change passages, whereas #passages remains constant.
.passage:last-child	In Jonah, this solely targets the “current” passage - the one at the bottom of the page.
.passage:not(:last-child)	In Jonah, this solely targets the past passages.
.passage .title	The passage title in Jonah.
.passage .toolbar	The passage toolbar in Jonah.
.passage a	Every link in a passage.
.passage a:hover	A link that the cursor is hovering over.
.passage a:active	A link that is in the midst of being clicked. (You can use this to make a link “light up” when clicked.)
.passage a.internalLink	Only links to other passages (and not, say, other websites).
.passage a.visitedLink	Every link to another passage that the player's visited at least once.
.passage a.internalLink:not(.visitedLink)	Every link to another passage that the player's not visited yet.
.passage a.externalLink	Only external links. Doesn't include HTML <a> links.
.passage li	Bulleted or numbered list items in a passage.
.passage img	Images in a passage.
.passage hr	Horizontal lines in a passage.
.disabled	Links that are not longer available to the reader, created through the «choice» macro, or by turning the Undo StorySetting to off.
#passages	A container for all passages displayed on the page.
body	The body of the HTML page – a great place to change the typeface for the entire page. But, individual elements' styles will usually override this.
#sidebar	The Sugarcane sidebar, containing the StoryMenu.
#sidebar li	List items inside the Sugarcane sidebar.
#floater	The Jonah StoryMenu (which usually only contains 'Restart Story')
#footer	The footer at the bottom of Jonah (e.g. “This story was built with Twine and is powered by TiddlyWiki”).
#credits	The credits in Sugarcane's sidebar (e.g. “This story was built with Twine and is powered by TiddlyWiki”).
