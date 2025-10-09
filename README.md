# Linux_Evaluation

## Mission 1

**Objectif:**

Sur cette mission on nous demande de de nous rendre tout en haut du Donjon.

Pour cela j'ai utiliser les commande de base de déplacement

    /ls // afficher l'arborésence
    /cd <dossier/> // ce deplacer dans le dossier
    /ls <dossier/> //pour afficher l'arborésenace de ce fichier

<img src="/assets/mission1/mission1.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission1/check.png" height="80%" widght="80%">

## Mission 2

**Objectif:**

Allez dans la cave du château.

Pour cela j'ai utiliser les commande de base de déplacement

    /ls
    /cd <dossier/>
    /ls <dossier/>
    /cd ../ // retour de 1 en arriere

<img src="/assets/mission2/mission2.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission2/check.png" height="80%" widght="80%">

## Mission 3

**Objectif:**

On nous demande de nous deplacer en 1 seul fois a la salle du trone et au repertoire d'origine

    /cd //pour aller au debut de notre game.sh
    /cd Chateau/Batiment_principal/Salle_du_trone

pour ce deplacer en une fois en donnant l'adresse complete fu fichier suivant la ou nous somme

    /cd lieux1/lieux2/lieux3

et pas faire

    /cd lieux1/
    /cd lieux2/
    /cd lieux3/

<img src="/assets/mission3/mission3.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission3/check.png" height="80%" widght="80%">

## Mission 4

**Objectif:**

On nous demande de crée une "Hutte" et a l'intérieur de cette derniere on veut crée un "Coffre"

je me suis donc deplacer jusqu'a la foret:

    /cd
    /cd <dossier/>
    /ls

et j'ai crée ce que l'on me demander

    /mkdir Hutte
    /mkdir Hutte/Coffre //pour pas avoir a me deplacer dedans

<img src="/assets/mission4/mission4.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission4/check.png" height="80%" widght="80%">

## Mission 5

**Objectif:**

On nous demande de rm tout les araignées qui ce trouve dans la cave du chateau

je me deplace

    /cd
    /cd <dossier/>
    /ls

et je les retire en utilisant rm

    /rm araignee_1 araignee_2 araignee_3

pour tous les rm en une ligne et pas

    /rm araignee_1
    /rm araignee_2
    /rm araignee_3

<img src="/assets/mission5/mission5.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission5/check.png" height="80%" widght="80%">

## Mission 6

**Objectif:**

Il nous faut Déplacer les pieces du jardin donc notre coffre dans la hutte de la mission précédante

pour ca j'utilise une commande

    /rm piece_1 piece_2 piece_3 ~/Foret/Hutte/Coffre

pour tout deplacer d'un coup vers notre coffre en lui donnant sont addresse au lieux de faire

    /rm piece_1 ~/Foret/Hutte/Coffre
    /rm piece_2 ~/Foret/Hutte/Coffre
    /rm piece_3 ~/Foret/Hutte/Coffre

<img src="/assets/mission6/mission6.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission6/check.png" height="80%" widght="80%">

## Mission 7

**Objectif:**

Il nous faut Déplacer tout les pieces cacher du jardin donc notre coffre dans la hutte de la mission précédante

comme c'est "piece" sont cacher on doit utiliser

    /ls -a //pour affichier les fichier cacher

puis on les move

    /rm piece_1 piece_2 piece_3 ~/Foret/Hutte/Coffre

<img src="/assets/mission7/mission7.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission7/check.png" height="80%" widght="80%">

## Mission 8

**Objectif:**

On doit rm toute les arraignées présente dans la cave

    /ls -a ~/Chateau/Cave/
    /rm ~/Chateau/Cave/*araignee*

en utilisant les \*\* j'indique que cette comande visee tout les fichier contenant le mots entre les \*\*

<img src="/assets/mission8/mission8.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission8/check.png" height="80%" widght="80%">

## Mission 9

**Objectif:**

On doit rm toute les arraignées cacher présente dans la cave

    /ls -a ~/Chateau/Cave/
    /rm ~/Chateau/Cave/.*araignee*

on rajoute le . pour indiquer que on prene en compte les fichiers cacher

<img src="/assets/mission9/mission9.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission9/check.png" height="80%" widght="80%">

## Mission 10

**Objectif:**

crée un copie des étendard présent dans la grande salle dans le chateau vers mon coffre dans ma hutte

pour evite de me deplacer je reste dans mon fichier et je donne juste l'addresse pour que les commande face le deplacement a ma place

    /ls ~/Chateau/Grande_salle/

et ensuite j'utilise cp pour copier mes etendard

    /cp ~/Chateau/Grande_salle/etendard_1 ~/Foret/Hutte/Coffre/
    /cp ~/Chateau/Grande_salle/etendard_2 ~/Foret/Hutte/Coffre/
    /cp ~/Chateau/Grande_salle/etendard_3 ~/Foret/Hutte/Coffre/
    /cp ~/Chateau/Grande_salle/etendard_4 ~/Foret/Hutte/Coffre/

je donne l'addresse des etendard et l'adresse de direction de la copie

<img src="/assets/mission10/mission10.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission10/check.png" height="80%" widght="80%">

## Mission 11

**Objectif:**

crée un copie des tapisserie présent dans la grande salle dans le chateau vers mon coffre dans ma hutte

Probleme, il y en a beaucoup alors on vas faire cela

    /cp ~/Chateau/Grande_salle/*tapisserie* ~/Foret/Hutte/Coffre

les \*\* vont viser tout les tapisserie présent dans le /Chateau/Grande_salle/ et vont les deplacer vers /Foret/Hutte/Coffre

<img src="/assets/mission11/mission11.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission11/check.png" height="80%" widght="80%">

## Mission 12

**Objectif:**

on doit crée une copie du plus ancien tableau présent dans le 1er etage du donjon /Chateau/Donjon/Premier_etage/

pour ca on utilise

    /ls -l ~/Chateau/Donjon/Premier_etage/ //cela nous donne plus d'information notament la date de creation

ensuit on fait comme pour les autre missions

    cp ~/Chateau/Donjon/Premier_etage/tableau_zNyYvvKI ~/Foret/Hutte/Coffre

on copie le tableau vers le Coffre

<img src="/assets/mission12/mission12.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission12/check.png" height="80%" widght="80%">

## Mission 13

**Objectif:**

on me demande de trouve le jour que sera le 25-05-2003.

pou cela rien de plus simple on prennt l'année et on fait

    /cale 2003

ca nous affiche le calendrier et plus ca nous de trouver le jour

**Voici la vérification:**

la reponse est donc le dimanche

<img src="/assets/mission13/mission13.png" height="80%" widght="80%">

## Mission 14

**Objectif:**

on me demande de crée un racourcci pour la commande ls -A on doit faire juste "la"

    alias la='ls -A'

alias est la pour crée un raccourci la on dit que si on rentre "la" dans le terminale ca lance la commande ls -A

<img src="/assets/mission14/mission14.png" height="80%" widght="80%">

## Mission 15

**Objectif:**

Cree un fichier journal.txt dans notre coffre

on utilise nano qui vas crée le fichier en plus de l'éditer puisque qu'il n'est pas crée il le fait

    /nano ~/Foret/Hutte/Coffre/journal.txt

<img src="/assets/mission15/mission15.1.png" height="60%" widght="60%">

**Voici la vérification:**

<img src="/assets/mission15/mission15.2.png" height="80%" widght="80%">

## Mission 16

**Objectif:**

on doit crée un alias de journal qui nous permet d'éditer notre journal.txt

    /alias journal='nano ~/Foret/Hutte/Coffre/journal.txt'

on précis bien la route depuis l'origine sinon ca ne fonctionne pas puisque l'addresse ne sera pas la bonne

~/Foret/Hutte/Coffre/journal.txt

**Voici la vérification:**

<img src="/assets/mission16/mission16.png" height="80%" widght="80%">

## Mission 17

**Objectif:**

On doit supprimer la raine des arraignées en 20 secondes ca cachette ce situe dans la cave donc on doit ce deplacer jusqu'a elle et la rm tout ca ce passe dasn des fichiers et dossier cacher .

    /rm <.nom>
    /la -a
    /cd <.dossier>

pour aller plus vite on utilise la touche TAB pour ecrire les noms des fichiers et dossiers

<img src="/assets/mission17/mission17.png" height="80%" widght="80%">

## Mission 18

**ERREUR:**

je ne peut pas faire cette exercice.

<img src="/assets/mission18/mission18.png" height="80%" widght="80%">

## Mission 19

**Objectif:**

on nous demande de lancer 3 feux d'artifice donc la command _flarigo_ pour lancer les feux d'artifice sauf faut faire un _gsh check_ en même temps de lancer nos feux d'artifice

    /gsh check & flarigo & flarigo & flarigo

on utilise donc des & pour lancer nos commande en même temps.

<img src="/assets/mission19/mission19.png" height="80%" widght="80%">

## Mission 20

**Objectif:**
