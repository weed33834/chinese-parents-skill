# Chinese Parents Skill

> A behavioral simulation and diagnosis framework for Chinese-style parenting (中国式家长). Based on a **10-dimension composable system** covering all behavioral variants. Supports **Simulation Mode** and **Diagnosis Mode**.

[中文](README.md)

---

## Overview

Chinese-style parenting is not monolithic. **This framework uses 10 independent dimensions to describe parental behavior differences.** Each dimension has 3-4 levels, theoretically covering 3^10 ≈ 59,049 parent profiles.

### Core Capabilities

| Mode | Purpose | Example |
|------|---------|---------|
| **Simulation** | Generate parent behavior from dimension combination | "Tiger mom with warmer tone, I ranked 3rd" |
| **Diagnosis** | Analyze parent type from user description | "Help me figure out what kind of parent my mom is" |

## 10-Dimension Profile System

| # | Dimension | Core Question | Levels |
|---|-----------|---------------|--------|
| 1 | **Control** | How much do they control? | Laissez-faire ← Moderate → Strict → Domineering |
| 2 | **Temperature** | How warm is the emotional climate? | Cold ← Rational → Warm → Indulgent |
| 3 | **Participation** | How involved are they? | Absent ← Passive → Active → Overbearing |
| 4 | **Anxiety** | How anxious about the future? | Zen ← Moderate → Anxious → Panicked |
| 5 | **Communication** | How do they talk to their child? | Command ← Lecture → Discuss → Listen |
| 6 | **Values** | Traditional or progressive? | Traditional ← Mixed → Progressive |
| 7 | **Finance** | How do they handle money? | Stingy ← Moderate → Generous |
| 8 | **Expectation** | How high are the expectations? | None ← Moderate → Extremely High |
| 9 | **Social** | How do they manage social life? | Restrictive ← Guided → Open |
| 10 | **Independence** | How do they foster independence? | Do-it-all ← Guide → Let Go |

## Usage

### Simulation Mode

Three ways to specify dimensions:

```
# Natural language description (recommended)
"My mom is super strict but really cares about me"
→ Control:Strict + Temperature:Warm

# Modify from reference type
"Like tiger mom, but warmer temperature"

# Direct specification
"Control:Strict + Temperature:Warm + Anxiety:Anxious + Communication:Discuss"
```

### Diagnosis Mode

Just describe the parent's behavior:

```
"Help me analyze what kind of parent my mom is"
"My mom always does this... what's her psychology?"
```

The AI will ask follow-up questions if needed, then generate a diagnostic report.

### Output Format

Simulation mode:

```
【Profile】
  Control: Strict | Temperature: Warm | Participation: Active
  Anxiety: Anxious | Communication: Command | Values: Traditional
  Finance: Moderate | Expectation: High | Social: Restrictive
  Independence: Do-it-all

【Scenario】xxx
【State】xxx
【Dialogue】xxx
【Inner Voice】xxx
```

Diagnosis mode:

```
┌──────────────────────────────────────┐
│    Chinese Parent Type Diagnosis      │
└──────────────────────────────────────┘
【Profile】10-dimension visualization
【Similar Types】Closest known parent types
【Scenario Predictions】Behavior predictions
【Communication Tips】Customized strategies
```

## 10 Scenarios

| Scenario | Triggers | Key Dimensions |
|----------|----------|----------------|
| Academic / Work | Exams, grades, performance | Control, Temperature, Anxiety, Expectation, Communication |
| Life Choices | Quitting, entrepreneurship, study abroad | Values, Control, Anxiety, Temperature, Communication |
| Relationships | Dating, marriage, being single | Values, Social, Control, Temperature |
| Spending | Shopping, large purchases, salary | Finance, Control, Values |
| Family | Phone calls, home visits, holidays | Temperature, Participation, Communication |
| Social / Friends | Going out, parties, socializing | Social, Control, Independence |
| Digital / Screens | Gaming, phone, internet,熬夜 | Control, Anxiety, Communication |
| Health / Habits | Eating, sleeping, exercise, diet | Temperature, Control, Participation |
| Appearance | Dressing, makeup, tattoos, piercings | Values, Control |
| Education | School choice, cram schools, study abroad | Anxiety, Finance, Expectation, Participation |

## Version History

| Version | Changes |
|---------|---------|
| 3.0.0 | Restructured to 10-dimension system + diagnosis mode + 10 scenarios × dimension matrix |
| 2.0.0 | Added 8 parent types, scenario × type matrix |
| 1.0.0 | Initial release |

## License

MIT