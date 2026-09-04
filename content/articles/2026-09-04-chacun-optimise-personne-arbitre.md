---
title: "Chacun optimise, personne n'arbitre"
date: 2026-09-04
description: "Green IT : un programme sobriété d'un côté, des projets qui déploient à tour de bras de l'autre. Premier article d'une série de quatre sur le green IT et l'économie circulaire de l'IT — le paradoxe des intentions parallèles, et pourquoi l'architecture d'entreprise est l'endroit où elles peuvent se rencontrer. (1/4)"
categories: ["Architecture"]
tags: ["green IT", "sobriété numérique", "architecture", "gouvernance", "économie circulaire", "Continuous Architecture"]
draft: false

cover:
    image: "/images/articles/green-it-arbitrage.png"
    alt: "Schéma opposant les métriques d'enveloppe d'un programme green à un point d'arbitrage de décision"
    caption: "D'un côté les indicateurs qui décrivent, de l'autre le point où l'on décide. Rien ne les relie."
    relative: false
    hidden: false
---

*Série Green IT — Article 1/4*

---

Un datacenter parfaitement refroidi, qui fait tourner en continu des traitements que plus personne ne consulte, affichera un excellent PUE.

C'est tout le problème. Et ce n'est que la version visible d'un paradoxe beaucoup plus large.

> **En bref**
> - Le PUE mesure l'efficacité de l'enveloppe, jamais l'utilité du calcul — et la même illusion se rejoue à l'échelle de l'organisation, où un programme green coexiste avec des projets qui n'ont aucune raison de le croiser.
> - L'architecture d'entreprise n'est pas là pour contraindre les choix ni arbitrer les visions. Elle est là pour rendre l'ensemble cohérent — encore faut-il qu'elle soit positionnée au bon endroit, avec les bons leviers.
> - La sobriété et l'économie circulaire de l'IT ne sont pas des programmes à côté du flux de valeur. Ce sont des attributs de qualité dans le flux de valeur.

{{< imprimer >}}

## Un indicateur irréprochable pour un système absurde

Commençons par l'outil, puisque c'est lui qu'on brandit.

L'indicateur roi du numérique responsable, c'est le PUE — *Power Usage Effectiveness*. Il est normalisé (ISO/IEC 30134-2, dont une nouvelle édition est parue en 2026), calculé sur douze mois glissants, et il dit une chose : le rapport entre l'énergie totale consommée par le site et celle consommée par les équipements informatiques eux-mêmes.

Lisez bien. Ce que le PUE évalue, c'est la part d'énergie qui part dans la climatisation, l'onduleur, la distribution électrique. Un indicateur d'efficacité de l'enveloppe. Rien de plus.

**Le PUE ne mesure pas l'utilité du calcul. Il mesure l'élégance avec laquelle on gaspille.**

Ce n'est pas un défaut de la norme — la série ISO/IEC 30134 précise explicitement qu'elle ne fixe ni limite ni cible, et qu'un indicateur isolé ne suffit pas à décrire une performance d'ensemble. Le défaut est dans l'usage : on a pris un indicateur d'ingénierie thermique et on en a fait un argument de communication environnementale.

Retenez la forme de ce paradoxe. Un objet local parfaitement optimisé, dans un ensemble qui ne l'est pas. Vous allez la retrouver partout.

## Le même paradoxe, un étage plus haut

Dans les couloirs d'une grande organisation, j'ai compté les écrans. Le menu de la cantine. Le plan du bâtiment. Le taux d'occupation en temps réel. Un cas d'usage, un écran. Plus loin des tablettes, plus loin encore des mini-PC.

Et sur la page d'accueil de l'intranet : un programme green flambant neuf.

Personne n'a menti. Personne n'a triché. Chaque décision, prise isolément, était défendable — et chaque équipe faisait correctement son travail. Le programme green tenait ses jalons. Les projets d'affichage répondaient à des besoins métier réels.

C'est la structure même du paradoxe qu'il faut regarder. Une organisation porte simultanément une dizaine de programmes transverses : sécurité, données, cloud, expérience collaborateur, sobriété. Parfois ils se renforcent. Parfois ils s'opposent frontalement — sécuriser peut vouloir dire dupliquer, et dupliquer coûte du carbone. Le plus souvent, ils ne se rencontrent tout simplement jamais.

Aucun des arbitrages d'écran n'est passé par le programme green. Non par mauvaise volonté : parce qu'il n'existait aucun mécanisme par lequel une commande d'écran pouvait rencontrer un objectif carbone.

**Chacun optimise. Personne n'arbitre.**

On appelle ça de l'indifférence. C'est une erreur de diagnostic, et une erreur coûteuse : tant qu'on croit à un problème de volonté, on répond par de la sensibilisation. Ce n'est pas un problème de volonté. C'est un problème d'architecture de décision.

Et j'insiste sur le mot *architecture*, parce que le mécanisme ne se décrète pas. Tracer les décisions ne suffit pas : des ADR empilés dans un répertoire, chacun correct isolément mais sans cohérence d'ensemble, perdent exactement le sens qu'on cherchait à leur donner. On retombe alors sur le problème de départ, avec de la documentation en plus. C'est un sujet en soi, sur lequel je reviendrai.

## Ce que l'architecture d'entreprise fait — et ce qu'elle ne fait pas

Ici, une clarification s'impose, parce que c'est le point où l'on se méprend le plus souvent sur mon métier. Et pour ça, il faut remonter loin.

Le mot vient du grec *arkhitekton* : le maître bâtisseur. Dès l'Antiquité, il désigne la capacité à concevoir un tout cohérent à partir d'éléments structurants. L'architecte romain est simultanément urbaniste, ingénieur et philosophe — un rôle à la croisée du technique, de l'esthétique et du civique. Dans *De architectura*, rédigé au I<sup>er</sup> siècle avant notre ère et dédié à Auguste, Vitruve pose les trois qualités essentielles d'un ouvrage : *firmitas*, la solidité dans la durée ; *utilitas*, l'utilité ; *venustas*, la beauté. Trois qualités indissociables, dont aucune ne se sacrifie aux deux autres.

Autrement dit : la première liste d'attributs de qualité de l'histoire de la discipline a plus de deux mille ans. Et elle commence par la durabilité.

**L'architecture d'entreprise n'est pas là pour contraindre les choix ni pour arbitrer les visions. Elle est là pour rendre l'ensemble cohérent.**

C'est aussi ce que dit [Xavier Chaumont](https://fr.linkedin.com/in/xchaumont/), qui dirige la gouvernance, la stratégie et l'architecture SI chez GRDF, dans une série d'images qu'il a partagée sur LinkedIn en 2024. Deux d'entre elles me semblent décisives ici. L'architecture d'entreprise comme **pont** d'abord : un connecteur entre le métier et la technologie, entre la stratégie et l'exécution, entre les directions générales et les équipes opérationnelles. Comme **partie d'échecs** ensuite, où l'essentiel du travail consiste à équilibrer des options, à réduire les risques d'une décision et à laisser certaines portes ouvertes pour trancher plus tard, au bon moment.

C'est le *trade-off* dont la communauté Continuous Architecture a fait le cœur du métier : arbitrer entre des attributs de qualité qui se contredisent, expliciter ce qu'on gagne et ce qu'on perd, et rendre le compromis lisible pour ceux qui décident.

L'architecture ne décide donc pas si le programme green a raison contre le projet d'affichage. Elle rend visible le fait qu'ils existent tous les deux, qu'ils tirent dans des directions différentes, et que quelqu'un doit trancher en connaissance de cause.

C'est une différence de nature, pas de degré. Une fonction qui contraint produit du contournement. Une fonction qui rend cohérent produit de la décision informée. Encore faut-il qu'elle soit positionnée au bon endroit, avec les bons leviers — et c'est précisément là que la plupart des dispositifs green IT échouent, en s'installant à côté du système de décision plutôt que dedans.

## Le poste que personne ne porte à son bilan

Revenons aux écrans, parce que les chiffres racontent une histoire que le programme green ne voyait pas.

L'étude ADEME-Arcep publiée en janvier 2022, sur des données 2020, estimait l'empreinte du numérique français à 17,2 MtCO₂e, soit 2,5 % de l'empreinte carbone du pays. Sa mise à jour, publiée en janvier 2025 sur des données 2022, porte ce chiffre à environ 29,5 MtCO₂e et 4,4 %. Les terminaux en pèsent la moitié. Et dans cette moitié, la fabrication écrase l'usage : environ 42 % de l'empreinte totale du numérique français vient de la fabrication des terminaux, contre 8 % pour leur utilisation.

Autrement dit : au moment où le bon de commande de l'écran est signé, l'essentiel de l'impact est déjà engagé. Avant le premier kilowattheure consommé dans le couloir.

Or cet impact-là ne figure dans aucun tableau de bord opérationnel. Il est en scope 3, c'est-à-dire chez le fournisseur, c'est-à-dire nulle part dans la décision. **Le poste le plus lourd de l'empreinte numérique est précisément celui que personne ne porte à son bilan.**

Et il faut nommer ce que c'est : de la malhonnêteté intellectuelle. L'écologie est une affaire commune — l'atmosphère ne tient pas de comptabilité par entité juridique. Se déclarer vertueux en poussant l'indicateur chez le fournisseur ne réduit rien du tout. Ça déplace une ligne dans un tableau. C'est du greenwashing, et le fait qu'il soit involontaire dans la plupart des cas ne le rend pas moins efficace.

C'est aussi là que l'économie circulaire de l'IT cesse d'être un sujet RSE pour devenir un sujet d'architecture. Si l'essentiel de l'impact est embarqué dans le matériel, alors le levier majeur n'est pas la consommation électrique : c'est la durée de vie, le réemploi, le reconditionnement, la mutualisation des usages sur un même équipement — et le décommissionnement propre. Autrement dit, la *firmitas* de Vitruve, vingt siècles plus tard.

Ce vocabulaire n'a d'ailleurs rien d'exotique pour un architecte. Quand on raisonne en coût total de possession, le décommissionnement fait partie de l'équation depuis toujours, au même titre que le build, le run et la montée en charge. L'économie circulaire ne demande pas d'inventer une catégorie : elle demande de prendre au sérieux la fin de vie qu'on avait déjà inscrite au tableau et qu'on n'instruit jamais.

Un détail mérite un arrêt, parce qu'il est le sujet même de cet article. Entre les deux publications — trois ans d'écart, deux ans entre les jeux de données — la part du numérique dans l'empreinte nationale a presque doublé. Les usages ont progressé, certes. Mais l'ADEME attribue elle-même cette hausse principalement à un changement de périmètre : les datacenters situés à l'étranger, qui hébergent des usages français, ont été intégrés au calcul alors qu'ils en étaient absents. Ce qui était invisible ne s'était pas absenté du réel. Il s'était absenté du compteur.

## Rantigny : quand le paradoxe change d'échelle

Cette dissociation entre l'intention déclarée et la décision réelle n'est pas une pathologie d'entreprise. Elle est partout, et elle grandit avec l'échelle.

À Rantigny, dans l'Oise, un projet de deux datacenters dédiés à l'IA a fait l'objet d'une enquête publique close en août 2026, dans une salle des fêtes où près de trois cents personnes se sont déplacées. Les chiffres du dossier : 33 hectares d'emprise, une modification du plan local d'urbanisme visant à reclasser près de 22 hectares de terres agricoles, une consommation annoncée d'environ 2,6 TWh par an à terme — soit plus de quatre fois la consommation des dix communes du Liancourtois.

Soyons précis, parce que la précision sert l'argument plutôt qu'elle ne l'affaiblit : le site est pour partie une ancienne friche industrielle, et l'artificialisation effective annoncée porte sur environ sept hectares. On n'est pas dans le pur sacrifice de plaine céréalière. On est dans quelque chose de plus intéressant : un territoire qui déclasse de la terre nourricière au titre d'un projet stratégique, pendant qu'un autre étage de la même République écrit des documents sur la souveraineté alimentaire et la sobriété foncière.

Comme l'a souligné le maire de Neuilly-sous-Clermont, commune voisine, la France ne manque pas de friches déjà artificialisées. La question n'est pas de savoir s'il a raison. La question est de savoir devant quelle instance cet arbitrage-là aurait pu être posé. Réponse : aucune. Le foncier, l'énergie, l'alimentation et le numérique s'instruisent séparément.

Écran de cantine ou campus hyperscale, c'est le même mécanisme : l'intention est déclarée à un endroit, la décision se prend à un autre, et rien n'est prévu pour que les deux se rencontrent.

## Une métrique qui n'arbitre rien est un rapport annuel

Voilà la charnière de cette série.

Le problème n'est pas qu'on ne mesure pas. On mesure énormément. Bilans carbone, PUE, tableaux de bord RSE, reporting CSRD : jamais autant de données environnementales n'ont circulé dans les organisations.

Le problème est que ces mesures arrivent **après**. Elles décrivent, elles consolident, elles alimentent un rapport annuel. Elles n'entrent jamais dans la boucle où quelqu'un décide s'il faut ou non un troisième écran dans ce couloir.

**Une métrique qui n'arbitre rien n'est pas un indicateur de pilotage. C'est de la comptabilité rétrospective.**

## La sobriété est un attribut de qualité, pas un programme

D'où ma proposition, et elle va à rebours du réflexe habituel.

Le réflexe, ce serait d'ajouter une brique. Un pilier GreenOps à côté du flux de valeur, un septième principe, un comité de plus. Ce serait reproduire à l'échelle du framework exactement la pathologie du couloir : une intention rangée dans une boîte séparée, sans mécanisme de rencontre avec les décisions réelles.

Je crois qu'il faut faire l'inverse. Ne rien ajouter, et faire entrer la soutenabilité là où elle a toujours eu sa place.

Le deuxième principe de Continuous Architecture, tel que le formulent Murat Erder, Pierre Pureur et Eoin Woods, tient en une phrase : piloter par les attributs de qualité plutôt que par les exigences fonctionnelles. La disponibilité, la sécurité, la performance, la résilience n'ont jamais été des programmes à côté. Ce sont des attributs de qualité : exprimés dans les exigences non fonctionnelles, tranchés dans des ADR, contrôlés par des fitness functions, mesurés en boucle de rétroaction.

**La sobriété n'est pas un programme à côté du flux de valeur. C'est un attribut de qualité dans le flux de valeur.**

Et pour qu'un attribut de qualité tienne, il lui faut une métrique décisionnable — un chiffre qu'on peut poser sur la table face à une option d'architecture, avant de la retenir. Cette métrique existe : le *Software Carbon Intensity*, normalisé sous ISO/IEC 21031 en 2024. Sa logique est l'exact opposé de celle du PUE. Ce n'est pas un ratio d'enveloppe mais un taux d'émissions rapporté à une unité fonctionnelle — par utilisateur, par transaction, par appel d'API. Et surtout, sa formule intègre les émissions embarquées du matériel : le scope 3 rentre dans l'équation au lieu d'en être expulsé.

Je ne dis pas que le SCI est parfait, ni que les données pour l'alimenter sont faciles à obtenir. Je dis qu'il est décisionnable là où le PUE ne l'est pas. C'est une différence de nature, pas de précision.

## Ce que ça change dans le couloir

Reprenons l'écran une dernière fois, avec cette grille.

Il ne se refuse pas au nom de la morale. Pas davantage parce qu'un architecte aurait obtenu un droit de veto — ce serait revenir à la fonction qui contraint, et donc au contournement. Il se discute. Et il se discute autrement, parce que le critère carbone est posé sur la table au même moment que la latence, le coût et la sécurité, devant les gens qui décident vraiment.

Peut-être que l'écran reste. Peut-être qu'il devient un affichage mutualisé pour quatre cas d'usage. Peut-être qu'on réemploie un équipement plutôt que d'en commander un neuf, ce qui, vu le poids de la fabrication, change davantage le bilan que six mois d'optimisation énergétique.

Le débat cesse d'être moral. Il redevient architectural. Et c'est très exactement ce que fait l'architecture d'entreprise quand elle est au bon endroit : elle ne tranche pas à la place des autres, elle fait en sorte que le tout tienne debout. *Firmitas, utilitas, venustas* — la troisième me manque encore dans nos systèmes d'information, mais c'est un autre sujet.

C'est la grille que j'utilise. Je ne la présente pas comme un standard, et je n'ai pas la prétention d'avoir résolu la question du sourçage des données, qui reste le point dur. Si vous faites autrement — si vous avez trouvé le moyen de faire entrer un critère carbone dans un arbitrage d'architecture sans créer un comité de plus — écrivez-moi. C'est exactement ce que je cherche à documenter.

*Prochain article : la dette technique est une dette carbone. Ce que les applications mortes, les données jamais purgées et le surprovisionnement coûtent réellement — et pourquoi les directions RSE gagneraient à travailler avec les architectes d'entreprise, qui n'ont ni plus de pouvoir ni plus de légitimité qu'elles, mais une vue transverse à partager.*

---

## Sources & liens utiles

### Mesure et normes

- **ISO/IEC 30134-2 — Power Usage Effectiveness (PUE)**, indicateur clé de performance des datacenters. Édition 2016 retirée, remplacée par l'édition 2026. La série ISO/IEC 30134 ne fixe ni limites ni cibles pour ses indicateurs. → [iso.org/standard/30134-2](https://www.iso.org/standard/30134-2)
- **ISO/IEC 21031:2024 — Software Carbon Intensity (SCI) specification**. Taux d'émissions carbone rapporté à une unité fonctionnelle logicielle, intégrant les émissions embarquées du matériel. → [iso.org/standard/86612.html](https://www.iso.org/standard/86612.html)
- **Green Software Foundation — spécification SCI** (version publique et outils associés). → [greensoftware.foundation/standards/sci](https://greensoftware.foundation/standards/sci/) et [sci.greensoftware.foundation](https://sci.greensoftware.foundation/)

### Empreinte environnementale du numérique en France

- **ADEME / Arcep**, *Empreinte environnementale du numérique en France*, premiers rapports remis au gouvernement le 19 janvier 2022 (données 2020) : 17,2 MtCO₂e, soit 2,5 % de l'empreinte carbone nationale. → [arcep.fr](https://www.arcep.fr/actualites/actualites-et-communiques/detail/n/environnement-190122.html)
- **ADEME / Arcep**, mise à jour publiée le 17 janvier 2025 (données 2022), avec extension du périmètre aux datacenters situés à l'étranger hébergeant des usages français : 4,4 % de l'empreinte carbone nationale. → [arcep.fr](https://www.arcep.fr/la-regulation/grands-dossiers-thematiques-transverses/lempreinte-environnementale-du-numerique.html)
- **ADEME**, dossier de presse « Numérique et environnement » (9 janvier 2025), qui attribue principalement la hausse à l'élargissement du périmètre de mesure. → [ademe.fr](https://www.ademe.fr/wp-content/uploads/2025/01/dossier-de-presse-numerique-et-environnement-090125.pdf)
- **Arcep**, enquête annuelle « Pour un numérique soutenable » : part des terminaux dans l'empreinte carbone du numérique, répartition fabrication / utilisation. → [arcep.fr](https://www.arcep.fr/cartes-et-donnees/nos-publications-chiffrees/impact-environnemental/enquete-annuelle-pour-un-numerique-soutenable-edition-2025.html)
- **Mission interministérielle Numérique écoresponsable**, actualisation des chiffres de l'impact du numérique en France. → [ecoresponsable.numerique.gouv.fr](https://ecoresponsable.numerique.gouv.fr/actualites/actualisation-ademe-impact/)

### Le projet de datacenters de Rantigny (Oise)

- **France 3 Hauts-de-France / Franceinfo**, reportage sur la réunion publique de clôture d'enquête publique du 19 août 2026 à Rantigny. → [france3-regions.franceinfo.fr](https://france3-regions.franceinfo.fr/hauts-de-france/oise/vous-allez-nous-mettre-un-radiateur-qui-fait-du-bruit-un-projet-de-data-center-divise-les-habitants-d-une-commune-de-l-oise-3404005.html)
- **Reporterre**, enquête sur l'opposition locale au projet : emprise, consommation électrique annoncée, espèces protégées recensées. → [reporterre.net](https://reporterre.net/Dans-l-Oise-l-opposition-grandit-contre-un-projet-de-data-centers-On-a-investi-dans-une)

### Cadres conceptuels mobilisés

- **Vitruve**, *De architectura*, traité en dix livres rédigé au I<sup>er</sup> siècle avant notre ère et dédié à Auguste. Les trois qualités énoncées au livre I — *firmitas*, *utilitas*, *venustas* — ont été formalisées sous le nom de « triade vitruvienne » par Claude Perrault au XVII<sup>e</sup> siècle. → [Notice De architectura](https://fr.wikipedia.org/wiki/De_architectura)
- **Xavier Chaumont**, *Enterprise Architecture — What or Why in 7 images*, série d'images partagée sur LinkedIn en octobre 2024. Gouvernance, stratégie et architecture SI chez GRDF. Les figures du pont et de la partie d'échecs sont reprises de cette publication. → [Profil LinkedIn](https://fr.linkedin.com/in/xchaumont/)
- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021), et *Continuous Architecture: Sustainable Architecture in an Agile and Cloud-Centric World* (Erder & Pureur, Morgan Kaufmann, 2015). Les six principes et les quatre activités essentielles — attributs de qualité, décisions d'architecture, dette technique, boucles de rétroaction. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### Mes textes en lien

- *Nous venons du chaos, l'IA de la logique* (2025) → [Le livre](https://amzn.eu/d/07jFAfN9)
- Dossier : *L'Architecture Continue face à l'imprévisible (2026)* → [/dossiers/architecture-continue-polycrise-2026.html](/dossiers/architecture-continue-polycrise-2026.html)
- Manifeste : *Les 6 habitudes d'un SI efficace* → [/manifeste/](/manifeste/)

---

*Vos réactions, désaccords, compléments d'information sont bienvenus — et sur ce sujet, particulièrement vos contre-exemples de terrain. Écrivez-moi à [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #SobrieteNumerique #ArchitectureEntreprise #ContinuousArchitecture #EconomieCirculaire #Gouvernance
