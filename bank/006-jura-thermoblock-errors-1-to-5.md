---
title: "Erreurs Jura 1 à 5 : la famille du thermobloc expliquée"
description: "Les erreurs Jura 1 à 5 touchent les thermoblocs, leurs sondes NTC ou leurs fusibles thermiques. Quel code pour quelle pièce, et le piège du froid."
---

Les codes 1 à 5 d'une Jura ressemblent à des numéros tirés au hasard ; ils ont pourtant un sujet commun : la chaleur. Chacun renvoie aux thermoblocs — les blocs de chauffe compacts installés en ligne, qui produisent l'eau de café et la vapeur — ou aux sondes et aux fusibles thermiques qui les surveillent. Une fois cette famille lue correctement, un code vous dit quel bloc de chauffe souffre, et si le problème relève de la mesure, de la température ou de l'alimentation.

## Deux thermoblocs, cinq codes

Une Jura abrite deux thermoblocs : celui du café chauffe l'eau d'infusion, celui de la vapeur alimente le circuit vapeur et eau chaude. Chacun porte une sonde NTC — une résistance dont la valeur évolue avec la température — qui rend compte à la carte de commande, et chacun est protégé par des fusibles thermiques qui coupent le courant si le bloc surchauffe. Les erreurs 1 à 5 sont la manière dont la carte signale qu'un de ces éléments dysfonctionne :

- **Les erreurs 1 et 2** visent le circuit de la sonde du thermobloc café.
- **Les erreurs 3 et 4** visent le thermobloc vapeur — valeur trop basse ou surchauffe.
- **L'erreur 5** signale un chauffage qui ne fournit pas.

## Les codes côté café

### Erreur 1 : défaut de sonde sur le thermobloc café

L'[erreur 1](https://fr.codefixcoffee.com/jura/automatic-machines/error-1/) apparaît quand la carte n'obtient aucune valeur exploitable de la sonde de température du thermobloc café — sur les familles S, X, J et Z, c'est le défaut de sonde classique, et sur la F comme l'E80, il s'agit en général d'une sonde endommagée. Détail à connaître : une machine qui débarque d'une voiture froide ou d'un garage peut afficher ce code sans que rien soit cassé. Si le message survient sur une machine chaude et revient immédiatement après un redémarrage, le circuit de la sonde est ouvert : la sonde, son câble, ou les fusibles thermiques qui alimentent le bloc.

### Erreur 2 : sonde interrompue — ou machine simplement froide

L'[erreur 2](https://fr.codefixcoffee.com/jura/automatic-machines/error-2/) est le code Jura le plus fréquent, et il a deux visages. Version bénigne : la machine est descendue sous environ 10 °C et la chauffe reste volontairement verrouillée jusqu'au réchauffement — courant sur les machines livrées en hiver ou entreposées dans une pièce froide. Version réelle : la sonde du thermobloc café ou ses fusibles thermiques sont passés en circuit ouvert.

Le test de réchauffage sert alors de diagnostic. Amenez la machine à température ambiante — certains utilisateurs soufflent cinq minutes avec un sèche-cheveux en position douce dans la loge du réservoir, ou remplissent le réservoir d'eau tiède (jamais chaude) — puis redémarrez. Si le code s'efface, rien n'est cassé : installez simplement la machine dans une pièce plus tempérée. S'il persiste sur une machine chaude, le circuit de mesure est ouvert, et la sonde NTC comme les fusibles doivent être contrôlés à l'intérieur.

### Le piège du froid en France, en Suisse et en Belgique

Une machine commandée en ligne et livrée par temps hivernal peut passer une nuit dans un camion proche de 0 °C : démarrée aussitôt, elle affiche l'erreur 2 sans la moindre panne. Laissez l'appareil quelques heures à température ambiante avant de le mettre sous tension — un réflexe décisif dans une cuisine non chauffée ou un chalet d'alpage. Les recommandations d'installation et d'entretien par modèle figurent sur le [site officiel Jura](https://www.jura.com).

## Les codes côté vapeur

### Erreur 3 : le thermobloc vapeur annonce trop froid

L'[erreur 3](https://fr.codefixcoffee.com/jura/automatic-machines/error-3/) est le miroir vapeur de l'erreur 1 : le thermobloc vapeur ne rapporte aucune température, que ce soit à cause de sa sonde, de son câble, ou d'une machine encore trop froide. Un angle supplémentaire : un dépôt de tartre important ralentit assez la montée en température pour déclencher le contrôle sur certains firmwares — un détartrage complet mérite donc sa place dans la liste avant tout démontage. À l'intérieur, inspectez le câble de la sonde là où il fléchit.

### Erreur 4 : surchauffe du thermobloc vapeur

L'[erreur 4](https://fr.codefixcoffee.com/jura/automatic-machines/error-4/) est celui qu'on prend au sérieux. Le thermobloc vapeur a dépassé la température prévue par la carte : soit la sonde sous-estime la réalité (tartre isolant, contacts corrodés), soit la carte de puissance n'a pas coupé la chauffe. Jura classe d'ailleurs les erreurs 2 et 4 parmi ses deux réparations les plus courantes. Après refroidissement et détartrage, la sonde se remplace en premier ; si le bloc surchauffe à nouveau avec une sonde NTC neuve, c'est que la carte de puissance n'éteint plus le chauffage et qu'elle doit être remplacée (prévoyez 120 à 250 €). Une résistance chauffante qui ne s'éteint plus présente un risque d'incendie : ne laissez pas la machine sous tension sans surveillance tant que ce code est affiché.

### Erreur 5 : la chauffe n'atteint jamais sa température

L'[erreur 5](https://fr.codefixcoffee.com/jura/automatic-machines/error-5/) signifie que le chauffage était actif mais que la température n'a jamais grimpé. Sur une Jura, ce sont presque toujours les fusibles thermiques qui protègent le thermobloc : ils claquent après une surchauffe, ou simplement avec l'âge ; l'autre cause est un élément chauffant mort. Une machine très froide peut aussi déclencher le code : réchauffez-la d'abord. À l'intérieur, mesurez au multimètre les fusibles puis l'élément — celui qui se lit ouvert est la pièce à remplacer. Cherchez ensuite pourquoi les fusibles ont claqué : tartre, relais collé, ou marche à sec quand le réservoir s'est vidé.

## La pièce qui relie tous ces codes

Dans cette famille, les fusibles thermiques et les sondes NTC sont les grands récurrents : comptez environ 25 à 40 € pour une sonde NTC d'origine, 15 à 30 € pour un jeu de fusibles, et 90 à 180 € pour un thermobloc. Quand une sonde est remplacée, les professionnels changent les fusibles dans la même intervention. Retenez aussi ce schéma : un fusible qui reclaque au bout de quelques jours signifie que la carte de puissance maintient la chauffe sous tension — non pas que le nouveau fusible a manqué de chance.

Dernier avertissement : le châssis Jura se ferme de vis de sécurité et les thermoblocs sont au potentiel du secteur. Cette famille de pannes relève de l'établi, sauf si vous êtes outillé et préparé. La réparation se justifie sur les S, Z, GIGA et E récents ; sur une Impressa de dix ans, comparez le devis avec une machine reconditionnée. Le reste de la gamme se lit dans l'[index des codes d'erreur Jura](https://fr.codefixcoffee.com/jura/).
