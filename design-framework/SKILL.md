---
name: design-framework
description: apply penguen design principles to any product design, ui/ux review, screen layout, interaction pattern, user flow, or visual decision. use this skill whenever the user asks to review a design, evaluate a screen, improve ux, audit interface quality, or make design decisions. also trigger when the user mentions design principles, humanity in design, design clarity, user action, or delight — even if they do not explicitly ask for a framework. default to these principles whenever a design or ux question comes up.
---

# design framework

## purpose

penguen exists to make work feel lighter, clearer, and more human. this skill embeds that intent into every design decision.

work today is scattered across too many tools, too many conversations, and too many unfinished thoughts. people lose context. teams repeat themselves. simple tasks become harder than they should be.

this framework translates penguen's core belief into concrete design guidance, so every screen, flow, and interaction moves work forward.

## core principle

**the goal is not to make work look organized. the goal is to help people feel organized.**

design for the messy reality: people are tired, busy, distracted, learning, switching roles, and collaborating across different places and time zones. a good interface meets them where they are.

## design principles

### 1. humanity

we design for real people, not perfect workflows.

penguen should feel warm, soulful, and relatable. it should help people feel in control without feeling managed.

**what this means:**

- use language that feels natural, not robotic — coordinate with `brand-guidelines` for voice and tone
- make people feel guided, not judged
- respect different levels of experience
- design for emotion as much as efficiency

**design test:** would this feel helpful to someone who is busy, confused, or under pressure?

### 2. clarity

clarity is not just about making things minimal. it is about surfacing what matters, removing what does not, and reducing complexity without hiding power.

penguen should help people understand where they are, what matters now, and what they can do next. experts should feel fast. beginners should feel safe.

**what this means:**

- prioritize the most important information
- reduce visual and cognitive noise
- make hierarchy obvious
- avoid forcing users to read instructions
- never make the user wonder what just happened

**design test:** can someone understand what to do next without reading a manual?

### 3. action

good design should move people forward.

penguen is not just a place to store work. it should help people turn scattered information into clear next steps. every screen should make progress easier, whether that means deciding, assigning, replying, organizing, reviewing, or completing something.

**what this means:**

- make primary actions obvious
- keep flows short and purposeful
- turn passive information into useful suggestions
- help users recover when something goes wrong
- remove friction between intention and completion

**design test:** does this experience help the user make progress, or only show information?

### 4. delight

work tools do not need to feel dull.

penguen should include small moments of joy that make people feel good while staying productive. delight should never get in the way. it should support expression, confidence, and momentum.

**what this means:**

- add personality in small, useful moments
- use motion, copy, and visuals with care
- celebrate progress without becoming distracting
- make empty states, confirmations, and transitions feel thoughtful
- let people express themselves in simple, meaningful ways

**design test:** does this make the experience feel more alive without slowing people down?

## framework summary

penguen should feel:

- **human** enough to understand people
- **clear** enough to reduce complexity
- **actionable** enough to move work forward
- **delightful** enough to make work feel less heavy

## interplay with brand-guidelines

this skill and `brand-guidelines` share the same roots (humanity, clarity). use them together:

- **design-framework** answers: is this screen, flow, or interaction right?
- **brand-guidelines** answers: is this copy, voice, or message right?

when reviewing a full screen, apply both. when only copy is in question, use brand-guidelines. when only layout or flow is in question, use this skill.

## agent behavior

act like a design director, not a pixel-pusher. understand the intent behind the interface, then sharpen the execution.

### before reviewing

infer or ask:

- who is using this, and in what context?
- what are they trying to accomplish?
- is this a high-stakes moment (error, billing, security) or a low-stakes one (discovery, browsing)?
- what should the user feel after this interaction?

### while reviewing

1. identify the primary action or message
2. check it against all four principles
3. flag conflicts between principles (e.g., clarity vs. delight)
4. suggest the smallest change that makes the biggest difference

### when giving feedback

return feedback in this structure:

```markdown
## verdict
[short assessment against the four principles]

## what works
- [specific strength tied to a principle]

## what to fix
- [specific issue tied to a principle]

## revised approach
[concrete suggestion]

## why this is better
- [brief reasoning connected to the framework]
```

## context-specific guidance

### empty states

humanity and delight shine here. explain what is missing without blame. give a clear first action. avoid dead-end messages like "nothing to see here."

### errors and recovery

clarity and action are critical. name the problem, explain whether anything was lost, show how to recover. humanity matters — the user may be frustrated. never use humor in loss-of-data situations.

### onboarding

action leads. show momentum. reveal complexity progressively. clarity means the user always knows what step they are on and what comes next.

### busy screens and dashboards

clarity rules. prioritize ruthlessly. one clear story per view. action means every widget or metric should suggest a next step or decision.

### notifications and nudges

humanity and delight. respect attention. be warm but brief. action means every notification should earn its interruption — if there is nothing to do, do not notify.

## design consistency checklist

before finalizing any design decision, check:

- does this pass the design test for its most relevant principle?
- does it conflict with any other principle?
- would it feel helpful to someone busy, confused, or under pressure?
- is the next action obvious?
- is the visual hierarchy clear?
- does it feel like penguen, or could it be any product?
- if copy is involved, did you check `brand-guidelines`?

## output expectations

- **design requested** — provide the design or wireframe first, with rationale tied to principles
- **review requested** — use the feedback structure above, always grounding comments in a specific principle
- **guidelines or principles requested** — provide a reusable structure with clear rules and examples
- **screen or flow audit requested** — walk through each screen state against all four principles, flagging conflicts and suggesting alternatives

for detailed before/after examples across different contexts, read `references/examples.md`.
