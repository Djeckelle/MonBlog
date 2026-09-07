---
title: "La dette technique est une dette carbone"
date: 2026-09-07
description: "Green IT : on demande à une DSI de mesurer son empreinte, et elle découvre qu'elle ne peut pas. Deuxième article d'une série de quatre — comment la dette d'information sur le patrimoine applicatif bloque simultanément l'obsolescence, le FinOps, la dette technique et le GreenOps, et pourquoi les directions RSE et les architectes doivent travailler ensemble. (2/4)"
categories: ["Architecture"]
tags: ["green IT", "dette technique", "architecture", "gouvernance", "patrimoine applicatif", "Continuous Architecture"]
draft: false
cover:
    image: "/images/articles/green-it-2-dette-information-fr.jpg"
    alt: "Le référentiel applicatif relié aux éléments de configuration, et les quatre indicateurs — obsolescence, FinOps, dette technique, GreenOps et reporting RSE — qui s'éteignent ensemble quand il se dégrade"
    caption: "Une dette d'information n'est pas une dette parmi d'autres : c'est celle qui empêche d'instruire les autres."
    relative: false
    hidden: false
---

*Série Green IT — Article 2/4*

---

Un jour, on demande à une DSI de mesurer l'empreinte carbone de son patrimoine applicatif. La demande est légitime, le sponsor est solide, l'échéance est réglementaire.

Et c'est là qu'on découvre que le chiffre est hors de portée. Pas parce que la méthode manque — parce que les données sur lesquelles il faudrait l'appliquer ont été mises à jour en masse, il y a quelques années, selon une règle dont plus personne ne connaît le contenu.

Un mot avant d'aller plus loin, car ce texte s'ouvre sur ce qui ressemble à un hors-sujet. Aucune dette carbone ne se chiffre sans mesurer la dette technique, et aucune dette technique ne se mesure sur un patrimoine qu'on ne sait plus décrire. Le détour est le chemin.

> **En bref**
> - Le référentiel applicatif n'est pas un inventaire administratif : c'est l'instrument qui rend calculables l'obsolescence, le FinOps, la dette technique et le GreenOps. Quand il se dégrade, les quatre s'éteignent ensemble.
> - Ce qu'on ne sait plus rattacher, on ne sait plus décommissionner — et ce qu'on ne décommissionne pas continue de porter une empreinte de fabrication déjà payée, qui ne s'amortit sur rien.
> - Les directions RSE savent quels principes doivent s'appliquer ; les architectes savent comment un principe devient une exigence opposable dans une décision. Ni les uns ni les autres ne peuvent le faire seuls.

{{< imprimer >}}

## On vous demande un chiffre que vous ne pouvez pas produire

Reprenons la scène, parce qu'elle se rejoue partout et qu'elle est instructive.

La direction RSE a besoin d'alimenter son reporting. Elle demande, très raisonnablement, de quoi est fait le parc : combien d'applications, hébergées où, sur quels équipements, depuis quand, pour quel usage. Rien d'exotique. Ce sont les questions qu'un référentiel applicatif est censé documenter.

Les réponses ne viennent pas. Ou plutôt : elles viennent, mais personne n'ose s'en servir. Parce qu'à un moment, quelques années plus tôt, une vague de mise à jour en masse a rempli les champs vides selon une règle du 80/20 — l'essentiel juste, le reste approximé. La règle n'a pas été documentée. Les personnes qui l'ont appliquée sont parties. Et aujourd'hui on regarde des valeurs sans savoir lesquelles ont été renseignées et lesquelles ont été devinées.

**On ne demande pas à cette organisation de réduire son empreinte. On lui demande de la mesurer, et elle ne peut pas.**

## La mise à jour en masse était la seule sortie rationnelle

Il faut comprendre comment on en arrive là, parce que le réflexe — chercher qui a mal fait son travail — nous ferait manquer l'essentiel.

Le référentiel applicatif est le plus souvent sous la responsabilité d'un architecte d'entreprise. Il porte l'outil, la pratique, la qualité de la donnée. Il subit la pression de tous les pilotes de KPI, qui ont besoin que ce soit à jour. Mais il ne produit pas la donnée : ce sont les autres architectes — solution, produit, full stack — qui l'alimentent au fil de leurs missions.

Et ceux-là font, très légitimement, ce qui suffit à mettre en production. Le minimum exigé par la porte de sortie, pas le renseignement complet d'un référentiel dont ils ne voient pas l'usage aval.

**Le responsable du référentiel porte donc une redevabilité sans autorité.** On lui demande la qualité d'une donnée qu'il ne produit pas, auprès de gens qui ne lui sont pas rattachés, sans levier autre que la persuasion.

Puis arrive un programme de la direction IT qui a besoin de données consolidées, avec une échéance. Le responsable de l'outil, poussé dans ses retranchements, arbitre à la grosse maille et met à jour en masse. Ce n'est pas une faute. Dans la position où on l'a placé, c'est la seule sortie possible.

Reconnaissez la forme. C'est celle du premier article de cette série : chacun optimise dans son périmètre, chaque décision est défendable isolément, et le résultat d'ensemble ne l'est pas. À une différence près, et elle est de taille. Dans le couloir aux écrans, l'organisation prenait des décisions incohérentes. Ici, elle perd la capacité de décider du tout.

## Ce qu'on ne sait plus

L'information manquante ne se signale pas. Elle se découvre à l'occasion : un grand plan de nettoyage avec un sponsor déterminé, un incident, une vague de remplacement de composants obsolètes, un audit, une facturation qu'on n'arrive pas à réconcilier.

Et les questions qui reviennent alors sont d'une banalité confondante. Qui est le responsable métier de cette application ? Est-elle encore en production ? Est-ce du développement interne ou un produit acheté ? À quoi sert-elle, exactement ?

Aucune n'est technique. Toutes sont sans réponse.

La cause est souvent tenue : la personne qui tenait l'information est partie, et dans le passage de poste on a oublié de dire qu'il fallait renseigner ces champs. Rien de dramatique sur le moment. Une omission par départ, multipliée par dix ans de rotation.

Dans les organisations où j'ai travaillé, l'ordre de grandeur est constant : environ un tiers des applications — celles qu'on juge critiques pour le métier — sont renseignées à hauteur de 80 %. Le reste dérive. Je donne ce chiffre pour ce qu'il est, une observation de terrain répétée, pas une statistique.

## Une dette qui bloque toutes les autres

Voilà pourquoi le sujet mérite mieux que le rayon « qualité de données ».

Sans rattachement fiable entre les applications et leurs éléments de configuration, quatre choses deviennent incalculables **en même temps** :

1. **L'obsolescence.** On ne sait pas quel composant supporte quoi, donc on ne sait pas ce qui casse si on le remplace, ni ce qui est exposé si on ne le remplace pas.
2. **Le FinOps.** On ne sait pas rattacher une facture d'hébergement à un service rendu, donc on optimise à l'aveugle ou pas du tout.
3. **La dette technique.** On ne sait pas dater le patrimoine ni mesurer son écart aux standards, donc on ne peut pas la chiffrer — et une dette qu'on ne chiffre pas ne se négocie pas en comité.
4. **Le GreenOps et le reporting RSE.** On ne sait pas quel matériel porte quel usage, donc l'empreinte reste une estimation de couloir.

**Une dette d'information n'est pas une dette parmi d'autres. C'est celle qui empêche d'instruire les autres.** C'est pour cette raison qu'elle passe inaperçue : elle ne produit aucun symptôme propre, seulement l'incapacité chronique à répondre aux questions qu'on pose ailleurs.

D'où le déplacement que j'observe dans les organisations où cela fonctionne — et il en existe. L'application n'y est pas déclarée au moment de la mise en production, quand le référentiel devient une formalité de sortie. Elle est déclarée dès la conception fonctionnelle. Parce que c'est là qu'on réserve des ressources, qu'on planifie des jalons, qu'on définit des fitness functions, qu'on construit des runways. Parce qu'il faut un identifiant pour rattacher l'objet à une capacité de l'entreprise, ne serait-ce que pour instruire l'étude d'opportunité.

Le bénéfice n'est pas administratif, il est décisionnel. On trace le pourquoi : pourquoi ce projet est allé jusqu'en production, ou pourquoi il s'est arrêté avant. Et quand vient un exercice de rationalisation, on peut ressortir du placard une étude vieille de trois ans en se disant que le moment est enfin venu. C'est toute la chaîne de valeur du SI qui redevient praticable, de la stratégie à l'exécution.

Le référentiel applicatif cesse alors d'être un inventaire qu'on subit. Il devient l'instrument qui rend les arbitrages possibles. Y compris ceux du premier article de cette série : sans lui, il n'y a pas de métrique décisionnable, seulement des estimations qu'on ne peut opposer à rien.

## Pourquoi la dette technique est une dette carbone

Venons-en au cœur, et posons le raisonnement dans l'ordre.

Une remarque préalable, parce qu'elle déplace la question de la faute vers celle de la pente. Dès 1974, en étudiant l'évolution d'OS/360 chez IBM, Meir Lehman et László Belády énonçaient que la complexité d'un système ancré dans le monde réel augmente à mesure qu'il évolue, sauf si un travail explicite est mené pour la maintenir ou la réduire. Lehman lui-même suggérait d'y voir un analogue du second principe de la thermodynamique.

Retenez la clause finale : *sauf si un travail explicite est mené*. La dette n'est pas un accident de gestion, c'est la pente. **Ne rien faire n'est donc pas une absence de décision. C'est une décision de laisser courir.**

Le premier article de cette série établissait que l'essentiel de l'empreinte du numérique est embarqué dans la fabrication du matériel, pas dans son usage. Cette empreinte-là est déjà payée au moment où l'équipement arrive. La seule variable qui reste, c'est ce qu'on en fait — c'est-à-dire sur combien d'années et sur combien d'usages réels on l'amortit.

Une application maintenue en vie sans usage ne consomme pas seulement de l'électricité. Elle immobilise du matériel dont l'empreinte de fabrication ne s'amortit sur rien. Elle occupe du stockage sauvegardé, répliqué, archivé en continu. Elle porte un dimensionnement calé sur un pic de charge qui n'existe plus. Et elle empêche la consolidation qui aurait permis de sortir des équipements du parc.

Le phénomène est documenté, et le chiffre le plus solide dont on dispose a onze ans. En 2015, Jonathan Koomey, chercheur à Stanford, et Jon Taylor, du cabinet Anthesis, ont analysé un échantillon de près de quatre mille serveurs et conclu que 30 % d'entre eux étaient « comateux » : alimentés, mais sans aucun travail utile depuis au moins six mois. L'étude portait sur le parc nord-américain, s'appuyait sur des données fournies par un éditeur de logiciels d'efficacité, et recoupait des estimations antérieures de l'Uptime Institute et de McKinsey.

Mais ce qui m'intéresse n'est pas le pourcentage. C'est le motif que les auteurs identifient : ces serveurs restent allumés parce que personne ne sait plus à quoi ils servent, ou n'ose prendre le risque de les éteindre. Et la conclusion qu'ils en tirent est que le problème n'est pas technique — il tient aux pratiques de gestion, à la circulation de l'information et aux incitations.

**Ce qu'on ne sait plus rattacher, on ne sait plus éteindre.** Le décommissionnement n'est pas empêché par un obstacle technique. Il est empêché par l'ignorance de ce qu'on décommissionnerait.

Un mot sur les données jamais purgées, puisqu'elles relèvent du même mécanisme. Je pourrais citer ici des chiffres spectaculaires sur les données dormantes. Ils circulent depuis 2020, proviennent d'un éditeur qui vend des solutions de gestion de données, et sont repris tels quels depuis, sans réactualisation. Je m'en abstiens : un article sur l'impossibilité de mesurer ne va pas s'appuyer sur des chiffres invérifiables. Le raisonnement suffit — ce qui n'est jamais purgé grossit, ce qui grossit se stocke, se réplique et se sauvegarde, et tout cela tient sur du matériel qu'il a fallu fabriquer.

Le surprovisionnement et l'absence de purge ne sont d'ailleurs pas les problèmes. Ce sont les symptômes d'un système d'information qu'on ne sait plus piloter.

## Le binôme qui manque

Reste la question de qui porte cela, et c'est ici que je veux être précise, parce que le sujet se traite d'ordinaire en désignant un responsable.

Une direction RSE connaît le cadre réglementaire, maîtrise les exigences du reporting extra-financier, dispose des facteurs d'émission et d'un accès aux instances de direction. Elle sait quels principes doivent s'appliquer. Ce qu'elle n'a pas de raison de savoir, c'est qu'un principe de responsabilité environnementale peut se traduire en exigence de qualité — inscrite dans les exigences non fonctionnelles, tranchée dans un ADR, contrôlée par une fitness function, et donc opposable au moment où l'on décide.

Un architecte sait faire cette traduction. Ce qu'il n'a pas, c'est le mandat réglementaire ni la connaissance fine du cadre extra-financier.

**Aucun des deux métiers ne détient la traduction en entier.** C'est exactement ce qui rend le binôme nécessaire — et ce n'est pas une politesse : c'est un constat de compétences complémentaires.

Deux précisions, tant qu'on y est. D'abord, le sujet ne se limite pas au matériel : l'empreinte d'une organisation intègre aussi les déplacements générés, l'équilibre des ressources humaines mobilisées, les achats de services. Autant d'éléments qui se documentent au moment où l'on conçoit un dispositif, pas au moment où l'on remplit un tableau annuel. Ensuite, cela ne concerne pas les seuls architectes d'entreprise. Architectes solution, produit, full stack : c'est à chaque niveau que la responsabilité sociétale s'inscrit ou se perd, de la conception au déploiement et jusqu'à la marche courante.

Je précise, parce que la phrase précédente pourrait s'entendre de travers : les architectes n'ont ni plus de pouvoir ni plus de légitimité que les directions RSE. Ils ont une vue transverse et un rattachement aux objets réels. C'est une contribution, pas une préséance.

## Ce qui fait tenir le dispositif

Dans les cas où cela fonctionne, la déclaration précoce n'a pas été obtenue par la conviction d'un architecte tenace. Elle figure dans les principes directeurs de la DSI, cosignés par le comité de direction IT.

Cela change tout. Un architecte convaincant produit un résultat qui disparaît avec lui. Un principe directeur cosigné produit un cadre qui survit aux départs — ce qui, sur un sujet dont la pathologie centrale est la perte d'information au passage de poste, n'est pas un détail.

Et cela confirme ce que je défendais dans le premier article : le mécanisme ne se décrète pas depuis le terrain. Il se pose là où les leviers existent.

Je ne prétends pas que ce soit simple, ni que j'aie vu beaucoup d'organisations le faire de bout en bout. J'en ai vu assez pour savoir que c'est possible, et que la difficulté n'est pas technique. Si vous avez fait entrer la qualité du référentiel applicatif dans les objectifs de vos équipes de conception — ou si vous avez essayé et que ça n'a pas tenu — écrivez-moi. L'échec m'intéresse autant que la réussite.

*Prochain article : l'IA pompier et pyromane. Ce que la vague actuelle fait à l'empreinte du numérique, ce que l'IT for green promet vraiment, et comment distinguer un gain net d'un déplacement d'impact.*

---

## Sources & liens utiles

### Patrimoine applicatif et serveurs inutilisés

- **Jonathan Koomey (Stanford University) et Jon Taylor (Anthesis Group)**, *New data supports finding that 30 percent of servers are « comatose »*, 2015. Échantillon de près de 4 000 serveurs, données collectées par TSO Logic. Un serveur est dit comateux lorsqu'il n'a délivré aucun travail utile pendant au moins six mois. → [anthesisgroup.com](https://www.anthesisgroup.com/insights/zombie-servers-hunting-down-the-lost-capital/)
- **Koomey & Taylor**, *Zombie/Comatose Servers Redux*, analyse de suivi sur un échantillon quatre fois plus large, méthodologie identique. → [Rapport (PDF)](https://info.anthesisgroup.com/hubfs/Website%20PDFs/Comatose-Servers-Redux.pdf)
- **NRDC**, analyse de 2014 conduite avec Anthesis, à l'origine de l'estimation reprise ensuite : des serveurs abandonnés par leurs propriétaires applicatifs mais maintenus en fonctionnement faute de savoir à quoi ils servent. → [nrdc.org](https://www.nrdc.org/bio/pierre-delforge/case-zombie-servers)

*Réserve de méthode : ces travaux datent de 2015, portent sur le parc nord-américain, et les données sous-jacentes ont été fournies par un éditeur de logiciels d'efficacité énergétique. Je les cite pour l'ordre de grandeur et pour le mécanisme identifié, pas comme une mesure actuelle du parc européen.*

### Cadres et référentiels

- **Meir M. Lehman et László A. Belády**, lois de l'évolution logicielle, formulées à partir de 1974 sur la base de l'étude des versions successives d'OS/360 chez IBM. La deuxième loi, dite de complexité croissante : la complexité d'un système de type E — c'est-à-dire ancré dans le monde réel — augmente à mesure qu'il évolue, sauf si un travail explicite est mené pour la maintenir ou la réduire. Lehman évoque lui-même l'analogie avec le second principe de la thermodynamique. → M. M. Lehman, *Laws of Software Evolution Revisited*, 1996 ([PDF](https://www.cs.kent.edu/~jmaletic/cs63902/Papers/Lehman96.pdf)) et *Programs, Life Cycles, and Laws of Software Evolution*, Proc. IEEE, vol. 68, n° 9, 1980.

- **Référentiel général de l'écoconception des services numériques (RGESN)**, version publiée le 17 mai 2024 par l'Arcep et l'Arcom en lien avec l'ADEME, en application de la loi REEN de 2021. 78 critères répartis en trois niveaux de priorité, dont l'allongement de la durée de vie des terminaux et la limitation de la collecte de données. → [ecoresponsable.numerique.gouv.fr](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/) et [arcep.fr](https://www.arcep.fr/mes-demarches-et-services/entreprises/fiches-pratiques/referentiel-general-ecoconception-services-numeriques.html)
- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021). La dette technique est l'une des quatre activités essentielles du cadre, aux côtés des attributs de qualité, des décisions d'architecture et des boucles de rétroaction. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### Mes textes en lien

- Article 1/4 : *Chacun optimise, personne n'arbitre* → [/articles/2026-09-04-chacun-optimise-personne-arbitre/](/articles/2026-09-04-chacun-optimise-personne-arbitre/)
- *Nous venons du chaos, l'IA de la logique* (2025) → [Le livre](https://amzn.eu/d/07jFAfN9)
- Dossier : *L'Architecture Continue face à l'imprévisible (2026)* → [/dossiers/architecture-continue-polycrise-2026.html](/dossiers/architecture-continue-polycrise-2026.html)
- Manifeste : *Les 6 habitudes d'un SI efficace* → [/manifeste/](/manifeste/)

---

*Vos réactions, désaccords, compléments d'information sont bienvenus — et sur ce sujet, particulièrement vos retours d'expérience sur la gouvernance des référentiels applicatifs. Écrivez-moi à [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #DetteTechnique #ArchitectureEntreprise #PatrimoineApplicatif #ContinuousArchitecture #RSE
