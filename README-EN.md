# Chinese Parent Simulator

> A behavioral simulation framework for Chinese-style parenting (中国式家长). Captures the archetypal speech patterns, decision logic, and emotional dynamics of traditional Chinese parents across various life scenarios.

[中文](README.md)

---

## Overview

Chinese-style parenting (中国式家长) is a well-recognized cultural archetype in contemporary Chinese society. It embodies a distinct set of values — academic achievement as the ultimate priority, stable employment above all, marriage at the "right" age, frugality, filial piety, and the pervasive influence of "face" (面子) in social comparisons.

This framework deconstructs these patterns into structured, reusable components:

- **Core value dimensions** — education, career, marriage, consumption, family, social dynamics
- **Life-stage mapping** — from primary school through adulthood, with shifting parental concerns
- **Scenario libraries** — pre-built response patterns for common flashpoints (grades, career changes, dating, spending, family gatherings)
- **Emotional layering** — the "tough exterior, soft interior" (刀子嘴豆腐心) dynamic that defines genuine Chinese parenting interactions

## Repository Structure

```
chinese-parent-simulator/
├── SKILL.md              # Main skill definition and scenario library
├── README.md             # Chinese documentation
├── README-EN.md          # English documentation (this file)
└── LICENSE               # MIT License
```

## Usage

This framework is designed as an AI Skill definition. It can be consumed by compatible AI agents to simulate Chinese-style parenting behavior in interactive scenarios.

### Trigger Scenarios

The skill activates when a user describes a scenario involving:

- Academic or work performance feedback
- Major life decisions (career change, entrepreneurship, relocation)
- Relationship and marriage status
- Spending and financial habits
- Family communication gaps

### Output Format

Each simulation response follows a structured format:

```
【场景】Context description of the current situation
【角色状态】Parent's emotional state (anxiety / anger / concern / relief / inner conflict)
【对话】The simulated dialogue in the parent's voice
【内心OS】Unspoken thoughts — revealing the care beneath the criticism
```

### Example

```
【场景】26-year-old son quits a big tech company to start a bubble tea shop

【角色状态】Shock → Anger → Worry → Reluctant acceptance

【对话】
"Are you crazy? You just quit a top-tier company? Do you know how many
people are dying to get in? A bubble tea shop? Do you know anything about
running a business? Do you have any idea how many shops have gone under?"

(Pause, tone softens)
"Fine. You're not going to listen to me anyway. How much capital do you have?
Have you picked a location? ... Forget it, I'll come with you this weekend to
take a look. Don't let anyone cheat you."

【内心OS】
He's worried sick but knows he can't stop him. The only thing left is to
help where he can. The harsh words are just a cover.
```

## Scenarios Covered

| Category | Triggers | Typical Response Pattern |
|----------|----------|------------------------|
| Academic / Work | Exams, grades, performance reviews, promotions | Peer comparison, downplaying success, catastrophic predictions |
| Life Choices | Quitting jobs, starting a business, changing careers | Strong opposition, worst-case scenarios, reluctant acceptance |
| Relationships | Dating, breakups, being single, matchmaking | Urgency, background interrogation, arranged dating |
| Spending | Shopping, large purchases, dining out | Price-checking, cost lectures, intergenerational comparison |
| Family | Phone calls, home visits, holidays | Guilt-tripping, "face" pressure, emotional manipulation |

## Value Dimensions

| Dimension | Core Belief | Typical Expression |
|-----------|------------|-------------------|
| Education | Grades determine the future | "Without a good university, your life is over" |
| Career | Stability above all | "Civil service, teaching, medicine — those are proper jobs" |
| Marriage | Marry at the right age, match social standing | "Everyone else's kid is already married" |
| Spending | Save first, spend later | "Money doesn't grow on trees" |
| Family | Filial piety, parental authority | "I've eaten more salt than you've eaten rice" |
| Social | Face, comparison, community standing | "Don't let the relatives laugh at us" |

## Boundaries

This framework is intended for **cultural research, educational simulation, and AI-assisted role-playing**. It explicitly excludes:

- Physical violence or abuse
- Illegal confinement or extreme control
- Regional or ethnic stereotypes
- Targeting specific real individuals
- One-dimensional negative portrayal (the framework preserves the underlying care dynamic)

## License

MIT