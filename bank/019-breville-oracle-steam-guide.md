---
title: Oracle Breville/Sage : vapeur et codes ER, par quoi commencer
description: Pannes vapeur de l'Oracle Breville/Sage : sens des codes Error et ER côté vapeur, la purge à tenter en premier, et quand le calcaire est le vrai coupable.
---

Sur une Breville Oracle, le circuit vapeur travaille plus que tout le reste : une chaudière vapeur en inox, une buse à texturation automatique, des sondes de niveau et une pompe de remplissage, le tout porté à température chaque jour. C'est aussi lui qui génère une grande partie des codes d'erreur de la machine. La famille Oracle utilise une table de service à 32 entrées que Breville ne publie pas, et au Royaume-Uni le même matériel porte un badge **Sage** — les codes sont identiques. Avant de conclure à une pièce morte, faites d'abord les vérifications peu coûteuses : la plupart des arrêts côté vapeur viennent d'un embout de buse obstrué, d'une purge qui n'a pas eu lieu ou du calcaire sur une sonde.

## Où se logent les codes vapeur dans la table Oracle

L'Oracle (BES980) et l'Oracle Touch (BES990) partagent une même table ; la BES980 affiche « Error 1 » à « Error 32 », la BES990 ajoute le préfixe ER. Les entrées liées à la vapeur se concentrent en cinq endroits :

- **Error 1 à 4** — la sonde NTC de la chaudière vapeur : circuit ouvert au démarrage, perte en fonctionnement, court-circuit dans l'une ou l'autre situation. Une seule sonde, quatre façons de la signaler.
- **Error 13 à 16** — le même quatuor pour la sonde de température propre à la buse vapeur, celle qui interrompt la texturation à la bonne température de lait. Elle loge à l'endroit le plus humide de la machine.
- **Error 18** — la chaudière vapeur ne chauffe pas normalement.
- **Error 20 et 21** — niveau d'eau de la chaudière vapeur ou problème de pompe de remplissage, et une sonde de niveau dont la lecture ne correspond pas à ce qu'attend la carte.
- **Error 26** — la chaudière vapeur a dépassé sa consigne ; **Error 32** signale une fuite ou un échec de remplissage de la chaudière vapeur.

Tout ce qui se trouve près de la buse n'est pas pour autant côté vapeur : les codes 5 à 8 appartiennent à la sonde de la chaudière café, dont [Error 8](https://fr.codefixcoffee.com/breville/oracle-bes980/error-8/) est l'entrée court-circuit en fonctionnement. La lecture du journal mémorisé aide à séparer les familles — sur la BES980, maintenez 1 CUP, 2 CUP et POWER ensemble machine éteinte pour ouvrir Error Storage et parcourir les 32 codes avec leurs compteurs.

## Par quoi commencer : la purge de la buse

Une vapeur faible ou qui crachote, ou un code survenu juste après une boisson lactée, désigne presque toujours l'embout plutôt que la chaudière :

1. Débranchez la machine et laissez la buse refroidir.
2. Dévissez l'embout vapeur et faites-le tremper dans de l'eau chaude additionnée d'un peu de détartrant ; débouchez chaque orifice avec l'aiguille de l'outil de nettoyage.
3. Lancez la purge — une dizaine de secondes de vapeur dans le bac d'égouttage, embout retiré, puis une seconde fois embout remonté.
4. Purgez la buse après chaque session de lait à partir de maintenant ; le lait séché dans l'embout est à l'origine de la plupart de ces arrêts.

Si la machine surveille la pression vapeur, comme l'Oracle Jet avec son code E16, un embout encroûté peut déclencher un code avant même que vous ne remarquiez que la vapeur a faibli. Pour aller plus loin dans le démontage, les [guides de réparation iFixit](https://www.ifixit.com/) documentent pas à pas de nombreuses machines expresso.

## Dureté de l'eau, calcaire et sondes de niveau

Là où l'eau est dure, le calcaire écrit ses propres codes d'erreur. Les sondes de niveau de la chaudière vapeur baignent en permanence dans l'eau chaude ; un dépôt les isole électriquement et la carte lit « plus d'eau » alors que la chaudière est pleine — c'est le chemin classique vers Error 20 ou 21, et vers l'échec de remplissage d'Error 32. Le tartre s'accumule aussi dans le circuit de la buse et à l'entrée de la pompe de remplissage. Un détartrage complet, cycle chaudière vapeur inclus, reste le diagnostic le moins cher que vous puissiez lancer, et il dissipe à lui seul une quantité surprenante de ces codes.

La machine sœur de la gamme illustre le même propos : la Dual Boiler garde ses codes 00 à 12 cachés dans un menu d'autotest, et le [code 00](https://fr.codefixcoffee.com/breville/dual-boiler-bes920/00/) — sonde de la chaudière vapeur non détectée — ouvre une table dont les entrées de niveau et de remplissage réagissent exactement de la même façon sous une eau dure.

## Détartrer plutôt que démonter

Détartrage d'abord, démontage ensuite — mais sachez où le détartrage cesse d'aider :

- **Détartrez d'abord** face aux codes de niveau, de sonde et de remplissage (20, 21, 32), devant une vapeur faible sans code affiché, et sur toute machine dont le dernier cycle remonte à plus de trois mois. Coût : une bouteille de détartrant.
- **Le détartrage ne réglera pas** un code de sonde qui revient immédiatement sur une machine fraîchement détartrée et chaude — que ce soit une entrée chaudière vapeur des codes 1 à 4 ou [Error 8](https://fr.codefixcoffee.com/breville/oracle-bes980/error-8/) côté café. Un code qui survit au détartrage désigne la sonde, son câble ou un connecteur.
- **Arrêtez-vous et contrôlez les joints** si Error 26 se répète : un joint torique de sonde qui fuit laisse la vapeur chauffer le câble de la sonde et imite une chaudière qui s'emballe. Des joints neufs coûtent peu ; une carte à triac incapable de couper la résistance chauffante, non.
- **Error 18** sur une machine qui ne produit plus aucune vapeur relève généralement du côté chauffage — fusible thermique, résistance chauffante ou carte — et non du calcaire : traitez-le comme une réparation, pas comme un nettoyage.

## Le prix des pièces

Les ensembles de sonde de température d'origine se situent entre 25 € et 95 € selon la sonde ; les ensembles buse vapeur, capteur inclus, autour de 60 € à 95 € ; un kit sonde et joints vaut environ 85 € et une pompe de remplissage 30 € à 60 €. Face à cela, les devis constructeur hors garantie pour un défaut interne tournent communément de 300 € à 500 € : la bouteille de détartrant d'abord, la réparation au niveau sonde ensuite, c'est presque toujours la meilleure arithmétique. Nos lecteurs britanniques retrouveront la couverture de ces mêmes tables sous badge Sage sur [l'édition britannique du site](https://fr.codefixcoffee.com/uk/).

### Eau dure : le paramètre incontournable en France, en Belgique et en Suisse

De nombreuses régions de ces trois pays ont une eau du robinet très calcaire, et le tartre est la première cause de panne vapeur sur ces machines. Mesurez la dureté avec une bandelette-test, réglez le paramètre correspondant dans le menu de votre Oracle, puis raccourcissez l'intervalle de détartrage en conséquence. Les guides d'entretien du [site de Sage Appliances](https://www.sageappliances.co.uk/) précisent la procédure machine par machine.
