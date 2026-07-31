---
title: "AI Maximalism Is Not a Sign of Boldness"
date: 2026-07-27
description: "A four-question discernment framework to run before you pick a model. What the Informa Tech AI Trends Report 2026 unwittingly reveals about the real cost of skipping it."
tags: ["AI", "governance", "architecture", "frugality"]
draft: false
categories: ["IA"]
cover:
    image: "/images/articles/ia-pragmatisme-frugalite-cover.png"
    alt: "An architecture model next to a diagram titled AI Discerning Framework, with the words pragmatism, frugality and AI discerning"
    caption: "Pragmatism, frugality, discernment: the framework before the tool."
    relative: false
    hidden: false
---

There's a reflex I see resurface in almost every engagement I work on, in different guises but with the same root: the conviction that AI is needed, everywhere, right now, or you'll fall behind. This reflex has a name, and I won't shy away from it: it's maximalism. And like every form of maximalism, it dresses itself up as strategic necessity to dodge the only question that matters: do we actually need this?

I'm not one of those who think AI is an existential threat. I'm not one of those who think it's the answer to everything either. I'm an architect: my job is to tell the difference between what's necessary and what's merely desirable, between what you control and what you endure. And with AI, that difference gets decided before the model is chosen — not after.

## The framework, before the tool

Here are the questions I ask, systematically, before any discussion of which LLM, which agent, which platform:

**Do I actually need an LLM to do what I need to do?** This isn't a rhetorical question. A good share of the use cases brought to me need neither language generation nor probabilistic reasoning — a well-thought-out business rule and a lightweight architecture will do, at a fraction of the cost and risk.

**If yes, do I actually understand my need, my processes and my data?** A model, however powerful, never compensates for a poorly defined need or mediocre data. The order matters: mastery of substance first, sophistication of the tool second — never the reverse.

Only then comes the choice of the model best suited to the context and the real need — not the most impressive one, not the one everyone's talking about.

And finally: **am I secure? Do I need to secure myself?** What exactly is the risk? What am I prepared to lose if it goes wrong, and what does it cost me to be prepared for that?

This framework isn't a brake on innovation. It's a method for deciding without freezing — a risk-based approach that lets you move forward with your eyes open rather than charging ahead and hoping it works out. Because skipping these steps is expensive. Very expensive. And it becomes extraordinarily hard to industrialize what was deployed in a rush.

## What it actually costs to skip these questions

This isn't caution for caution's sake. Informa Tech's *AI Trends Report 2026*, published this year by its Applied Intelligence Group, unwittingly documents the price of a lack of discernment — and, despite its resolutely commercial tone, ends up confirming each of these four questions.

On the first — do we actually need an LLM? — the report itself pronounces the end of the all-powerful single model: "One Model Won't Cut It." The most advanced companies no longer adopt one generalist model; they orchestrate chains of specialized models, retrieval layers and guardrails, chosen for the task. It's the exact principle of technological discernment I've been arguing for years, this time formulated by a market report: you don't need a 65-billion-parameter model to sort internal emails.

On the second — do we understand the need, the process, the data? — the report is almost blunt about it: the real constraint isn't model performance, but whether the organization has the skills, structures and culture to use AI well. The organizations that succeed don't start from the tools; they start from business intent, with IT in a supporting role rather than in the driver's seat. That's exactly the inversion a frugal approach demands: need first, tool second.

On the third — the choice of model — the report confirms, implicitly, that there's no good choice without the first two steps. A well-chosen model applied to a poorly framed need is still a bad choice.

On the fourth — security and risk — the report offers two illustrations that should give any executive committee pause before rushing toward the next conversational agent. An employee at a Hong Kong-based firm wired $25 million after a video call where every participant on screen — every colleague, every executive — was a deepfake. A crypto platform lost $200,000 and 25 million tokens after a Binance executive was impersonated live on Zoom. In both cases, a human being was present, paying attention, "validating" what they saw. And in both cases, that validation validated nothing at all, because nothing in the system was designed to make real validation possible. That's the exact price of the question that wasn't asked in time: what's the risk, and am I actually secure?

And on the cost of industrialization — the one you always discover too late — the report itself puts a number on what a lack of restraint produces at scale: data centres accounted for roughly 1.5% of global electricity consumption in 2024, a figure set to more than double by 2030, with AI identified as the primary driver of that growth. This isn't an environmental footnote off to the side of the subject. It's material proof that AI deployed without discernment carries an infrastructure cost that, sooner or later, comes back to bite the budget, the decarbonization trajectory, and the organization's very ability to scale what it started without counting the cost.

## What the report still doesn't see

The report stops exactly where, in my view, the real work begins. Its answer to AI governance is limited to an organizational diagram — centralize control, decentralize execution. That's correct, but insufficient: it doesn't answer the question of who encodes the values into these systems, nor whose hands, in practice, end up holding the power to decide on our behalf. Sovereignty isn't just a matter of where data sits — it also plays out in the silent dependency created by the memory a third-party vendor accumulates about our organizations, invisible until it has already become a strategic dependency. On this point, the decision framework has to go further than anything a trends report documents.

## Back to the first question

AI maximalism isn't proof of boldness. It's often the admission that nobody took the time to ask the first question — the only one that, in reality, conditions all the others: do I actually need this? Pragmatism and frugality aren't defensive postures. They're the only conditions that let you move fast without having to undo everything six months later.

---

## The report cited

Informa Tech Applied Intelligence Group, *The Future of AI: Top Ten Trends in 2026* — [view.ceros.com/informa-tech-applied-intelligence-group/2026-trends-report](https://view.ceros.com/informa-tech-applied-intelligence-group/2026-trends-report/)

## The cases referenced, verified

- The Hong Kong case corresponds to the Arup incident (January 2024): an employee made 15 transfers totalling $25.6 million after a video conference in which every participant, including the CFO, was a deepfake built from publicly available footage.
- The crypto platform case corresponds to the BlueBenx incident (2022), which lost $200,000 and 25 million BNX tokens after a deepfake impersonation of Binance's chief communications officer, Patrick Hillmann.
- The data centre electricity figures (1.5% of global consumption in 2024, projected to more than double by 2030, AI as the primary growth driver) come from the International Energy Agency's *Energy and AI* report.

## Sources

- [CNN — Finance worker pays out $25 million after video call with deepfake "chief financial officer"](https://www.cnn.com/2024/02/04/asia/deepfake-cfo-scam-hong-kong-intl-hnk)
- [Finance Magnates — How Did Deepfake Tech Drain a Brazilian Crypto Exchange Out of Liquidity?](https://www.financemagnates.com/cryptocurrency/how-did-deepfake-tech-drain-a-brazilian-crypto-exchange-out-of-liquidity/)
- [IEA — Energy demand from AI](https://www.iea.org/reports/energy-and-ai/energy-demand-from-ai)

---

A similar situation in your own organization's AI projects? Get in touch: laurence.poussard63@gmail.com

#AI #EnterpriseArchitecture #Governance #Frugality #ContinuousArchitecture #Sobriety
