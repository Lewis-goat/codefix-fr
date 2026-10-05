---
title: Codes ER Sage/Breville : décoder la table de service cachée
description: Codes ER des machines Sage et Breville : une table de service jamais publiée. La logique des codes ER01 à ER18 et la numérotation différente de l'Oracle.
---

Votre machine expresso Breville s'arrête net et affiche ER05 ? La notice ne vous dira pas ce que cela signifie — et ce n'est pas un oubli. Les codes d'erreur Breville proviennent des tables de service internes, utilisées en atelier et jamais diffusées aux propriétaires. Le même matériel se vend au Royaume-Uni sous la marque **Sage** — machines identiques, seul le badge change — donc un code ER sur une Sage Barista Touch signifie exactement la même chose que sur une Breville. Notre [section Breville / Sage](https://fr.codefixcoffee.com/breville/) couvre la gamme actuelle ; cet article vous montre comment la numérotation s'organise, pour qu'un code jamais croisé vous apprenne tout de même quelque chose d'utile.

## Pourquoi Breville ne les publie pas

La notice utilisateur couvre le nettoyage et le détartrage, pas le diagnostic. Les tables complètes vivent derrière le mode service de chaque machine : des écrans protégés par mot de passe, pensés pour les techniciens, avec compteurs d'erreurs mémorisés et lectures de capteurs en direct. Ces codes constituent un outil de réparation plus qu'une fonction grand public ; Breville ne les a jamais publiés dans un document officiel, et la plupart des propriétaires ne voient de leur vie que le code unique qui a provoqué l'arrêt. Le contraste avec Miele est frappant : la marque imprime la signification de ses codes F dans ses modes d'emploi, ce qui permet aux [pages de codes Miele](https://fr.codefixcoffee.com/miele/) de citer la notice mot pour mot.

## La table de la Barista Touch : ER01 à ER18

La Barista Touch (BES880) et la Barista Touch Impress (BES881) — même famille de cartes de commande, donc même table — utilisent une table à 18 entrées. Une fois la structure saisie, elle se lit sans effort : les codes capteurs arrivent par **groupes de quatre**, un groupe par capteur, en parcourant le circuit ouvert au démarrage, le circuit ouvert en fonctionnement, le court-circuit au démarrage puis le court-circuit en fonctionnement.

- **ER01 à ER04** — la sonde NTC du thermobloc ThermoJet, dans ses quatre variantes circuit ouvert / court-circuit. [ER01](https://fr.codefixcoffee.com/breville/barista-touch-bes880/er01/) est l'entrée « circuit ouvert au démarrage ».
- **ER05 à ER08** — la sonde de température du pichet à lait, la petite sonde de la zone du bac d'égouttage qui surveille le pichet pendant que la buse texture le lait. ER05, le circuit ouvert au démarrage, est de très loin le code Barista Touch le plus signalé, et les quatre entrées partagent une même solution.
- **ER09 à ER12** — la sonde de température en ligne (eau d'infusion), sur le même motif en quatre variantes.
- **ER13 et ER14** — erreurs de comptage du débitmètre, au démarrage puis en fonctionnement : la pompe tournait et la machine n'arrivait pas à compter l'eau qui la traversait.
- **ER15** — défaut de communication entre modules électroniques internes ; souvent une nappe délogée ou un connecteur humidifié plutôt qu'une carte morte.
- **ER16 et ER17** — le broyeur : moteur en surchauffe qui s'est mis en sécurité, puis moteur qui n'a pas terminé sa tâche dans le temps imparti.
- **ER18** — protection « E-fast », défaut électrique ou de sécurité tel qu'un courant de fuite ; c'est le code capable de faire déclencher aussi le différentiel de votre prise.

## L'Oracle, une numérotation à part

Passez à l'Oracle et la même idée s'étire. L'Oracle (BES980) et l'Oracle Touch (BES990) partagent une liste de 32 entrées, mais la BES980 les affiche en « Error 1 » à « Error 32 » tandis que la BES990 les préfixe en ER. Les seize premières suivent la logique des quatuors sur quatre sondes — chaudière vapeur codes 1 à 4, chaudière café codes 5 à 8 ([Error 8](https://fr.codefixcoffee.com/breville/oracle-bes980/error-8/) étant le court-circuit de la sonde en fonctionnement), groupe d'infusion chauffant 9 à 12, buse vapeur 13 à 16. La suite couvre les chaudières qui ne chauffent plus (17 à 19), les défauts de niveau et de remplissage de la chaudière vapeur (20 et 21), les problèmes de débitmètre (22 et 23), les sondes de niveau et la surchauffe (24 à 27), un défaut de communication de carte en 28, le broyeur en 29 et 30, le moteur de tassage en 31, et une fuite ou un échec de remplissage de la chaudière vapeur en 32.

Deux tables plus petites complètent la famille. L'Oracle Jet (BES985) utilise sa propre table E1 à E19, plus courte, et la Dual Boiler (BES920) garde ses codes à deux chiffres 00 à 12 dissimulés dans un menu d'autotest plutôt qu'à l'écran normal — une Dual Boiler peut donc vivre avec un défaut que vous n'avez jamais vu s'afficher.

## Lire le journal d'erreurs caché vous-même

Puisque ces tables relèvent des données de service, la façon de consulter l'historique de votre machine passe par ces mêmes écrans. Les chemins d'accès sont pensés pour des techniciens, mais les réparateurs les ont bien documentés :

- **Barista Touch et Oracle Touch** — coupez au mur, maintenez le bouton Power frontal en rétablissant le courant, relâchez à l'apparition du logo, saisissez le mot de passe service 00000, puis ouvrez Error Counter pour les défauts mémorisés ou Live Debug pour les températures et niveaux d'eau en direct.
- **Barista Touch Impress** — même séquence de boutons, mais le mot de passe service est 02015.
- **Oracle BES980** — machine branchée mais éteinte, maintenez 1 CUP, 2 CUP et POWER ensemble au moins une seconde ; après le long bip, appuyez sur la molette SELECT pour ouvrir Error Storage et parcourir les erreurs 1 à 32 avec leurs compteurs.

Considérez ces écrans comme de la lecture seule : notez ce qui est mémorisé, ne touchez pas aux réglages, et n'effacez le journal qu'après une réparation — c'est ainsi que vous saurez si un code revient.

## Ce que coûtent les réparations

Même face à une table non publiée, l'économie du sujet reste prévisible. Les ensembles de sonde de température se situent entre 25 € et 95 € selon la sonde concernée (buse vapeur et pichet à lait sont les chères), et les kits de joints toriques entre 10 € et 20 € ; un kit de réparation capteur-lait vaut environ 30 € à 50 € contre 80 € à 95 € pour l'ensemble d'origine. Les devis constructeur hors garantie pour un défaut interne tournent communément autour de 300 € à 500 € : une réparation au niveau capteur, aux tarifs d'un réparateur indépendant, est presque toujours le meilleur chemin. Nos lecteurs britanniques trouveront la couverture de ces mêmes tables sous badge Sage sur [l'édition britannique du site](https://fr.codefixcoffee.com/uk/).

### Bon à savoir côté européen

En France, en Belgique et en Suisse, ces machines se vendent sous la marque Sage — Breville est réservé à l'Amérique du Nord et à l'Océanie — mais les références produit (BES880, BES980…) restent identiques : citez-les pour commander vos pièces. Le [site officiel de Sage Appliances](https://www.sageappliances.co.uk/) publie notices et guides d'entretien pour toute la gamme européenne. Enfin, dans l'Union européenne, la garantie légale de conformité de deux ans s'applique en France comme en Belgique, même une fois la garantie commerciale écoulée.
