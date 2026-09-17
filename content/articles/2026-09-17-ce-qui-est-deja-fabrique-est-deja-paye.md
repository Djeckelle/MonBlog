---
title: "Ce qui est déjà fabriqué est déjà payé"
date: 2026-09-17
description: "Green IT : une exigence non fonctionnelle environnementale qu'on m'a remise, et les trois mots qui la vidaient de sa portée. Dernier article d'une série de quatre sur le green IT et l'économie circulaire de l'IT — pourquoi la durée de vie du matériel est le vrai levier, et ce que coûte de ne pas préparer le terrain. (4/4)"
categories: ["Architecture"]
tags: ["green IT", "économie circulaire", "architecture", "gouvernance", "CSRD", "Continuous Architecture"]
draft: false
cover:
    image: "/images/articles/green-it-4-Economie Circulaire-fr.jpg"
    alt: "Barre représentant l'empreinte d'un équipement, divisée en un large segment fabrication et un petit segment usage ; l'exigence ne couvre que le segment usage, tandis que cinq leviers — durée de vie, réemploi, reconditionnement, mutualisation, décommissionnement — s'appliquent au segment fabrication"
    caption: "L'exigence ne regardait que le petit segment. Le grand était déjà payé, et c'est le seul sur lequel on peut encore agir."
    relative: false
    hidden: false
---

*Série Green IT — Article 4/4*

---

Il y a deux ans, dans le cadre d'un programme de mise en conformité CSRD, on m'a remis une exigence non fonctionnelle. Elle tenait en une phrase : la solution doit permettre de disposer d'indicateurs permettant d'évaluer son impact environnemental pendant son exploitation.

Une exigence environnementale, écrite noir sur blanc, dans un document qui engage la conception. Sur le papier, c'est une victoire.

> **En bref**
> - Trois mots suffisent à vider une exigence environnementale de sa portée : *pendant son exploitation* exclut la fabrication, c'est-à-dire le poste le plus lourd.
> - Ce qui est déjà fabriqué est déjà payé. La seule variable qui reste est la durée de vie, le réemploi et le décommissionnement — c'est là que l'économie circulaire de l'IT devient un sujet d'architecture.
> - La contrainte réglementaire a reculé ; l'empreinte, non. Une organisation qui n'a pas préparé le terrain se retrouvera au même point quand la demande reviendra.

{{< imprimer >}}

## Trois mots qui vident une exigence

Relisons-la, parce que tout se joue dans sa formulation.

Elle demande de « disposer d'indicateurs permettant d'évaluer ». C'est une capacité, pas un seuil. Aucune unité fonctionnelle : un impact rapporté à quoi, par utilisateur, par transaction, par document traité ? Aucune valeur cible. Résultat, n'importe quel tableau de bord la satisfait, et aucune option d'architecture ne peut être écartée sur son fondement.

Mais le vrai problème est ailleurs, dans trois mots : **pendant son exploitation**.

Cette formule exclut par construction l'empreinte de fabrication. Or c'est environ 42 % de l'empreinte du numérique français qui vient de la fabrication des terminaux, contre 8 % pour leur utilisation, selon les travaux ADEME-Arcep cités dans le premier article de cette série. Et quand un groupe industriel international mesure son propre parc et publie ses chiffres, il trouve pour ses ordinateurs un rapport de 80 % de fabrication contre 20 % d'usage électrique.

**Une exigence environnementale qui ne regarde que l'exploitation écarte quatre cinquièmes de ce qu'elle prétend cadrer.**

Ce n'est pas de la mauvaise foi. C'est un réflexe : on mesure ce qui se consomme sous nos yeux, sur nos factures, dans nos tableaux de bord. La fabrication est ailleurs, chez le fournisseur, avant la livraison. Elle n'apparaît nulle part — et le premier article de cette série montrait déjà que le poste le plus lourd est précisément celui que personne ne porte à son bilan.

## Ce qui est déjà fabriqué est déjà payé

Et c'est là que le sujet bascule.

Si l'essentiel de l'impact est embarqué dans le matériel, alors cet impact est déjà payé au moment où l'équipement arrive sur le quai. Aucune optimisation d'exploitation ne le récupérera. La seule variable qui reste, c'est ce qu'on en fait : sur combien d'années, et sur combien d'usages réels, on l'amortit.

Autrement dit, **le levier majeur du green IT n'est pas la consommation électrique. C'est la durée de vie.** Et avec elle : le réemploi, le reconditionnement, la mutualisation de plusieurs usages sur un même équipement, et le décommissionnement propre de ce qui ne sert plus.

C'est exactement la conclusion qu'en tire le groupe industriel dont je parlais plus haut. Une fois la mesure disponible par catégorie, avec le détail entre coût de fabrication et coût d'usage, la stratégie devient évidente : il faut cibler la durée d'usage du matériel. Pas l'efficience de la climatisation.

Ce raisonnement, un architecte le tient déjà sans le savoir. Quand on raisonne en coût total de possession, le décommissionnement fait partie de l'équation depuis toujours, au même titre que le build, le run et la montée en charge. L'économie circulaire de l'IT ne demande pas d'inventer une catégorie : elle demande d'instruire enfin la fin de vie qu'on avait déjà inscrite au tableau et qu'on ne regarde jamais.

Et c'est pour cette raison qu'elle n'est pas un sujet RSE. Une direction RSE peut porter l'objectif, elle ne peut pas décider qu'on mutualise quatre cas d'usage sur un seul écran, qu'on prolonge un parc de deux ans, ou qu'on décommissionne une application dormante. Ces décisions-là se prennent dans les arbitrages d'architecture — le premier article de cette série défendait déjà que la sobriété y a sa place comme attribut de qualité, aux côtés de la latence, de la disponibilité et de la sécurité.

## Ce que l'exigence aurait pu dire

Reprenons la phrase qu'on m'a remise, et corrigeons-la sur les trois points qui la rendaient inopérante.

Il lui manquait une **unité fonctionnelle**. Un impact en valeur absolue ne se compare à rien ; rapporté à une transaction, à un utilisateur actif ou à un document traité, il devient un chiffre qu'on peut poser en face d'une option d'architecture.

Il lui manquait un **seuil**. Une capacité d'évaluation ne permet d'écarter aucune solution. Une valeur cible, même approximative et révisable, oblige à choisir.

Et il lui manquait le **périmètre complet**, émissions embarquées comprises. C'est le point décisif, et c'est aussi celui qui fait la différence entre les deux métriques que cette série a opposées. Le PUE est un ratio d'enveloppe qui ignore ce que le calcul sert. Le *Software Carbon Intensity*, normalisé sous ISO/IEC 21031 en 2024, est un taux d'émissions rapporté à une unité fonctionnelle, dont la formule intègre les émissions embarquées du matériel.

Quant à savoir où cette exigence se trace et se surveille une fois écrite correctement, l'architecture continue fournit les objets sans qu'on ait rien à créer : l'arbitrage se documente dans une décision d'architecture, le seuil se contrôle par une fitness function, et la capacité se prépare en amont. Ce sont des moyens, pas le sujet. Le sujet, c'est que la phrase soit écrite de façon à pouvoir trancher quelque chose.

## Le point dur, c'est la donnée

Je le dis depuis le premier article de cette série : je n'ai pas résolu la question du sourçage des données, et je ne vais pas faire semblant maintenant.

Le témoignage public que j'ai cité plus haut donne une idée honnête de ce que ça coûte. Le groupe a commencé en 2019 avec un tableur, pour explorer les méthodologies et les périmètres. Puis un outil interne, élargi, audité par des tiers. La difficulté identifiée est toujours la même : il faut automatiser les flux de collecte, et atteindre un niveau de qualité suffisant de la donnée source pour que le résultat soit fiable.

Dans les faits, chaque source devait être personnalisée. Pour un même élément technique — un serveur — plusieurs sources différentes selon les modèles, et du code à réactualiser à chaque changement. D'où le passage à une solution du marché adossée à la CMDB, déployée en moins de trois mois avec marche en double, transfert des règles métier, standardisation des flux et analyse partagée des écarts entre les deux outils.

Nous sommes en 2026. Le prochain objectif annoncé est de passer de grandes catégories — serveurs, logiciels, équipements réseau — à la maille application. Sept ans après le premier tableur.

Ce n'est pas un reproche, c'est une mesure de la difficulté. Et c'est très exactement ce que défendait le deuxième article de cette série : sans rattachement fiable entre les applications et leurs éléments de configuration, l'empreinte reste une estimation. La maille application n'est pas un raffinement, c'est la condition pour que le chiffre serve à décider.

Un détail de ce témoignage mérite qu'on s'y arrête, parce qu'il est la meilleure nouvelle de cet article. Une fois la mesure disponible, les équipes techniques ont compris que l'outil ne restituait rien d'autre que la qualité de la donnée qu'elles fournissaient. Alors elles ont redoublé d'efforts pour fournir une donnée de qualité, afin d'obtenir en retour une mesure de qualité.

**Personne ne les y a contraintes. La mesure a suffi, parce qu'elle leur revenait.** C'est une boucle de rétroaction au sens strict, observée en production — et c'est la démonstration que le dispositif tient sans comité supplémentaire, à condition que le chiffre soit visible par ceux qui alimentent la donnée.

## L'exigence était juste, elle est arrivée trop tôt

Revenons à ma phrase de départ, et à ce que j'en ai fait.

J'ai fait le travail que je pouvais faire : rendre visibles les incohérences, et documenter l'impossibilité de mettre en œuvre cette exigence dans un écosystème qui n'était pas prévu pour la recevoir. Pas de référentiel exploitable, pas de facteurs d'émission rattachables aux objets, pas de chaîne de collecte.

La réponse a été : on la traitera en dernier, mais on la traitera.

Vous connaissez cette phrase. Elle signifie qu'on ne la traitera pas. Je n'avais aucun levier pour obtenir autre chose — et le deuxième article de cette série expliquait pourquoi : un architecte convaincant sans mandat produit un résultat qui disparaît avec lui. Je suis partie. Je ne sais pas ce qu'ils en ont fait.

Ce que je sais, c'est que la pression réglementaire a reculé entre-temps. La directive Omnibus I, entrée en vigueur le 18 mars 2026, a relevé les seuils de la CSRD à mille salariés et 450 millions d'euros de chiffre d'affaires net, réduisant d'environ 80 % le nombre d'entreprises concernées, et repoussant de deux ans les échéances des vagues suivantes. Beaucoup d'organisations qui avaient lancé un chantier en 2024 se retrouvent hors champ, ou avec un calendrier qui a glissé.

Je comprends le soulagement. Je le trouve dangereux.

**La contrainte réglementaire a reculé. L'empreinte, non.** L'atmosphère ne tient pas de comptabilité par directive européenne, et le matériel déjà fabriqué reste déjà payé. Le recul ne change qu'une chose : la date à laquelle la question reviendra.

Et elle reviendra. Par la réglementation — une clause de revoyure est inscrite dans le texte — ou par le coût de l'énergie, ou par la disponibilité des équipements, ou par un client qui l'exigera dans son questionnaire fournisseur.

Ce jour-là, l'organisation que j'ai quittée se retrouvera exactement au point où je l'ai laissée. Sauf si quelqu'un, entre-temps, a construit la capacité de répondre. C'est précisément ce que signifie préparer le terrain : instruire le référentiel, rattacher les équipements aux usages, et écrire l'exigence de façon à pouvoir trancher. Pas parce qu'on y est obligé aujourd'hui. Parce qu'on le sera demain, et qu'il sera trop tard pour commencer.

## Ce que cette série aura dit

Quatre articles, et un seul mécanisme.

Un programme green d'un côté, un écran par cas d'usage de l'autre : chacun optimise, personne n'arbitre. Un référentiel applicatif qu'on ne sait plus lire, et quatre indicateurs qui s'éteignent ensemble. Une IA qu'on déploie sans instruire ce qu'elle apporte, parce qu'aucune instance ne pose la question. Et une exigence environnementale écrite trop tôt pour un système qui ne savait pas la recevoir.

À chaque fois, la même chose manque : non pas la bonne intention, non pas la bonne technologie, mais un endroit où les arbitrages se posent ensemble.

Je n'ai pas de recette, et cette série n'en propose pas. J'ai une conviction, formée sur le terrain et corrigée par lui : la sobriété et l'économie circulaire de l'IT ne sont pas des programmes à installer à côté. Ce sont des attributs de qualité, qui se tranchent là où se tranchent déjà la latence, le coût et la sécurité.

Si vous faites autrement, ou si vous avez essayé et que ça n'a pas tenu, écrivez-moi. C'est ce que je cherche à documenter depuis le début de cette série, et je n'ai pas fini.

---

## Sources & liens utiles

### Mesure et métriques

- **ISO/IEC 21031:2024 — Software Carbon Intensity (SCI) specification**. Taux d'émissions carbone rapporté à une unité fonctionnelle logicielle, intégrant les émissions embarquées du matériel. → [iso.org/standard/86612.html](https://www.iso.org/standard/86612.html)
- **Green Software Foundation — spécification SCI**. → [greensoftware.foundation/standards/sci](https://greensoftware.foundation/standards/sci/)
- **ADEME / Arcep**, évaluation de l'empreinte environnementale du numérique en France : part de la fabrication des terminaux dans l'empreinte totale. Voir les sources détaillées du premier article de cette série.

### Retour d'expérience public

- **Témoignage client publié par l'éditeur Aguaro**, sur la démarche de mesure de l'empreinte carbone IT d'un groupe industriel international : démarrage en 2019 sur tableur, outil interne, puis intégration à la CMDB ServiceNow ; répartition fabrication/usage observée sur le parc d'ordinateurs ; passage à la maille application annoncé comme objectif suivant. → [Témoignage et vidéo](https://www.aguaro.io/fr/customer-stories/michelin-decarbonation-numerique-comptabilite-environnementale)

*Réserve de méthode : il s'agit d'un témoignage client produit et publié par un éditeur de logiciels, donc d'une source ayant un intérêt commercial dans le récit qu'elle présente. Je le cite pour les ordres de grandeur, pour la chronologie et pour le mécanisme de boucle de rétroaction décrit, non comme une évaluation indépendante.*

### Cadre réglementaire

- **Directive (UE) 2025/794 dite « stop the clock »**, avril 2025 : report de deux ans des obligations de reporting pour les vagues suivantes de la CSRD.
- **Directive « Omnibus I »**, publiée au Journal officiel de l'Union européenne le 26 février 2026 et entrée en vigueur le 18 mars 2026 : relèvement des seuils CSRD à 1 000 salariés et 450 M€ de chiffre d'affaires net, réduction d'environ 80 % du nombre d'entreprises concernées, allègement des normes ESRS. Transposition en droit national attendue au plus tard le 19 mars 2027. → [Service Public Entreprendre](https://entreprendre.service-public.gouv.fr/actualites/A18827)

### Cadre conceptuel mobilisé

- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021). Attributs de qualité, décisions d'architecture, dette technique et boucles de rétroaction. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### Les autres articles de cette série

- Article 1/4 : *Chacun optimise, personne n'arbitre* → [/articles/2026-09-04-chacun-optimise-personne-arbitre/](/articles/2026-09-04-chacun-optimise-personne-arbitre/)
- Article 2/4 : *La dette technique est une dette carbone* → [/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/](/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/)
- Article 3/4 : *Ce n'est pas l'IA qui est pyromane* → [/articles/2026-09-09-ce-n-est-pas-l-ia-qui-est-pyromane/](/articles/2026-09-09-ce-n-est-pas-l-ia-qui-est-pyromane/)
- *Nous venons du chaos, l'IA de la logique* (2025) → [Le livre](https://amzn.eu/d/07jFAfN9)
- Dossier : *L'Architecture Continue face à l'imprévisible (2026)* → [/dossiers/architecture-continue-polycrise-2026.html](/dossiers/architecture-continue-polycrise-2026.html)

---

*Vos réactions, désaccords, compléments d'information sont bienvenus — et sur ce sujet, particulièrement vos exigences non fonctionnelles environnementales, réussies ou non. Écrivez-moi à [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #EconomieCirculaire #ArchitectureEntreprise #CSRD #ContinuousArchitecture #SobrieteNumerique
