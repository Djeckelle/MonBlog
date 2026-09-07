---
title: "Technical debt is carbon debt"
date: 2026-09-07
description: "Green IT: an IT department is asked to measure its footprint, and discovers it cannot. Second in a four-part series — how information debt on the application portfolio simultaneously blocks obsolescence, FinOps, technical debt and GreenOps, and why CSR teams and architects need each other. (2/4)"
categories: ["Architecture"]
tags: ["green IT", "technical debt", "architecture", "governance", "application portfolio", "Continuous Architecture"]
draft: false
cover:
    image: "/images/articles/green-it-2-dette-information-en.jpg"
    alt: "The application reference linked to configuration elements, and the four indicators — obsolescence, FinOps, technical debt, GreenOps and CSR reporting — that fade together when it degrades"
    caption: "Information debt is not just another debt: it's the one that prevents you from examining the others."
    relative: false
    hidden: false
---

*Green IT series — Article 2/4*

---

One day, an IT department is asked to measure the carbon footprint of its application portfolio. The request is legitimate, the sponsor is solid, the deadline is regulatory.

And that is when it emerges that the number is out of reach. Not because the method is missing — because the data it would have to be applied to was bulk-updated some years ago, according to a rule nobody remembers the content of.

A word before going further, since this text opens on what looks like a digression. No carbon debt can be quantified without measuring technical debt, and no technical debt can be measured across a portfolio you can no longer describe. The detour is the road.

> **In short**
> - The application repository is not an administrative inventory: it is the instrument that makes obsolescence, FinOps, technical debt and GreenOps calculable. When it degrades, all four go dark together.
> - What you can no longer trace, you can no longer decommission — and what is not decommissioned goes on carrying a manufacturing footprint already paid for, amortised against nothing.
> - CSR teams know which principles must apply; architects know how a principle becomes a requirement you can hold a decision against. Neither can do it alone.

{{< imprimer >}}

## You are asked for a number you cannot produce

Let us take the scene again, because it plays out everywhere and it is instructive.

The CSR team needs to feed its reporting. It asks, very reasonably, what the estate consists of: how many applications, hosted where, on what equipment, since when, for what use. Nothing exotic. These are the questions an application repository is supposed to document.

The answers do not come. Or rather: they come, but nobody dares use them. Because at some point, some years earlier, a wave of bulk updates filled the empty fields according to an 80/20 rule — the essentials accurate, the rest approximated. The rule was never documented. The people who applied it have left. And today we look at values without knowing which were recorded and which were guessed.

**Nobody is asking this organisation to reduce its footprint. They are asking it to measure it, and it cannot.**

## The bulk update was the only rational way out

We need to understand how this happens, because the reflex — looking for whoever did their job badly — would make us miss the point.

The application repository usually sits under the responsibility of an enterprise architect. They own the tool, the practice, the quality of the data. They absorb pressure from every KPI owner who needs it to be current. But they do not produce the data: it is fed by the other architects — solution, product, full stack — in the course of their assignments.

And those architects do, quite legitimately, what is enough to reach production. The minimum the exit gate demands, not the full completion of a repository whose downstream use they never see.

**The repository owner therefore carries accountability without authority.** They are asked for the quality of data they do not produce, from people who do not report to them, with no lever beyond persuasion.

Then along comes an IT leadership programme that needs consolidated data, with a deadline. The tool owner, cornered, arbitrates coarsely and updates in bulk. This is not a failing. In the position they were placed in, it is the only way out.

Recognise the shape. It is the one from the first article in this series: everyone optimises within their own perimeter, every decision is defensible in isolation, and the aggregate is not. With one difference, and it is a significant one. In the corridor full of screens, the organisation was making incoherent decisions. Here, it loses the ability to decide at all.

## What is no longer known

Missing information does not announce itself. It surfaces by accident: a major clean-up drive with a determined sponsor, an incident, a wave of obsolete component replacement, an audit, an invoice nobody can reconcile.

And the questions that come back then are startlingly ordinary. Who is the business owner of this application? Is it still in production? Is it built in-house or bought? What exactly does it do?

None of them is technical. None of them has an answer.

The cause is usually slight: the person who held the information left, and during the handover nobody mentioned that these fields needed filling in. Nothing dramatic at the time. One omission per departure, multiplied by ten years of turnover.

In the organisations I have worked in, the order of magnitude is consistent: roughly a third of applications — those deemed business-critical — are documented to around 80%. The rest drifts. I give that figure for what it is, a repeated field observation, not a statistic.

## A debt that blocks all the others

This is why the subject deserves better than the "data quality" shelf.

Without a reliable link between applications and their configuration items, four things become incalculable **at the same time**:

1. **Obsolescence.** You do not know which component supports what, so you do not know what breaks if you replace it, nor what is exposed if you do not.
2. **FinOps.** You cannot connect a hosting invoice to a service delivered, so you optimise blind or not at all.
3. **Technical debt.** You cannot date the estate or measure its distance from standards, so you cannot quantify it — and a debt that goes unquantified is never negotiated in committee.
4. **GreenOps and CSR reporting.** You do not know which hardware carries which use, so the footprint stays a corridor estimate.

**Information debt is not one debt among others. It is the one that prevents the others from being examined.** That is why it goes unnoticed: it produces no symptom of its own, only a chronic inability to answer questions asked elsewhere.

Hence the shift I observe in organisations where this works — and they exist. The application is not declared at go-live, when the repository becomes an exit formality. It is declared at functional design. Because that is where resources are reserved, milestones planned, fitness functions defined, runways built. Because you need an identifier to attach the object to a business capability, if only to run the opportunity study.

The benefit is not administrative, it is decisional. You trace the why: why this project reached production, or why it stopped short. And when a rationalisation exercise comes round, you can pull a three-year-old study out of the drawer and decide the moment has finally arrived. The whole IT value chain becomes workable again, from strategy through to execution.

The application repository then stops being an inventory you endure. It becomes the instrument that makes trade-offs possible. Including those of the first article in this series: without it there is no decisionable metric, only estimates you cannot hold anything against.

## Why technical debt is carbon debt

Now to the heart of it, and let us lay the reasoning out in order.

A preliminary remark, because it moves the question from fault to gradient. As early as 1974, studying the evolution of OS/360 at IBM, Meir Lehman and László Belády stated that the complexity of a system embedded in the real world increases as it evolves, unless explicit work is done to maintain or reduce it. Lehman himself suggested seeing an analogue of the second law of thermodynamics in it.

Note the closing clause: *unless explicit work is done*. Debt is not a management accident, it is the gradient. **Doing nothing is therefore not the absence of a decision. It is a decision to let it run.**

The first article in this series established that most of the digital footprint is embodied in manufacturing hardware, not in using it. That footprint is already paid for by the time the equipment arrives. The only remaining variable is what you do with it — that is, across how many years and how many real uses you amortise it.

An application kept alive without use does not merely consume electricity. It immobilises hardware whose manufacturing footprint is amortised against nothing. It occupies storage that is backed up, replicated and archived continuously. It carries a sizing calibrated on a peak load that no longer exists. And it prevents the consolidation that would have taken equipment out of the estate.

The phenomenon is documented, and the most solid figure available is eleven years old. In 2015, Jonathan Koomey, a research fellow at Stanford, and Jon Taylor, of the Anthesis consultancy, analysed a sample of nearly four thousand servers and concluded that 30% of them were "comatose": powered, but delivering no useful work for at least six months. The study covered the North American estate, drew on data supplied by an efficiency software vendor, and corroborated earlier estimates from the Uptime Institute and McKinsey.

But what interests me is not the percentage. It is the motive the authors identify: these servers stay switched on because nobody knows what they do any more, or nobody dares take the risk of turning them off. And the conclusion they draw is that the problem is not technical — it comes down to management practices, information flows and incentives.

**What you can no longer trace, you can no longer switch off.** Decommissioning is not blocked by a technical obstacle. It is blocked by ignorance of what would be decommissioned.

A word on never-purged data, since it follows the same mechanism. I could quote spectacular figures here on dormant data. They have been circulating since 2020, come from a vendor selling data management solutions, and have been repeated verbatim ever since without any refresh. I will refrain: an article about the impossibility of measuring is not going to lean on unverifiable numbers. The reasoning is enough — what is never purged grows, what grows is stored, replicated and backed up, and all of that sits on hardware somebody had to manufacture.

Overprovisioning and the absence of purging are not, in fact, the problems. They are the symptoms of an information system nobody knows how to steer any more.

## The pairing that is missing

That leaves the question of who carries this, and here I want to be precise, because the subject is usually handled by designating someone responsible.

A CSR team knows the regulatory framework, masters the requirements of extra-financial reporting, holds the emission factors and has access to executive bodies. It knows which principles must apply. What it has no particular reason to know is that a principle of environmental responsibility can be translated into a quality requirement — written into non-functional requirements, settled in an ADR, checked by a fitness function, and therefore something a decision can be held against at the moment it is taken.

An architect knows how to make that translation. What an architect does not have is the regulatory mandate or a fine-grained knowledge of the extra-financial framework.

**Neither profession holds the whole translation.** That is exactly what makes the pairing necessary — and it is not a courtesy: it is an observation about complementary competence.

Two clarifications while we are here. First, the subject is not confined to hardware: an organisation's footprint also takes in the travel it generates, the balance of human resources mobilised, the services it purchases. All of which is documented when a set-up is designed, not when an annual table is filled in. Second, this does not concern enterprise architects alone. Solution, product, full stack: societal responsibility is inscribed or lost at every level, from design through deployment and into business as usual.

Let me be explicit, because the previous sentence could be read the wrong way: architects hold neither more power nor more legitimacy than CSR teams. They hold a cross-cutting view and an attachment to the real objects. That is a contribution, not a precedence.

## What makes the arrangement hold

In the cases where this works, early declaration was not obtained through the conviction of a stubborn architect. It is written into the IT department's guiding principles, co-signed by the IT leadership committee.

That changes everything. A persuasive architect produces a result that disappears with them. A co-signed guiding principle produces a framework that survives departures — which, on a subject whose central pathology is information lost at handover, is not a detail.

And it confirms what I argued in the first article: the mechanism cannot be decreed from the ground. It is placed where the levers are.

I do not claim this is simple, nor that I have seen many organisations do it end to end. I have seen enough to know it is possible, and that the difficulty is not technical. If you have brought the quality of the application repository into the objectives of your design teams — or if you tried and it did not hold — write to me. The failures interest me as much as the successes.

*Next article: AI as arsonist and firefighter. What the current wave is doing to the digital footprint, what IT for green actually promises, and how to tell a net gain from a displaced impact.*

---

## Sources and further reading

### Application portfolio and unused servers

- **Jonathan Koomey (Stanford University) and Jon Taylor (Anthesis Group)**, *New data supports finding that 30 percent of servers are "comatose"*, 2015. Sample of nearly 4,000 servers, data collected by TSO Logic. A server is deemed comatose when it has delivered no useful work for at least six months. → [anthesisgroup.com](https://www.anthesisgroup.com/insights/zombie-servers-hunting-down-the-lost-capital/)
- **Koomey & Taylor**, *Zombie/Comatose Servers Redux*, follow-up analysis on a sample four times larger, identical methodology. → [Report (PDF)](https://info.anthesisgroup.com/hubfs/Website%20PDFs/Comatose-Servers-Redux.pdf)
- **NRDC**, 2014 analysis conducted with Anthesis, the origin of the estimate taken up subsequently: servers abandoned by their application owners but kept running because nobody knows what they do. → [nrdc.org](https://www.nrdc.org/bio/pierre-delforge/case-zombie-servers)

*Methodological caveat: this work dates from 2015, covers the North American estate, and the underlying data was supplied by an energy efficiency software vendor. I cite it for the order of magnitude and for the mechanism identified, not as a current measurement of the European estate.*

### Frameworks and reference standards

- **Meir M. Lehman and László A. Belády**, laws of software evolution, formulated from 1974 onwards on the basis of successive releases of OS/360 at IBM. The second law, of increasing complexity: the complexity of an E-type system — one embedded in the real world — increases as it evolves, unless explicit work is done to maintain or reduce it. Lehman himself raises the analogy with the second law of thermodynamics. → M. M. Lehman, *Laws of Software Evolution Revisited*, 1996 ([PDF](https://www.cs.kent.edu/~jmaletic/cs63902/Papers/Lehman96.pdf)) and *Programs, Life Cycles, and Laws of Software Evolution*, Proc. IEEE, vol. 68, no. 9, 1980.
- **French general reference framework for the eco-design of digital services (RGESN)**, version published on 17 May 2024 by Arcep and Arcom with ADEME, under the 2021 REEN law on reducing the environmental footprint of digital technology. 78 criteria across three priority levels, including extending device lifespan and limiting data collection. → [ecoresponsable.numerique.gouv.fr](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/) and [arcep.fr](https://www.arcep.fr/mes-demarches-et-services/entreprises/fiches-pratiques/referentiel-general-ecoconception-services-numeriques.html)
- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021). Technical debt is one of the four essential activities of the framework, alongside quality attributes, architectural decisions and feedback loops. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### My related writing

- Article 1/4: *Everyone optimises, no one arbitrates* → [/en/articles/2026-09-04-chacun-optimise-personne-arbitre/](/en/articles/2026-09-04-chacun-optimise-personne-arbitre/)
- *Nous venons du chaos, l'IA de la logique* (2025, in French) → [The book](https://amzn.eu/d/07jFAfN9)
- Report: *Continuous Architecture facing the unpredictable (2026, in French)* → [/dossiers/architecture-continue-polycrise-2026.html](/dossiers/architecture-continue-polycrise-2026.html)
- Manifesto: *Six habits of an effective information system* → [/en/manifesto/](/en/manifesto/)

---

*Your reactions, disagreements and additions are welcome — and on this subject, your experience of governing application repositories especially. Write to me at [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #TechnicalDebt #EnterpriseArchitecture #ApplicationPortfolio #ContinuousArchitecture #CSR
