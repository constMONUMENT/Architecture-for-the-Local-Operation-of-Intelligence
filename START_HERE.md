# Start Here

A five minute read. If you finish this and want more, the last paragraph tells you which file to open next.

## The basic problem

When you talk to an AI assistant today, the conversation has no memory and no rules.

Each session starts from scratch. The assistant does not remember what you said last week. It does not know which of your projects matter, which mistakes would be expensive, which people in your life it should treat carefully. You re-explain everything, every time.

It also has no rules that are really yours. It has the vendor's rules, applied the same way to everyone, and a few thin settings you can adjust. Nothing that actually fits your life.

## The basic idea

Treat AI setup like training an assistant, not like asking a search engine a question.

An assistant who works with you over time needs three kinds of training. The paper calls them the three layers.

1. **Bones.** The mechanics. How they triage incoming tasks. What process they run for the complicated ones. How they record what was done. How they learn from your corrections so the corrections do not vanish the next session.
2. **Flavor.** Who they are working for. What you do. Who matters in your life. What they must never do, no matter who asks. The areas where a mistake would hurt the most.
3. **Presence.** Optional. How warm, formal, or conversational they should be. The texture of the working relationship.

The framework in this repo describes how to set all of that up in a way that travels. You configure it once. It loads itself the same way every session. If you switch AI vendors later, your configuration comes with you.

## A small example

Imagine you are a student in your second year of nursing school.

Without this framework, you open an AI assistant and ask it to help you study for a pharmacology exam. It does. The next day you ask about something else. It has no idea you are in nursing school. You re-explain. You also have to remember, every time, that it sometimes invents drug interactions, so you double check every answer.

With this framework, the assistant already knows you are in nursing school. It knows the exam is Friday. It knows that academic standing is a domain where a mistake would actually hurt you. It knows that on medical content it should never make something up and should always tell you which source it pulled from. Those are not nice features you remembered to ask for. They are written into the configuration and load every time.

You did the work once, when you set things up. After that, the structure does the remembering.

## What this is, and what it is not

This is a framework. A way of setting up AI assistance so the structure carries the work that you would otherwise have to redo by hand, every session.

This is not an app. There is nothing to download and run. You do not need to be a programmer. The paper, plus the Pioneer Kit (the install template), is enough to set yours up in a chat with any modern AI assistant.

This is also not a magic upgrade. The AI still has the limitations of whatever model you are using. What changes is the structure around the AI, which is most of what is missing right now.

## Where to go next

- Worried about misuse, cheating, privacy, or what the AI is allowed to do? Open `FAQ.md`.
- Want the framework in plain language, with more depth than this page? Open `architecture_for_local_operation_of_intelligence_layperson.html` in any browser.
- Want the full academic version? Open the PDF.
- Want to look up a term you saw? Open `GLOSSARY.md`.
- Want to install the framework on your own AI assistant? Read `PIONEER_KIT.md`, after at least the layperson HTML.

You do not have to read it all. Most people will not. Pick the door that matches what you came for.
