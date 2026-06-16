# Quick Industry Research Codex Skill

This project is a Codex Skill for building a first-pass industry research brief within about 1 hour.

## What this skill is

This is not a simple information-gathering prompt pack.

It is a structured industry research method designed to help Codex produce a consulting-style Markdown brief with:

- conclusion first
- clear research boundaries
- progressive question logic
- evidence-backed judgment
- diagram and table outputs
- reusable research assets for follow-up work

The expected output is not a raw note dump or source list. It should be a structured brief that answers:

1. What industry are we studying?
2. How does it work?
3. How big is it?
4. How does it make money?
5. Who wins and why?
6. What changes the game?
7. So what?
8. What should be verified next?

## Core characteristics

- Conclusion-led: start with the thesis, not with background noise.
- Boundary clarity: define included and excluded scope before sizing the market.
- Question progression: each chapter leads to the next.
- Evidence support: facts, estimates, judgments, assumptions, and verification items must be separated.
- Visual output: use Mermaid diagrams, Markdown tables, and structured matrices.
- Reusable assets: findings should be captured as reusable research databases, not one-off notes.

## Core files

- Formal Skill file: [quick-industry-research/SKILL.md](quick-industry-research/SKILL.md)
- Research brief template: [quick-industry-research/report-template.md](quick-industry-research/report-template.md)
- Research asset framework: [quick-industry-research/database-framework.md](quick-industry-research/database-framework.md)
- Skill UI metadata: [quick-industry-research/agents/openai.yaml](quick-industry-research/agents/openai.yaml)

## How to use

Ask Codex to use the `quick-industry-research` Skill and provide:

- industry
- country or region
- research purpose
- output depth
- time budget
- optional priority topics

Example:

```markdown
Use $quick-industry-research to research the low-altitude economy industry in China.

Inputs:
- Industry: Low-altitude economy
- Country or region: China
- Research purpose: Consulting project pre-research
- Output depth: Standard brief
- Time budget: 1 hour
- Priority topics: policy, market size, value chain, competitors, business models, opportunities and risks
```

Expected output:

- executive thesis
- industry research logic map
- industry boundary and scope
- value-chain and value-flow analysis
- market data table
- business-model analysis
- competition tiering table
- external-driver matrix
- risk-opportunity matrix
- next-step validation priorities

## Notes

- This repository contains a formal Codex Skill, not a web page or frontend project.
- The main review entry is [quick-industry-research/SKILL.md](quick-industry-research/SKILL.md).
- The skill is designed to produce a research brief with consulting judgment, not just a material collection list.
