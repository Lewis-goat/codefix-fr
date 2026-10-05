---
title: Le détartrage, enfin expliqué
description: Le calcaire et les thermoblocs, pourquoi le vinaigre abîme certaines machines, citrique ou lactique, et la bonne fréquence de détartrage selon l'eau.
---

Dans toute liste de pannes de machine à café, une cause racine domine toutes les autres : le calcaire. L'eau dure transporte du calcium et du magnésium dissous ; chauffez-la, et les carbonates précipitent pour se déposer sur le métal le plus chaud de la machine. Le tartre n'est que cela, et il se cache derrière une part démesurée des codes de ce site — pannes de chauffe, pannes de vanne, échecs d'amorçage et voyants de détartrage bloqués. C'est aussi la seule famille de pannes qui se règle pour 10 €.

## Ce que le tartre fait à un thermobloc

Un thermobloc est une masse de métal parcourue d'un canal étroit où l'eau se chauffe en route vers la tasse. Le tartre se plaque sur les parois de ce canal, et le carbonate de calcium est un assez bon isolant thermique — c'est précisément là le problème.

- **La chauffe ralentit.** La résistance chauffante met plus de temps à atteindre la température cible, et un dépôt lourd peut freiner la montée au point de faire échouer les contrôles de température de la carte — la famille d'erreurs thermobloc de Jura relie explicitement le tartre à ces codes.
- **La sonde se met à mentir.** Une couche de tartre modifie la vitesse à laquelle la sonde de température du bloc perçoit la chaleur : la carte peut croire la machine en surchauffe, ou incapable de chauffer, sans qu'aucun des deux soit vrai.
- **Le bloc fonctionne trop chaud.** Un métal isolé thermiquement monte au-dessus de sa température de conception, ce qui met à rude épreuve les fusibles thermiques chargés de le protéger. Un thermobloc entarté à bloc se remplace, il ne se nettoie plus : comptez 90 à 180 € sur une Jura, pour un tartre qu'une bouteille de détartrant aurait dissous.

## Ce que le tartre fait aux vannes et aux petits orifices

Le second terrain de dégâts, c'est tout ce qui est étroit. Sur les machines Jura à vanne céramique motorisée, le tartre rigidifie le disque jusqu'à l'empêcher d'atteindre la position commandée par la carte — c'est très exactement ce que rapporte l'[erreur 6](https://fr.codefixcoffee.com/jura/automatic-machines/error-6/), et pourquoi un détartrage complet constitue la première étape, gratuite, de sa résolution. Les entrées étroites se bouchent de la même façon : l'[erreur 05 Philips](https://fr.codefixcoffee.com/philips-saeco/espresso-machines/error-05/) peut survivre à l'amorçage parce qu'une prise d'eau entartée n'autorise plus la pompe à aspirer le moindre filet. Les capteurs de niveau y ont droit aussi — du tartre sur un flotteur de réservoir explique classiquement un faux message « réservoir vide » sur un réservoir plein. Et un débitmètre entarté ne compte plus, l'une des façons dont un [voyant De'Longhi reste allumé après le détartrage](https://fr.codefixcoffee.com/delonghi/magnifica-dinamica/descale-light-stays-on-after-descaling/) : la machine n'a jamais enregistré le cycle que vous avez lancé.

## Pourquoi le vinaigre nuit à certaines machines

Le vinaigre ménager est de l'acide acétique, et pour une machine à espresso il cumule trois défauts. Il est faible : il faut un long contact pour ramollir un tartre compacté dans un canal exigu. Il attaque les raccords en laiton chromé et gonfle certains joints caoutchouc. Et son odeur survit à de nombreux rinçages dans les tubulures plastiques. [Nespresso](https://www.nespresso.com/) est explicite sur la conséquence — ne détarrez pas au vinaigre, cela endommage le circuit et fait sauter l'assistance — un rappel utile quand un [clignotement orange de Vertuo](https://fr.codefixcoffee.com/nespresso/vertuo-machines/blinking-lights/) vous envoie vers la routine de détartrage. Une bouilloire ? Le vinaigre convient. Une machine avec pompe, vanne et garantie ? Passez à un détartrant dédié, comme les [produits d'entretien De'Longhi](https://www.delonghi.com/) le préconisent.

## Acide citrique ou acide lactique

Presque tous les détartrants du commerce reposent sur l'un de ces deux acides alimentaires :

- **Acide citrique** — vendu en poudre, 3 à 6 € pour de quoi tenir un an dans la plupart des foyers ; fort et rapide sur le tartre lourd. C'est la base de la plupart des détartrants universels, et bien rincé, il ne laisse rien derrière lui.
- **Acide lactique** — plus doux et quasi inodore, présent dans les bouteilles de marque livrées avec les machines. Plus tendre avec les joints et les surfaces chromées, en échange d'un temps de contact un peu plus long pour dissoudre le même tartre.

L'un ou l'autre fonctionne dès lors qu'il passe par le programme de détartrage de la machine elle-même. Ce qui compte, c'est de mener le cycle au bout : les compteurs de rappel ne valident qu'un cycle complet lancé depuis le menu détartrage, buse installée et phase de rinçage incluse. Arrêtez en route ou improvisez au pichet, et [le voyant reste allumé](https://fr.codefixcoffee.com/delonghi/magnifica-dinamica/descale-light-stays-on-after-descaling/).

## À quelle fréquence — tout dépend de votre eau

Les rappels des machines se calent sur des volumes — tasses servies, litres pompés — jamais sur la dureté de l'eau : en région calcaire, il faut détarter avant que le voyant ne s'allume. Une règle pratique :

- **Eau douce** (moins d'environ 7 °dH, soit 125 ppm) : le rappel de la machine suffit, en pratique tous les 3 à 6 mois.
- **Moyennement dure** (7 à 14 °dH) : tous les 2 à 3 mois.
- **Dure** (plus de 14 °dH) : environ tous les mois, et plus tôt si le débit ralentit ou si la pompe devient bruyante.

Un étui de bandelettes de dureté coûte 5 à 10 €, et votre distributeur d'eau publie la valeur de votre commune. Les signes tardifs concordent d'une marque à l'autre : cafés maigres et lents, pompe sonore, boisson moins chaude — puis les codes cités plus haut. Détartrez au calendrier et la plupart de ces codes n'arriveront jamais ; une bouteille à 10 € reste la réparation la moins chère que ce site recommandera.

### Dureté de l'eau — repères France, Suisse et Belgique

La France mesure la dureté en degrés français (°f), avec la conversion 1 °dH ≈ 1,78 °f : le Bassin parisien dépasse souvent 25 °f, soit environ 14 °dH, d'où l'intérêt d'un détartrage proche du mensuel pour les machines à espresso. En Suisse romande, l'eau du Lac Léman est douce et descend sous 5 °dH, tandis que les régions calcaires du Jura donnent des eaux nettement plus dures. En Belgique, tout dépend du sous-sol : douce en Ardennes, l'eau devient très dure en Hainaut et autour de Liège, sur les roches calcaires.
