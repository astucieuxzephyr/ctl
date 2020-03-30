# Version française du test des couleurs de Max Lüscher :

 - Auteur : Tanguy Bodin-Hullin.

## Changelog
 - Récupération sur Github du programme russe CTL (clinical test) fait par Daria Titova : 23 avril 2013
 - Nouvelle version du programme, en français, par Tanguy Bodin-Hullin, en mars 2020

## Historique de ce programme :
 - Le programme russe a été récupéré en avril 2013 sur Github
 Une première traduction a été faite, et le programme JS amélioré, mais le fichier a été perdu.
 - En mars 2020, une nouvelle version, améliorée, est mise en ligne.
 Cette version bénéficie des améliorations suivantes :
 - Mise à jour de JQuery (de la version 1.7.1 à la version 3.4.1)
 - Nouvelle interface, qui s'appuie sur le système de cartes de Bootstrap 4.1
 - Ajout de la possibilité de mettre facilement des noms par défaut dans le programme,
 pour faciliter les passations.
 - Interface de résultats lisible, et qui permet de récupérer plus facilement des données de passation
 par copier-coller.
 - Code mieux documenté, avec la possibilité d'afficher les messages de debug dans la console.
 - Textes soigneusement traduits en français
 - Amélioration de la documentation au format Markdown.

## To-Do :
   - Ajouter la possibilité d'obtenir les résultats dans d'autres langues, notamment en anglais.

## Description :
- Il s'agit du test des couleurs du psychologue Max Lüscher (1923-2017), en version ultra-simplifiée.
- Le test des couleurs permet d'évaluer l'état émotionnel d'une personne à un moment donné, en fonction de sa préférence de couleurs sur le moment.
- Ce test est peu connu mais est d'un bon intérêt clinique, il est pertinent et assez "puissant".
- C'est un test qui s'appuie sur la relation entre la perception des longueurs d'onde des couleurs, et les émotions. Il est très scientifique.
- Ce n'est pas pour rien qu'existent dans la langue française des expressions comme : "Voir le monde en gris". Ou encore : "Voir la vie en couleurs"...il y a un lien entre la perception des couleurs et la vie intérieure psychologique du sujet.

# Usage :
Le test a déjà été utilisé à de maintes reprises à travers le monde.
Certains psychologues l'utilisent encore, notamment des psychologues russes dans le domaine du support psychologique des athlètes de haut niveau. Dans ce domaine, le test a été utilisé pour mesurer le niveau de stress des sportifs, ainsi que l'efficacité de leur autorégulation mentale.
J'ai constaté qu'un médecin l'utilisait également en France.

## Passation du test :
Huit couleurs sont présentées en même temps à la personne qui passe le test.
Les couleurs sont : bleu, vert, rouge, jaune, violet, marron, noir et gris.
Le sujet choisit les couleurs une à une, selon son ordre de préférence du moment (et cela est très important, voir ci-après les précautions de passation).

### Précautions de passation :
Le sujet ne doit pas associer la couleur à un objet qu'il aime, par exemple, sinon cela fausse le test. Ou encore, si sa couleur préférée est généralement le bleu ou autre, il ne doit pas en tenir compte.
La notice du livre précise :
> "SURTOUT n'essayez pas d'associer cette couleur à autre chose, à un tissu de robe, à un intérieur, à une voiture ou n'importe quel autre objet. Choisissez simplement la couleur qui vous attire le plus parmi les huit couleurs que vous avez devant vous."
>
> -- <cite>("Le nouveau test des couleurs", 1992, pp.181)</cite>

Le classement va permettre une projection de certaines composantes de la personnalité psychosomatique du sujet, au moment où il a fait le test.

## Historique de mon intérêt personnel pour ce programme :
> J'ai découvert le test des couleurs au début des années 2000, après avoir trouvé, par hasard, une application sur Internet qui permettait de le passer.
J'ai utilisé l'application à plusieurs reprises sur moi-même et j'ai été très surpris par l'extraordinaire pertinence des résultats. Je l'ai aussi fait passer à d'autres personnes, et cela m'a convaincu de la force du test et de sa validité.
Ayant des difficultés psychologiques à l'époque, j'étais très intéressé pour me passer le test chaque jour pendant une période donnée. Le seul problème, c'est que le programme que j'avais récupéré (TESTCOUL.EXE) ne permettait pas d'enregistrer l'historique des passations, et de créer ainsi une base de données analysables. Etant formé en programmation de par mes premières études, j'ai donc décidé en 2007 de créer un programme sous le logiciel Microsoft Access qui le permettait. J'ai bien avancé dans ce programme, et j'avais une interface graphique fonctionnelle qui permettait de faire le choix des couleurs.
Mais je n'avais pas les phrases exactes qui sont données en résultats d'analyse, phrases très précises établies par Max Lüscher, et après avoir recopié un certains nombre de phrases venant du logiciel initial TESTCOUL, j'ai essayé de trouver un ouvrage sur le sujet.
J'ai trouvé à la bibliothèque de Nanterre un exemplaire du livre qui me permettrait d'en savoir plus, et j'en ai photocopié des parties qui me paraissaient les plus essentielles, mais j'avais d'autres chose à faire et j'ai mis le programme en standby.
Début 2008, j'ai à nouveau avancé sur le programme Access. En mars 2008, j'étais étudiant en psychologie à l'Université de Paris Descartes, et j'étais souvent à la bibliothèque pour travailler. J'ai constaté sur le catalogue de la bibliothèque qu'il existait un autre ouvrage sur le test des couleurs, plus récent que celui que j'avais photocopié à Nanterre. Mais l'ouvrage était à la bibliothèque de l'Université de Toulouse. Heureusement, il existe un service de Prêt Entre Bibliothèques (PEB) qui m'a permis de commander l'ouvrage et de le consulter à Paris. Là encore, j'ai photocopié l'ouvrage, parce que je ne pouvais le garder longtemps comme je le souhaitais.
>
> -- <cite>Tanguy Bodin-Hullin, psychologue clinicien, mars 2020</cite>



## Autres programmes intéressants.
  - Plusieurs programmes ont été développés pour le mobile (Android)
  - L'un des programmes a été développé par ...

## Fichiers :

  - `luscher_test_russian.html` : la version originale du programme
  - `lusher.html` : la version améliorée, en langue française, incluant bootstrap
  - `assets/css/styles.css` : la feuille de styles
  - `LISEZMOI.md` : documentation complète en français au format Markdown (ce fichier)
  - `README.md` : documentation en anglais au format Markdown

## A propos de Max Lüscher (résumé à partir de Wikipédia)

Max Lüscher est un psychologue et philosophe suisse, professeur de psychologie.
Il est considéré comme le père de la psychologie des couleurs.

Max Lüscher a exploré l’hypothèse d’une correspondance entre les couleurs et les caractéristiques de la personnalité. Il postulait que l’attirance pour les couleurs étant fondée sur des processus inconscients, le test montrerait comment la personne est en réalité, par opposition à comment elle pourrait être, s’imaginer ou comment elle voudrait être.

Nous nous sommes servie de son test pour évaluer l’état psycho-physiologique de la personne, sa capacité à gérer le stress, son activité et ses compétences de communication.

Le test consiste à ordonner des cartons de couleur de la plus aimée à la moins
aimée des couleurs. Il existe deux variantes de ce test, la complète et la courte. C’est la
courte, proposant 8 couleurs, que nous avons utilisée

## Extraits du livre de Max Lüscher "Le nouveau test des couleurs", 1992
### La perception des couleurs
> La perception des couleurs est liée à la fois au cerveau formé (néo-cortex) et au cerveau primitif comme l'a prouvé Becker en 1953 en démontrant qu'un réseau de fibres nerveuses allait directement d'un nucleus de la rétine au cerveau moyen (mésencéphale) et à l'hypophyse.
Le fait de pouvoir distinguer les couleurs, les identifier, les nommer, y réagir sur le plan esthétique, sont des fonctions du cortex, dues plus à un développement et à une formation qu'à des réactions instinctives.
>
> -- <cite>("Le nouveau test des couleurs", 1992, pp.16-17)</cite>

> La perception des couleurs est la même pour tous les hommes, quelle que soit leur culture. [...]
Si ces perceptions sont les mêmes pour tout le monde, chacun leur attribue néanmoins une valeur particulière : on peut aller dans le sens de cette perception excitante, parce qu'elle nous stimule, ou bien la refuser, parce qu'elle nous énerve. (p.256)
[...]
Dans le test de Lüscher, selon que l'on accepte ou que l'on rejette une couleur, on dévoile l'aspect le plus caché de son comportement, psychique et physique. Le choix de ces couleurs étant dicté par l'inconscient, il définit ce que l'on est réellement, et non, comme cela peut se produire au cours d'une consultation, d'une séance de psychanalyse, ou dans un questionnaire, ce que l'on croit être.
>
> -- <cite>("Le nouveau test des couleurs", 1992, p.257)</cite>

### Marketing
Les recherches de Lüscher ont confirmé que l'utilisation de la juste couleur sur les emballages peut avoir un effet hypnotique sur l'acheteur. De même la coloration des objets peut influer sur leur succès commercial (par exemple la coccinelle de Volkswagen lui devrait une part de sa réussite).

## Test des couleurs de Lüscher

### Formes du test
Le test de Lüscher existe sous plusieurs formes :
- test complet utilisant un vaste nuancier de couleurs, disponible seulement en allemand,
- test simplifié utilisant des cubes cartonnés de six (6) couleurs différentes
- une version logicielle du test, qui présente huit cartes de couleur, et qui donne une analyse poussée de l'état psychologique d'un sujet.
- le programme d'origine russe qui est proposé sur ce repository GitHub est similaire à la version logicielle, puisqu'il présente les 8 cartes de couleur, mais il délivre une information nettement plus succincte et simplifiée. Voir le détail au paragraphe "Résultats délivrés par le programme"

# Résultats délivrés par le programme
Le programme utilise le test simplifié, mais il délivre seulement deux résultats.
1. La *tension neuropsychique*
2. Le *coefficient végétatif*

### A propos du test complet :
Le Test Complet de Lüscher révèle plus que les simples réactions d'un individu à sa situation et son comportement général ; il montre aussi comment son comportement est conditionné, ses réactions inconscientes dans le domaine des émotions, ses désirs, ses aspirations, les élans et les besoins du plus profond de son psychisme.
Ces renseignements peuvent permettre au psychologue, au psychiatre et psychanalyste de faire non seulement un diagnostic complet et précis, mais aussi de voir plus facilement la meilleure thérapeutique à suivre. (SOURCE : 1986)


### Interprétation du test :
Elle est complexe et documentée sur le [Site officiel Lüscher Color Diagnostik](https://www.luscher-color.ch/)
Vous pourrez la retrouver également dans l'ouvrage "Le nouveau test des couleurs" (1992), voir la section Références.

Selon le site du [cabinet Auriol présentant le test](http://cabinet.auriol.free.fr/psychologie/luscher.htm), une interprétation simple de ce test consiste à regarder si une couleur est classée parmi les préférées (les quatre premières) ou les moins aimées (les quatre dernières).

### Intérêt du test :
Ce test est peu connu mais est d'un certain intérêt clinique. Il (Zirilli G. ,1967), est très employé par certains spécialistes du recrutement de personnel.

### Variations des résultats selon l'âge :
Les résultats du test peuvent varier en fonction de l'âge.
Le [site de Bernard Auriol](http://cabinet.auriol.free.fr/psychologie/luscher.htm) (médecin psychiatre et psychanalyste) qui présente le test indique qu'un quotient couleurs a été créé qui permet d'évaluer une sorte d'âge émotionnel via le test de Lüscher.
> Les personnes qui ont de l'énergie, de la créativité, du succès auraient à ce test un âge très jeune par rapport à leur âge réel.

## Références bibliographiques
### Français
 - Lüscher M., (1981). Le Color test de Max Lüscher. Votre personnalité révélée par les couleurs, Avignon, Aubanel, coll. Encycl. de sciences humaines et de psychologie pratique.
 - Lüscher M., (1992). Le nouveau test des couleurs. une méthode scientifique et facile, Paris, Solar.
(titre original) Die Lüscher-Würfel : zur Selbsterfahrung und Personlichkeitsbeurteilung. (traduction : pour la conscience de soi et l'évaluation de la personnalité).
 - [Canivet N. Le test de Lüscher](https://www.persee.fr/doc/clini_0373-6261_1964_num_17_1_1217). In: Bulletin de la Société française du Rorschach et des méthodes projectives, n°17-18, 1964. (pp. 57-61).
 - [Dounovetz A., Durand de Bousingen R. Utilisation en psychologie clinique du test de choix de couleurs (Luscher)](https://www.persee.fr/doc/clini_0373-6261_1969_num_23_1_1293). In: Bulletin de la Société française du Rorschach et des méthodes projectives, n°23, 1969. Psycholinguistique et techniques projectives. (pp. 95-98).

### English / Italian
- Zirilli G., Applications of the colored "(Koch) tree (drawing) test" in psychiatry.
### in Italian :
- Zirilli G., Applications of the colored "tree test" in psychiatry.
Translation in italian : Applicazioni del Koch "test ad albero" colorato in psichiatria
Acta Neurol. (Napoli). 1967 Sep-Oct;22(5):619-43. Italian.
No abstract available.

## Liens :
 - [Max Lüscher sur Wikipédia](https://fr.wikipedia.org/wiki/Max_L%C3%BCscher)
 - [Site officiel Lüscher Color Diagnostik](https://www.luscher-color.ch/) : site multilingue sur le système de Lüscher. Une vidéo de Max Lüscher est disponible, ainsi que de nombreuses explications.
 - [Site de conseil Auriol présentant le test](http://cabinet.auriol.free.fr/psychologie/luscher.htm)
 Notamment, un lien permet de télécharger le programme de Lüscher (pour ancienne version de Windows)
