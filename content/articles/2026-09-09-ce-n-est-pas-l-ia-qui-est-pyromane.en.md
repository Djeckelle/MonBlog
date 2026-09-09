---
title: "AI is not the arsonist"
date: 2026-09-09
description: "Green IT: AI as firefighter and arsonist is the ambient narrative. Third in a four-part series — what the oil century taught us about arbitration criteria, how an AI use case enters the architecture value chain, and why the resource was never the problem. (3/4)"
categories: ["IA", "Architecture"]
tags: ["green IT", "AI", "governance", "architecture", "decision", "Continuous Architecture"]
draft: false
cover:
    image: "/images/articles/green-it-3-pyromane-arbitrage-en.jpg"
    alt: "Diagram contrasting the ambient narrative of AI as firefighter and arsonist, set aside, with a decision arbitration body surrounded by several axes of value including a dotted carbon axis, above a band showing architecture decision records, fitness functions and runways"
    caption: "A technology has no intentions. The question is which body weighs what a use case brings against what it costs."
    relative: false
    hidden: false
---

*Green IT series — Article 3/4*

---

I have a weather station at home. It gives me temperature, pressure, humidity and the variations of the last few hours. With that, I have a fair idea of tomorrow's weather — and if I am unsure, a dozen outlets publish the forecast for free.

And yet the question of tomorrow's weather is put to generative AI thousands of times a day. Systems which must analyse everything before answering.

> **In short**
> - As long as the only adjustment variable is whether to use it or not, we have no architectural lever. We have a moral one — and a moral lever produces no arbitration.
> - The oil century showed what happens when a single criterion crushes all the others. The resource is not what is at fault; what we do with it is.
> - An AI use case is an architectural decision. It is reasoned through in an ADR, monitored by a fitness function and prepared in a runway — not in one more committee.

{{< imprimer >}}

## Reflex rather than decision

Let us stay with the weather, because it is a textbook case.

The data exists. The reasoning is within reach of anyone who looks at their barometer twice. And the forecast itself is produced once and then distributed to millions — a pooling model we would do well to draw on more often. Going through a system that must analyse everything before answering, despite all that, is not a decision. It is a reflex.

Multiply that reflex by the number of times someone asks a generative AI what a search, a formula, a lookup table or a colleague would have produced faster. We are in the novelty phase: we try everything, on everything, to see. That is human, and at this stage it is even healthy — you only discover the useful applications by exploring the absurd ones.

That is not where the problem lies. It lies in the fact that **the only adjustment variable available to us today is binary: use it, or do not.** That is a moral lever, not an architectural one. And a moral lever, as the first article in this series showed, produces awareness campaigns, workarounds and guilt. Never an arbitration.

Which explains why the debate is stuck. Those who say "do not use it" and those who say "use it everywhere" are arguing over the same binary variable. The interesting questions are elsewhere: for which use, at what granularity, with which model, on what volume, at what frequency.

## What the oil century taught us

Let us take a detour, because we have lived through this sequence before.

Oil was a revolution, then a shock, then a way of life. A resource long treated as inexhaustible, around which one of the most powerful economic empires in history was built. Out of a need for mobility shared by billions of people, a few thousand grew considerably rich. Then reality returned: the resource turned out to be finite, its combustion polluting, and geopolitical crises sent the barrel soaring. Only then did we look seriously at the alternatives.

Beware the temptation here. The easy story would have it that some miracle technology was deliberately buried. That is not what history says, and I have no need of that story. What happened is both more mundane and more serious: **we made things bankable before we made them useful, durable and affordable.** The alternatives were studied, particularly after the oil shocks, and then shelved — not because they did not work, but because the economics of the moment did not reward them.

That is not suppression. It is an absence of arbitration. A single criterion, immediate profitability, crushed all the others — not through conspiracy, but because no forum weighed the others against it.

It is the exact pattern of the first two articles in this series. And it is the situation of AI today.

## The plateau will not arrive on its own

There is an objection to be made here, and I would rather make it myself.

One might hope that the novelty effect wears off, that curiosity reaches a plateau and that we then consume more sensibly. My own oil example says otherwise.

In 1865, in *The Coal Question*, the economist William Stanley Jevons observed that Watt's steam engine, far more economical in coal than Newcomen's, had not reduced English coal consumption. It had multiplied it — because by making the use cheaper, it had made it practicable everywhere. Jevons wrote this already worried about the exhaustion of British reserves.

This is what we now call the rebound effect. Its exact reach remains debated: economists agree on its existence, much less on its magnitude, and rarely to the point of concluding that an efficiency gain is always entirely cancelled out. But the direction is clear.

**An efficiency gain unaccompanied by an arbitration reduces nothing. It widens the field of use.** Every lighter model, every more efficient chip makes AI practicable where it was not, and the unit gain dissolves into volume.

The plateau will therefore arrive if someone decides it will. Not because curiosity runs out.

## Value is not a single number

That leaves the question of whether any of this is theoretical. It is not, and I can speak about it all the more freely because I built the arrangement myself, in-house.

In an organisation where I held the AI function, we put in place a method for arbitrating use cases. It classified first by opportunity — routine use or innovation, internal or external, support function or specific business line — then valued each case against criteria proper to its category, completed by cost, risk and complexity. And crucially, it led somewhere: executive management decided. Some use cases were adopted. Others were not.

An example of one that was, because it says better than anything else what I mean by value.

On an industrial site, a physically demanding production post required real know-how. It was held by seasonal workers who had to be trained every year, with two difficulties that kept worsening: the people trained did not always come back, having found work elsewhere in the meantime, and younger generations no longer want that kind of post. The work, however, still had to be done.

AI took over the task. The people already trained moved from an uncomfortable position on the line to one where they validate the system's decisions, correct them and train it. The know-how was not replaced: it changed place — and it accumulates instead of walking out at the end of every season.

That use case was not adopted because it cost less. It was adopted because it addressed, simultaneously, a physical burden, an erosion of competence and an operational fragility. **Valuing something is precisely that: putting several things on the table and looking at what each option gains and loses on each of them.**

One clarification is due here, because it would be easy to hold it against me: the carbon criterion was not yet in that grid. It was written into my roadmap; it was not in the grid at the time of writing. Hold on to that imperfection — I will come back to it in a moment.

Now the counter-example, because it is more mundane and therefore more instructive.

I go to book an appointment with a practitioner who has followed me for ten years, on a large medical booking platform. I select my reason for consultation — a procedure this practitioner has already performed three times. A message invites me to telephone for that type of procedure. I telephone: a voice assistant takes me through a menu, I select the reason again, and it informs me that it cannot book an appointment for that procedure, before sending me back to the platform.

I end up writing to the practitioner through the platform. The next day, the receptionist calls me back. She apologises, and explains the situation: she now spends her days handling cases one by one — those who come to complain at the desk in person, those who, like me, send a message. Because wherever she places an appointment, the assistant places another one in parallel. She devotes a considerable amount of time to repairing the diary, and no longer has any left for the rest of her job.

Let us do the tally, on the same axes. The patient lost time. The receptionist lost far more, when the tool was meant to save her some — and she loses it correcting the tool itself. The practitioner runs the risk of losing patients less persistent than I am. And meanwhile, two systems ran, consumed, and generated additional human work. Let us hope things have been sorted out for her by the time you read this.

This is not an AI problem. It is a use case whose value nobody examined before deploying it.

And this is why I asked you to hold on to my imperfection. My grid was incomplete — but it existed, and someone used it. **An incomplete grid that a decision body actually uses is worth infinitely more than a perfect criterion nobody ever puts on the table.** When the arbitration mechanism is there, adding a criterion is a few weeks' work. When it is not — the corridor of screens in the first article, the degraded repository in the second, the medical diary above — no criterion gets any purchase at all, and the best carbon indicator in the world is of no use.

It is what I argued last June coming out of the Decision Day: before choosing a model or a budget, map your decisions. Who decides on use cases, against which criteria, and what happens when an opportunity collides with something else? These trade-offs are prepared, not improvised.

## Bringing the decision into the value chain

That leaves the question of how — and I am keen that it should not end in one more committee. Continuous Architecture provides three objects that already exist in organisations that practise it. There is nothing to create.

**The architectural decision, recorded in an ADR.** An AI use case is an architectural decision like any other. You record the model size chosen, the retraining frequency, the caching strategy, the alternatives discarded, and what is gained and lost on each attribute. The document is not the point — the point is having had to make the trade-off explicit in front of someone.

**The fitness function.** A threshold, measured continuously, that raises a flag when an option drifts. On an AI use case, that might be consumption or emissions per functional unit — per transaction processed, per document analysed, per assisted decision. The point is not metrological perfection. It is having a number that moves and that someone looks at.

**The runway.** Preparing capability before you need it. On this subject, that means having a usable application repository — the second article in this series explains why — an inventory of models in production, and a real measure of usage. Without that foundation, the fitness function has nothing to measure.

And the questions to ask in a design review, in this order:

1. **What decision does this use support or prepare**, and at what level of delegation?
2. **Is there a more direct means** — a business rule, a lookup table, a calculation, data already produced elsewhere?
3. **What model size is sufficient** for a scoped task? A specialised model often does as well as a generalist one.
4. **What volume of data is genuinely required**, and how fresh must it be?
5. **What share of calls is avoidable** through caching, pre-aggregation or upstream filtering?
6. **Does this task require reasoning, or simple generation?** The energy gap between the two runs to orders of magnitude.
7. **How often do we retrain**, and on what signal?

None of these questions is moral. All of them are decisionable. And none of them gets asked as long as the only thing we know how to say is "it consumes".

## What we can measure, and it is little

A word on the figures now, because they are more fragile than either side of the debate admits.

What we are sure of: the electricity consumption of datacentres is rising fast. The International Energy Agency puts it at 485 TWh in 2025 and projects a doubling by 2030, to around 950 TWh — close to 3% of world electricity. AI-dedicated datacentres triple over the same period.

What we are less sure of begins as soon as you look at how the figure is built. For that same year, 2025, the Energy Institute puts forward 787.8 TWh, on a broader scope covering 47 countries, cooling and ancillary systems included. The two institutions are not in disagreement: they are not measuring the same thing.

You recognise the shape. It is the one from the first article, when the footprint of French digital went from 2.5% to 4.4% for largely methodological reasons. **On the footprint of digital technology, the first figure to ask for is not the value. It is the scope.**

Go down to consumption per query and it is worse: estimates vary by an order of magnitude depending on source and year, providers publish values well below independent assessments, and almost none specifies whether it covers inference alone, amortised training, or the hardware that had to be manufactured. So I quote none of them — not out of excessive caution, but because I could not tell you what any of them measures.

One point is established, however, and it is the one that matters for question 6 above: not all uses are equivalent. The IEA notes that video generation, reasoning and agentic uses can consume several hundred to several thousand times more energy per query than simple text generation.

Which is precisely the proof that the subject is architectural, not moral.

## AI is not the arsonist

The ambient narrative fits in one image: AI as both firefighter and arsonist, sold as a climate solution by the very people building the infrastructure that weighs.

The image is useful for naming actors, and on that point it hits its mark. It becomes misleading the moment it is applied to the technology. A model has no intentions. It does not decide to be deployed on a booking loop that books nothing, nor to produce a weather forecast that ten outlets already publish. Nor does it decide to lift someone out of a physically punishing job.

We do.

**AI is not the arsonist. We are — as with coal, as with oil, and for the same reason: consuming without asking the question of durability is human, and nothing in our organisations obliges anyone to ask it.**

Which is, on balance, good news. If the problem were the technology, we would have to wait for the next generation. If it lies in our decision mechanisms, it is within our reach — and it is the work of enterprise architecture.

What would change everything is not spectacular: that the question of what a use case brings and what it costs be asked in the same room, at the same moment, in front of the same people. Not in two forums that never meet.

I have no recipe, and I have not yet seen an organisation bring an environmental criterion into an AI arbitration grid end to end. If you have done it, or broken your teeth trying, write to me. That is exactly what I am trying to document.

*Next article: sobriety as a fitness function. How an environmental criterion concretely enters a non-functional requirement, an architectural decision and a feedback loop — and why it is neither a brake nor a nicety, but a quality attribute in its own right.*

---

## Sources and further reading

### Energy consumption of AI and datacentres

- **International Energy Agency (IEA)**, *Key Questions on Energy and AI*. Datacentre electricity consumption estimated at 485 TWh in 2025, projected at around 950 TWh in 2030, close to 3% of world electricity demand; AI-dedicated datacentres triple over the period. The report also notes that video generation, reasoning and agentic tasks can consume several hundred to several thousand times more energy per query than simple text generation. → [iea.org](https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary)
- **Energy Institute**, *Statistical Review of World Energy 2026*. Estimate of 787.8 TWh for 2025 on a scope covering 47 countries, cooling and ancillary systems included. The gap with the IEA is a matter of measurement scope, not disagreement on the trend. → [energyinst.org](https://www.energyinst.org/statistical-review)

*Methodological caveat: estimates of consumption per query vary by an order of magnitude depending on source, year and scope adopted (inference alone, amortised training, embodied hardware emissions). Values published by providers are appreciably lower than independent assessments. I refrain from quoting any.*

### Rebound effect

- **William Stanley Jevons**, *The Coal Question: An Inquiry Concerning the Progress of the Nation, and the Probable Exhaustion of Our Coal Mines*, Macmillan & Co., 1865. Jevons observes that James Watt's improvement of the steam engine, more economical in coal than Thomas Newcomen's, increased total coal consumption rather than reducing it. → [The Coal Question](https://en.wikipedia.org/wiki/The_Coal_Question)
- On the limits of the paradox: the existence of the rebound effect is broadly agreed, its magnitude much less so. See Antoine Missemer, *Les Économistes et la fin des énergies fossiles (1865-1931)*, Classiques Garnier, 2017 (in French).

### Frameworks drawn on

- **Murat Erder, Pierre Pureur, Eoin Woods**, *Continuous Architecture in Practice* (Addison-Wesley, 2021). Architectural decisions, quality attributes, technical debt and feedback loops — the four essential activities of the framework. → [continuousarchitecture.com](https://continuousarchitecture.com/continuous-architecture-principles/)

### My related writing

- Article 1/4: *Everyone optimises, no one arbitrates* → [/en/articles/2026-09-04-chacun-optimise-personne-arbitre/](/en/articles/2026-09-04-chacun-optimise-personne-arbitre/)
- Article 2/4: *Technical debt is carbon debt* → [/en/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/](/en/articles/2026-09-11-la-dette-technique-est-une-dette-carbone/)
- *Before deploying AI, have you mapped your decisions?* (June 2026, in French) → [/articles/2026-06-05-cartographier-decisions-avant-ia/](/articles/2026-06-05-cartographier-decisions-avant-ia/)
- *Nous venons du chaos, l'IA de la logique* (2025, in French) → [The book](https://amzn.eu/d/07jFAfN9)
- Report: *Continuous Architecture facing the unpredictable (2026, in French)* → [/dossiers/architecture-continue-polycrise-2026.html](/dossiers/architecture-continue-polycrise-2026.html)

---

*Your reactions, disagreements and additions are welcome — and on this subject, your AI use-case arbitration grids especially, whether or not they include an environmental criterion. Write to me at [laurence.poussard63@gmail.com](mailto:laurence.poussard63@gmail.com).*

#GreenIT #AI #EnterpriseArchitecture #AIGovernance #ContinuousArchitecture #ReboundEffect
