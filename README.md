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
