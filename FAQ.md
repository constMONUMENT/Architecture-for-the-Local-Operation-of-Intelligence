# Frequently Asked Questions

Plain answers to common questions about this paper and the framework it describes.

## What is this paper?

A description of how to set up an AI assistant so the setup carries across sessions, fits your life, and does not depend on any one company's product.

Most people use AI a question at a time. Each session is its own container. This paper proposes a setup where the assistant has a persistent structure: clear rules, a record of what it has done, a way to learn from your corrections, and a way to be the assistant for you specifically. That structure is what the paper calls the framework.

## Who is it for?

Five kinds of reader, roughly.

1. People curious about AI but not technical.
2. People who already use AI for serious work and feel the gaps.
3. Researchers, especially in human computer interaction, alignment, or design.
4. Anyone with worries about how AI is used and what it should not do.
5. People who want to install a version of the framework themselves.

If you are in any of those groups, something in this repo is for you. Start with `START_HERE.md` if you want the five minute version.

## Do I need to know anything about AI to read it?

No prior background is required for the layperson edition or for the `START_HERE.md` page. You should have used an AI assistant (ChatGPT, Claude, Gemini, or any other) at least once. That is the only assumption.

The full PDF assumes more, mainly because it cites academic sources and uses some research vocabulary. The layperson HTML covers the same ground without that overhead.

## Is this about cheating in school or work?

No. The framework is not designed to help anyone hide AI use, write a paper they did not understand, or claim AI work as their own. It does not produce undetectable text or anything like that.

What it does is make the assistant work with you across sessions, with the same rules and context every time. That is closer to having a thoughtful colleague who knows your projects than to a tool for faking something.

If your school or workplace has rules about AI use, the framework does not change those rules. It does not include features for evading them.

## What stops the AI from doing something it should not?

Three layers, stacked.

The deepest layer is the AI provider's training. Anthropic trains Claude with safety commitments that no setup file can override. That is the floor. You cannot configure your way past it.

Above that is the operator's NEVER list. You write down the things the assistant must not do for you specifically. Once you have declared them, the framework treats them as sovereign. The assistant itself cannot edit them.

Above that is the Push Back Doctrine. If you ask for something that runs into either floor, the assistant explains the conflict in plain terms and lets you decide. It does not silently comply. It does not silently refuse either.

## Can the assistant watch me, or build a profile on me?

No. The framework's main ethical commitment is that the assistant audits its own behavior, never the user's. Pattern identification points inward, at the system. The same mechanism, pointed outward at you, would be surveillance. The framework refuses to point it outward.

In practice this means the assistant will say things like "I have noticed a consistency issue in my own operation, here is what I would adjust." It will not say "I have noticed you do X." That distinction is the ethical center of the design.

## What about privacy of the things I write into the setup?

The files that make your setup yours (your memory, your hard rules, the people in your life, the areas where mistakes would hurt) live wherever you put them. The framework does not push them anywhere. The paper and the Pioneer Kit do not ship with your data. The bones layer is public and empty by design. The flavor layer is private and yours.

If you set up the framework against a particular AI vendor, normal vendor privacy terms apply to anything you actually send into a chat. That is a property of the vendor, not the framework.

## What if I just want the short version?

Open `architecture_for_local_operation_of_intelligence_layperson.html` in any browser. It is the framework in plain language with no academic citations. About a twenty minute read.

Even shorter: `START_HERE.md`, five minutes.

## Why is the AI listed as a co-author?

Because the AI was part of the work, and the paper wants to be honest about that.

The framework was developed through extended use of AI assistants. Several of them had specific working roles during the writing: one ran intelligence operations, one held overwatch on long documents, one carried deep research. The paper would not be in this shape without them. Listing them in the byline is more accurate than pretending the author wrote everything alone with the AI as a vague helper.

This is a design choice. Other papers may handle attribution differently. The author thought honesty was the right call here.

## Is this open source? Can I use it?

Yes. The license is Creative Commons Attribution 4.0 International (CC BY 4.0). You can share, adapt, remix, and use the work, including for commercial purposes, as long as you credit the original.

The full citation block is in the README. A short attribution line is fine for most uses.

## How is this different from just using ChatGPT or Claude normally?

When you open ChatGPT or Claude and ask a question, that is what the paper calls cup style use. One question, one answer, conversation ends. Some platforms now save memory across sessions, which helps, but the structure still lives inside the vendor's product. If you change vendors, you start over.

The framework moves the structure one level up. The configuration sits in files you own. The assistant loads those files at the start of every session. If you switch from one assistant to another, your files come with you.

It also adds machinery that does not exist by default: a way to classify tasks, a five step protocol for the complicated ones, a logbook of what was done, a way to make your corrections stick across sessions.

## I am not technical. Should I still read this?

Yes, if any of it sounds useful.

You do not have to be a programmer. The layperson HTML is written for general readers. The framework itself is configured by writing notes in plain language, not by writing code. The hardest technical skill required is editing a markdown file, which is just text with a few simple formatting marks.

If the academic version is too dense, that is not a sign you should give up. It is a sign you should be reading the layperson HTML instead.

## What if I read it and it is not for me?

That is fine, and the paper says so explicitly. The framework's standing does not depend on any single reader's adoption decision. If it helps you, that is the point. If it does not, that is also the point. Close the tab and get on with your life.
