# Challenge

Citations des Simpsons

Ton attention STP ! Avant la dernière mise à jour (18 mars 2020), le challenge de cette quête reposait sur l'API Chuck Norris. On nous a remonté que certaines des blagues de cette API étaient offensantes ou grossières, aussi a-t-elle été remplacée par l'API Simpsons Quotes. Ne sois pas étonné si les solutions de tes camarades ne semblent pas conformes aux instructions ci-dessous, ils n'ont pas eu le même énoncé ;).

L'API Simpsons Quotes va te fournir tout ce qu'il faut pour épater tes amis, en leur présentant ta propre application de citation des Simpsons ! Elle te donnera des citations obtenues aléatoirement :). Cela rappellera quelque chose aux wilders apprenant React !

Il va s'agir d'adapter le dernier exemple avec axios, pour aller interroger cette API.

- Télécharge ce template, et sauvegarde-le dans un nouveau dossier.
- Initialise un repo Git dans ce dossier, et crée un repository sur GitHub (par exemple ajax-simpsons-quotes).
- Récupère le code d'exemple utilisant axios avec l'API Pokémon,

Adapte le code pour :

- appeler la bonne URL ("Get one quote" dans la documentation),
- tenir compte du fait que response.data sera un tableau d'objets, n'en contenant qu'un seul, contrairement aux API Pokémon et Chuck Norris qui ne renvoient qu'un objet ! Il faut donc utiliser le premier élément de ce tableau (même syntaxe en JS qu'en PHP, Java, C#, Python...)
- générer le HTML contenant le nom et l'avatar du personnage des Simpsons, et le texte de la citation, à partir de l'objet à partir de l'objet récupéré,
- afficher ce bloc HTML dans la div appropriée.
- Commit et push
- Dans l'onglet "Settings" de ton repo GitHub, active GitHub Pages sur la branche master.

Bonus (plutôt pour les élèves JS !)

Si tu souhaites te challenger, tu peux ajouter un bouton permettant, sur un clic, de charger une nouvelle citation, au lieu d'avoir à recharger la page (voir ou revoir la façon de gérer un clic)

Poste l'URL de la page sur GitHub Pages.

Critères de validation
- La page est accessible via GitHub Pages
- Une citation des Simpsons apparaît, avec le nom, l'avatar et le texte
