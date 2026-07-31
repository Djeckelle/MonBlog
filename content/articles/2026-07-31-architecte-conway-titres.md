---
title: "Loi de Conway : quand les titres RH fragmentent le système avant le code"
date: 2026-07-31
description: "Architecte cloud, architecte IA : pourquoi accoler un titre à une technologie dilue la fonction d'architecte sans conférer la légitimité de l'expert. Une analyse à la lumière de la loi de Conway."
tags: ["EnterpriseArchitecture", "ArchitectureEntreprise", "ContinuousArchitecture", "ConwaysLaw", "TeamTopologies", "TechLeadership", "Europe"]
draft: false
categories: ["Architecture"]

cover:
    image: "/images/articles/dualitetech.png"
    alt: "Role Schizophrenia"
    caption: "When the architect is but a shadow"
    relative: false
    hidden: false
---

# Loi de Conway : quand les titres RH fragmentent le système avant le code

Architecte cloud. Architecte IA. Architecte DevOps. Architecte intégration. Demain, sans doute, architecte agentique. Chaque vague technologique réclame son totem, et l'organisation s'exécute — un poste, une fiche, une ligne dans l'organigramme.

Le problème n'est pas le mot qu'on accole. Le problème, c'est ce qu'on croit obtenir en l'accolant.

***Accoler architecte et cloud, c'est n'avoir ni l'un ni l'autre.*** Pas une double compétence : une double dilution. Celui qui porte ce titre n'exerce plus vraiment la fonction d'architecte — la vision systémique, l'arbitrage transverse, la mise en cohérence entre le métier, les produits voisins, la trajectoire à trois ans — parce qu'il est absorbé par la profondeur technique qu'on attend de lui. Et il n'a plus la légitimité complète de l'expert, parce qu'on lui demande en même temps de "faire de l'architecture", donc de ne jamais aller au bout de cette profondeur. Deux légitimités qu'on a voulu fusionner produisent, mécaniquement, un poste qui n'en a aucune tout à fait.

On connaît la loi de Conway : les organisations conçoivent des systèmes qui reproduisent leur structure de communication. On la cite toujours après coup, pour expliquer pourquoi tel système est aussi fragmenté que l'organigramme qui l'a produit. Mais il y a une Conway plus discrète, plus précoce, qu'on n'examine presque jamais : celle qui opère au moment même où l'on rédige une fiche de poste. ***Un titre composite n'est pas neutre. C'est déjà une décision d'architecture*** — prise sans arbitrage conscient, souvent par les RH ou le recrutement, sans que personne n'ait vraiment tranché la question qui compte : *veut-on garder cette fonction transverse, ou accepter de la fragmenter par technologie ?*

**Le système fragmenté n'arrive pas après. Il est déjà écrit dans l'intitulé du poste.**

## Deux façons de n'être ni l'un ni l'autre

Ce vide de fonction ne se manifeste pas d'une seule manière. On peut le rater par excès de technique, ou par excès de posture. Les deux versions sont aussi fréquentes l'une que l'autre, et aussi coûteuses.

**Première version : l'expert déguisé.** Il connaît son cloud provider sur le bout des doigts, sait arbitrer entre deux services managés à trois heures du matin, a un avis tranché sur la bonne façon de tagger des ressources. Mais il ne s'est jamais demandé ce que sa plateforme fait au produit voisin, à la stratégie de sourcing de l'entreprise, à la trajectoire de dépendance vis-à-vis d'un fournisseur. Il produit une expertise pointue et locale — précieuse en soi — mais aucune traversée. Le titre d'architecte ne fait ici que masquer l'absence de vision systémique derrière un vernis de légitimité stratégique que la fonction n'a, dans les faits, jamais exercée.

**Deuxième version : le gouverneur sans mains.** À l'inverse, on trouve le titulaire du titre qui a fini par ne plus toucher à rien de concret. Il produit des schémas, anime des comités, valide des choix qu'il ne sait plus vraiment challenger sur le fond, parce que sa compréhension de la technologie s'est arrêtée au moment où on lui a collé l'étiquette. Il a la posture sans la profondeur — et perd, du même coup, la crédibilité technique qui seule permet à un architecte de se faire entendre d'un expert. C'est le syndrome PowerPoint dans sa version la plus classique : on gouverne un territoire qu'on ne comprend plus assez pour y arbitrer utilement.

Ces deux figures ne sont pas des erreurs individuelles. Ce sont deux issues logiques, prévisibles, du même geste initial : avoir demandé à un seul poste de porter deux légitimités qui exigent, chacune, un investissement à temps plein. ***On ne peut pas être à la fois dans la profondeur du comment et dans la traversée du faut-il sans sacrifier l'une des deux*** — et c'est presque toujours la traversée qui cède, parce qu'elle est moins visible, moins mesurable, moins valorisée dans l'instant qu'une compétence technique démontrable.

**Le résultat n'est pas neutre pour l'organisation : elle recrute un poste en attendant qu'il tienne deux fonctions à plein régime, et n'en obtient aucune vraiment.**

## Un cas d'école : l'industrie 4.0

Prenez un site industriel qui se lance dans sa transformation 4.0. Capteurs IoT sur les lignes, remontée de données vers un MES, ambition de jumeau numérique, convergence progressive entre le monde OT (automates, SCADA, réseaux industriels) et le monde IT (ERP, data platform, cloud). Le sujet est réel, le besoin de compétence pointue aussi : protocoles industriels (OPC-UA, MQTT), edge computing, cybersécurité OT — personne ne conteste qu'il faille une expertise sérieuse là-dessus.

L'organisation crée alors un poste : architecte IoT industriel. Et c'est précisément là que la Conway anticipée fait son travail, avant même que la première ligne ne soit connectée.

Ce que ce titre finit par produire, dans la plupart des cas observés : quelqu'un de très légitime pour choisir le bon protocole de collecte, dimensionner l'edge computing, sécuriser le flux capteur-vers-cloud sur *sa* ligne, *son* site. Un travail réel, technique, nécessaire. Mais personne, dans ce montage, n'est mandaté pour se demander si le modèle de données du site A sera exploitable par le site B, si le jumeau numérique promis à la direction industrielle pourra un jour s'assembler à l'échelle du groupe, ou si la remontée vers l'ERP central respecte la même sémantique métier que celle utilisée par les équipes qualité. ***Chaque "architecte IoT" optimise localement, avec compétence et sincérité — et le système global se fragmente exactement au même rythme que les intitulés de poste***, site après site.

Deux ou trois ans plus tard, l'entreprise se retrouve avec cinq jumeaux numériques incompatibles, cinq choix de protocoles défendables individuellement mais impossibles à consolider, et un programme de convergence OT/IT qui découvre, après coup, qu'il doit refaire le travail d'intégration que personne n'avait pour mission de faire en premier lieu. On appelle alors ça "dette technique". **C'est en réalité une dette de gouvernance, contractée au moment de la fiche de poste, bien avant qu'un seul capteur ne soit posé.**

L'ironie est que le poste manquant avait un nom disponible depuis longtemps : l'architecte produit ou l'architecte plateforme aurait été le bon mandataire pour poser ces questions transverses — quitte à s'appuyer, précisément, sur l'expert IoT pour trancher le comment. Mais ce poste-là ne fait pas rêver un comité de direction en quête de signal d'innovation. "Architecte IoT industriel" sonne mieux dans une communication interne que "architecte produit qui s'appuie sur un expert IoT". ***Le choix du titre a été un choix de communication avant d'être un choix d'organisation*** — et l'organisation en paie le prix, en silence, deux ans plus tard.

## Deux légitimités, pas une hiérarchie

Il serait tentant, à ce stade, de conclure que l'architecte doit reprendre la main sur l'expert — remettre le généraliste au-dessus du spécialiste, comme on remettrait de l'ordre. Ce serait retomber dans le travers inverse, celui de l'*ivory tower architect* que la Continuous Architecture combat depuis des années : l'architecte qui théorise loin du terrain, produit des schémas que personne n'implémente, et perd toute crédibilité technique faute de jamais y retourner. Ce n'est pas un progrès sur le poste fantôme. C'est son symétrique.

**La bonne lecture n'est pas hiérarchique, elle est fonctionnelle : l'expert et l'architecte répondent à deux questions différentes, pas à deux étages d'une même question.** L'expert IoT sait *comment* faire — quel protocole, quelle architecture edge, quel niveau de chiffrement sur quel segment réseau. L'architecte plateforme sait *si* et *où* le faire — est-ce que ce choix reste cohérent avec les quatre autres sites, avec la trajectoire du groupe, avec ce que l'ERP central pourra digérer dans trois ans.

C'est exactement l'image que propose ***[Gregor Hohpe](https://architectelevator.com)*** avec son *architecte-ascenseur* : quelqu'un qui fait la navette entre la salle des machines, où se joue le détail technique, et le dernier étage, où se prennent les décisions stratégiques — et dont l'utilité tient précisément à ce mouvement constant entre les deux, pas à une résidence permanente dans l'un ou l'autre. Un "architecte IoT" scotché à sa salle des machines ne prend jamais l'ascenseur.

Reprenez aussi ***[Kotusev](https://kotusev.com)*** : la zone de dialogue entre l'intentionnel et l'émergent n'existe que si quelqu'un l'anime des deux côtés à la fois — ce n'est le métier ni du pur expert, immergé dans l'émergent, ni de l'architecte hors-sol, qui ne fait qu'intentionnel. C'est un travail de traversée continue, pas un arbitrage ponctuel rendu d'en haut.

Dans le cas du site industriel, ça change concrètement la manière de construire l'équipe : un architecte plateforme qui n'a pas besoin de savoir configurer un gateway OPC-UA, mais qui doit être capable de challenger l'expert sur l'impact de son choix ailleurs dans le système — et un expert IoT qui n'a pas besoin de porter la vision du jumeau numérique à l'échelle groupe, mais qui doit accepter qu'une partie de ses choix locaux lui soit questionnée au nom d'une cohérence qu'il ne voit pas depuis sa ligne de production. **Chacun tient sa légitimité pleine. Aucun des deux n'a besoin de porter le titre de l'autre pour être utile.**

C'est là que le T-Shape prend tout son sens : cette image d'une compétence en double dimension, une vraie profondeur quelque part et une vraie largeur partout ailleurs — mais chez la même personne, pas éclatée entre un titre et une réalité de poste qui ne se recouvrent plus.

## Et si le prochain titre s'appelait architecte IA

Tout ce qui vient d'être dit sur le cloud, l'IoT ou le DevOps vaut pour l'IA. ***Mais en pire.***

Parce qu'avec l'IA, l'erreur de titre ne dilue pas seulement une fonction — elle se trompe carrément de compétence à protéger. Ce qui fait la différence entre un système d'IA qui sert réellement une organisation et un système qui produit de jolis résultats sans impact, ce n'est presque jamais le choix du modèle, la taille du GPU, le mode d'hébergement ou le fournisseur du moment. Ces choix-là sont réels, ils demandent un expert, ils méritent d'être bien faits — mais ils sont interchangeables, révisables, et honnêtement secondaires face à la vraie question : ***est-ce que celui qui conçoit le système comprend le métier qu'il s'apprête à assister ?*** Ses processus réels, pas ceux du schéma officiel. Sa donnée, avec ses trous, ses biais historiques, ses définitions maison qui ne correspondent à aucune norme. Ses utilisateurs, avec ce qu'ils font vraiment de l'outil une fois que personne ne les regarde.

Un "architecte IA" recruté sur la maîtrise des modèles et des infrastructures, sans connaissance approfondie du métier qu'il instrumente, reproduit exactement le poste fantôme décrit plus haut — sauf que l'enjeu est plus élevé, parce que l'IA touche directement à la donnée, aux décisions, parfois aux personnes, et que les dégâts d'une architecture pensée par la technique seule n'y sont plus seulement de l'intégration ratée : **ce sont des décisions biaisées, des process dégradés, une confiance érodée, à une échelle et une vitesse qu'aucune techno précédente n'avait atteintes.**

***La vraie compétence rare, sur l'IA, n'est pas technique.*** C'est la connaissance fine du métier qu'on assiste, capable de dire ce qui doit rester sous contrôle humain, ce que la donnée peut vraiment supporter, et ce qu'un processus perd de sens le jour où on l'automatise à moitié. Cette compétence-là, aucun expert en modèles ne la porte par défaut — et aucun titre composite ne la fait apparaître par magie.

Alors non, ***il n'existe pas d'architecte IA.*** Il existe des experts en modèles, en hosting, en fine-tuning — précieux, nécessaires, à recruter sans complexe sous leur vrai nom. Et il existe des architectes, dont le métier reste, IA ou pas, exactement le même qu'avant : savoir ce qu'une technologie fait au reste du système, avant de savoir comment elle fonctionne. **Accoler les deux ne crée pas un super-poste. Ça en efface deux.**

---

## Sources et inspirations

- **[Gregor Hohpe](https://architectelevator.com)** — *The Software Architect Elevator: Redefining the Architect's Role in the Digital Enterprise*, et le concept d'*architecte-ascenseur* développé sur [architectelevator.com](https://architectelevator.com)
- **[Svyatoslav Kotusev](https://kotusev.com)** — *The Practice of Enterprise Architecture: A Modern Approach to Business and IT Alignment*, et ses travaux sur la zone de dialogue entre architecture intentionnelle et design émergent, disponibles sur [kotusev.com](https://kotusev.com)
- Continuous Architecture — [continuous-architecture.org](https://www.continuous-architecture.org/), en particulier les concepts d'*ivory tower architect* et de fitness functions
- Team Topologies — le principe d'alignement des équipes sur l'architecture visée, et non l'inverse
