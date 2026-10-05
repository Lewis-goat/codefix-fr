---
title: Breville Dual Boiler 00 à 12 — les codes à deux chiffres
description: La Dual Boiler BES920 consigne ses pannes en codes 00 à 12 dans un menu d'autodiagnostic caché. Familles de codes, côté vapeur ou côté café, remèdes.
---

Chez Breville, la plupart des machines à espresso annoncent leurs pannes sur l'écran ordinaire : la Barista Touch affiche des codes ER, l'Oracle des codes « Error », l'Oracle Jet des numéros E. La **Dual Boiler BES920** joue dans un autre registre. Sa table de pannes est une série de codes à deux chiffres en clair, **00 à 12**, et elle loge dans un menu d'autodiagnostic caché plutôt que sur l'affichage du quotidien. Inutile d'épier la façade pendant une journée normale — encore faut-il connaître la combinaison de touches.

La numérotation mérite deux minutes d'attention, car elle forme un tableau remarquablement ordonné : le bloc où siège un code vous dit la nature de la panne, et dans chaque bloc le code désigne la pièce qui se plaint.

## Lire le journal d'erreurs

On atteint le journal depuis le menu d'autodiagnostic :

1. Coupez la machine au mur.
2. Maintenez **EXIT** et **MANUAL** enfoncés tout en rétablissant l'alimentation — le menu d'autodiagnostic apparaît.
3. Appuyez sur **MENU** jusqu'à l'élément 3, le journal d'erreurs. L'élément 4 affiche l'état de niveau des chaudières, noté LLL (bas) ou HHH (haut).
4. Dans le journal, **MENU** fait défiler les codes 00 à 12, chacun avec un compteur mémorisé.
5. Sur « ErSt », maintenez **MANUAL** jusqu'au bip pour effacer les codes enregistrés — le compteur de tasses, lui, ne se remet pas à zéro.

Le compte pèse autant que le code. Une panne comptée une fois il y a un an appartient à l'histoire ; une panne dont le compteur grimpe chaque semaine est un problème vivant qui mûrit.

## Ce que couvre la famille 00

Les codes **00 à 05** forment le bloc des capteurs de température, organisé en trois paires. Dans chaque paire, le numéro le plus bas signale un capteur **non détecté** — la carte lit un circuit ouvert — et le numéro le plus haut une lecture en **court-circuit** :

- **00 et 01** — capteur de température de la chaudière vapeur, non détecté puis court-circuit.
- **02 et 03** — capteur de température de la chaudière café, non détecté puis court-circuit.
- **04 et 05** — capteur de température du groupe d'infusion chauffé, non détecté puis court-circuit.

La BES920 assemble deux chaudières en inox et un groupe chauffé : ces trois sondes couvrent donc ses trois zones chauffantes. La [page du code 00](https://fr.codefixcoffee.com/breville/dual-boiler-bes920/00/) traite de la sonde de la chaudière vapeur, et son conseil pratique vaut pour les cinq autres : réinsérez et inspectez le connecteur de la sonde avant d'acheter la moindre pièce, et traquez l'humidité — de l'eau qui s'immisce dans un connecteur se lit tantôt en circuit ouvert, tantôt en court-circuit selon sa position. Les ensembles de sondes NTC d'origine coûtent de 25 à 90 € selon laquelle des trois est visée ; les kits de joints toriques, à 10 ou 20 €, sont souvent les vrais coupables.

## Côté vapeur contre côté café

Le reste de la table se scinde selon la même ligne matérielle que les paires de sondes :

- **Chaudière vapeur** — 06 (problème de pompe au démarrage), 07 (défaut de niveau d'eau ou de pompe) et 11 (surchauffe détectée).
- **Chaudière café, le côté infusion** — 08 (problème de pompe ou de débit), 09 (défaut de niveau d'eau) et 10 (surchauffe détectée).
- **Groupe d'infusion** — 12 (surchauffe détectée).

### Les codes qui voyagent ensemble

Ces pannes s'enchaînent, et c'est bien pourquoi lire tout le journal vaut mieux qu'un code isolé. Le code 08 signifie que la pompe a tourné et que le débitmètre n'a rien vu passer — le plus souvent du tartre sur l'hélice du débitmètre, ou une petite pompe qui vibre sans pousser d'eau, et le détartrage est le premier geste dans les deux cas. Le code 11, une surchauffe de la chaudière vapeur, suit habituellement une chaudière qui ne se remplit plus — vérifiez si 07 ou 08 affiche lui aussi un compteur — car la résistance chauffante continue de chauffer une chaudière à niveau bas ; un joint de sonde qui fuit est l'autre cause. Avant de commander quoi que ce soit, consultez l'élément 4 du menu d'autodiagnostic : un état de niveau en désaccord avec ce que vous entendez au remplissage vous dit de quel côté se trouve réellement la panne.

Le code 12, surchauffe du groupe d'infusion, est le bout rare de la table — et celui où la récurrence compte le plus. Une surchauffe qui revient sans cesse pointe une carte de puissance qui maintient un chauffage en marche plutôt qu'une dérive de sonde. La [page du code 12](https://fr.codefixcoffee.com/breville/dual-boiler-bes920/12/) y consacre son développement.

## Le prix des pièces

- Détergent de détartrage pour les codes de débit et de niveau — environ 10 €, et il en règle une belle part.
- Pompe de remplissage — de 30 à 60 €.
- Sonde de chaudière vapeur avec kit de joints — environ 85 € ; joints toriques seuls, 10 à 20 €.
- Fusible thermique — 10 à 20 €, mais trouvez d'abord pourquoi il a claqué.
- Triac ou carte de puissance — de 80 à 150 €.

Les devis constructeur hors garantie pour une panne interne se situent couramment entre 300 et 500 € et au-delà — une pompe ou une sonde méritent donc l'auto-réparation, une carte sur une machine âgée mérite d'abord un devis. L'eau et le courant secteur se partagent le sommet de la chaudière — débranchez avant de toucher aux sondes.

### La Dual Boiler en France, en Belgique et en Suisse

Dans ces trois pays, la machine se vend sous la marque **Sage** (the Dual Boiler) — le nom européen de Breville — et le service après-vente passe par le [site officiel Sage Appliances](https://www.sageappliances.co.uk). Compte tenu de la dureté fréquente de l'eau du robinet dans ces régions, un détartrage régulier est votre meilleure assurance contre les codes 08 et 09. Pour visualiser connecteurs et sondes avant le démontage, les guides illustrés de [iFixit](https://www.ifixit.com) offrent un bon point de repère.

Pour comprendre comment les autres machines de la gamme formulent leurs codes, voyez la [section Breville](https://fr.codefixcoffee.com/breville/) — les modèles à codes ER partagent des idées de diagnostic, mais pas la numérotation.
