<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo.jpg">
    <img src="assets/logo.jpg" alt="Chinese Parents Skill" width="180">
  </picture>
</p>

<h1 align="center">Chinese Parents Skill</h1>

<p align="center">
  <em>A behavioral simulation & diagnosis framework for Chinese-style parenting</em>
</p>

<p align="center">
  <a href="https://github.com/weed33834/chinese-parents-skill/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/weed33834/chinese-parents-skill?style=flat-square&color=red" alt="License">
  </a>
  <a href="https://github.com/weed33834/chinese-parents-skill/releases">
    <img src="https://img.shields.io/github/v/release/weed33834/chinese-parents-skill?style=flat-square&color=orange" alt="Version">
  </a>
  <a href="https://github.com/weed33834/chinese-parents-skill/stargazers">
    <img src="https://img.shields.io/github/stars/weed33834/chinese-parents-skill?style=flat-square" alt="Stars">
  </a>
  <a href="https://github.com/weed33834/chinese-parents-skill/commits/main">
    <img src="https://img.shields.io/github/last-commit/weed33834/chinese-parents-skill?style=flat-square&color=blue" alt="Last Commit">
  </a>
  <a href="https://github.com/weed33834/chinese-parents-skill/issues">
    <img src="https://img.shields.io/github/issues/weed33834/chinese-parents-skill?style=flat-square&color=green" alt="Issues">
  </a>
  <a href="https://github.com/weed33834/chinese-parents-skill">
    <img src="https://img.shields.io/github/repo-size/weed33834/chinese-parents-skill?style=flat-square" alt="Repo Size">
  </a>
</p>

<p align="center">
  <a href="README.md">中文</a> · <a href="README-EN.md">English</a>
</p>

<p align="center">
  <a href="#-introduction">Introduction</a> •
  <a href="#-10-dimension-profile-system">10 Dimensions</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-10-scenarios">Scenarios</a> •
  <a href="#-repository-structure">Structure</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## 📖 Introduction

**Chinese Parents Skill** is a behavioral simulation and diagnosis framework based on a **10-dimension composable system**. It captures the archetypal speech patterns, decision logic, and emotional dynamics of traditional Chinese parents.

> Chinese-style parenting is not monolithic. **Different parent types can react in completely opposite ways to the same situation.** This framework uses 10 independent dimensions to describe parental behavior differences, with 3-4 levels per dimension, theoretically covering 3^10 ≈ 59,049 parent profiles.

### Two Core Capabilities

| Mode | Description | Example |
|------|-------------|---------|
| **🎭 Simulation** | Generate parent behavior from dimension combination | "Tiger mom with warmer tone, I ranked 3rd" |
| **🔍 Diagnosis** | Reverse-analyze parent type from user descriptions | "Help me figure out what kind of parent my mom is" |

---

## 🧩 10-Dimension Profile System

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
| 10 | **Independence** | Foster or stifle independence? | Do-it-all ← Guide → Let Go |

### Reference Types (Common Dimension Combinations)

| Type | Control | Temp | Participation | Anxiety | Comm | Values | Expect | Social | Indep |
|------|---------|------|---------------|---------|------|--------|--------|--------|-------|
| **Tiger Parent** | Strict | Rational | Active | Anxious | Command | Traditional | High | Restrictive | Do-it-all |
| **Hustle Parent** | Strict | Warm | Active | Panicked | Lecture | Mixed | High | Guided | Guide |
| **Helicopter Parent** | Strict | Warm | Overbearing | Panicked | Command | Mixed | Moderate | Restrictive | Do-it-all |
| **Zen Parent** | Moderate | Warm | Active | Zen | Discuss | Progressive | None | Open | Let Go |
| **Controller** | Domineering | Cold | Active | Anxious | Command | Traditional | High | Restrictive | Do-it-all |
| **Democratic** | Moderate | Warm | Active | Moderate | Listen | Progressive | Moderate | Open | Let Go |
| **Zombie Parent** | Laissez | Cold | Absent | Moderate | Command | Traditional | Moderate | Restrictive | N/A |
| **Absent Parent** | Laissez | Cold | Absent | Zen | Command | Traditional | None | N/A | N/A |

---

## 🚀 Quick Start

### Simulation Mode

Three ways to specify dimensions:

```bash
# 1. Natural language description (recommended)
"My mom is super strict but really cares about me"
→ Auto-maps to Control:Strict + Temperature:Warm

# 2. Modify from reference type
"Like tiger mom, but warmer temperature"

# 3. Direct specification
"Control:Strict + Temperature:Warm + Anxiety:Anxious + Communication:Discuss"
```

### Diagnosis Mode

Describe the parent's behavior:

```bash
"Help me analyze what kind of parent my mom is"
"My mom always does this... what's her psychology?"
```

The AI will ask follow-up questions if needed, then generate a complete diagnostic report.

### Output Examples

<details>
<summary>Click to expand → Simulation Mode Output</summary>

```
【Profile】
  Control: Strict | Temperature: Warm | Participation: Active
  Anxiety: Anxious | Communication: Command | Values: Traditional
  Finance: Moderate | Expectation: High | Social: Restrictive
  Independence: Do-it-all

【Scenario】Daughter ranked 3rd in midterm exams

【State】Proud inside + calm outside + wants to encourage without causing complacency

【Dialogue】
"3rd place? That's great, you've improved!"
"What about 1st and 2nd? ... Oh, 50 students in the class, 3rd is very good."
"92 on math? Were those 8 points from carelessness or something you didn't understand?"
"Mom is proud of you. What do you want for dinner?"
```
</details>

<details>
<summary>Click to expand → Diagnosis Mode Output</summary>

```
┌────────────────────────────────────────────────┐
│      Chinese Parent Type Diagnosis Report       │
└────────────────────────────────────────────────┘

【Profile】
  Control    ████████████░░░░░░  Strict (75%)
  Temperature ████████░░░░░░░░░░  Rational (55%)
  Participation ████████████░░░░  Active (70%)
  Anxiety    ██████████████░░░░  Anxious (80%)
  Communication ██████████░░░░░░  Lecture (60%)
  Values     ██████████░░░░░░░░  Mixed (60%)
  Finance    ████████░░░░░░░░░░  Moderate (50%)
  Expectation ████████████████░░  High (85%)
  Social     ██████░░░░░░░░░░░░  Guided (40%)
  Independence ██████████░░░░░░  Guide (55%)

【Similar Types】Tiger Parent (85%) · Hustle Parent (70%)
```
</details>

---

## 📋 10 Scenarios

| Scenario | Triggers | Key Dimensions |
|----------|----------|----------------|
| A Academic/Work | Exams, grades, performance reviews | Control, Temperature, Anxiety, Expectation, Communication |
| B Life Choices | Quitting, starting a business, studying abroad | Values, Control, Anxiety, Temperature, Communication |
| C Relationships | Dating, marriage, being single | Values, Social, Control, Temperature |
| D Spending | Shopping, large purchases, salary | Finance, Control, Values |
| E Family | Phone calls, home visits, holidays | Temperature, Participation, Communication |
| F Social/Friends | Going out, parties, socializing | Social, Control, Independence |
| G Digital/Screens | Gaming, phone, internet, screens | Control, Anxiety, Communication |
| H Health/Habits | Eating, sleeping, exercise, diet | Temperature, Control, Participation |
| I Appearance | Dressing, makeup, tattoos, piercings | Values, Control |
| J Education | School choice, cram schools, study abroad | Anxiety, Finance, Expectation, Participation |

---

## 📁 Repository Structure

```
chinese-parents-skill/
├── SKILL.md                  # Core skill definition
├── README.md                 # Chinese documentation
├── README-EN.md              # English documentation
├── CHANGELOG.md              # Version history
├── CONTRIBUTING.md           # Contributing guide
├── CODE_OF_CONDUCT.md        # Code of conduct
├── LICENSE                   # MIT License
├── assets/
│   ├── logo.jpg              # Project logo
│   └── og-image.jpg          # Social preview image
└── .github/
    ├── ISSUE_TEMPLATE/
    ├── PULL_REQUEST_TEMPLATE.md
```

---

## 🤝 Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

- 🐛 Found a bug? Open an [Issue](https://github.com/weed33834/chinese-parents-skill/issues/new)
- 💡 Have an idea? Submit a [Feature Request](https://github.com/weed33834/chinese-parents-skill/issues/new)
- 📖 New scenario? Submit a [Scenario Suggestion](https://github.com/weed33834/chinese-parents-skill/issues/new)

## 📄 License

[MIT](LICENSE) © 2026 badhope