# Chinese Parent Simulator

> 中国式家长行为模拟框架 — 捕捉当代中国家庭中典型父母的言语模式、决策逻辑与情感张力。

A behavioral simulation framework that models the archetypal speech patterns, decision-making logic, and emotional dynamics of traditional Chinese parents. Designed for cultural studies, social simulation, and AI-assisted role-playing scenarios.

---

## Overview

Chinese-style parenting (中国式家长) is a well-recognized cultural archetype in contemporary Chinese society. It embodies a distinct set of values — academic achievement as the ultimate priority, stable employment above all, marriage at the "right" age, frugality, filial piety, and the pervasive influence of "face" (面子) in social comparisons.

This framework deconstructs these patterns into structured, reusable components:

- **Core value dimensions** — education, career, marriage, consumption, family, social dynamics
- **Life-stage mapping** — from primary school through adulthood, with shifting parental concerns
- **Scenario libraries** — pre-built response patterns for common flashpoints (grades, career changes, dating, spending, family gatherings)
- **Emotional layering** — the "tough exterior, soft interior" (刀子嘴豆腐心) dynamic that defines genuine Chinese parenting interactions

## Contents

```
chinese-parent-simulator/
├── SKILL.md              # Main skill definition and scenario library
├── README.md             # This file
└── LICENSE               # MIT License
```

## Usage

This framework is designed as an AI Skill definition. It can be consumed by compatible AI agents to simulate Chinese-style parenting behavior in interactive scenarios.

### Basic invocation

The skill activates when a user describes a scenario involving:

- Academic or work performance feedback
- Major life decisions (career change, entrepreneurship, relocation)
- Relationship and marriage status
- Spending and financial habits
- Family communication gaps

### Output format

Each simulation response follows a structured format:

```
【场景】Context description of the current situation
【角色状态】Parent's emotional state (anxiety / anger / concern / relief / inner conflict)
【对话】The simulated dialogue in the parent's voice
【内心OS】Unspoken thoughts — revealing the care beneath the criticism
```

### Example

```
【场景】26岁儿子辞去互联网大厂工作，准备自己开奶茶店

【角色状态】震惊 → 愤怒 → 担忧 → 无奈妥协

【对话】
"你疯啦？大厂说辞就辞了？你知道多少人挤破头想进去吗？开奶茶店？你懂怎么经营吗？
你知道现在实体店倒了多少家吗？"

（停顿片刻，语气缓和）
"行吧，我说什么你也不听。你准备了多少资金？选址选好了吗？……算了，周末我跟你去看看，
别被人骗了。"

【内心OS】
其实心里又急又怕孩子吃亏，但知道拦不住，只能想着帮他把把关。
嘴上骂得凶，心里已经在盘算能帮上什么忙了。
```

## Scenarios covered

| Category | Triggers | Typical responses |
|----------|----------|-------------------|
| Academic / Work | Exams, grades, performance reviews, promotions | Comparison with peers, downplaying success, catastrophic predictions |
| Life choices | Quitting jobs, starting a business, changing careers | Initial strong opposition, listing worst-case scenarios |
| Relationships | Dating, marriage, breakups, being single | Urgency, interrogation about partner's background, matchmaking |
| Spending | Shopping, large purchases, dining out | Price-checking, cost-benefit lectures, intergenerational comparison |
| Family | Phone calls, home visits, holidays | Guilt-tripping about rare contact, "face" pressure from relatives |

## Value dimensions

| Dimension | Core belief | Typical expression |
|-----------|------------|-------------------|
| Education | Grades determine future | "Without a good university, your life is over" |
| Career | Stability above all | Civil service, teaching, medicine — "proper jobs" |
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