---
title: "Everyone optimises, no one arbitrates"
date: 2026-09-04
description: "Green IT: a sustainability programme on one side, projects rolling out hardware on the other. First in a four-part series on green IT and the circular economy of IT — the paradox of parallel intentions, and why enterprise architecture is where they can finally meet. (1/4)"
categories: ["Architecture"]
tags: ["green IT", "digital sobriety", "architecture", "governance", "circular economy", "Continuous Architecture"]
draft: false
cover:
    image: "/images/articles/green-it-arbitrage-en.jpg"
    alt: "Two-column diagram: on the left the envelope metrics of a green programme, on the right quality attributes including sobriety alongside latency, availability and security; at the centre a decision trade-off point connecting both and leading to an informed decision"
    caption: "Green programme indicators on one side, quality attributes on the other. Architecture does not decide for others: it makes the trade-off legible."
    relative: false
    hidden: false
---

*Green IT series — Article 1/4*

---

A perfectly cooled datacentre, running workloads no one consults any more, will post an excellent PUE.

That is the whole problem. And it is only the visible version of a much wider paradox.

> **In short**
> - PUE measures the efficiency of the envelope, never the usefulness of the computation — and the same illusion plays out at organisational scale, where a green programme coexists with projects that have no reason to ever cross its path.
> - Enterprise architecture is not there to constrain choices or arbitrate between visions. It is there to make the whole coherent — provided it sits in the right place, with the right levers.
> - Sobriety and the circular economy of IT are not programmes running alongside the value stream. They are quality attributes within the value stream.

{{< imprimer >}}

## A flawless indicator for an absurd system

Let us start with the tool, since the tool is what gets brandished.

The reigning indicator of responsible IT is PUE — *Power Usage Effectiveness*. It is standardised (ISO/IEC 30134-2, with a new edition published in 2026), calculated over a rolling twelve months, and it says one thing: the ratio between the total energy consumed by the facility and the energy consumed by the IT equipment itself.

Read that again. What PUE evaluates is the share of energy lost to cooling, to the UPS, to power distribution. An efficiency indicator for the envelope. Nothing more.

**PUE does not measure the usefulness of the computation. It measures how elegantly we waste.**

This is not a flaw in the standard — the ISO/IEC 30134 series states explicitly that it sets neither limits nor targets, and that a single indicator in isolation cannot describe overall performance. The flaw is in the use: we took a thermal engineering metric and turned it into an environmental communications argument.

Remember the shape of this paradox. A locally optimised object, inside a whole that is not. You will find it everywhere.

## The same paradox, one floor up

In the corridors of a large organisation, I counted the screens. The canteen menu. The floor plan. Real-time occupancy rates. One use case, one screen. Further along, tablets. Further still, mini-PCs.

And on the intranet homepage: a brand-new green programme.

Nobody lied. Nobody cheated. Every decision, taken in isolation, was defensible — and every team was doing its job properly. The green programme was hitting its milestones. The display projects were answering real business needs.

It is the structure of the paradox that deserves attention. An organisation runs a dozen cross-cutting programmes simultaneously: security, data, cloud, employee experience, sustainability. Sometimes they reinforce each other. Sometimes they pull in opposite directions — securing can mean duplicating, and duplicating costs carbon. Most of the time, they simply never meet.

Not one of those screen decisions went through the green programme. Not out of bad faith: because no mechanism existed by which a screen purchase order could ever encounter a carbon objective.

**Everyone optimises. No one arbitrates.**

We call this indifference. That is a diagnostic error, and an expensive one: as long as we believe it is a problem of willingness, we answer with awareness campaigns. It is not a problem of willingness. It is a problem of decision architecture.

And I insist on the word *architecture*, because the mechanism cannot simply be decreed. Recording decisions is not enough: ADRs piled up in a directory, each individually sound but with no coherence across them, lose precisely the meaning they were meant to carry. We land back on the original problem, with added documentation. That deserves its own article, and it will get one.

## What enterprise architecture does — and what it does not

A clarification is needed here, because this is where my profession is most often misunderstood. And for that, we need to go back a long way.

The word comes from the Greek *arkhitekton*: the master builder. From antiquity onwards it names the capacity to conceive a coherent whole out of structuring elements. The Roman architect is simultaneously urban planner, engineer and philosopher — a role at the crossroads of the technical, the aesthetic and the civic. In *De architectura*, written in the first century BC and dedicated to Augustus, Vitruvius sets out the three essential qualities of a work: *firmitas*, durability over time; *utilitas*, usefulness; *venustas*, beauty. Three inseparable qualities, none of which may be sacrificed to the other two.

Put differently: the first list of quality attributes in the history of the discipline is more than two thousand years old. And it opens with durability.

**Enterprise architecture is not there to constrain choices or to arbitrate between visions. It is there to make the whole coherent.**

This is also what [Xavier Chaumont](https://fr.linkedin.com/in/xchaumont/), who leads IT governance, strategy and architecture at GRDF, conveys in a series of images he shared on LinkedIn in 2024. Two of them strike me as decisive here. Enterprise architecture as a **bridge** first: a connector between business and technology, between strategy and execution, between executive management and operational teams. As a **chess game** next, where the essential work consists of balancing options, reducing the risk carried by a decision, and leaving certain doors open so they can be settled later, at the right moment.

This is the *trade-off* that the Continuous Architecture community has made the core of the craft: arbitrating between quality attributes that contradict one another, making explicit what is gained and what is lost, and rendering the compromise legible to those who decide.

Architecture therefore does not decide whether the green programme is right against the display project. It makes visible that both exist, that they pull in different directions, and that someone must settle the matter with full knowledge of what is at stake.

This is a difference in kind, not in degree. A function that constrains produces workarounds. A function that makes things coherent produces informed decisions. Provided, again, that it sits in the right place with the right levers — and this is precisely where most green IT arrangements fail, by installing themselves next to the decision system rather than inside it.

## The line item nobody carries on their books

Back to the screens, because the numbers tell a story the green programme could not see.

The study published in January 2022 by ADEME, France's ecological transition agency, and Arcep, its telecoms regulator, drawing on 2020 data, put the French digital sector's footprint at 17.2 MtCO₂e, or 2.5% of the country's carbon footprint. Its update, published in January 2025 on 2022 data, raises that to roughly 29.5 MtCO₂e and 4.4%. Devices account for half. And within that half, manufacturing dwarfs use: around 42% of the total footprint of French digital comes from manufacturing devices, against 8% for using them.

Put differently: by the time the screen's purchase order is signed, most of the impact is already committed. Before the first kilowatt-hour is consumed in the corridor.

Yet that impact appears on no operational dashboard. It sits in scope 3 — meaning at the supplier's, meaning nowhere in the decision. **The heaviest line item in the digital footprint is precisely the one nobody carries on their books.**

And it needs naming for what it is: intellectual dishonesty. Ecology is a shared matter — the atmosphere does not keep accounts by legal entity. Declaring yourself virtuous while pushing the indicator onto your supplier reduces nothing at all. It moves a line in a table. That is greenwashing, and the fact that it is unintentional in most cases makes it no less effective.

This is also where the circular economy of IT stops being a CSR topic and becomes an architecture topic. If most of the impact is embodied in the hardware, then the major lever is not electricity consumption: it is lifespan, reuse, refurbishment, pooling several uses onto the same equipment — and clean decommissioning. Vitruvius's *firmitas*, twenty centuries later.

None of this vocabulary is exotic to an architect. When you reason in total cost of ownership, decommissioning has always been part of the equation, alongside build, run and scaling. The circular economy does not ask us to invent a category: it asks us to take seriously the end of life we had already written down and never actually examine.

One detail deserves a pause, because it is the very subject of this article. Between the two publications — three years apart, two years between the datasets — the share of digital in the national footprint nearly doubled. Usage did grow, certainly. But ADEME itself attributes the rise principally to a change of scope: datacentres located abroad, hosting French usage, were brought into the calculation when they had previously been absent. What was invisible had not absented itself from reality. It had absented itself from the meter.

## Rantigny: when the paradox changes scale

This dissociation between declared intention and actual decision is not a corporate pathology. It is everywhere, and it grows with scale.

In Rantigny, in the Oise département of northern France, a project for two AI datacentres went through a public inquiry that closed in August 2026, in a village hall where close to three hundred people turned up. The figures on file: 33 hectares of footprint, a local planning amendment reclassifying nearly 22 hectares of farmland, and an announced consumption of around 2.6 TWh a year at full capacity — more than four times the consumption of the ten municipalities of the Liancourtois.

Let us be precise, because precision serves the argument rather than weakening it: the site is partly a former industrial brownfield, and the announced net land take is around seven hectares. This is not the pure sacrifice of arable plain. It is something more interesting: a territory downgrading food-producing land in the name of a strategic project, while another floor of the same Republic writes documents on food sovereignty and land-use restraint.

As the mayor of neighbouring Neuilly-sous-Clermont pointed out, France is not short of brownfield sites that have already been built over. Whether he is right is not the question. The question is which forum could have hosted that trade-off in the first place. The answer: none. Land, energy, food and digital are each examined separately.

Canteen screen or hyperscale campus, the mechanism is identical: the intention is declared in one place, the decision is taken in another, and nothing is designed for the two to meet.

## A metric that arbitrates nothing is an annual report

Here is the hinge of this series.

The problem is not that we do not measure. We measure enormously. Carbon assessments, PUE, CSR dashboards, CSRD reporting: never has so much environmental data circulated inside organisations.

The problem is that these measurements arrive **afterwards**. They describe, they consolidate, they feed an annual report. They never enter the loop where someone decides whether or not a third screen belongs in that corridor.

**A metric that arbitrates nothing is not a steering indicator. It is retrospective accounting.**

## Sobriety is a quality attribute, not a programme

Hence my proposal, and it runs against the usual reflex.

The reflex would be to add a building block. A GreenOps pillar alongside the value stream, a seventh principle, one more committee. That would reproduce, at framework scale, exactly the pathology of the corridor: an intention filed away in a separate box, with no mechanism for meeting real decisions.

I believe we should do the opposite. Add nothing, and bring sustainability in where it has always belonged.

The second principle of Continuous Architecture, as Murat Erder, Pierre Pureur and Eoin Woods formulate it, fits in one sentence: focus on quality attributes rather than functional requirements. Availability, security, performance and resilience have never been programmes on the side. They are quality attributes: expressed in non-functional requirements, settled in ADRs, checked by fitness functions, measured through feedback loops.

**Sobriety is not a programme alongside the value stream. It is a quality attribute within the value stream.**

And for a quality attribute to hold, it needs a decisionable metric — a number you can put on the table against an architecture option, before adopting it. That metric exists: *Software Carbon Intensity*, standardised as ISO/IEC 21031 in 2024. Its logic is the exact opposite of PUE's. It is not an envelope ratio but a rate of emissions per functional unit — per user, per transaction, per API call. And crucially, its formula incorporates the embodied emissions of hardware: scope 3 enters the equation instead of being expelled from it.

I am not claiming SCI is perfect, nor that the data to feed it is easy to obtain. I am claiming it is decisionable where PUE is not. That is a difference in kind, not in precision.

## What changes in the corridor

Let us take the screen one last time, with this lens.

It is not refused in the name of morality. Nor because an architect has been granted a veto — that would take us back to the function that constrains, and therefore to workarounds. It gets discussed. And it gets discussed differently, because the carbon criterion is on the table at the same moment as latency, cost and security, in front of the people who actually decide.

Perhaps the screen stays. Perhaps it becomes a shared display serving four use cases. Perhaps a piece of equipment gets reused rather than newly ordered, which — given the weight of manufacturing — shifts the balance more than six months of energy optimisation.

The debate stops being moral. It becomes architectural again. And that is exactly what enterprise architecture does when it sits in the right place: it does not decide for others, it makes sure the whole stands up. *Firmitas, utilitas, venustas* — the third one is still missing from our information systems, but that is another subject.

This is the lens I use. I do not present it as a standard, and I make no claim to have solved the question of data sourcing, which remains the hard part. If you do it differently — if you have found a way to bring a carbon criterion into an architecture trade-off without creating one more committee — write to me. That is exactly what I am trying to document.

*Next article: technical debt is carbon debt. What dead applications, never-purged data and overprovisioning actually cost — and why CSR departments would gain from working with enterprise architects, who hold neither more power nor more legitimacy than they do, but a cross-cutting view worth sharing.*

---

## Sources and further reading

### Measurement and standards

- **ISO/IEC 30134-2 — Power Usage Effectiveness (PUE)**, key performance indicator for datacentres. The 2016 edition has been withdrawn and replaced by the 2026 edition. The ISO/IEC 30134 series sets neither limits nor targets for its indicators. → [iso.org/standard/30134-2](https://www.iso.org/standard/30134-2)
- **ISO/IEC 21031:2024 — Software Carbon Intensity (SCI) specification**. A rate of carbon emissions per software functional unit, incorporating the embodied emissions of hardware. → [iso.org/standard/86612.html](https://www.iso.org/standard/86612.html)
- **Green Software Foundation — SCI specification** (public version and associated tooling). → [greensoftware.foundation/standards/sci](https://greensoftware.foundation/standards/sci/) and [sci.greensoftware.foundation](https://sci.greensoftware.foundation/)

### Environmental footprint of digital technology in France

- **ADEME / Arcep**, *Environmental footprint of digital technology in France*, first reports submitted to the government on 19 January 2022 (2020 data): 17.2 MtCO₂e, or 2.5% of the national carbon footprint. → [arcep.fr](https://www.arcep.fr/actualites/actualites-et-communiques/detail/n/environnement-190122.html)
- **ADEME / Arcep**, update published on 17 January 2025 (2022 data), extending scope to datacentres located abroad that host French usage: 4.4% of the national carbon footprint. → [arcep.fr](https://www.arcep.fr/la-regulation/grands-dossiers-thematiques-transverses/lempreinte-environnementale-du-numerique.html)
- **ADEME**, press pack "Numérique et environnement" (9 January 2025), attributing the rise principally to the broadened measurement scope. → [ademe.fr](https://www.ademe.fr/wp-content/uploads/2025/01/dossier-de-presse-numerique-et-environnement-090125.pdf)
- **Arcep**, annual survey "Pour un numérique soutenable": share of devices in the carbon footprint of digital, manufacturing versus use. → [arcep.fr](https://www.arcep.fr/cartes-et-donnees/nos-publications-chiffrees/impact-environnemental/enquete-annuelle-pour-un-numerique-soutenable-edition-2025.html)
- **French interministerial Numérique écoresponsable programme**, updated figures on the impact of digital technology in France. → [ecoresponsable.numerique.gouv.fr](https://ecoresponsable.numerique.gouv.fr/actualites/actualisation-ademe-impact/)

### The Rantigny datacentre project (Oise, France)

- **France 3 Hauts-de-France / Franceinfo**, report on the closing public meeting of the inquiry, 19 August 2026 in Rantigny. → [france3-regions.franceinfo.fr](https://france3-regions.franceinfo.fr/hauts-de-france/oise/vous-allez-nous-mettre-un-radiateur-qui-fait-du-bruit-un-projet-de-data-center-divise-les-habitants-d-une-commune-de-l-oise-3404005.html)
- **Reporterre**, investigation into local opposition to the project: land footprint, announced electricity consumption, protected species recorded. → [reporterre.net](https://reporterre.net/Dans-l-Oise-l-opposition-grandit-contre-un-projet-de-data-centers-On-a-investi-dans-une)

### Conceptual frameworks drawn on

- **Vitruvius**, *De architectura*, a treatise in ten books written in the first century BC and dedicated to Augustus. The three qualities set out in Book I — *firmitas*, *utilitas*, *venustas* — were formalised as the "Vitruvian triad" by Claude Perrault in the seventeenth century. → [De architectura](https://en.wikipedia.org/wiki/De_architectura)
- **Xavier Chaumont**, *Enterprise Architecture — What or Why in 7 images*, a series of images shared on LinkedIn in October 2024. IT governance, strategy and architecture at GRDF. The bridge and chess game figures are drawn from that publication. → [LinkedIn profile](https://fr.linkedin.com/in/xchaumont/)
- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021), and *Continuous Architecture: Sustainable Architecture in an Agile and Cloud-Centric World* (Erder & Pureur, Morgan Kaufmann, 2015). The six principles and four essential activities — quality attributes, architectural decisions, technical debt, feedback loops. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### My related writing

- *Nous venons du chaos, l'IA de la logique* (2025, in French) → [The book](https://amzn.eu/d/07jFAfN9)
- Report: *Continuous Architecture facing the unpredictable (2026, in French)* → [/dossiers/architecture-continue-polycrise-2026-en.html](/dossiers/architecture-continue-polycrise-2026-en.htmll)
- Manifesto: *Six habits of an effective information system* → [/en/manifesto/](/en/manifesto/)

---

*Your reactions, disagreements and additions are welcome — and on this subject, counter-examples from the field especially. Write to me at [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #DigitalSobriety #EnterpriseArchitecture #ContinuousArchitecture #CircularEconomy #Governance
