---
title: Codes C des fours Samsung — la famille température des cuisinières connectées
description: Codes C-21, C-24 et C-F2 des fours Samsung — surchauffe, ventilation et ventilateur de refroidissement, causes, diagnostic et prix.
---

Cuisinières et fours encastrables Samsung — séries NE et NX, ainsi que leurs cousines NV et NZ — parlent deux dialectes d'erreurs. Les codes en deux parties comme E-08 ou E-27 concernent les organes de chauffe, tandis que les codes courts comme SE et tE signalent le panneau de commande. Entre les deux se tient la famille C : C-21, C-24 et C-F2, les codes de température et de surveillance du ventilateur répertoriés dans notre [index des codes four Samsung](https://fr.codefixcoffee.com/samsung-oven-error-codes/). Ce sont ceux qu'il faut prendre le plus au sérieux, car l'un d'eux au moins signifie que le four a réellement dépassé sa limite de température.

## Aucun journal d'erreurs à consulter

Les fours Samsung n'offrent aucun journal d'erreurs accessible à l'utilisateur. Le code reste affiché tant que la cause n'est pas corrigée ou que vous ne coupez pas l'alimentation au disjoncteur — comptez cinq à dix minutes pour les procédures de la famille C. Si le code revient après la remise sous tension, prenez-le au sérieux au lieu de réinitialiser en boucle en espérant qu'il disparaisse.

## C-21 — la coupure pour surchauffe

[C-21](https://fr.codefixcoffee.com/samsung/range-wall-oven/c-21/) vient du surveilleur de sécurité : la température interne de la cavité a dépassé la fenêtre autorisée, et la carte de commande a coupé la chauffe. Des utilisateurs ont rapporté des cuisinières devenant dangereusement chaudes avant même l'apparition du code : considérez C-21 comme un signal d'arrêt immédiat de la cuisson, pas comme une simple nuisance. Le coupable habituel est la sonde de température de cavité ou son faisceau ; la carte de commande principale arrive en second suspect.

1. Coupez l'alimentation au disjoncteur pendant cinq à dix minutes, puis relancez un test unique ; si C-21 réapparaît à la prochaine montée en température, la panne est bien réelle.
2. Débranchez la cuisinière, retirez les deux vis qui tiennent la sonde sur la paroi arrière de la cavité, puis tirez le faisceau vers vous pour le débrancher.
3. Mesurez la sonde au multimètre : environ 1 080 Ω à température ambiante est sain. Un circuit ouvert ou une valeur aberrante impose le remplacement.
4. Inspectez le connecteur du faisceau là où il passe près de la résistance chauffante — un connecteur fondu produit exactement le même code.
5. Si la sonde est bonne et que le déclenchement persiste, la carte régule mal les résistances : c'est une réparation de niveau service.

## C-24 — le contrôle de montée rapide

[C-24](https://fr.codefixcoffee.com/samsung/range-wall-oven/c-24/) se détecte autour de la zone de ventilation et d'électronique : le compartiment technique chauffe plus vite que ce que la carte attend. Samsung documente la famille C-24/C-25 comme une surchauffe liée à cette zone de ventilation. En pratique, trois causes se partagent le tableau : un ventilateur de refroidissement qui ne démarre jamais, un flux d'air obstrué autour de l'appareil, ou une sonde NTC de surchauffe fatiguée qui lit « chaud » une zone pourtant saine.

Le diagnostic tient surtout à l'oreille et à l'œil. Réinitialisez au disjoncteur, lancez une cuisson et écoutez le ventilateur de convection et de refroidissement pendant la montée en température : le silence est votre réponse. Contrôlez les dégagements d'installation et assurez-vous qu'aucune grille, dessous ou derrière la cuisinière, n'est obstruée par la menuiserie, du papier aluminium ou de la poussière. Hors tension, la sonde NTC de surchauffe se mesure directement à son connecteur — elle appartient à la même classe d'environ 1 000 Ω que la sonde de cavité, et une valeur ouverte ou dérivante conduit au remplacement. Si le ventilateur est mort, remplacez-le avant que la carte de commande ne cuise : la chaleur est la cause, la carte n'est que la victime.

## C-F2 — le retour du ventilateur de refroidissement

[C-F2](https://fr.codefixcoffee.com/samsung/range-wall-oven/c-f2/) ressemble à un code de surchauffe, mais il ne l'est généralement pas. La famille C-F signale qu'un composant surveillé ne répond plus ; pour C-F2, ce composant est le circuit du ventilateur de refroidissement : la carte d'affichage ne reçoit pas le signal de retour qu'elle attend. Soit le ventilateur ne tourne réellement pas, soit son connecteur est desserré ou brûlé, soit la ligne de retour vers la carte est défaillante.

Procédez dans l'ordre. Après une réinitialisation au disjoncteur, chauffez le four et vérifiez si la pale tourne physiquement. Un ventilateur qui tourne avec un code persistant désigne le chemin du signal : rebranchez fermement le connecteur du ventilateur sur la carte et cherchez des broches décolorées par la chaleur. Un ventilateur silencieux oriente vers une pale bloquée — poussière, ou vis tombée derrière le panneau — puis vers une mesure de l'enroulement en circuit ouvert. Ventilateur et connecteur se réparent pour peu ; un C-F2 qui survit à ces deux contrôles pointe vers l'entrée de la carte principale.

### Installation — repères France, Suisse et Belgique

En France, la norme NF C 15-100 impose un circuit dédié à la cuisson (généralement 32 A), ce qui rend le disjoncteur du four facile à repérer au tableau : utilisez-le pour vos réinitialisations plutôt que de débrancher l'appareil. Respectez aussi les dégagements indiqués dans la notice, car un four serré dans sa niche ou une ventilation obstruée recrée exactement les conditions de C-24. Les règles d'installation belges (RGIE) et suisses (NIN) exigent pareillement une ligne dédiée avec terre pour les appareils de cuisson.

## Le prix des pièces

Les sondes de température de cavité coûtent 15 à 40 € et se remplacent en dix minutes au tournevis — c'est la réparation la plus fréquente de cette famille. Les ventilateurs de refroidissement se situent entre 40 et 90 €, les faisceaux entre 10 et 20 €. L'article onéreux est la carte principale à 150-300 €, et vous ne devriez en rechercher une qu'après avoir contrôlé sonde et ventilateur. Un déplacement de technicien se facture environ 120 à 250 € diagnostic compris ; sur une cuisinière hors garantie avec une panne de carte, demander ce devis avant toute commande reste l'ordre des opérations le plus raisonnable. La [page d'assistance Samsung](https://www.samsung.com/fr/support/) publie les notices et manuels utiles pour identifier votre modèle.

Une règle vaut pour toute la famille : ne réinitialisez pas C-21 en boucle pour continuer à cuisiner. Le code signifie que la carte a déjà constaté une température qui ne lui plaisait pas, et le prochain déclenchement sera peut-être plus haut dans l'échelle.
