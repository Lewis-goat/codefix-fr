---
title: Lave-vaisselle GE 888 et CFE — quand la carte de commande est en cause
description: Affichage 888 ou CFE sur un lave-vaisselle GE — ce que le blocage de l'écran signifie, les contrôles d'eau à mener et le remplacement de la carte.
---

La plupart des codes des lave-vaisselle GE désignent quelque chose de mouillé — C1 est une vidange qui dépasse le délai, C6 une eau qui n'a jamais chauffé, H2O une absence totale d'eau. Et puis il y a les deux codes qui pointent vers l'électronique, sèche celle-là. [888](https://fr.codefixcoffee.com/ge/dishwasher/888/) signifie que la carte de commande principale a échoué à son propre autotest ; [CFE](https://fr.codefixcoffee.com/ge/dishwasher/cfe/) signifie que l'interface utilisateur montée dans la porte et la carte principale ne se parlent plus. Aucun des deux ne déguise un filtre encrassé. Cet article décrypte ce blocage de l'affichage, les contrôles d'eau utiles avant de commander une carte, et la réalité d'un remplacement.

## Ce que signifie l'affichage 888

Sur un afficheur à segments, 888 correspond à toutes les positions de chiffres allumées simultanément. Ce n'est pas un numéro de panne au sens des codes C — c'est la carte qui allume tout parce qu'elle a raté son propre contrôle et ne peut plus dérouler son programme normal. Là où [C1](https://fr.codefixcoffee.com/ge/dishwasher/c1/) dit « la pompe de vidange a tourné deux minutes et la cuve est restée pleine », 888 dit que l'ordinateur qui aurait dû s'en apercevoir est lui-même la pièce cassée.

Le déclencheur habituel est électrique plutôt que mécanique : une surtension — orage, groupe électrogène — corrompt un registre mémoire de la carte, et dès lors l'autotest échoue à chaque démarrage. Voilà pourquoi le conseil classique — couper au disjoncteur pendant 60 secondes puis relancer — mérite un essai, et un seul. Une réinitialisation efface un bug passager ; elle ne répare pas une mémoire corrompue. Si 888 revient après la remise à zéro, les dégâts sont faits et la carte doit être remplacée. Parfois la cause n'est pas une surtension mais une fuite qui a mouillé la carte — d'où les contrôles ci-dessous.

## CFE, l'autre code de carte

CFE est un défaut de communication : l'interface de porte et la carte de commande ont perdu leur liaison. Les suspects habituels se comptent sur une main — un faisceau desserré ou effiloché là où le câblage franchit la zone de charnière de porte, un connecteur tombé humide, ou l'une des deux cartes qui lâche. L'ordre du diagnostic compte ici, car les deux cartes ne se paient pas au même prix : réinitialisez d'abord au disjoncteur, puis, courant coupé, inspectez et rebranchez le faisceau aux deux extrémités en cherchant l'usure là où la porte fléchit à chaque cycle. Ce n'est qu'avec un faisceau sain que l'on passe aux cartes — et l'interface utilisateur est d'ordinaire la moins chère des deux.

## Les contrôles d'eau sur la carte

Avant de commander la moindre pièce, accordez dix minutes à l'élimination de la piste de fuite — une carte neuve installée dans une machine mouillée meurt aussi :

1. Tirez le lave-vaisselle assez loin pour voir dessous, et cherchez de l'eau ou des auréoles sur le sol.
2. Déposez la plinthe en bas de façade et inspectez le socle à la lampe torche — de l'eau stagnante dans le bac de fond signifie qu'une fuite a rendu visite au voisinage de la carte.
3. Passez en revue les sources évidentes — mousse née d'un mauvais détergent, joint de porte abîmé, tuyau fendu, joint de pompe de vidange qui suinte.
4. Si quelque chose est humide, séchez entièrement et réparez la fuite d'abord, puis réinitialisez et retestez. Une carte éclaboussée une fois puis séchée récupère parfois ; une carte immergée dans l'eau stagnante, jamais.

Si tout est parfaitement sec et que 888 ou CFE revient malgré la coupure de 60 secondes au disjoncteur, commandez la carte.

## La réalité du remplacement — une carte enfichable

Voici la bonne nouvelle que les mots « carte de commande » masquent — sur les lave-vaisselle GE, la carte est un module enfichable, pas une pièce soudée. Elle se loge derrière la plinthe ou dans la porte selon le modèle, et le travail se résume à ceci :

1. Coupez le courant au disjoncteur — pas seulement sur l'interrupteur — avant de déposer le moindre panneau.
2. Ouvrez la plinthe ou la façade de porte pour dégager la carte.
3. Photographiez les connecteurs avant de toucher à quoi que ce soit.
4. Débranchez chaque connecteur de l'ancienne carte, montez la neuve, puis rebranchez aux mêmes emplacements.

Aucune soudure, aucun câblage à refaire — mais les connecteurs sont nombreux et non étiquetés, et c'est précisément ce qui justifie la photo. Une carte de commande principale coûte de 90 à 200 €, une interface utilisateur de 60 à 120 € : la réparation se joue donc au jugement — rentable sur un lave-vaisselle de moins de six ou sept ans, à comparer au prix d'une machine neuve au-delà. Une visite à domicile de technicien ajoute 120 à 250 € de diagnostic plus la pièce si vous préférez déléguer ; les tutoriels de démontage de [iFixit](https://www.ifixit.com) aident à visualiser les panneaux avant de se lancer.

### Le cas de la France, de la Suisse et de la Belgique

Les lave-vaisselle GE se vendent presque exclusivement en Amérique du Nord — en France, en Belgique ou en Suisse, on en hérite généralement par importation ou déménagement. Les cartes de rechange (références WD) transitent le plus souvent par une expédition outre-Atlantique, alors anticipez délais et frais de douane avant de planifier la réparation. Si la machine a été importée, vérifiez qu'elle est bien alimentée en 120 V via un transformateur adapté — un transformateur sous-dimensionné reste une cause classique de carte grillée. Les notices et références officielles se contrôlent sur [l'assistance GE Appliances](https://www.geappliances.com).

## En résumé

L'[index des lave-vaisselle GE](https://fr.codefixcoffee.com/ge/dishwasher/) couvre tous les codes, mais l'arbre de décision des codes de carte tient en une ligne — une réinitialisation au disjoncteur, dix minutes de contrôles de fuite, puis soit un rebranchement de faisceau (CFE), soit un échange de carte. Ce que ce n'est jamais — un problème de filtre, un problème de détergent, ou quelque chose qu'une troisième réinitialisation finirait par arranger.
