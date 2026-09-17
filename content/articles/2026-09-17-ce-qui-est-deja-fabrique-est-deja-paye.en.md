---
title: "What is already manufactured is already paid for"
date: 2026-09-17
description: "Green IT: an environmental non-functional requirement I was handed, and the three words that emptied it of its force. Last in a four-part series on green IT and the circular economy of IT — why hardware lifespan is the real lever, and what it costs not to prepare the ground. (4/4)"
categories: ["Architecture"]
tags: ["green IT", "circular economy", "architecture", "governance", "CSRD", "Continuous Architecture"]
draft: false
cover:
    image: "/images/articles/green-it-4-Economie Circulaire-en.jpg"
    alt: "Bar showing the footprint of a device, split into a large manufacturing segment and a small usage segment; the requirement covers only the usage segment, while five levers — lifespan, reuse, refurbishment, pooling, decommissioning — apply to the manufacturing segment"
    caption: "The requirement looked only at the small segment. The large one was already paid for, and it is the only one still open to action."
    relative: false
    hidden: false
---

*Green IT series — Article 4/4*

---

Two years ago, as part of a CSRD compliance programme, I was handed a non-functional requirement. It came down to a single sentence: the solution must make it possible to have indicators for assessing its environmental impact during operation.

An environmental requirement, written in black and white, in a document that binds design. On paper, that is a win.

> **In short**
> - Three words are enough to empty an environmental requirement of its force: *during operation* excludes manufacturing, which is to say the heaviest item of all.
> - What is already manufactured is already paid for. The only remaining variable is lifespan, reuse and decommissioning — which is where the circular economy of IT becomes an architecture subject.
> - Regulatory pressure has receded; the footprint has not. An organisation that has not prepared the ground will find itself at exactly the same point when the demand returns.

{{< imprimer >}}

## Three words that empty a requirement

Let us read it again, because everything turns on how it is worded.

It asks for the ability "to have indicators for assessing". That is a capability, not a threshold. No functional unit: impact relative to what — per user, per transaction, per document processed? No target value. As a result, any dashboard satisfies it, and no architecture option can be ruled out on its basis.

But the real problem lies elsewhere, in three words: **during operation**.

That phrasing excludes embodied manufacturing emissions by construction. Yet around 42% of the footprint of French digital technology comes from manufacturing devices, against 8% for using them, according to the ADEME-Arcep work cited in the first article of this series. And when an international industrial group measures its own estate and publishes the figures, it finds a ratio of 80% manufacturing to 20% electricity use for its computers.

**An environmental requirement that looks only at operation writes off four fifths of what it claims to govern.**

This is not bad faith. It is a reflex: we measure what is consumed in front of us, on our invoices, in our dashboards. Manufacturing happens elsewhere, at the supplier's, before delivery. It appears nowhere — and the first article in this series already showed that the heaviest line item is precisely the one nobody carries on their books.

## What is already manufactured is already paid for

And this is where the subject tips over.

If most of the impact is embodied in the hardware, then that impact is already paid for by the time the equipment reaches the loading bay. No operational optimisation will recover it. The only remaining variable is what you do with it: across how many years, and how many real uses, you amortise it.

Put differently, **the main lever in green IT is not electricity consumption. It is lifespan.** And with it: reuse, refurbishment, pooling several uses onto a single piece of equipment, and cleanly decommissioning what no longer serves.

That is exactly the conclusion drawn by the industrial group mentioned above. Once the measurement was available by category, with the split between manufacturing cost and usage cost, the strategy became obvious: target how long the hardware stays in use. Not the efficiency of the cooling.

An architect already makes this argument without realising it. When you reason in total cost of ownership, decommissioning has always been part of the equation, alongside build, run and scaling. The circular economy of IT does not ask us to invent a category: it asks us finally to examine the end of life we had already written down and never look at.

Which is why it is not a CSR subject. A CSR team can carry the objective; it cannot decide that four use cases will share one screen, that an estate will run two years longer, or that a dormant application will be decommissioned. Those decisions are taken in architectural trade-offs — and the first article in this series already argued that sobriety belongs there as a quality attribute, alongside latency, availability and security.

## What the requirement could have said

Let us take the sentence I was handed and correct it on the three points that made it inoperative.

It lacked a **functional unit**. An impact in absolute terms compares to nothing; related to a transaction, an active user or a document processed, it becomes a number you can put next to an architecture option.

It lacked a **threshold**. A capability to assess rules out no solution. A target value, even approximate and revisable, forces a choice.

And it lacked the **full scope**, embodied emissions included. That is the decisive point, and it is also what separates the two metrics this series has set against each other. PUE is an envelope ratio that ignores what the computation serves. *Software Carbon Intensity*, standardised as ISO/IEC 21031 in 2024, is a rate of emissions per functional unit whose formula incorporates the embodied emissions of hardware.

As for where such a requirement gets recorded and monitored once written properly, Continuous Architecture supplies the objects without anything needing to be created: the trade-off is documented in an architectural decision, the threshold is checked by a fitness function, and the capability is prepared upstream. These are means, not the subject. The subject is that the sentence be written so that it can settle something.

## The hard part is the data

I have said it since the first article in this series: I have not solved the question of sourcing the data, and I am not going to pretend otherwise now.

The public testimonial cited above gives an honest sense of what it costs. The group started in 2019 with a spreadsheet, to explore methodologies and scopes. Then an internal tool, broadened, audited by third parties. The difficulty identified is always the same: you have to automate the collection flows, and reach a sufficient level of source data quality for the result to be reliable.

In practice, each source had to be customised. For a single technical item — a server — several different sources depending on the model, and code to update with every change. Hence the move to a market solution sitting on the CMDB, deployed in under three months with a parallel run, business rules transferred, data flows standardised, and the gaps between the two tools analysed and shared with the teams.

It is now 2026. The stated next objective is to move from broad categories — servers, software, network equipment — down to application level. Seven years after the first spreadsheet.

This is not a criticism, it is a measure of the difficulty. And it is precisely what the second article in this series argued: without a reliable link between applications and their configuration items, the footprint stays an estimate. Application-level granularity is not a refinement, it is the condition for the number to be usable in a decision.

One detail of that testimonial deserves a pause, because it is the best news in this article. Once the measurement was available, the technical teams understood that the tool reflected nothing other than the quality of the data they supplied. So they redoubled their efforts to supply quality data, in order to get a quality measurement back.

**Nobody compelled them. The measurement was enough, because it came back to them.** That is a feedback loop in the strict sense, observed in production — and it is the demonstration that the arrangement holds without one more committee, provided the number is visible to the people who feed the data.

## The requirement was right; it arrived too early

Back to my opening sentence, and to what I did with it.

I did the work I was able to do: make the inconsistencies visible, and document the impossibility of implementing that requirement in an ecosystem that was not built to receive it. No usable repository, no emission factors attachable to the objects, no collection chain.

The answer was: we will deal with it last, but we will deal with it.

You know that sentence. It means it will not be dealt with. I had no lever to obtain anything else — and the second article in this series explained why: a persuasive architect without a mandate produces a result that disappears with them. I left. I do not know what became of it.

What I do know is that regulatory pressure has receded in the meantime. The Omnibus I directive, in force since 18 March 2026, has raised the CSRD thresholds to one thousand employees and €450 million in net turnover, cutting the number of companies in scope by roughly 80%, and pushing back the deadlines for subsequent waves by two years. Many organisations that started a programme in 2024 now find themselves out of scope, or on a timetable that has slipped.

I understand the relief. I find it dangerous.

**Regulatory pressure has receded. The footprint has not.** The atmosphere keeps no accounts by European directive, and hardware already manufactured remains already paid for. The retreat changes only one thing: the date on which the question comes back.

And it will come back. Through regulation — a review clause is written into the text — or through the cost of energy, or through equipment availability, or through a client who will demand it in a supplier questionnaire.

On that day, the organisation I left will find itself exactly where I left it. Unless someone, in the meantime, has built the capability to answer. That is what preparing the ground means: getting the repository in order, attaching equipment to uses, and writing the requirement so that it can settle something. Not because you are obliged to today. Because you will be tomorrow, and it will be too late to start.

## What this series will have said

Four articles, and a single mechanism.

A green programme on one side, one screen per use case on the other: everyone optimises, no one arbitrates. An application repository nobody can read any more, and four indicators going dark together. An AI deployed without anyone examining what it brings, because no forum asks the question. And an environmental requirement written too early for a system that could not receive it.

Every time, the same thing is missing: not good intentions, not the right technology, but a place where the trade-offs are weighed together.

I have no recipe, and this series proposes none. I have a conviction, formed in the field and corrected by it: sobriety and the circular economy of IT are not programmes to be installed alongside. They are quality attributes, settled where latency, cost and security are already settled.

If you do it differently, or if you have tried and it did not hold, write to me. That is what I have been trying to document since the start of this series, and I am not finished.

---

## Sources and further reading

### Measurement and metrics

- **ISO/IEC 21031:2024 — Software Carbon Intensity (SCI) specification**. A rate of carbon emissions per software functional unit, incorporating the embodied emissions of hardware. → [iso.org/standard/86612.html](https://www.iso.org/standard/86612.html)
- **Green Software Foundation — SCI specification**. → [greensoftware.foundation/standards/sci](https://greensoftware.foundation/standards/sci/)
- **ADEME / Arcep**, assessment of the environmental footprint of digital technology in France: share of device manufacturing in the total footprint. See the detailed sources in the first article of this series.

### Public field testimonial

- **Customer testimonial published by the software vendor Aguaro**, on an international industrial group's approach to measuring its IT carbon footprint: started in 2019 on a spreadsheet, then an internal tool, then integration with the ServiceNow CMDB; manufacturing/usage split observed on the computer estate; move to application-level granularity announced as the next objective. → [Testimonial and video](https://www.aguaro.io/fr/customer-stories/michelin-decarbonation-numerique-comptabilite-environnementale)

*Methodological caveat: this is a customer testimonial produced and published by a software vendor, and therefore a source with a commercial interest in the story it presents. I cite it for the orders of magnitude, the chronology and the feedback-loop mechanism described, not as an independent assessment.*

### Regulatory framework

- **Directive (EU) 2025/794, known as "stop the clock"**, April 2025: two-year postponement of reporting obligations for the subsequent CSRD waves.
- **"Omnibus I" directive**, published in the Official Journal of the European Union on 26 February 2026 and in force since 18 March 2026: CSRD thresholds raised to 1,000 employees and €450m net turnover, roughly 80% fewer companies in scope, ESRS standards lightened. Transposition into national law expected by 19 March 2027 at the latest. → [Service Public Entreprendre (in French)](https://entreprendre.service-public.gouv.fr/actualites/A18827)

### Framework drawn on

- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021). Quality attributes, architectural decisions, technical debt and feedback loops. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### The other articles in this series

- Article 1/4: *Everyone optimises, no one arbitrates* → [/en/articles/2026-09-04-chacun-optimise-personne-arbitre/](/en/articles/2026-09-04-chacun-optimise-personne-arbitre/)
- Article 2/4: *Technical debt is carbon debt* → [/en/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/](/en/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/)
- Article 3/4: *AI is not the arsonist* → [/en/articles/2026-09-09-ce-n-est-pas-l-ia-qui-est-pyromane/](/en/articles/2026-09-09-ce-n-est-pas-l-ia-qui-est-pyromane/)
- *Nous venons du chaos, l'IA de la logique* (2025, in French) → [The book](https://amzn.eu/d/07jFAfN9)
- Report: *Continuous Architecture facing the unpredictable (2026, in French)* → [/dossiers/architecture-continue-polycrise-2026.html](/dossiers/architecture-continue-polycrise-2026.html)

---

*Your reactions, disagreements and additions are welcome — and on this subject, your environmental non-functional requirements especially, successful or otherwise. Write to me at [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #CircularEconomy #EnterpriseArchitecture #CSRD #ContinuousArchitecture #DigitalSobriety
