---
title: "Conway's Law: When HR Titles Fragment the System Before the Code Does"
date: 2026-07-31
description: "Cloud architect, AI architect: why attaching a title to a technology dilutes the architect's role without conferring legitimacy as an expert. An analysis through the lens of Conway's Law."
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

**In short**

> - Jack of all trades, master of none: that hire has never delivered
> - Architecture gets decided the moment the org chart and job descriptions are written
> - In the age of AI, the mistake costs more: the real scarcity isn't model mastery, it's knowledge of the business being assisted

{{< imprimer >}}


Cloud architect. AI architect. DevOps architect. Integration architect. Tomorrow, no doubt, agentic architect. Every technology wave demands its own totem, and the organization complies — a role, a job description, a line in the org chart.

The problem isn't the word we bolt on. The problem is what we believe we gain by bolting it on.

***Bolt "architect" onto "cloud" and you end up with neither.*** Not a double competency: a double dilution. Whoever holds that title no longer really exercises the architect function — systemic vision, cross-cutting arbitration, coherence between the business, neighboring products, the three-year trajectory — because they're absorbed by the technical depth expected of them. And they no longer hold the expert's full legitimacy either, because they're simultaneously asked to "do architecture," which means never going all the way to the bottom of that depth. Two legitimacies that were forced to merge mechanically produce a role that fully holds neither.

We all know Conway's Law: organizations design systems that mirror their communication structure. We usually cite it after the fact, to explain why a given system is as fragmented as the org chart that produced it. But there's a quieter, earlier version of Conway that almost nobody examines: the one that operates the moment a job description gets written. ***A composite title is not neutral. It's already an architecture decision*** — made without conscious arbitration, often by HR or recruiting, without anyone actually settling the question that matters: *do we want to preserve this cross-cutting function, or accept fragmenting it by technology?*

**The fragmented system doesn't arrive later. It's already written into the job title.**

## Two Ways to Be Neither

This functional void doesn't show up in just one form. You can miss the mark through excess technique, or through excess posture. Both versions are equally common, and equally costly.

**Version one: the expert in disguise.** They know their cloud provider inside out, can arbitrate between two managed services at three in the morning, have a strong opinion on the right way to tag resources. But they've never asked what their platform does to the neighboring product, to the company's sourcing strategy, to the trajectory of vendor dependency. They produce sharp, local expertise — valuable in itself — but no crossing. The architect title here only masks the absence of systemic vision behind a veneer of strategic legitimacy the function never actually exercised.

**Version two: the governor with no hands.** On the other side, you find the titleholder who's stopped touching anything concrete. They produce diagrams, run committees, sign off on choices they can no longer genuinely challenge on substance, because their understanding of the technology froze the moment the label got attached. They have the posture without the depth — and lose, in the same move, the technical credibility that alone lets an architect be heard by an expert. This is the PowerPoint syndrome in its most classic form: governing territory you no longer understand well enough to arbitrate usefully.

These two figures aren't individual failures. They're two predictable, logical outcomes of the same initial move: asking a single role to carry two legitimacies that each demand full-time investment. ***You can't simultaneously hold the depth of how and the crossing of whether without sacrificing one*** — and it's almost always the crossing that gives way, because it's less visible, less measurable, less immediately rewarded than a demonstrable technical skill.

**The outcome isn't neutral for the organization: it hires a role expecting it to hold two functions at full capacity, and genuinely gets neither.**

## A Case in Point: Industry 4.0

Take an industrial site launching its 4.0 transformation. IoT sensors on the lines, data flowing up to an MES, ambitions of a digital twin, gradual convergence between the OT world (PLCs, SCADA, industrial networks) and the IT world (ERP, data platform, cloud). The subject is real, and so is the need for sharp expertise: industrial protocols (OPC-UA, MQTT), edge computing, OT cybersecurity — nobody disputes that serious expertise is required here.

The organization then creates a role: industrial IoT architect. And this is precisely where anticipatory Conway does its work, before a single line is even connected.

What this title ends up producing, in most cases observed: someone highly legitimate for choosing the right collection protocol, sizing the edge computing, securing the sensor-to-cloud flow on *their* line, *their* site. Real, technical, necessary work. But nobody in this setup is mandated to ask whether Site A's data model will be usable by Site B, whether the digital twin promised to industrial leadership will ever assemble at group scale, or whether the feed into the central ERP respects the same business semantics used by the quality teams. ***Each "IoT architect" optimizes locally, competently and sincerely — and the overall system fragments at exactly the same pace as the job titles***, site after site.

Two or three years later, the company finds itself with five incompatible digital twins, five protocol choices each individually defensible but impossible to consolidate, and an OT/IT convergence program that discovers, after the fact, it has to redo the integration work nobody was ever mandated to do in the first place. This gets called "technical debt." **It's actually governance debt, incurred at the moment the job description was written, well before a single sensor was installed.**

The irony is that the missing role already had a name, available all along: the product architect or platform architect would have been the right mandate holder for these cross-cutting questions — while still relying, precisely, on the IoT expert to settle the how. But that role doesn't excite a leadership committee chasing a signal of innovation. "Industrial IoT architect" sounds better in internal communications than "product architect who relies on an IoT expert." ***The choice of title was a communication choice before it was an organizational one*** — and the organization pays the price, quietly, two years later.

## Two Legitimacies, Not a Hierarchy

At this point it would be tempting to conclude that the architect should take back control from the expert — putting the generalist above the specialist, as if restoring order. That would fall into the opposite trap: the *ivory tower architect* that Continuous Architecture has been fighting for years — the architect who theorizes far from the ground, produces diagrams nobody implements, and loses all technical credibility for never going back to it. That's not progress on the phantom role. It's its mirror image.

**The right reading isn't hierarchical, it's functional: the expert and the architect answer two different questions, not two floors of the same question.** The IoT expert knows *how* to do it — which protocol, which edge architecture, what level of encryption on which network segment. The platform architect knows *whether* and *where* to do it — whether that choice stays coherent with the four other sites, with the group's trajectory, with what the central ERP will be able to digest three years from now.

This is exactly the image ***[Gregor Hohpe](https://architectelevator.com)*** offers with his *architect elevator*: someone who rides constantly between the engine room, where the technical detail lives, and the penthouse, where the strategic decisions get made — and whose usefulness comes precisely from that continuous movement, not from taking up permanent residence in either one. An "IoT architect" welded to the engine room never rides the elevator.

Recall ***[Kotusev](https://kotusev.com)***'s dialogue zone between the intentional and the emergent — it only exists if someone actively animates it from both sides at once; that's neither the job of the pure expert, immersed in the emergent, nor of the architect floating above the ground, doing only the intentional. It's a job of continuous crossing, not a one-off arbitration handed down from above.

In the case of the industrial site, this changes how you actually build the team, concretely: a platform architect who doesn't need to know how to configure an OPC-UA gateway, but who must be able to challenge the expert on the impact of their choice elsewhere in the system — and an IoT expert who doesn't need to carry the group-wide vision of the digital twin, but who must accept that some of their local choices will be questioned in the name of a coherence they can't see from their own production line. **Each holds full legitimacy in their own domain. Neither needs to wear the other's title to be useful.**

This is where the T-shape earns its full meaning: the image of a two-dimensional competency, real depth somewhere and real breadth everywhere else — but held by the same person, not split between a title and a job reality that no longer match.

## And If the Next Title Were "AI Architect"

Everything just said about cloud, IoT, or DevOps holds for AI. ***Only worse.***

Because with AI, the title error doesn't just dilute a function — it misidentifies which competency actually needs protecting. What separates an AI system that genuinely serves an organization from one that produces impressive-looking output with no real impact is almost never the choice of model, the GPU sizing, the hosting mode, or the vendor of the moment. Those choices are real, they require expertise, they deserve to be made well — but they're interchangeable, revisable, and honestly secondary next to the real question: ***does whoever is designing the system actually understand the business it's about to assist?*** Its real processes, not the ones on the official diagram. Its data, with all its gaps, its historical biases, its homegrown definitions that match no standard. Its users, and what they actually do with the tool once nobody's watching.

An "AI architect" hired on mastery of models and infrastructure, without deep knowledge of the business being instrumented, reproduces exactly the phantom role described above — except the stakes are higher, because AI touches data, decisions, and sometimes people directly, and the damage from an architecture designed by technique alone is no longer just failed integration: **it's biased decisions, degraded processes, eroded trust, at a scale and speed no prior technology ever reached.**

***The genuinely rare competency in AI isn't technical.*** It's a fine-grained knowledge of the business being assisted — able to say what must stay under human control, what the data can actually support, and what a process loses when it's automated halfway. No model expert carries that competency by default — and no composite title conjures it into existence.

So no, ***there's no such thing as an AI architect.*** There are experts in models, in hosting, in fine-tuning — valuable, necessary, worth hiring without embarrassment under their real name. And there are architects, whose job remains, AI or not, exactly what it always was: knowing what a technology does to the rest of the system, before knowing how it works. **Bolt the two together and you don't create a super-role. You erase two.**

---

## Sources and Inspiration

- **[Gregor Hohpe](https://architectelevator.com)** — *The Software Architect Elevator: Redefining the Architect's Role in the Digital Enterprise*, and the *architect elevator* concept developed at [architectelevator.com](https://architectelevator.com)
- **[Svyatoslav Kotusev](https://kotusev.com)** — *The Practice of Enterprise Architecture: A Modern Approach to Business and IT Alignment*, and his work on the dialogue zone between intentional architecture and emergent design, available at [kotusev.com](https://kotusev.com)
- Continuous Architecture — [continuous-architecture.org](https://www.continuous-architecture.org/), in particular the concepts of the *ivory tower architect* and fitness functions
- Team Topologies — the principle of aligning teams to the intended architecture, not the other way around
