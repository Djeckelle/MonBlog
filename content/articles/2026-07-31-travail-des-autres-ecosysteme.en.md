---
title: "When the Unknown Pushes Us to Do Other People's Work"
date: 2026-07-31
description: "Faced with an organizational blind spot, everyone tends to fill it themselves. This seemingly harmless reflex has a measurable cost — and a precise cause: not knowing your own ecosystem."
tags: ["OrganisationDuTravail", "Leadership", "TeamTopologies", "Gouvernance", "RolesEtResponsabilites", "Productivite"]
draft: false
categories: ["Organisation"]

cover:
    image: "/images/articles/Unknown-Pushes-Us-toDo-Other.jpg"
    alt: "When the Unknown Pushes Us to Do Other People's Work"
    caption: "When the architect is but a shadow"
    relative: false
    hidden: false
---
*Faced with an organizational blind spot, everyone tends to fill it themselves — and that reflex comes with a measurable price.*

**In short**
- Role ambiguity is, per the research, the costliest workplace stressor there is
- Escalating a need for clarity is healthy; bypassing someone else's role to decide in their place isn't
- Changing roles is legitimate — quietly exercising one you never took on isn't

{{< imprimer >}}

## The Perception Trap

# When the Unknown Pushes Us to Do Other People's Work

There's a behavior found in almost every company, regardless of size or industry.

**Faced with a blind spot, we tend to fill it ourselves.**

We assume a topic belongs to no one. We assume a decision was never made. We assume a process doesn't exist. So we build our own solution.

The intention is usually excellent. The outcome, much less so — and that's not just an impression. It's a documented phenomenon, with a cost that can be measured.

## The perception trap

Employees very rarely set out to encroach on someone else's work. Most of the time, they simply don't know their own ecosystem.

They don't know who decides, who's accountable, what principles are already in place, where to find the information, or even that someone is already working on the topic. From there, everyone builds their own mental map of the organization. And since every mental map is incomplete, everyone ends up rebuilding a piece of something that already exists.

This mechanism has a name in organizational research: *role ambiguity* — uncertainty about what's expected of you, about the boundaries of your responsibility, about which decisions are actually yours to make. It's not a minor HR footnote. A 2026 meta-analysis published in the *Journal of Vocational Behavior*, covering 515 studies and nearly 800,000 workers across sixty years of data, identifies ***role ambiguity as the single most damaging workplace stressor*** of all those studied — ahead of workload and role conflict, and across every dimension measured: stress, performance, burnout, intent to quit (Sawhney et al., 2026).

This isn't a peripheral problem. According to this research, it's the primary one.

## The company pays for the same thing more than once

When several teams independently respond to the same need, the result isn't an addition of value. It's an addition of cost.

The same thinking gets done more than once. The same rule gets defined more than once. The same control gets built more than once. The same documentation gets rewritten more than once. In the end, the company funds several people to produce a result that could have been achieved once — and these parallel outputs gradually diverge, forcing teams to spend more time resolving inconsistencies than creating value.

The figure isn't anecdotal. Some studies on the cost of role ambiguity estimate that affected employees lose between 4 and 7 hours per week — roughly 10 to 17% of their working time — to clarification, duplicated effort, and resolving ownership conflicts. At organizational scale, that's the equivalent of funding a full day of work every week to produce nothing but confusion.

The phenomenon also has a more visible side: collaborative overload. Rob Cross's research at Babson College, conducted over two decades and published in the *Harvard Business Review*, shows that time spent on collaborative activities — meetings, email, colleague requests — has risen by at least 50% over the period, to the point where many managers now spend **80% or more of their week** responding to others rather than producing their own work. A significant share of that collaboration isn't coordinating distinct expertise — it's compensating, in the absence of anything better, for a lack of clarity about who should already own the topic.

## The paradox

This phenomenon has a particularly interesting side effect.

***By trying to do everyone else's work, everyone ends up doing less of their own.***

The developer becomes an architect. The architect becomes an operator. The operator becomes an urban planner. The project manager becomes a governance lead. The product owner becomes a security officer.

Everyone acts with the best of intentions, but no one fully exercises the expertise they were hired for. The organization looks very busy. It is. But a significant share of that energy goes into reproducing work already done elsewhere — instead of advancing the work only that person can do.

## Architects and operations: a frequent example

The dialogue between architecture teams and operations teams illustrates this situation perfectly.

Architects define a frame: technical principles, standards, models, conventions, trajectories. Operations teams, meanwhile, have to build, deploy, and run things. When that frame is poorly known, hard to access, or insufficiently explained, a temptation appears: operations redefine their own standards — sometimes because they think none exist, sometimes because they don't know where to find them, sometimes because they consider them a poor fit for their need.

The reverse also happens: architects sometimes try to control decisions that belong to day-to-day operations. In both cases, ***the problem is rarely a matter of competence. It's above all a lack of understanding of respective responsibilities*** — exactly what Team Topologies describes through the lens of cognitive load: when team boundaries aren't clear, each team absorbs, by default, a load that isn't theirs to carry, at the expense of what it was actually formed to do.

## A concrete case: BCM and Business Process Owners

A recent example illustrates this mechanism with unusual clarity, because the chain of legitimacy here is particularly well-defined — four links, each with a precise role.

GPOs (*Global Process Owners*) define the business process. The business then decides whether that process requires a Business Continuity Management (BCM) plan — a criticality judgment that belongs neither to architects nor to operations. Architects then translate these elements into the solution architecture, so that operations can build and deliver what's expected.

Four links, four distinct legitimacies. The business process belongs to the GPO. The continuity need belongs to the business. The translation into architecture belongs to the architect. The build belongs to operations.

The risk appears when operations, chasing speed or lacking visibility into this framing, go define things directly with the GPOs and feed that information straight into their own processes and tools. On the surface, they save time. In reality, they bypass the architectural translation link, and take on a legitimacy for defining business process that isn't theirs to claim.

This isn't just duplicated work. It's a subtler risk: ***the divergence of truth.*** If operations rebuild their own reading of the business process inside their tools, without going back through the architecture that holds the coherence view, two versions of the same process start existing in parallel — the one the GPO maintains at group level, and the one operations froze into their tooling at a given point in time. The day the GPO evolves the process, nothing guarantees the operational version gets updated in mirror. This is no longer just lost efficiency. It's the source of truth itself that fragments.

A nuance is worth adding here, to avoid swinging to the opposite excess. The problem isn't direct conversation between operations and GPOs — talking to the source to understand the intent behind a rule is often healthy, even desirable. The problem is **writing directly** into business repositories without going back through architecture. Consulting directly: yes. Deciding and documenting directly, bypassing the architectural translation: no.

***Escalating a need for clarification is a healthy signal*** — it's the normal function of the crossing between the ground and the framing. Going to define things yourself, with the source, what should have been translated by a party mandated for exactly that — that's rebuilding part of the value chain, with all the divergence it eventually produces.

## Before acting, understand the ecosystem

In a complex organization, the first question should never be:

> "How am I going to solve this problem?"

It should be:

> "Who's already handling this?"

This simple question changes everything. It surfaces decisions already made, existing constraints, accountable people, available repositories, and dependencies with other teams. Only after this step can anyone determine their actual role in the value chain.

Gallup, in its global workplace engagement survey, asks a question that has become central to management literature — *"I know what is expected of me at work"* — and its 2025 edition points out that unclear expectations remain one of the top drivers of disengagement, contributing to an estimated global productivity loss of several hundred billion dollars a year. The mirror image of that question — *knowing what's expected of you* — is knowing what's already owned by someone else. That second half rarely gets discussed. It's just as costly to ignore.

## A role isn't a wall

Defining your scope doesn't mean working in a silo. It means understanding where your responsibility starts... and where it ends.

Organizational boundaries aren't there to prevent collaboration. They exist to avoid duplication, clarify accountability, and let each expertise produce maximum value. ***Collaborating isn't about doing someone else's work. Collaborating is about correctly articulating different expertise.***

## Changing roles, yes — bypassing them, no

This piece isn't arguing that everyone should stay locked in their lane for their entire career.

If someone in operations wants to move into architecture, let them become an architect — with the training, the role, the duties, and the accountability that comes with it. If an architect wants to go back into operations, the same logic applies. If someone wants to move to the business side, nothing stands in the way — provided that, here too, they fully take on the role and the accountability, not just the decisions they find interesting.

What this piece is criticizing isn't the ambition to change function. It's the quiet exercise of a function one never actually took on. ***Doing architecture without carrying its role, its training, and its accountability isn't versatility — it's a workaround.*** The question is never "who's allowed to do what," in some restrictive sense. The question is that everyone respects their own role and everyone else's, for as long as they hold it — and that changing roles means actually changing roles, not informally extending the previous one.

## The maturity of an organization

A mature organization isn't one where everyone can do everything. It's one where everyone knows what they're supposed to produce, what others produce, and who to turn to when a question falls outside their scope.

This knowledge of the ecosystem is probably one of the most underrated skills in the corporate world — and, based on the available data on the cost of role ambiguity and collaborative overload, one of the cheapest to fix relative to what it returns.

Because before solving a problem, you first have to understand where it sits. And above all... understand that it may already belong to someone else.

---

## Sources and Inspiration

- Sawhney, G. et al. (2026) — sixty-year meta-analysis of role stressor research, *Journal of Vocational Behavior* (515 studies, roughly 800,000 workers)
- Cross, R., Rebele, R., Grant, A. — *[Collaborative Overload](https://hbr.org/2016/01/collaborative-overload)*, Harvard Business Review, and Rob Cross's subsequent work on collaborative overload
- Gallup — *[State of the Global Workplace](https://www.gallup.com/workplace/349484/state-of-the-global-workplace.aspx)*, annual survey on engagement and clarity of workplace expectations
- Team Topologies (Skelton & Pais) — the cognitive load concept applied to team boundaries
