---
title: "Ce n'est pas l'IA qui est pyromane"
date: 2026-09-09
description: "Green IT : l'IA pompier et pyromane, c'est le discours ambiant. Troisième article d'une série de quatre — ce que le siècle du pétrole nous apprend des critères d'arbitrage, comment faire entrer un cas d'usage IA dans la chaîne de valeur de l'architecture, et pourquoi le problème n'a jamais été la ressource. (3/4)"
categories: ["IA", "Architecture"]
tags: ["green IT", "IA", "gouvernance", "architecture", "décision", "Continuous Architecture"]
draft: false
cover:
    image: "/images/articles/green-it-3-pyromane-arbitrage-fr.jpg"
    alt: "Schéma opposant le discours ambiant de l'IA pompier et pyromane, mis de côté, à une instance d'arbitrage entourée de plusieurs axes de valeur dont un axe carbone en pointillés, au-dessus d'une frise présentant la décision d'architecture, la fitness function et le runway"
    caption: "Une technologie n'a pas d'intention. La question est de savoir quelle instance pèse ce qu'un cas d'usage apporte face à ce qu'il coûte."
    relative: false
    hidden: false
---

*Série Green IT — Article 3/4*

---

J'ai chez moi une station météo. Elle me donne la température, la pression, l'hygrométrie et les variations des dernières heures. Avec ça, je sais à peu près le temps qu'il fera demain — et si je doute, une dizaine de médias diffusent le bulletin gratuitement.

Pourtant, la question du temps qu'il fera est posée chaque jour, des milliers de fois, à des IA génératives. Qui, elles, doivent tout analyser avant de répondre.

> **En bref**
> - Tant que la seule variable d'ajustement est d'utiliser ou de ne pas utiliser, nous n'avons pas de levier d'architecture. Nous n'avons qu'un levier moral — et un levier moral ne produit pas d'arbitrage.
> - Le siècle du pétrole a montré ce qui arrive quand un seul critère écrase les autres. Ce n'est pas la ressource qui est en cause, c'est ce que nous en faisons.
> - Un cas d'usage IA est une décision d'architecture. Elle s'instruit dans un ADR, se contrôle par une fitness function et se prépare dans un runway — pas dans un comité supplémentaire.

{{< imprimer >}}

## Le réflexe plutôt que la décision

Restons sur la météo, parce que c'est un cas d'école.

La donnée existe. Le raisonnement est à la portée de quiconque regarde deux fois son baromètre. Et le bulletin, lui, est produit une fois puis diffusé à des millions de personnes — un modèle de mutualisation dont on ferait bien de s'inspirer plus souvent. Passer malgré tout par un système qui doit tout analyser avant de répondre, ce n'est pas une décision. C'est un réflexe.

Multipliez ce réflexe par le nombre de fois où l'on demande à une IA générative ce qu'une recherche, une formule, une table de référence ou un collègue aurait donné plus vite. Nous sommes dans la phase d'effet whaou : on essaie tout, sur tout, pour voir. C'est humain, et c'est même sain à ce stade — on ne découvre les usages pertinents qu'en explorant les usages absurdes.

Le problème n'est pas là. Il est dans le fait que **la seule variable d'ajustement dont nous disposons aujourd'hui est binaire : utiliser, ou ne pas utiliser.** C'est un levier moral, pas un levier d'architecture. Et un levier moral, on l'a vu dans le premier article de cette série, produit de la sensibilisation, du contournement et de la culpabilité. Jamais un arbitrage.

C'est ce qui explique l'enlisement du débat. Ceux qui disent « n'utilisez pas » et ceux qui disent « utilisez partout » se disputent sur la même variable binaire. Les questions intéressantes sont ailleurs : pour quel usage, à quelle maille, avec quel modèle, sur quel volume, à quelle fréquence.

## Ce que le siècle du pétrole nous a appris

Faisons un détour, parce que nous avons déjà vécu cette séquence.

Le pétrole a été une révolution, un choc, puis un mode de vie. Une ressource longtemps traitée comme inépuisable, autour de laquelle s'est construit l'un des empires économiques les plus puissants de l'histoire. D'un besoin de déplacement partagé par des milliards de personnes, quelques milliers se sont considérablement enrichis. Puis le réel est revenu : la ressource s'est révélée finie, sa combustion polluante, et les crises géopolitiques ont fait flamber le baril. Alors seulement on a regardé sérieusement les alternatives.

Attention à la tentation, ici. Le récit facile voudrait qu'une technologie miracle ait été délibérément enterrée. Ce n'est pas ce que dit l'histoire, et je n'ai pas besoin de ce récit-là. Ce qui s'est passé est plus banal et plus grave : **on a rendu bankable avant de rendre utile, pérenne et abordable.** Les alternatives ont été étudiées, notamment après les chocs pétroliers, puis rangées — non parce qu'elles ne fonctionnaient pas, mais parce que l'économie du moment ne les récompensait pas.

Ce n'est pas une suppression. C'est une absence d'arbitrage. Un critère unique, la rentabilité immédiate, a écrasé tous les autres — non par complot, mais parce qu'aucune instance ne pesait les autres en face de lui.

C'est le motif exact des deux premiers articles de cette série. Et c'est la situation de l'IA aujourd'hui.

## Le palier ne viendra pas tout seul

Il y a une objection à me faire, et je préfère me la faire moi-même.

On pourrait espérer que l'effet whaou s'épuise, que la curiosité atteigne un palier et qu'on consomme mieux ensuite. Mon propre exemple pétrolier dit le contraire.

En 1865, dans *The Coal Question*, l'économiste William Stanley Jevons observait que la machine à vapeur de Watt, bien plus économe en charbon que celle de Newcomen, n'avait pas réduit la consommation anglaise de charbon. Elle l'avait démultipliée — parce qu'en rendant l'usage moins coûteux, elle l'avait rendu praticable partout. Jevons écrivait cela en s'inquiétant, déjà, de l'épuisement des réserves britanniques.

C'est ce qu'on appelle aujourd'hui l'effet rebond. Sa portée exacte reste débattue : les économistes s'accordent sur son existence, beaucoup moins sur son ampleur, et rarement au point de conclure qu'un gain d'efficacité serait toujours intégralement annulé. Mais la direction est claire.

**Un gain d'efficacité qui ne s'accompagne pas d'un arbitrage ne réduit rien. Il élargit le champ de l'usage.** Chaque modèle plus léger, chaque puce plus efficiente rend l'IA praticable là où elle ne l'était pas, et le gain unitaire se dissout dans le volume.

Le palier viendra donc si quelqu'un le décide. Pas parce que la curiosité s'épuise.

## La valeur n'est pas un chiffre unique

Reste à savoir si tout ceci est théorique. Ça ne l'est pas, et j'en parle d'autant plus librement que j'ai construit le dispositif moi-même, en interne.

Dans une organisation où j'ai porté la fonction IA, nous avons mis en place une méthode d'arbitrage des cas d'usage. Elle classifiait d'abord par opportunité — usage courant ou innovation, usage interne ou externe, fonctions support ou métier spécifique — puis valorisait chaque cas selon des critères propres à sa catégorie, complétés par le coût, le risque et la complexité. Et surtout, elle aboutissait quelque part : la direction générale tranchait. Certains cas d'usage ont été retenus. D'autres non.

Un exemple de ceux qui l'ont été, parce qu'il dit mieux que tout ce que j'entends par valeur.

Sur un site industriel, un poste de production physiquement pénible exigeait un vrai savoir-faire. Il était tenu par des saisonniers qu'il fallait former chaque année, avec deux difficultés qui s'aggravaient : les personnes formées ne revenaient pas toujours, ayant trouvé un emploi ailleurs entre-temps, et les générations plus jeunes ne veulent plus de ce type de poste. Le travail, lui, devait continuer.

L'IA a pris la tâche. Les personnes déjà formées sont passées d'un poste inconfortable sur chaîne à un poste où elles valident les décisions du système, les corrigent et l'entraînent. Le savoir-faire n'a pas été remplacé : il a changé de place — et il s'accumule au lieu de repartir chaque fin de saison.

Ce cas d'usage n'a pas été retenu parce qu'il coûtait moins cher. Il a été retenu parce qu'il traitait simultanément une pénibilité, une érosion de compétence et une fragilité d'exploitation. **Valoriser, c'est précisément ça : poser plusieurs choses sur la table et regarder ce que chaque option gagne et perd sur chacune.**

Une précision s'impose ici, parce qu'il serait facile de me la reprocher : le critère carbone ne figurait pas encore dans cette grille. Il était inscrit dans ma feuille de route, il n'y était pas au moment où j'écris. Gardez cette imperfection en tête, j'y reviens dans un instant.

Le contre-exemple, maintenant, parce qu'il est plus banal et donc plus instructif.

Je prends rendez-vous chez un praticien qui me suit depuis dix ans, sur une grande plateforme de réservation médicale. Je sélectionne mon motif de consultation — un acte que ce praticien a déjà réalisé trois fois. Un message m'invite à téléphoner pour ce type d'acte. Je téléphone : un assistant vocal me fait écouter un menu, je choisis à nouveau le motif, et il m'annonce qu'il ne peut pas prendre de rendez-vous pour cet acte, avant de me renvoyer vers la plateforme.

Je finis par écrire au praticien via la plateforme. Le lendemain, la secrétaire me rappelle. Elle s'excuse, et m'explique la situation : elle passe désormais ses journées à traiter au cas par cas — ceux qui viennent se plaindre directement au bureau, ceux qui, comme moi, envoient un message. Car là où elle positionne un rendez-vous, l'assistant en place un autre en parallèle. Elle consacre un temps considérable à réparer l'agenda, et n'a plus celui de faire le reste de son travail.

Faisons le compte, sur les mêmes axes. Le patient a perdu du temps. La secrétaire en a perdu beaucoup plus, alors que l'outil était censé lui en faire gagner — et elle le perd à corriger l'outil lui-même. Le praticien encourt le risque de perdre des patients moins tenaces que moi. Et pendant ce temps, deux systèmes ont tourné, consommé, et généré du travail humain supplémentaire. Souhaitons que la situation soit rentrée dans l'ordre pour elle quand vous lirez ces lignes.

Ce n'est pas un problème d'IA. C'est un cas d'usage dont personne n'a instruit la valeur avant de le déployer.

Et voilà pourquoi je vous demandais de garder mon imperfection en tête. Ma grille était incomplète — mais elle existait, et quelqu'un s'en servait. **Une grille incomplète dont une instance se sert vaut infiniment mieux qu'un critère parfait que personne ne pose.** Quand le mécanisme d'arbitrage est là, ajouter un critère est un travail de quelques semaines. Quand il n'existe pas — le couloir aux écrans du premier article, le référentiel dégradé du deuxième, l'agenda médical plus haut — aucun critère n'a la moindre prise, et le meilleur indicateur carbone du monde ne sert à rien.

C'est ce que je défendais en juin dernier en sortant du Decision Day : avant de choisir un modèle ou un budget, cartographier ses décisions. Qui décide des cas d'usage, selon quels critères, et que fait-on quand une opportunité entre en collision avec autre chose ? Ces arbitrages se préparent, ils ne s'improvisent pas.

## Faire entrer la décision dans la chaîne de valeur

Reste la question du comment — et je tiens à ce qu'elle ne débouche pas sur un comité de plus. L'architecture continue fournit trois objets qui existent déjà dans les organisations qui la pratiquent. Il n'y a rien à créer.

**La décision d'architecture, tracée dans un ADR.** Un cas d'usage IA est une décision d'architecture comme une autre. On y consigne la taille de modèle retenue, la fréquence de réentraînement, la stratégie de cache, les alternatives écartées, et ce qu'on gagne et perd sur chaque attribut. Le document n'est pas l'objectif — l'objectif est d'avoir dû expliciter le compromis devant quelqu'un.

**La fitness function.** Un seuil, mesuré en continu, qui alerte quand une option dérive. Sur un cas d'usage IA, cela peut être une consommation ou une émission rapportée à l'unité fonctionnelle — par transaction traitée, par document analysé, par décision assistée. Le point n'est pas d'atteindre la perfection métrologique. Il est d'avoir un chiffre qui bouge et qu'on regarde.

**Le runway.** Préparer la capacité avant d'en avoir besoin. Sur ce sujet, cela veut dire disposer d'un référentiel applicatif exploitable — le deuxième article de cette série dit pourquoi —, d'un inventaire des modèles en production et d'une mesure d'usage réelle. Sans ce socle, la fitness function n'a rien à mesurer.

Et les questions à poser en revue de conception, dans cet ordre :

1. **Quelle décision cet usage prend-il ou prépare-t-il**, et à quel niveau de délégation ?
2. **Existe-t-il un moyen plus direct** — une règle métier, une table de référence, un calcul, une donnée déjà produite ailleurs ?
3. **Quelle taille de modèle suffit** pour une tâche cadrée ? Un modèle spécialisé fait souvent aussi bien qu'un généraliste.
4. **Quel volume de données est réellement nécessaire**, et à quelle fraîcheur ?
5. **Quelle part des appels est évitable** par un cache, une pré-agrégation, un filtrage en amont ?
6. **Cette tâche demande-t-elle un raisonnement, ou une génération simple ?** L'écart énergétique entre les deux se compte en ordres de grandeur.
7. **À quelle fréquence réentraîne-t-on**, et sur quel signal ?

Aucune de ces questions n'est morale. Toutes sont décisionnables. Et aucune n'est posée tant que la seule chose qu'on sait dire est « ça consomme ».

## Ce qu'on sait mesurer, et c'est peu

Un mot sur les chiffres, maintenant, parce qu'ils sont plus fragiles qu'on ne le dit des deux côtés du débat.

Ce dont on est sûr : la consommation électrique des datacenters augmente vite. L'Agence internationale de l'énergie l'estime à 485 TWh en 2025 et projette un doublement d'ici 2030, à environ 950 TWh — près de 3 % de l'électricité mondiale. Les datacenters dédiés à l'IA, eux, triplent sur la période.

Ce dont on est moins sûr commence dès qu'on regarde comment le chiffre est fabriqué. Pour la même année 2025, l'Energy Institute avance 787,8 TWh, sur un périmètre plus large couvrant 47 pays, refroidissement et systèmes annexes inclus. Les deux institutions ne sont pas en désaccord : elles ne mesurent pas la même chose.

Vous reconnaissez la figure. C'est celle du premier article, quand l'empreinte du numérique français est passée de 2,5 % à 4,4 % pour une raison largement méthodologique. **En matière d'empreinte du numérique, le premier chiffre à demander n'est pas la valeur. C'est le périmètre.**

Descendez à la consommation par requête et c'est pire : les estimations varient d'un ordre de grandeur selon la source et l'année, les fournisseurs publient des valeurs nettement inférieures aux évaluations indépendantes, et presque aucune ne précise si elle couvre l'inférence seule, l'entraînement amorti ou le matériel qu'il a fallu fabriquer. Je n'en cite donc aucune — non par prudence excessive, mais parce que je ne saurais pas vous dire ce qu'elle mesure.

Un point est en revanche établi, et c'est celui qui compte pour la question 6 ci-dessus : tous les usages ne se valent pas. L'AIE souligne que la génération vidéo, le raisonnement et les usages agentiques peuvent consommer plusieurs centaines à plusieurs milliers de fois plus d'énergie par requête qu'une génération de texte simple.

C'est bien la preuve que le sujet est architectural, et non moral.

## Ce n'est pas l'IA qui est pyromane

Le discours ambiant tient en une image : l'IA serait pompier et pyromane, vendue comme solution climatique par ceux-là mêmes qui construisent les infrastructures qui pèsent.

L'image est utile pour désigner des acteurs, et sur ce point elle vise juste. Elle devient trompeuse dès qu'on l'applique à la technologie. Un modèle n'a pas d'intention. Il ne décide pas d'être déployé sur une boucle de prise de rendez-vous qui ne prend aucun rendez-vous, ni de produire un bulletin météo que dix médias diffusent déjà. Il ne décide pas non plus de sortir quelqu'un d'un poste pénible.

Nous, si.

**Ce n'est pas l'IA qui est pyromane. C'est nous — comme avec le charbon, comme avec le pétrole, et pour la même raison : consommer sans se poser la question de la pérennité est humain, et rien dans nos organisations n'oblige à se la poser.**

Ce qui est plutôt une bonne nouvelle. Si le problème était la technologie, il faudrait attendre la génération suivante. S'il est dans nos mécanismes de décision, il est de notre ressort — et c'est le métier de l'architecture d'entreprise.

Ce qui changerait tout n'est pas spectaculaire : que la question de ce qu'un cas d'usage apporte et de ce qu'il coûte se pose dans la même pièce, au même moment, devant les mêmes personnes. Pas dans deux instances qui ne se croisent jamais.

Je n'ai pas de recette, et je n'ai pas encore vu d'organisation faire entrer un critère environnemental dans une grille d'arbitrage IA de bout en bout. Si vous l'avez fait, ou si vous vous y êtes cassé les dents, écrivez-moi. C'est exactement ce que je cherche à documenter.

*Prochain article : la sobriété comme fitness function. Comment un critère environnemental entre concrètement dans une exigence non fonctionnelle, une décision d'architecture et une boucle de rétroaction — et pourquoi ce n'est ni un frein ni un supplément d'âme, mais un attribut de qualité de plein droit.*

---

## Sources & liens utiles

### Consommation énergétique de l'IA et des datacenters

- **Agence internationale de l'énergie (AIE)**, *Key Questions on Energy and AI*. Consommation électrique des datacenters estimée à 485 TWh en 2025, projetée à environ 950 TWh en 2030, soit près de 3 % de la demande électrique mondiale ; les datacenters dédiés à l'IA triplent sur la période. Le rapport souligne également que les tâches de génération vidéo, de raisonnement et les usages agentiques peuvent consommer plusieurs centaines à plusieurs milliers de fois plus d'énergie par requête qu'une génération de texte simple. → [iea.org](https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary)
- **Energy Institute**, *Statistical Review of World Energy 2026*. Estimation de 787,8 TWh pour 2025 sur un périmètre couvrant 47 pays, refroidissement et systèmes annexes inclus. L'écart avec l'AIE tient au périmètre de mesure, non à un désaccord sur la tendance. → [energyinst.org](https://www.energyinst.org/statistical-review)

*Réserve de méthode : les estimations de consommation par requête varient d'un ordre de grandeur selon la source, l'année et le périmètre retenu (inférence seule, entraînement amorti, émissions embarquées du matériel). Les valeurs publiées par les fournisseurs sont sensiblement inférieures aux évaluations indépendantes. Je m'abstiens d'en citer.*

### Effet rebond

- **William Stanley Jevons**, *The Coal Question: An Inquiry Concerning the Progress of the Nation, and the Probable Exhaustion of Our Coal Mines*, Macmillan & Co., 1865. Jevons y observe que le perfectionnement de la machine à vapeur par James Watt, plus économe en charbon que celle de Thomas Newcomen, a accru la consommation totale de charbon au lieu de la réduire. → [Notice The Coal Question](https://en.wikipedia.org/wiki/The_Coal_Question)
- Sur les limites du paradoxe : l'existence de l'effet rebond fait consensus, son ampleur beaucoup moins. Voir Antoine Missemer, *Les Économistes et la fin des énergies fossiles (1865-1931)*, Classiques Garnier, 2017.

### Cadres mobilisés

- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021). Décisions d'architecture, attributs de qualité, dette technique et boucles de rétroaction — les quatre activités essentielles du cadre. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### Mes textes en lien

- Article 1/4 : *Chacun optimise, personne n'arbitre* → [/articles/2026-09-04-chacun-optimise-personne-arbitre/](/articles/2026-09-04-chacun-optimise-personne-arbitre/)
- Article 2/4 : *La dette technique est une dette carbone* → [/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/](/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/)
- *Avant de déployer l'IA, avez-vous cartographié vos décisions ?* (juin 2026) → [/articles/2026-06-05-cartographier-decisions-avant-ia/](/articles/2026-06-05-cartographier-decisions-avant-ia/)
- *Nous venons du chaos, l'IA de la logique* (2025) → [Le livre](https://amzn.eu/d/07jFAfN9)
- Dossier : *L'Architecture Continue face à l'imprévisible (2026)* → [/dossiers/architecture-continue-polycrise-2026.html](/dossiers/architecture-continue-polycrise-2026.html)

---

*Vos réactions, désaccords, compléments d'information sont bienvenus — et sur ce sujet, particulièrement vos grilles d'arbitrage de cas d'usage IA, qu'elles intègrent ou non un critère environnemental. Écrivez-moi à [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #IA #ArchitectureEntreprise #GouvernanceIA #ContinuousArchitecture #EffetRebond
