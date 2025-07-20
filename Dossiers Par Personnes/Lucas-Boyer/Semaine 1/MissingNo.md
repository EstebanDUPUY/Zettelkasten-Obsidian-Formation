# Bugs Légendaires dans l’Histoire du Jeu Vidéo

## MissingNo. - Bug de type "glitch" dû à une mauvaise gestion des données dans la mémoire

- Comment faire apparaître le glitch / la reproduction du bug :
    La méthode pour déclencher l'apparition de MissingNo. est décrite pour la première fois par Nintendo dans le numéro de mai 1999 du magazine Nintendo Power, en réponse à un lecteur, tout en précisant que « tout contact avec lui peut facilement effacer votre fichier de sauvegarde ou corrompre les graphismes du jeu ». Le magazine explique que pour rencontrer MissingNo., le joueur doit se rendre à la ville de Jadielle afin de parler à un vieil homme qui explique comment capturer un Pokémon ; ensuite, il doit utiliser la capacité « Vol » pour se rendre à Cramois'Île, puis utiliser la capacité « Surf » pour longer la côte est de l'île, la où se trouve MissingNo.

- Les résultats du glitch et ses effets sur le jeu / symptômes :

  - Lorsque l'on rencontre ce Bugs, 128 exemplaires de l'objet qui se trouve a la 6e place de l'inventaire seront ajoutés uniquement si le joueur en possède moins de 128. Ce bugs affecte donc le 6e objet lors de son apparition et réaffecte le 6e objet au moment où on le capture, cette astuce peut donc affecter donc deux types d'objet différents en les échangeant de place pendant le combat (Super Bonbon et Master Ball par exemple…).
  - Crash / Perte de donner
  - Monter des Niveau des Pokémons Sauvage rencontrer (Plus de 100).

Cela est dû au fait que les Pokémon sont reconnus par le Pokédex par un nombre valant "0" si le Pokémon n'a jamais été vu et "128" s'il a été vu. Un autre nombre gère similairement la capture du Pokémon.

Les développeurs n'ont jamais prévu qu'on puisse rencontrer donc capturer MissingNo, donc le nombre qui gère le fait de l'avoir vu est stocké au même emplacement que le nombre d'objets dans le 6e emplacement du sac. Les développeurs n'ont pas non plus prévu la possibilité qu'un joueur puisse avoir plus de 99 exemplaires d'un objet dans un seul emplacement du sac, ce qui provoque un bug graphique.
Il est néanmoins possible de savoir combien d'objets sont présents, il suffit d'aller dans un Centre Pokémon.

- Une fois MissingNo. rencontré, il existe un risque de voir le Panthéon corrompu, avec :

  - Des noms aléatoires, comprenant chiffres, lettres avec ou sans accents, voire des carrés vides.

  - Des sprites ne ressemblant aucunement aux Pokémon connus, voire un fond uniforme en tant que sprite.

  - Des attaques, une fois encore, corrompues, des niveaux parfois supérieurs à 100, à savoir que la valeur maximale gérée par le jeu est 255.

Seuls les exemplaires existants du Panthéon sont corrompus : chaque fois suivante que le joueur bat la Ligue, le nouvel exemplaire sera correct jusqu'à rencontrer MissingNo à nouveau.

La corruption du Panthéon n'a qu'un effet potentiellement néfaste, et uniquement dans Pokémon Rouge et Bleu, où visualiser un Panthéon corrompu au dernier étage de la Sylphe SARL. corrompt cet étage, ce qui donne un résultat ressemblant à Bug-ville. Sauvegarder dans cet étage corrompu y bloque le joueur.
