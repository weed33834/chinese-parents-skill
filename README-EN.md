<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo.jpg">
    <img src="assets/logo.jpg" alt="Chinese Parents Skill" width="180">
  </picture>
</p>

<h1 align="center">Chinese Parents Skill</h1>

<p align="center">
  <em>What kind of parent do you have? 10 dimensions will tell you.</em>
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
  <a href="#what-is-this">What</a> ·
  <a href="#10-dimensions">10 Dimensions</a> ·
  <a href="#how-to-use">How to Use</a> ·
  <a href="#classic-quotes">Quotes</a> ·
  <a href="#10-scenarios">Scenarios</a> ·
  <a href="#contributing">Contributing</a>
</p>

---

## What is this

Did your mom ever say "look at someone else's kid"?

Did she praise you for ranking 3rd, then immediately ask "what did 1st place get"?

Is your mom a tiger mom, a hustle mom, or a zen mom?

This project doesn't do academic research. It does one thing: **makes AI simulate your parent's tone, logic, and inner monologue.**

Two things it can do:

- **Simulate** — tell it what your parent is like, it acts it out
- **Diagnose** — describe your parent's behavior, it figures out what type they are

Chinese parenting isn't one thing. Same "ranked 3rd" — some moms scold first, some praise first, some don't care. 10 dimensions, theoretically **59,049 parent profiles**. Yours is probably in there.

---

## 10 Dimensions

Not all parents are the same. These 10 dimensions determine how yours differs from everyone else's:

| Dimension | What it controls | Levels |
|-----------|------------------|--------|
| Control | How much they manage | Hands-off · Moderate · Strict · Domineering |
| Temperature | Warm or cold emotionally | Cold · Rational · Warm · Indulgent |
| Participation | How involved | Absent · Passive · Active · Overbearing |
| Anxiety | How worried about the future | Zen · Moderate · Anxious · Panicked |
| Communication | How they talk to you | Command · Lecture · Discuss · Listen |
| Values | Traditional or progressive | Traditional · Mixed · Progressive |
| Finance | How they handle money | Stingy · Moderate · Generous |
| Expectation | How high the bar is | None · Moderate · Extremely High |
| Social | How they manage your social life | Restrictive · Guided · Open |
| Independence | Foster or stifle | Do-it-all · Guide · Let Go |

### Common Combinations (Reference Types)

These aren't all of them — just shortcuts. Each type is a specific combination of 10 dimensions. Mix and match freely:

| Type | Control | Temp | Participation | Anxiety | Comm | Values | Expect | Social | Indep |
|------|---------|------|---------------|---------|------|--------|--------|--------|-------|
| Tiger Parent | Strict | Rational | Active | Anxious | Command | Traditional | High | Restrictive | Do-it-all |
| Hustle Parent | Strict | Warm | Active | Panicked | Lecture | Mixed | High | Guided | Guide |
| Helicopter | Strict | Warm | Overbearing | Panicked | Command | Mixed | Moderate | Restrictive | Do-it-all |
| Zen Parent | Moderate | Warm | Active | Zen | Discuss | Progressive | None | Open | Let Go |
| Controller | Domineering | Cold | Active | Anxious | Command | Traditional | High | Restrictive | Do-it-all |
| Democratic | Moderate | Warm | Active | Moderate | Listen | Progressive | Moderate | Open | Let Go |
| Zombie Parent | Hands-off | Cold | Absent | Moderate | Command | Traditional | Moderate | Restrictive | Hands-off |
| Absent Parent | Hands-off | Cold | Absent | Zen | Command | Traditional | None | Hands-off | Hands-off |

---

## How to use

### Simulate your parent

Three ways, use whichever:

```
# 1. Plain English (recommended)
"My mom is super strict but really cares about me"
→ Auto-maps to Control:Strict + Temperature:Warm

# 2. Modify a reference type
"Like tiger mom, but warmer"

# 3. Specify dimensions directly
"Control:Strict + Temperature:Warm + Anxiety:Anxious + Communication:Discuss"
```

### Diagnose your parent

Describe their behavior, AI figures out the type:

```
"Help me analyze what kind of parent my mom is"
"My mom always does this... what's her psychology?"
```

AI will ask follow-up questions, then generate a diagnostic report.

### What simulation looks like

<details>
<summary>Click to expand → Simulation output</summary>

```
【Profile】
  Control: Strict | Temperature: Warm | Participation: Active
  Anxiety: Anxious | Communication: Command | Values: Traditional
  Finance: Moderate | Expectation: High | Social: Restrictive
  Independence: Do-it-all
  (Reference: Tiger variant, temperature raised)

【Scenario】Daughter ranked 3rd in midterm exams

【State】Proud inside + calm outside + wants to encourage without causing complacency

【Dialogue】
"3rd place? That's great, you've improved!"
"What about 1st and 2nd? ... Oh, 50 students in the class, 3rd is very good."
"92 on math? Were those 8 points from carelessness or something you didn't understand?"
"Mom is proud of you. What do you want for dinner?"

【Inner monologue】Wants to post on social media but held back. Afraid too much praise will make her stop trying.
```
</details>

### What diagnosis looks like

<details>
<summary>Click to expand → Diagnosis report</summary>

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

【Predicted Reactions】
  Good grades    → "Not bad, but room to improve" (proud but won't show it)
  Unconventional major → Strong opposition, lists employment difficulties
  Dating         → Interrogates partner's family background
  Spending       → Asks about price but doesn't restrict

【Communication Tips】
  ✓ Acknowledge their concern first, then express your thoughts
  ✓ Use concrete data and facts — more effective than emotional pushback
  ✗ Don't talk back — triggers control escalation
```
</details>

### Same situation, different parents

Same "quitting to start a business" — different dimensions produce opposite reactions:

<details>
<summary>Click to expand → Controller vs Democratic</summary>

**Control:Domineering + Values:Traditional + Temperature:Cold**
```
"No. I already got someone to find you a position. You start Monday.
 Starting a business? How many succeed at that?"
(Inner monologue: Terrified of failure, but expresses it as anger, never worry.)
```

**Control:Moderate + Values:Progressive + Temperature:Warm**
```
"That's a big decision. Can you tell me what you're thinking?"
(listens carefully)
"Starting a business is risky, but you're young and the cost of failure is low.
 Have you done market research? Let us know if you need help."
(Inner monologue: Worried sick all night, but knows the kid is grown. Can't stop them.)
```
</details>

---

## Classic Quotes

Has your mom said any of these?

```
□ "I'm doing this for your own good"           → Temperature:Rational
□ "Look at so-and-so's kid"                    → Expectation:Extremely High
□ "You'll understand when you're a parent"     → Communication:Lecture
□ "If it weren't for you, I would have..."     → Temperature:Rational + Control:Domineering
□ "Just study hard, don't worry about else"    → Expectation:High + Independence:Do-it-all
□ "What time? Who with? Male or female?"       → Control:Strict
□ "Do you need money? Let me send you some"    → Finance:Generous + Temperature:Warm
□ "This is a disaster, what do we do!"         → Anxiety:Panicked
□ "Do whatever you want"                       → Control:Hands-off
□ "Don't hang out with those people"           → Social:Restrictive
```

The more you check, the more that dimension stands out.

---

## 10 Scenarios

Each scenario produces completely different responses depending on dimension levels. Full rules in [SKILL.md](SKILL.md).

**A Academic/Work** — failed a test, got a raise, want to quit
Key: Control · Anxiety · Expectation · Communication → scold first or ask first

**B Life Choices** — quitting, startup, career change, gap year
Key: Values · Control · Anxiety → support or block

**C Relationships** — no partner yet, dating, marriage pressure
Key: Values · Social · Control → push marriage or stay open

**D Spending** — bought something expensive, broke, lending money
Key: Finance · Control → "spend what you need" or "wasteful"

**E Family** — phone calls, visits, holidays
Key: Temperature · Participation · Communication → nagging or ignoring

**F Social** — friends, going out, parties
Key: Social · Control → vetting friends or letting you go

**G Screens** — gaming, scrolling, staying up late
Key: Control · Anxiety → confiscate phone or don't care

**H Health** — eating, sleeping, exercise, diet
Key: Temperature · Participation → meal prep or hands-off

**I Appearance** — clothes, makeup, tattoos, hair
Key: Values · Control → respect your style or dictate what you wear

**J Education** — school choice, cram schools, study abroad
Key: Anxiety · Finance · Expectation → spend everything or let it be

---

## Repository Structure

```
chinese-parents-skill/
├── SKILL.md                  # Core skill definition (dimensions, scenarios, diagnosis rules)
├── README.md                 # Chinese docs
├── README-EN.md              # This file
├── CHANGELOG.md              # Version history
├── CONTRIBUTING.md           # Contributing guide
├── CODE_OF_CONDUCT.md        # Code of conduct
├── LICENSE                   # MIT
├── assets/
│   ├── logo.jpg
│   └── og-image.jpg
└── .github/
    ├── ISSUE_TEMPLATE/       # bug, feature, scenario
    └── PULL_REQUEST_TEMPLATE.md
```

---

## Contributing

Does your mom have a unique quote this project doesn't cover? A scenario that doesn't feel right? A dimension description that's off?

Don't hold back — open an Issue or send a PR. This project is built on everyone's mom experiences.

- Found a problem → [Open Issue](https://github.com/weed33834/chinese-parents-skill/issues/new?template=bug_report.md)
- Have an idea → [Feature Request](https://github.com/weed33834/chinese-parents-skill/issues/new?template=feature_request.md)
- New scenario → [Scenario Suggestion](https://github.com/weed33834/chinese-parents-skill/issues/new?template=scenario_suggestion.md)

Check [CONTRIBUTING.md](CONTRIBUTING.md) first.

## License

[MIT](LICENSE) © 2026 badhope
