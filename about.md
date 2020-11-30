---
layout: lecture
title: "Pourquoi donnons-nous ce cours"
---

Au cours d'une formation standard en informatique, il est fort probable que vous
suivrez de nombreux cours portant sur des sujets avancés de l'informatique, des
systèmes d'exploitation à l'apprentissage machine, en passant par les langages
de programmation. Mais, un sujet rarement abordé dans de nombreuses
institutions et dont on attend des étudiants qu'ils se forment eux-mêmes est
la connaissance de l'écosystème informatique.

Nous avons participé , depuis de nombreuses années, à l'enseignement de
plusieurs matières au MIT. Et chaque année, nous avons constaté qu'un certain
nombre d'étudiants n'avaient qu'une connaissance limitée des outils qu'ils
avaient à leur disposition. À l'origine, les ordinateurs ont été conçus pour
automatiser certaines tâches, et pourtant, certains étudiants font eux-mêmes ces
tâches à la fin ou ne tirent pas complètement profit des puissants outils tels
que la gestion de versions ou les éditeurs de texte. Dans le meilleur des cas,
cela conduit à de l'inefficacité et de la perte de temps ; dans le pire cas,
cela peut entraîner des pertes de données ou l'incapacité de réaliser certaines
tâches.

Ces sujets ne font pas partie de l'enseignement universitaire : les étudiants ne
voient jamais comment utiliser ces outils (ou en tout cas de façon efficace), et
passent alors beaucoup de temps sur des tâches qui _devraient_ être simples. Le
curriculum classique en informatique ne traite donc pas de ces sujets importants
de l'écosystème informatique qui pourraient grandement venir en aide aux
étudiants.

# Le semestre manquant de votre formation en informatique

Pour combler ce manque, nous avons construit un cours portant sur l'ensemble des
sujets que nous considérons comme cruciaux pour être un bon informaticien et
développeur. Le cours en lui-même est pragmatique, met l'accent sur la pratique,
et fournit une introduction aux outils et techniques que vous pourrez appliquer
dans un grand nombre de scénarios. Les cours sont donnés lors de la "Période
d'Activités Indépendantes" du MIT de Janvier 2020 – un 'semestre' d'un mois avec
des cours faits par les étudiants. Bien que les cours sont accessibles
uniquement aux étudiants du MIT, nous allons rendre l'ensemble des cours,
ressources pédagogiques, et vidéos accessibles au publique.

Si vous pensez que cela peut vous être utile, voici quelques exemples concrets
de ce qui est enseigné dans ce cours :

## Commandes shell

Comment automatiser des tâches fréquentes et répétitives grâces à des alias, des
scripts, et des moteurs de productions ? Grâce à ce cours, vous n'aurez plus à
copier et coller des commandes depuis un fichier de texte. Ou alors à "exécuter
ces 15 commandes les unes à la suite des autres". Ou encore, "vous avez oublié
d'exécuter cette instruction" ou "vous avez oublié de passer cet argument".

Par exemple, savoir chercher à travers son historique d'instructions peut
constituer un gain de temps énorme. Dans la vidéo qui suit, nous montrons
plusieurs astuces en lien avec la navigation dans l'historique de votre shell
pour les commandes `convert`.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/history.mp4" type="video/mp4">
</video>

## Gestion de versions

Comment _bien_ utiliser un gestionnaire de version et ainsi éviter tout
désastre, collaborer avec vos collègus, et trouver rapidement certaines
modifications erronnées ? Grâce à ce cours, plus jamais de `rm -rf; git clone`.
Plus jamais (ou alors, moins) de conflits engendrés par des fusions. Plus jamais
non plus de longs blocs de code commentés ou de tracas à rechercher ce qui a
fait planter le code. Plus jamais de "oh non, est-ce qu'on vient de supprimer
tout le code ?!". Nous allons même vous apprendre à contribuer à d'autres
projets grâce à des _pull requests_ !

Dans l'exemple suivant, nous utilisons `git bisect` pour identifier quel commit
a cassé un test unitaire, puis comment corriger cela avec `git revert`.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/git.mp4" type="video/mp4">
</video>

## Édition de texte

Comment éditer efficacement des fichiers depuis le terminal aussi bien
localement qu'à distance en profitant de fonctionnalités avancées d'un éditeur ?
Fini les copier-coller de fichiers à tout va. Fini les modifications répétitives
d'un fichier.

Les macros de Vim sont l'une des fonctionnalités les plus intéressantes. Dans
l'exemple suivant, nous montrons comment convertir rapidement un tableau HTML en
un tableau CSV en utilisant des macros imbriquées.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/vim.mp4" type="video/mp4">
</video>

## Machines distantes

Comment travailler sereinement avec plusieurs machines distantes grâces aux clés
SSH et au 'terminal multiplexing' ? Fini les innombrables fenêtres de terminal
ouvertes juste pour exécuter simultanément deux commandes. Fini les saisies de
mots de passe à chaque fois que vous souhaitez vous connecter. Fini les pertes
de données suites aux déconnexions intempestives ou aux redémarrages de votre
machine.

Dans l'exemple ci-après, nous utilisons `tmux` pour garder des sessions actives
sur des machines distantes, et `mosh` pour gérer l'itinérance réseau et les
déconnexions.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/ssh.mp4" type="video/mp4">
</video>

## Recherche de fichiers

Comment trouver rapidement des fichiers que vous recherchez ? Fini les clics et
ouvertures de fichiers dans vos projets jusqu'à ce que vous avez trouvé celui
que vous cherchiez initialement.

Dans l'exemple ci-après, nous montrons comment chercher rapidement dans des
fichiers avec `fd`. Nous montrons aussi comment retrouver du code avec la
commande `rg`. Enfin, nous montrons aussi comment la commande `fasd` peut être
utilisée pour combiner `cd` et `vim` sur des fichiers récemment ou fréquemment
utilisés.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/find.mp4" type="video/mp4">
</video>

## Traitement de données

Comment éditer, visualiser, tracer des graphiques, faire des calculs sur des
données ? Et tout cela, facilement et rapidement depuis le terminal ? Fini les
copier-coller depuis des fichiers de logs. Fini les analyses statistiques à la
main. Fini les tracés de graphes sur des feuilles de calcul.

## Machines virtuelles

Comment utiliser des machines virtuelles pour tester un nouveau système
d'exploitation, isoler de projects indépendants, et pour garder son disque
principal propre ? Fini les fichiers corrompus accidentellement lorsque vous
travailliez sur votre TP de sécurité. Fini les millions de paquets installés
de façon chaotique pour gérer des différences de versions.

## Sécurité

Comment surfer sur le Web sans révéler immédiatement tous vos secrets au monde
entier ? Fini la recherche d'un mot de passe se devant de respecter des critères
farfelus. Fini les utilisations dangereuses de réseaux WiFi publiques. Fini les
discussions non-encryptées.

# Conclusion

Tout cela, et bien plus encore, sera étudié durant ces 12 cours. Chacun de ces
cours comprend aussi des exercices pour que vous puissiez vous familiariser
directement avec les outils présentés. Si vous ne pouvez pas attendre jusqu'à
Janvier, vous pouvez aussi jeter un coup d'oeil aux cours sur [Hacker
Tools](https://hacker-tools.github.io/lectures/), qui ont été donnés lors d'un
IAP (Intermediate Alternative Program) l'an passé. Il s'agit du précurseur de ce
cours, et couvre un grand nombre des sujets listés plus haut.

Nous espérons vous voir en Janvier, que ce soit à distance ou en personne !

Bon codage,<br>
Anish, Jose, et Jon
