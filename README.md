# Quick Industry Research Codex Skill

This Skill is not a data collection checklist. It is designed to produce a consulting-style industry research brief with a progressive logic chain, evidence-backed judgments, visualized outputs, and next-step validation questions.

这个 Skill 不是简单搜集资料，而是按照行研报告逻辑，快速生成一份结论前置、边界清晰、问题递进、证据支撑、图表化输出、可复用的行业研究简报。

## 1. What this Skill is

`quick-industry-research` is a Codex Skill for rapidly understanding an unfamiliar industry and producing a first-pass consulting-style Markdown brief within a limited time budget.

It is designed to answer:

1. What is the industry?
2. How does it work?
3. How big is it?
4. How does it make money?
5. Who wins and why?
6. What changes the game?
7. So what?
8. What should be verified next?

## 2. Best-fit scenarios

- 咨询项目行业预研
- 陌生客户或陌生赛道快速理解
- 投研初筛
- 商业分析
- 竞品分析
- 面试前行业准备
- 新业务机会判断

## 3. When not to use it

- 完整尽调或深度专项研究
- 法律、医疗、投资建议等高风险结论
- 一句话百科式解释
- 非行业层面的窄任务，如单公司财务建模
- 实时交易决策

## 4. Core capabilities

- Conclusion-led industry brief generation
- Clear industry boundary definition
- Value-chain and value-flow analysis
- Market sizing and growth-driver assessment
- Business-model and profit-pool analysis
- Competitive landscape and key company comparison
- Policy timeline and external-driver analysis
- Risk-opportunity synthesis and next-step validation

## 5. Output structure

The standard output is a consulting-style Markdown brief with:

- executive thesis
- scope and assumptions
- industry definition
- industry structure and value chain
- market space and growth drivers
- business model and profit pool
- competitive landscape
- external drivers
- risks and opportunities
- consulting judgment
- next-step validation
- source and evidence notes

## 6. How to use

Ask Codex to use `$quick-industry-research` and provide:

- industry
- country or region
- research purpose
- output depth
- time budget
- optional priority topics

## 7. Example input

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

## 8. Example output structure

- One-sentence conclusion
- Logic map
- Scope and assumptions
- Industry definition and boundary
- Value-chain and profit-pool analysis
- Market tables
- Business-model table
- Competitive landscape table
- Key company comparison table
- Policy timeline
- External-driver matrix
- Risk-opportunity matrix
- Validation priority table
- Source and evidence notes

## 9. File structure

```text
quick-industry-research/
├── SKILL.md
├── report-template.md
├── database-framework.md
└── agents/
    └── openai.yaml
```

## 10. Quality standards

- 必须形成完整研究主线，而不是并列模块
- 每章必须有判断和 Transition / Implication
- 必须区分 `[Fact]`、`[Estimate]`、`[Judgment]`、`[Assumption]`、`[To verify]`
- 不允许虚构数据
- 必须说明来源口径和边界
- 必须提供图表化输出，而不是资料清单

## Review Entry

- Formal Skill: [quick-industry-research/SKILL.md](quick-industry-research/SKILL.md)
- Report template: [quick-industry-research/report-template.md](quick-industry-research/report-template.md)
- Research asset framework: [quick-industry-research/database-framework.md](quick-industry-research/database-framework.md)
