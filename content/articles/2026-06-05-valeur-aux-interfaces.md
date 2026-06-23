---
title: "La valeur est aux interfaces, pas dans la tech"
date: 2026-06-05
description: "Série Decision Day 2026 (3/3). Pourquoi la loi de Conway explique mieux l'échec des programmes IA que n'importe quel benchmark technique — et ce que cela change pour le rôle de l'architecte d'entreprise."
tags: ["IA", "architecture", "loi de Conway", "gouvernance", "Decision Day 2026", "Continuous Architecture", "architecte stratège"]
draft: false
---

*Série Decision Day 2026 — Article 3/3*

---

Il y a une phrase que Vincent Luciani, cofondateur d'Artefact, a posée avec une simplicité désarmante lors du Decision Day 2026 :

> *Ce n'est pas l'IA en tant que telle qui apporte de la valeur. La valeur inexploitée se trouve aux interfaces entre les silos, et dans la transformation des processus.*

Une phrase courte. Qui devrait mettre fin à beaucoup de discussions inutiles — et en ouvrir d'autres, beaucoup plus importantes.

## Ce que cette phrase dit vraiment

Elle dit que l'IA est un révélateur, pas un créateur. Elle ne produit pas de valeur là où il n'y en avait pas. Elle amplifie — en bien comme en mal — ce qui existe déjà dans l'organisation.

Cette intuition n'est pas nouvelle. Elle a une formulation théorique célèbre, attribuée à Melvin Conway en 1968 : *toute organisation qui conçoit un système produit inévitablement un design dont la structure reflète celle de sa propre communication interne*. Autrement dit : les systèmes ressemblent aux organisations qui les fabriquent. Les silos organisationnels engendrent des SI silotés. Les ruptures de communication entre directions produisent des interfaces techniques défaillantes. Les non-décisions stratégiques se traduisent en dette d'architecture.

Conway parlait du logiciel. Mais sa loi décrit en réalité une mécanique plus profonde : **les artefacts techniques sont la projection matérielle d'une géographie organisationnelle**. Et c'est précisément ce que l'IA révèle aujourd'hui, avec une brutalité nouvelle.

Quand Luciani montre que connecter les retours clients au marketing en boucle de feedback temps réel crée de la valeur, il ne décrit pas un cas d'usage IA. Il décrit une interface organisationnelle défaillante — un point de friction entre deux directions qui ne se parlaient pas, ou trop lentement, ou sans langage commun — que la technologie permet désormais de traverser. L'IA n'a pas créé cette valeur. Elle a rendu visible et exploitable ce que l'organisation, par sa structure même, ne pouvait pas faire toute seule.

C'est pour cela que les organisations qui déploient massivement l'IA sans interroger leur géographie interne obtiennent presque toujours le même résultat : **elles automatisent leurs dysfonctionnements**. L'IA fait plus vite ce qui marchait mal. Elle industrialise les ruptures de traduction que la loi de Conway avait gravées dans le SI longtemps avant que ChatGPT n'existe.

## Ce que j'écrivais déjà sur ce fossé

Cette observation, je la formulais autrement dans mon dossier sur [l'Architecture Continue dans un contexte de polycrise](https://laurence-poussard.com/dossiers/architecture-continue-polycrise-2026.html), rédigé au printemps 2026 :

> *Il y a dans presque toutes les grandes organisations un fossé entre ceux qui décident la stratégie et ceux qui font tourner les systèmes. Ce fossé porte des noms divers — silos, dette technique, manque d'alignement — mais sa nature profonde est une rupture de traduction. Personne n'est en charge de relier les bouleversements du monde à la réalité des systèmes.*

Cette rupture de traduction, c'est exactement ce que Luciani appelle *les interfaces entre silos*. Et c'est aussi ce que Conway avait diagnostiqué soixante ans avant lui : un SI qui ne sait pas faire dialoguer ses composants est le reflet fidèle d'une organisation qui ne sait pas faire dialoguer ses directions.

La technologie ne résoudra jamais ce problème. Elle peut au mieux le contourner — et l'IA, avec sa capacité à traverser des langages et des systèmes hétérogènes, est aujourd'hui le contournement le plus puissant jamais inventé.

**Mais contourner n'est pas réparer.** Et c'est là que la question du rôle se pose.

## Le vrai sujet : qui gouverne les interfaces ?

La transformation IA a produit un curieux paradoxe organisationnel. Elle a créé une demande massive de rôles techniques — data engineers, ML engineers, prompt engineers — et a simultanément laissé sans réponse une question structurelle : **qui, dans l'organisation, est responsable de la cohérence entre les silos que l'IA est censée relier ?**

Pas la DSI, dont le périmètre naturel est l'infrastructure et la sécurité.

Pas le CDO, dont le mandat est généralement centré sur la donnée.

Pas le CODIR, qui décide la stratégie mais ne voit pas les systèmes.

Pas les équipes métier, qui vivent à l'intérieur de leurs silos.

Il y a une fonction pour ça. On l'appelle **architecte d'entreprise**. Et dans un monde agentique où la valeur se crée précisément aux interfaces, cette fonction devient non pas moins pertinente, mais structurellement indispensable — à condition qu'elle soit exercée différemment, et que l'organisation lui en donne les moyens.

## L'architecte urbaniste vs l'architecte stratège

C'est le cœur du sujet, et la ligne de partage que le Decision Day a rendu encore plus nette.

**L'architecte urbaniste** produit des schémas. Des cartographies. Des référentiels. Des standards techniques. Il documente l'existant et planifie la cible. C'est utile. C'est nécessaire. Ce n'est pas suffisant — et dans un monde qui se recompose plus vite que les cartographies ne se finalisent, c'est parfois contre-productif. L'urbaniste travaille sur des plans qui supposent une certaine stabilité du territoire. Or le territoire ne tient plus en place.

**L'architecte stratège** fait autre chose. Il fait le trajet complet — de la salle du CODIR au backlog d'une équipe produit, et retour. En boucle. En continu. Il capte les signaux du monde avant qu'ils deviennent des crises. Il traduit — un durcissement réglementaire, une bascule géopolitique, une opportunité IA — en implications concrètes pour le SI. Il structure les conditions dans lesquelles les équipes peuvent décider de manière cohérente sans centraliser chaque arbitrage. Et il ferme la boucle en revisitant régulièrement les hypothèses sur lesquelles les décisions d'architecture ont été prises.

Cette boucle — **capter, traduire, structurer, apprendre** — c'est ce que l'Architecture Continue formalise. C'est aussi ce dont les organisations ont besoin pour que la promesse de Luciani ne reste pas une slide de conférence.

Mais cette boucle ne peut fonctionner que si l'organisation lui donne trois choses indissociables : **un mandat clair, une place dans les instances de décision réelles, et les moyens humains et méthodologiques de tenir la durée**. Sans cela, l'architecture d'entreprise reste ce qu'elle est trop souvent aujourd'hui — une fonction de production de schémas que personne ne lit, dans une organisation qui prend ses décisions stratégiques sans elle.

## Ce que l'IA agentique change pour ce rôle

L'émergence des agents IA amplifie ce besoin de deux façons simultanées.

D'abord, **les agents traversent les silos par nature**. Un agent qui orchestre un workflow entre le CRM, l'ERP et une plateforme d'analyse traverse exactement les interfaces dont Luciani parle — et qui, selon Conway, sont les zones les plus fragiles du SI parce qu'elles reflètent les zones les plus fragiles de l'organisation. S'il n'y a pas de gouvernance de ces interfaces — pas de contrats de délégation clairs, pas de périmètres d'autorité définis, pas de traçabilité des décisions prises — l'agent ne crée pas de valeur aux interfaces. **Il crée du chaos aux interfaces**, à grande vitesse, sur des périmètres que personne n'avait pris la peine de cartographier.

Ensuite, **les agents vont faire émerger des "agents architectes"** — capables de cartographier, d'analyser des incohérences, de proposer des patterns. Ce n'est pas une menace pour la fonction. C'est une évolution du matériau de travail. Comme le BIM a transformé l'architecte du bâtiment sans le supprimer, les agents vont transformer les outils de l'architecte d'entreprise sans remplacer ce qui fait sa valeur réelle : le jugement stratégique, la traduction politique, la capacité à décider ce que l'organisation ne peut pas déléguer à une machine.

Mais cette évolution ne se fera pas toute seule. Elle suppose que les organisations cessent de considérer l'architecture comme une fonction support, et acceptent de la traiter comme ce qu'elle est devenue : **un levier de pilotage stratégique** sans lequel la transformation IA reproduit, au mieux, les dysfonctionnements existants — et, au pire, les amplifie de façon irréversible.

## La question que personne ne pose encore

Luciani a raison : la valeur est aux interfaces. Conway avait raison soixante ans avant lui : les interfaces techniques sont le miroir des interfaces organisationnelles. Et si ces deux observations sont vraies, alors voici la question que les CODIR devraient poser avant leur prochain programme IA :

**Avons-nous, dans notre organisation, quelqu'un dont le mandat explicite est de gouverner ces interfaces — de relier la stratégie à l'exécution, de traduire le monde en contraintes d'architecture, de décider ce que nous déléguons aux agents et ce que nous gardons dans la main ? Et si oui, lui avons-nous donné les moyens et la légitimité institutionnelle d'exercer ce mandat ?**

Pas un chef de projet IA. Pas un data scientist. Pas un consultant qui produit un rapport tous les dix-huit mois.

Un architecte stratège. Présent en continu. Ancré dans le réel. Inscrit dans les instances qui décident. Capable de tenir simultanément le langage du CODIR et le langage des équipes — et de faire circuler la valeur entre les deux. Investi par l'organisation d'un mandat qui dépasse la production de schémas, et qui touche à ce que l'organisation est, à ce qu'elle veut devenir, à ce qu'elle accepte ou refuse de déléguer.

**C'est ce rôle que cette série d'articles a tenté de documenter**, à partir d'une journée de travail aux Invalides. Pas le rôle de celui qui garde le temple technique. Celui de celui qui tient la traduction vivante — dans un monde où l'IA, sans traducteur, ne fera qu'industrialiser nos fractures au lieu de nous aider à les réparer.



## Sources & liens utiles

### L'événement

- **Decision Day 2026**, Hôtel national des Invalides, 5 juin 2026 — journée de réflexion sur la gouvernance des décisions à l'ère de l'IA.

### Les intervenants cités

- **Vincent Luciani**, cofondateur et PDG d'Artefact.
  [Page officielle Artefact](https://www.artefact.com/fr/persons/vincent-luciani/)

### Cadres conceptuels

- **Melvin Conway**, *« How Do Committees Invent? »*, Datamation, avril 1968.
  [Texte original](http://www.melconway.com/Home/Committees_Paper.html)
- **Gregor Hohpe**, *The Software Architect Elevator*, O'Reilly Media, 2020.
  [Présentation O'Reilly](https://www.oreilly.com/library/view/the-software-architect/9781492077534/)
- **Continuous Architecture**, pratique d'architecture évolutive.
  [continuous-architecture.org](https://continuous-architecture.org)

### La série complète Decision Day 2026

1. *Avant de déployer l'IA, avez-vous cartographié vos décisions ?* — [Lire l'article 1/3](/articles/2026-06-05-cartographier-decisions-avant-ia/)
2. *Ce que l'IA fait à notre cerveau* — [Lire l'article 2/3](/articles/2026-06-05-ce-que-ia-fait-a-notre-cerveau/)
3. *La valeur est aux interfaces, pas dans la tech* — cet article

### Mes textes en lien

- *Nous venons du chaos, l'IA de la logique* — Laurence Poussard, 2025. [Disponible sur Amazon](https://amzn.eu/d/07jFAfN9)
- *L'Architecture Continue face à l'imprévisible (2026)* — dossier d'analyse stratégique. [Consulter le dossier](/dossiers/architecture-continue-polycrise-2026.html)
- *Les 6 habitudes d'un SI efficace* — manifeste. [Lire le manifeste](/manifeste/)

---

*Vos réactions, désaccords, compléments d'information sont bienvenus. Écrivez-moi à [contact@laurence-poussard.com](mailto:laurence.poussard63@gmail.com).*

#DecisionDay2026 #ArchitecteStratège #LoiDeConway #GouvernanceIA #ArchitectureContinue #ValeurAuxInterfaces
