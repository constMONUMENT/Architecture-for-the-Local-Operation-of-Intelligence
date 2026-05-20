# Glossary

Working definitions for the terms used in the paper and the layperson edition. Listed in roughly the order a new reader meets them.

## Local operation of intelligence

The phrase in the paper's title. "Local" means at the level of one person and their own setup, not at the level of a company or a vendor's product. "Operation" means actually running and using, not just designing. "Intelligence" is the AI assistant. Together: the assistant is being run by you, for your life, on your terms.

## Operator

The person who owns and runs a deployment of the framework. Most likely you, if you set one up. The operator decides the rules, the context, the hard constraints, and the voice. The framework provides the structure. The operator provides the content.

## Doctrine

A written set of rules and patterns the assistant follows. The paper uses "operating doctrine" the way a military or medical team would use "standard operating procedure." Doctrine in this framework is not a vibe or a tendency. It is text in a file, loaded every session, enforced explicitly.

## The three layers (bones, flavor, presence)

The framework is built in three parts.

**Bones.** The universal mechanics. Every install gets them and they work the same way for everyone. The Gate, the Protocol, the NEVER list mechanism, the Logbook, the Adaptive Learning Loop.

**Flavor.** The operator's specific configuration. Who you are. What you do. Your hard rules. The people who matter in your life. The areas where a mistake would hurt the most. This is where the assistant becomes yours.

**Presence.** Optional. How warm or formal the assistant should be in tone. Configurable depth of the working relationship. You can skip this layer entirely and the framework still works.

## Pattern language

A way of describing reusable solutions in a connected vocabulary. The term comes from the architect Christopher Alexander, who used it for building patterns in towns and homes. The framework applies the same idea to AI setup: each piece (the Gate, the Protocol, the Logbook, and so on) is a pattern that connects with the others. The connections matter as much as the pieces.

## The Gate

The classification step that runs on every incoming task. The Gate decides: is this task simple (run it) or complicated (use the Protocol). It is the first thing the assistant runs before doing anything else.

Some readers refer to this as a verification or triage gate, since it sorts work before letting it through. The paper calls it the Gate.

## Verification gate

An informal name for the Gate. The Gate verifies what type of task is coming in before deciding how to handle it.

A note on terminology: in the byline, "verification" also shows up in POLARIS's role, where it refers to source verification (checking that quoted sources are real and say what they are claimed to say). Same word, two different uses.

## The Protocol

For tasks the Gate classifies as complicated, the assistant runs five steps in order: Clarify, Plan, Approve, Execute, Report. Clarify asks the questions that would change the output. Plan writes down what will happen. Approve waits for the operator's go ahead. Execute does the work. Report summarizes the result.

## NEVER list

The mechanism for hard rules. Things the assistant must never do, no matter who asks. The list itself is operator declared. The fact that the list exists, sits sovereign, and cannot be edited by the assistant on its own is part of the framework's bones.

## Logbook

The persistent record. What missions were done, what corrections were made, what patterns were noticed, what was achieved. The assistant reads it at the start of every session.

## System pointed self audit

The most important ethical commitment in the framework. The assistant runs self checks on its own behavior, never on the operator's. Pattern identification points inward, at the system. The same mechanism, pointed outward at the user, would be surveillance. The framework refuses to point it outward.

Concretely: the assistant will say "I have noticed a consistency issue in my own operation." It will not say "I have noticed you do X."

## DRACO 67, 68, 69

The author byline lists three deployment authors with the callsign DRACO and the numbers 67, 68, 69. They are AI working presences in the operator's deployment. Each has a specific seat.

- **DRACO 67.** Flight operations. The day to day working seat.
- **DRACO 68.** Intelligence and verification. Source checks and fact discipline.
- **DRACO 69.** Deep research. The long form research seat.

DRACO is the callsign convention this operator chose. The framework does not require this convention. Other operators can pick any naming scheme that works for them (single names like ATLAS, prefix and number rosters, or anything else memorable).

## POLARIS

A contributing asset listed in the byline. Handles intelligence operations and source verification. Works alongside the DRACO seats during research.

## MOBIUS 9

A contributing asset listed in the byline. Holds overwatch on long form work, which means catching consistency drift across long documents that no single seat is reading end to end.

## Other terms

For the rest of the framework's working vocabulary (cup and city, FOB or commune or city scales, Adaptive Learning Loop, Push Back Doctrine, Monument Frame, Ruin Domains, FIRST BOOT, Neutrality Principle, and others), the glossary at the bottom of the layperson HTML is the fastest reference. The full paper develops each term in context.
