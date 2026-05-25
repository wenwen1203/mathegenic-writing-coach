# Mathegenic Writing Coach

A QoderWork skill that guides parents, teachers, and learners to use AI as a writing scaffold — not a ghostwriter — based on Mathegenic principles.

> **Mathegenic** means "learning-generative." The educational value of a tool is not measured by the output it produces, but by the new understanding, strategies, reflection, and capabilities it helps students develop.

## What This Skill Does

When a user asks about AI-assisted writing, this skill:

1. **Diagnoses** the user's role (parent / teacher / student), the learner's writing development stage, and the specific goal
2. **Matches** the need to the right output type: prompt cards, printable worksheets, workflow plans, or evaluation tools
3. **Generates** ready-to-use materials that follow the core rule: **AI must not write for the student. AI should ask questions, give feedback, compare options, or check structure.**

## Core Principle: The Two U-Curves

This skill is built on the intersection of two U-shaped curves:

- **Writing Development U-Curve**: Children start as intuitive storytellers, hit a "restructuring dip" around age 11 when they become aware of structure but can't yet organize it well, and eventually develop reflective writing ability.
- **AI Cognitive Offloading U-Curve**: Using no AI = moderate learning depth. Naive offloading (letting AI write everything) = learning crash. Strategic offloading (using AI for feedback, comparison, planning) = amplified thinking.

**The danger**: Students in the restructuring dip who let AI ghostwrite skip the very mental work that would let them use AI successfully later.

**The opportunity**: AI can become a "dialogue partner, scaffold, mirror, and sparring partner" that helps students cross the dip with support.

## File Structure

```
mathegenic-writing-coach/
├── SKILL.md          # Core logic: diagnosis → match → generate
├── reference.md      # Knowledge base: 18 prompts, 6 worksheets, 4 rubrics, textbook cases, talk scripts
├── examples.md       # Three annotated scenarios: parent, teacher, textbook conversion
└── README.md         # This file
```

## Quick Start

### For Parents

Your 11-year-old is staring at a blank page. Instead of saying "let AI write it," try this:

1. Have them **draw a map** of the story world (5 min)
2. Use the **Question-Asker Prompt** (in `reference.md`, Prompt 1.9) with ChatGPT — AI asks one question at a time
3. Write **one section per day** — beginning today, middle tomorrow, end the day after

### For Teachers

Converting a textbook text into an AI-scaffolded writing task:

1. Identify the text's **core writing mechanism** (perspective? route? contrast?)
2. Apply the **8-Scaffold Model** from the textbook case study in `reference.md`
3. Use the **Process Portfolio** approach: students submit 6-8 materials, not just one essay

## The 8-Scaffold Model (Textbook Case Example)

Applied to "A Drop of Water Passes Through Lijiang":

| Scaffold | Function | AI Role |
|----------|----------|---------|
| 1. Text Writing Discovery | Deconstruct how the text works | Question-asker |
| 2. Perspective Generator | Generate 8 non-human narrator options | Option generator |
| 3. Route Design | Plan the spatial/emotional journey | Structure coach |
| 4. Detail Amplifier | Push from "it's beautiful" to sensory specifics | Detail追问器 |
| 5. Language Pattern Lab | Design sentence templates for imitation | Pattern demonstrator |
| 6. Text Roaming Engine | Walk through the designed space interactively | Experience generator |
| 7. Structure Mirror | Check logic, consistency, emotional arc | Logic checker |
| 8. Revision Explainer | Document why changes were made | Meta-cognition trainer |

## License

MIT License — feel free to use, adapt, and share. If you create additional textbook cases or project models, contributions are welcome.

## Credits

Built on Mathegenic learning theory, the Writing Development U-Curve, and the AI Cognitive Offloading U-Curve. Designed for parents, educators, and self-directed learners who believe that AI's educational value lies not in bypassing difficulty, but in helping students cross it with better scaffolding.
