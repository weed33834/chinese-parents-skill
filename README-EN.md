# Chinese Parents Skill

> A behavioral simulation framework for Chinese-style parenting (中国式家长). Captures the archetypal speech patterns, decision logic, and emotional dynamics of traditional Chinese parents. Supports **8 parent type profiles** — each responds differently to the same scenario.

[中文](README.md)

---

## Overview

Chinese-style parenting is a well-recognized cultural archetype in contemporary Chinese society. It embodies a distinct set of values — academic achievement as the ultimate priority, stable employment above all, marriage at the "right" age, frugality, filial piety, and the pervasive influence of "face" (面子) in social comparisons.

However, Chinese parenting is not monolithic. **Different parent types can react in completely opposite ways to the same situation.** This framework deconstructs Chinese parenting into 8 distinct profiles, each with its own belief system, speech patterns, and emotional dynamics.

### Parent Types

| Type | One-liner | Emotional Temperature |
|------|-----------|---------------------|
| **Tiger Parent** | Grades are everything, strictness is love | Cold |
| **Hustle Parent** | Can't lose at the starting line | Warm |
| **Helicopter Parent** | My child can't do it without me | Warm |
| **Zen Parent** | Let nature take its course | Hot |
| **Zombie Parent** | Absent until it's time to criticize | Cold |
| **Controller Parent** | I'll arrange your life for you | Cold |
| **Democratic Parent** | We communicate as equals | Hot |
| **Absent Parent** | Child-rearing is not my job | Freezing |

## Repository Structure

```
chinese-parents-skill/
├── SKILL.md              # Main skill definition with full scenario library
├── README.md             # Chinese documentation
├── README-EN.md          # English documentation (this file)
└── LICENSE               # MIT License
```

## Usage

### Selecting a Parent Type

Users can activate a specific type in three ways:

**Explicit:**
```
"Use tiger mom mode"
"Switch to zen parent"
"Simulate a helicopter parent"
```

**Inferred from description:**
```
"My mom signed me up for five more classes" → Hustle Parent
"My dad controls everything I do" → Controller Parent
```

**Default:** Falls back to "Typical Mixed Chinese Parent" when no type is specified.

### Output Format

Each simulation follows this structure:

```
【Parent Type】Tiger Parent

【Scenario】Description of the current situation

【State】Parent's emotional state

【Dialogue】Simulated dialogue in the parent's voice

【Inner Voice】Unspoken thoughts — revealing the care beneath the criticism
```

### Scenario × Type Comparison

Same scenario ("child ranked 3rd in class") — different parent types:

| Type | Reaction |
|------|----------|
| **Tiger** | "3rd? What about 1st and 2nd? ... 92 on math? Where did you lose those 8 points?" (then calls relatives to brag) |
| **Hustle** | "3rd is okay, but the neighbor's kid took three summer cram courses. I signed you up for a sprint class." |
| **Zen** | "3rd is great! What do you want for dinner? Don't put too much pressure on yourself." |
| **Helicopter** | "Is the teacher not good enough? I'm going to talk to the school tomorrow." |
| **Controller** | "I've already arranged extra tutoring — two hours of math and one hour of English every weekend." |
| **Zombie** | "Only 3rd? And I wasn't even pushing you." (goes back to phone) |
| **Democratic** | "Are you happy with your results? Any subject you need help with?" |
| **Absent** | "Oh, nice. ... Hey, is your mom planning to sign up for any classes?" |

## Scenarios Covered

| Category | Triggers | Coverage |
|----------|----------|----------|
| Academic / Work | Exams, grades, performance reviews | 8 distinct response patterns per scenario |
| Life Choices | Quitting jobs, starting a business, changing careers | From "strong opposition" to "analytical support" |
| Relationships | Dating, breakups, being single, marriage pressure | From "forced marriage" to "respect your choice" |
| Spending | Shopping, large purchases | From "financial control" to "enjoy your money" |
| Family | Phone calls, home visits, holidays | From "set rules" to "we miss you" |

## Version History

| Version | Changes |
|---------|---------|
| 2.0.0 | Added 8 parent type profiles, scenario × type matrix, type selection mechanism, hybrid mode |
| 1.0.0 | Initial release with basic scenario library |

## License

MIT