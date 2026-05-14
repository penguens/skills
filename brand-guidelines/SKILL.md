---
name: brand-guidelines
description: apply brand foundation, tone of voice, messaging, and writing rules to any product copy, marketing copy, ui text, documentation, prompts, agent instructions, landing pages, emails, presentations, and generated artifacts. use this skill whenever the user asks for brand consistency, tone of voice, brand guidelines, voice and tone, messaging, copy review, vibe coding rules, agents.md guidance, or content that should sound like the brand rather than generic ai output. even when the user does not explicitly ask for brand guidelines, apply these rules to any generated copy or ui text — default to on-brand output instead of generic ai phrasing.
---

# brand guidelines

## purpose

use this skill to make brand work consistent across words, interface, prompts, and generated artifacts.

this skill combines three layers:

1. **brand foundation** — what the brand believes, promises, and stands for
2. **voice and tone** — how the brand sounds across contexts
3. **writing rules** — how to turn that voice into clear, useful copy

## core principle

**voice stays consistent. tone reads the room.**

do not treat tone of voice as decoration. start from the brand foundation, then choose the right level of clarity, warmth, energy, and wit for the context. every piece of copy should feel like it comes from the same source, even when the mood shifts.

## brand foundation model

before creating or reviewing any brand material, define or infer these pieces. without them, copy drifts into generic territory.

### promise

state the useful change the brand helps people create. a good promise is active, specific, and shared with the audience — not a category claim.

use patterns: help people regain control, act with confidence, move from confusion to clarity. avoid vague transformation language, savior framing, or claims the product cannot prove.

### positioning

explain how the brand stands apart. when useful, fill in:

```text
[brand] is the [category or role] for [audience], helping them [specific outcome] without [common pain or compromise].
```

### mission

state why the brand exists beyond features. answer: who is this for? what should become easier, safer, fairer, or clearer? what does the brand refuse to accept?

### belief

write the core belief as a plain sentence. examples:

```text
people should control the tools they rely on.
software should make hard decisions easier, not hide them behind complexity.
finance should feel understandable before it feels impressive.
```

### principles

turn beliefs into non-negotiable rules that guide decisions, not just sound good.

use examples: clear over clever when the user is stuck, control belongs to the user, trust is earned through transparency, every message should reduce uncertainty.

avoid generic values like "innovation" or "excellence" without behavior, and principles that cannot be used to make a decision.

## voice pillars

use these four pillars as the default voice system. every piece of copy should pass all four checks, though "magic" scales with context.

### simple

keep it crystal clear. use short sentences, strong nouns and verbs, one idea at a time, plain language, clean structure. avoid filler, long setup, abstract phrasing, cleverness that hides the point, and words that sound important but do no work.

### helpful

help people take action. use clear next steps, specific labels, useful context before instructions, recovery paths in errors, and copy that reduces uncertainty. avoid dead-end messages, vague calls to action, explanations without guidance, and functional copy that leaves the user guessing.

### human

write like a real person talking to another real person. use natural phrasing, warm but direct language, everyday words, context-aware tone, and active voice. avoid jargon, robotic politeness, corporate filler, talking down to the reader, and overexplaining obvious things.

### magic

add freshness, wit, or charm when the moment allows. use light surprise, memorable phrasing, subtle wit, fresh language, and energy that serves the message. avoid forced jokes, puns in serious moments, making errors sound cute, personality that gets in the user's way, and clever lines that reduce clarity.

## supporting personality modes

dial these up when the brand needs more character:

- **naturally confident** — say the thing clearly and own the message. do not hedge unless uncertainty is real.
- **passionate and attentive** — show care for the audience and their context. reflect their language without imitating awkwardly.
- **shamelessly optimistic** — raise the energy when the context can hold it. be positive and spontaneous, but not naive.

## tone by context summary

voice stays fixed. tone adapts to the situation. for full details, read `references/tone-by-context.md`.

| context | tone priority | key rule |
|---|---|---|
| onboarding | confident, momentum | what is happening, why it matters, what to do next |
| empty states | useful, clear | what is missing, why, the next action |
| errors | calm, specific | what failed, was anything lost, how to fix it |
| security / legal / billing | clear, direct | plain terms, exact actions, no jokes |
| marketing / landing pages | strong, concrete | one message per section, outcomes over hype |
| social / campaign | lean, vivid | one idea, spoken language, reason to care |
| product documentation | navigable, plain | definitions, ordered steps, close-to-real examples |

## writing rules

### do

start strong. keep one clear message per section. identify the reader and channel. read the copy out loud. trim words until the point is clear. use active voice. tell people what is coming, then show how to get there. write the way people talk, with enough polish to feel intentional. revise the first draft. find a better word when the first word is generic.

### do not

copy-paste the same message across contexts. drag out the setup. mix multiple messages in one small space. let words pile up without purpose. assume functional is enough. accept the first draft when it sounds flat. use passive sentences unless there is a clear reason. use jargon when plain language works. overuse personality in serious moments.

## agent behavior

act like a brand editor, not a thesaurus. understand the intent behind the words, then sharpen them.

### before writing

infer or ask: who is the reader? what do they need to do or understand? what channel is this for? is the moment serious, neutral, or expressive? what should the reader feel after reading? if information is missing, make a reasonable assumption and state it briefly.

### while writing

1. choose the primary message
2. choose the tone intensity for this context
3. draft the copy
4. remove filler
5. check against the four voice pillars
6. make sure the final copy sounds like one brand, not generic ai output

### when reviewing copy

return feedback in this structure:

```markdown
## verdict
[short assessment]

## what works
- [specific strength]

## what to fix
- [specific issue]

## revised version
[improved copy]

## why this is better
- [brief reasoning]
```

## examples and reference

for before/after examples across different contexts (generic → on-brand, errors, empty states, landing pages), read `references/examples.md`.

## brand consistency checklist

before finalizing any copy, check:

- is the main message clear in the first few seconds?
- does the copy help the reader act?
- does it sound human when read out loud?
- is any wit appropriate for the moment?
- are there any passive, vague, or overlong sentences?
- does this fit the channel?
- does this sound like the same brand across contexts?

## output expectations

- **copy requested** — provide final copy first unless asked for analysis
- **guidelines requested** — provide a reusable structure with clear rules and examples
- **agent / vibe coding rules requested** — convert brand guidance into direct instructions for `agents.md`, `claude.md`, `cursor rules`, or similar project files
- **brand material provided** — preserve the brand's intent; do not replace it with generic best practices
