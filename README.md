# Case-to-Principle Writing Skill

Turn big-book cases into clear arguments, writing angles, and plain-language explanations.

This project is a GitHub-ready Codex skill plus a structured study layer. It is built for users who want to think and write with the help of classic popular books such as:

- `Sapiens`
- `A Brief History of Time`
- `A Short History of Nearly Everything`
- `Thinking, Fast and Slow`
- `Atomic Habits`
- `Guns, Germs, and Steel`
- `Influence`
- `The Black Swan`
- `Principles`
- `Scale`
- `Out of Control`
- `Seven Brief Lessons on Physics`

Its purpose is not to summarize books.

Its purpose is to do this:

> case in a classic book -> underlying principle -> real-world mapping -> stronger writing angle

## What This Skill Does

When a user brings a topic, problem, or writing task, the skill should:

1. Find the most structurally similar case, model, or story from the book set.
2. Explain the principle behind that case.
3. Transfer that principle to the user's real-world context.
4. Turn it into writing material:
   - angle
   - hook
   - structure
   - title ideas
   - memorable lines

## What This Skill Is Not

- Not a book-summary bot
- Not a quote generator
- Not a fake citation machine
- Not a generic philosophy voice
- Not a "force every problem into a famous-book analogy" tool

## Project Structure

```text
case-to-principle-writing-skill/
├── README.md
├── docs/
│   ├── examples.md
│   ├── extension-guide.md
│   ├── knowledge-base-structure.md
│   ├── naming.md
│   ├── skill-positioning.md
│   └── test-cases.md
└── skill/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    └── references/
        ├── books-learning-cards.md
        ├── case-selection-rules.md
        ├── output-template.md
        └── safety-rules.md
```

## Why The Name

Several candidate names were considered:

1. `brief-history-thinking-skill`
2. `big-book-analogy-skill`
3. `classic-case-transfer-skill`
4. `analogy-to-argument-skill`
5. `case-to-principle-writing-skill`

Chosen name: `case-to-principle-writing-skill`

Reason:

- It clearly describes the core motion.
- It is GitHub-searchable.
- It is specific enough to stand out, but broad enough to expand.
- It avoids sounding like a simple reading-note project.

## Design Principles

- Start from cases, not slogans.
- Explain mechanism, not only morals.
- Transfer carefully, not mechanically.
- Prefer clear summaries over long quotations.
- State uncertainty when source text is not directly verified.
- Keep copyright compliance explicit.

## Core Workflow

The skill uses a three-step reasoning pattern:

1. `Source the case`
2. `Extract the principle`
3. `Apply it to reality and writing`

The default output format is documented in [skill/references/output-template.md](skill/references/output-template.md).

## Source Integrity

This project is designed to be honest about source boundaries.

It should not claim:

- exact page numbers unless verified from accessible text
- verbatim quotations unless the text is actually available and legally usable
- that it has "fully read" copyrighted books when it only relies on widely known public knowledge

Instead, it stores:

- structured learning cards
- reusable cases
- transferable principles
- scenario mappings
- writing-entry conversions

## Skill Trigger Examples

- "Use a big-book case to explain why users stay locked into platforms."
- "Find me a Sapiens-style case for explaining personal branding."
- "Turn this business topic into a case -> principle -> writing angle analysis."
- "Use Thinking, Fast and Slow to explain why people buy expensive courses."

## Best Use Cases

- topic ideation
- article planning
- video scripts
- long-form threads
- business analysis
- product explanation
- social phenomenon breakdown
- personal-growth writing
- simplifying hard concepts
- opinion building

## Limits

This skill is weak when:

- the user wants precise textual scholarship
- the best answer should come from current news or live data instead of books
- there is no meaningful structural analogy
- the analogy would mislead more than it clarifies

## Next Steps

- Read [docs/skill-positioning.md](docs/skill-positioning.md)
- Read [docs/knowledge-base-structure.md](docs/knowledge-base-structure.md)
- Read [docs/examples.md](docs/examples.md)
- Read [skill/SKILL.md](skill/SKILL.md)
