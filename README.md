# JARVIS
JARVIS est un assistant de vie. Une interface modulable à base d'intelligence artificielle accessible sur téléphone portable ou ordinateur.
Cet assistant doit regrouper des outils dans un même endroit pour faciliter et automatiser une routine humaine.
JARVIS s'organise en sous-assistants qui peuvent s'entraider pour prendre des décisions et les proposer à l'utilisateur.
JARVIS est donc le cerveau, les assistants de JARVIS sont les organes le faisant vivre. Seul JARVIS communique avec l'utilisateur en faisant appel aux assistant si besoin.

L'outil développé est une interface accessible sur téléphone ou ordinateur, doter de mémoire de tout ce qui ce passe pour avoir un suivi continu de l'utilisateur.
Attention, l'utilisateur reste maître de sa vie. L'interface doit être fait de sorte à ce que l'utilisateur fasse des choix ou valide les propositions de JARVIS.

## Assistants
Voici les assistants de JARVIS, ayant chacun un rôle précis.

### Module CLAIRE
L'utilisateur peut avoir accès à des actualités: elles doivent être résumées et brèves. Plusieurs thèmes sont accessibles: comme la politique de la france/euro/mondiale, le sport, 
la musique, le spatial/aérospatial et les sciences. Les thèmes favoris qui sont ses centres d'intérêt sont mis en avant, mais s'il veut l'utilisateur peut demander à voir plus large dans les actualités. 
Par exemple, dans l'onglet "Actualités" JARVIS donne un résumé très bref, avec les informations nécessaires de chaque actualité des thèmes principaux. Mais, l'utilisateur peut aussi cliquer sur la catégorie "Sport"
et voir plus d'actualité, plus large que seulement le badminton ou l'athlétisme.

L'utilisateur écris de manière claire (mots-clés) ses centres d'intérêts ou quels sujets devraient lui être présentés, une espace de partage disponible dans les paramètres de ce module. Par exemple: badminton, 
athlétisme, dessin, musique, Billie Eilish, géopolitique, politique française, cinéma, avancées et découvertes positives, etc...

Chaque jour l'actualité doit être différente. Si un jour, un des thèmes de préférence n'a pas d'actualité alors JARVIS préférera donner un autre actualité sportive (dans ce cas par exemple, una actualité sur le
foot plutôt que sur le badminton ou l'athlétisme).

S'il y a plusieurs mots clés liés à un même thème (par exemple "badminton" et "athlétisme" réfèrent au thème "Sport", alors le résumé d'actualités de la catégorie sport doit comprendre un débrief de ces plusieurs
sujets.

L'interface présente les résumés concrets de chaque actualité sous forme de bullet point avec des mots-clés. Le tout doit permettre une assimilation facile en mémoire de l'utilisateur. Si l'utilisateur veut
aprofondir le sujet, il peut cliquer sur le sujet et le détail (résumé tout de même par JARVIS). Dans ces résumés un peu plus développés, JARVIS doit toujours citer les sources utilisées pour la formation du
résumé. Si le sujet nécéssite un débat ou des points de vus différents, alors JARVIS doit citer les points de vus différents, en citant les sources toujours. JARVIS doit donner l'avis moyen de la population si connu.

En plus des catégories favorites de l'utilisateur, JARVIS doit proposer obligatoirement des actualités qu'il juge comme nécessaire à la connaissance de l'utilisateur. JARVIS est un outil qui doit permettre à
l'utilisateur d'augmenter son spectre de connaissance et d'être alerte sur les sujets primordiaux aussi.

Une dernière actualité que JARVIS doit obligatoirement proposé est un sujet à débat que les gens sont en train traiter. Posé sous forme de question, le débat peut parler de tout et JARVIS donne ensuite la 
répartition des réponses en pourcentage.

Dernier point, JARVIS est un outil neutre, les actualités doivent traiter les bonnes comme les moins bonnes nouvelles.

### Module REMI

L'utilisateur peut accéder dans l'interface à l'outil REMI, c'est le cuistot de l'utilisateur.
Quand l'utilisateur à besoin d'idée de recette, il clique sur l'outil REMI, choisit soit:
- que REMI lui propose une recette une fois que l'utilisateur lui a donné ses quelques idées. Par exemple:
        "Plat rapide à cuisiner, moins de 30 min. Equilibré. Je veux utiliser des saucisses et des courgettes"
- d'ouvrir le manuscrit sacré des recettes enregistrées jusque là. Pour le parcourir et choisir lui même.
Dans les deux cas, REMI créer la recette, donne les quantités puis les étapes.

L'utilisateur peut importer des idées de recettes: par des captures d'écran, des vidéos d'Instagram ou de tiktok, un photo de recette écrite à la main. Dans tous les cas, REMI devra les retravailler pour les mettre au format "Ingrédients - Quantités - Etapes" et les ajouter au manuscrit sacré des recettes.

L'utilisateur peut choisir le nombre de personne, la recette s'y adapte.

### Module CENA

CENA est un outil faisant le suivit sportif de l'utilisateur. L'interface permet à l'utilisateur de choisir quelle séance de sport il veut faire entre:
- Une séance à la salle de sport, de renforcement jambes et cheville
- Un séance à la salle de sport, vitesse et pliométrie
- Une séance de renforcement abdominal
- Une séance de fractionné spécifque badminton
- Une séance de fractionné basique 3*8(30s 80% - 30s 10%)

Chaque protocoles d'entrainement ci-dessus compte 15min (ou autre si l'utilisateur change) de course à pied puis les exercices spécifiques. L'outil à déjà été développé.
L'utilisateur doit aller jusqu'à la fin du protocol pour pouvoir valider le fait d'avoir fait la séance et l'inscrire dans le suivit temporel de son sport.
A la fin de chaque séance, l'utilisateur doit noter sur 5 étoiles: sa satisfaction de son entrainement, sa fatigue musculaire, son état d'esprit. Il peut ajouter en plus un commentaire écrit à la séance.

L'utilisateur retrouve son suivit dans un calendrier mensuel. Si une séance de CENA a été faite (validée) alors la date se met en bleu. Si un sport autre à été fait alors l'utilisateur peut cliquer sur la date, dire quel sport à été fait (exemple, badminton ou autre) et la case se met en rouge. Si les deux on été fait la case et mi rouge mi bleue.

CENA connait les séances de sport planifiées dans la semaine grâce à JARVIS communiquant avec MINISTRE. 
CENA lui doit faire des recommandations du sport chaque jour à faire. En prenant en compte les remarques de l'utilisateur. Par exemple, en contexte, l'utilisateur peu lui dire en plus: "je peux faire du sport à la salle le midi entre 12h15 et 13h30. Je préfère avoir une séance de renforcement des jambes/chevilles avant mon entrainement de badminton le mercredi et après les compétitions du weekend. Mais ça ne doit pas faire trop, il faut prévoir les courbatures. Donc généralement le lundi midi je fais cette séance". CENA se base sur des connaissances sportives sérieuses, pour une joueuse de badminton ayant souvent mal au genoux (d'où le renforcement) et des chevilles fragiles.

CENA peut faire une recommandation en connaissant les comlentaires des séances que l'utilisateur a rempli. Par exemple: Si la séance d'avant l'utilisateur était vraiment fatigué, CENA ne va peut être pas conseiller de faire du fractionné le jour d'après, peut être plutôt une séance plus calme comme des abdos, ou bien de la course à pied. CENA doit savoir dire à l'utilisateur quand faire des pauses dans la semaine, le midi on le soir. 

CENA doit basé ses conseils sur des connaissances sourcées, concernant le sport et le renforcement musculaire. Des conseils qui doivent s'appliquer au profil de l'utilisateur.


### Module MINISTRE

JARVIS communique avec le MINISTRE pour afficher sur l'interface Ministre les évènements prévus de la journée et les recommandations du Ministre.

Sur cette page de l'interface, l'heure est affichée, la météo locale est affichée, les évènements du jours planifié, les recommandations de JARVIS sont affichés. 

MINISTRE connait les évènements planifiés car il a accès au Google Agenda de l'utilisateur.
MINISTRE connait les recommandations sportif de CENA. Il peut alors alerter l'utilisateur de ce conseil sportif.


