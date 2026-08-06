<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo.jpg">
    <img src="assets/logo.jpg" alt="Chinese Parents Skill" width="180">
  </picture>
</p>

<h1 align="center">Chinese Parents Skill</h1>

<p align="center">
  <em>中国式家长行为模拟与诊断框架</em>
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
  <a href="#-简介">简介</a> •
  <a href="#-10维家长画像系统">10 维画像</a> •
  <a href="#-快速开始">快速开始</a> •
  <a href="#-10大场景">场景</a> •
  <a href="#-目录结构">目录</a> •
  <a href="#-贡献">贡献</a>
</p>

---

## 📖 简介

**Chinese Parents Skill** 是一个基于 **10 维组合系统** 的中国式家长行为模拟与诊断框架。它捕捉当代中国家庭中典型父母的言语模式、决策逻辑与情感张力。

> 中国式家长并非单一模式。**不同类型的家长，面对同一个场景，反应可能截然相反。** 本框架用 10 个独立维度描述家长行为差异，每个维度 3-4 个档位，理论上可覆盖 3^10 ≈ 59049 种家长形态。

### 两大核心能力

| 模式 | 一句话 | 示例 |
|------|--------|------|
| **🎭 模拟模式** | 按维度组合生成家长行为反应 | "用虎妈但温度调高，我考了第三" |
| **🔍 诊断模式** | 反向分析家长类型并给出建议 | "帮我分析一下我妈是什么家长" |

---

## 🧩 10 维家长画像系统

| # | 维度 | 核心问题 | 档位 |
|---|------|---------|------|
| 1 | **控制** | 管得多宽？ | 放任 ← 适度 → 严格 → 控制 |
| 2 | **温度** | 情感是暖是冷？ | 冷漠 ← 理性 → 温暖 → 溺爱 |
| 3 | **参与** | 投入了多少精力？ | 缺席 ← 被动 → 主动 → 过度介入 |
| 4 | **焦虑** | 对未来有多焦虑？ | 佛系 ← 适度 → 焦虑 → 恐慌 |
| 5 | **沟通** | 怎么跟孩子说话？ | 命令 ← 说教 → 商量 → 倾听 |
| 6 | **观念** | 思想开明还是保守？ | 传统保守 ← 混合 → 开明现代 |
| 7 | **经济** | 给钱的方式和态度？ | 苛刻 ← 适度 → 慷慨 |
| 8 | **期望** | 对孩子期望多高？ | 无要求 ← 适度 → 极高 |
| 9 | **社交** | 怎么管孩子社交？ | 封闭 ← 引导 → 开放 |
| 10 | **独立** | 培养还是包办？ | 包办 ← 引导 → 放手 |

### 参考类型（常见维度组合）

| 类型 | 控制 | 温度 | 参与 | 焦虑 | 沟通 | 观念 | 期望 | 社交 | 独立 |
|------|------|------|------|------|------|------|------|------|------|
| **虎妈虎爸** | 严格 | 理性 | 主动 | 焦虑 | 命令 | 传统 | 极高 | 封闭 | 包办 |
| **鸡娃家长** | 严格 | 温暖 | 主动 | 恐慌 | 说教 | 混合 | 极高 | 引导 | 引导 |
| **直升机家长** | 严格 | 温暖 | 过度 | 恐慌 | 命令 | 混合 | 适度 | 封闭 | 包办 |
| **佛系家长** | 适度 | 温暖 | 主动 | 佛系 | 商量 | 开明 | 无要求 | 开放 | 放手 |
| **控制型家长** | 控制 | 冷漠 | 主动 | 焦虑 | 命令 | 传统 | 极高 | 封闭 | 包办 |
| **民主型家长** | 适度 | 温暖 | 主动 | 适度 | 倾听 | 开明 | 适度 | 开放 | 放手 |
| **诈尸式育儿** | 放任 | 冷漠 | 缺席 | 适度 | 命令 | 传统 | 适度 | 封闭 | 放任 |
| **丧偶式育儿** | 放任 | 冷漠 | 缺席 | 佛系 | 命令 | 传统 | 无要求 | 放任 | 放任 |

---

## 🚀 快速开始

### 模拟模式

三种方式指定维度组合：

```bash
# 1. 口语化描述（推荐）
"我妈管我管得特别严，但对我特别好"
→ 自动映射为 控制:严格 + 温度:温暖

# 2. 参考类型修改
"像虎妈，但温度调高一点"

# 3. 直接指定
"控制:严格 + 温度:温暖 + 焦虑:焦虑 + 沟通:商量"
```

### 诊断模式

描述家长行为，AI 自动分析：

```bash
"帮我分析一下我妈是什么类型的家长"
"我妈总是这样，她到底是什么心理？"
```

AI 会主动追问补充信息，然后生成完整的诊断报告。

### 输出示例

<details>
<summary>点击展开 → 模拟模式输出示例</summary>

```
【家长画像】
  控制: 严格 | 温度: 温暖 | 参与: 主动
  焦虑: 焦虑 | 沟通: 命令 | 观念: 传统
  经济: 适度 | 期望: 极高 | 社交: 封闭
  独立: 包办
  （参考类型：虎妈变体，温度调高）

【场景】女儿期中考试全班第三名，回家告诉妈妈

【角色状态】内心骄傲 + 表面理性 + 想鼓励但又怕飘

【对话】
"第三名？很不错啊，进步了！"
"那第一名多少分？第二名呢？……哦，你们班50个人，第三名很好了。"
"数学92分，这8分是粗心还是不会？如果是粗心我们下次注意就好。"
"妈妈为你骄傲。晚上想吃什么？"

【内心OS】其实高兴得想发朋友圈，但忍住了。怕表扬太多孩子就不努力了。
```
</details>

<details>
<summary>点击展开 → 诊断模式输出示例</summary>

```
┌────────────────────────────────────────────────┐
│          中国式家长类型诊断报告                   │
└────────────────────────────────────────────────┘

【维度画像】
  控制  ████████████░░░░░░  严格（75%）
  温度  ████████░░░░░░░░░░  理性（55%）
  参与  ████████████░░░░░░  主动（70%）
  焦虑  ██████████████░░░░  焦虑（80%）
  沟通  ██████████░░░░░░░░  说教（60%）
  观念  ██████████░░░░░░░░  混合（60%）
  经济  ████████░░░░░░░░░░  适度（50%）
  期望  ████████████████░░  极高（85%）
  社交  ██████░░░░░░░░░░░░  引导（40%）
  独立  ██████████░░░░░░░░  引导（55%）

【参考类型】虎妈虎爸（85%）· 鸡娃家长（70%）

【建议沟通方式】
  ✓ 先肯定她的关心，再表达自己的想法
  ✓ 用具体数据和事实说服，比情绪对抗有效
  ✗ 不要用顶撞的方式对抗，会触发控制加强
```
</details>

---

## 📋 10 大场景

| 场景 | 触发词 | 关键维度 |
|------|--------|---------|
| A 学业/工作 | 考试、分数、绩效、升职 | 控制、温度、焦虑、期望、沟通 |
| B 人生选择 | 辞职、创业、转行、gap year | 观念、控制、焦虑、温度、沟通 |
| C 婚恋关系 | 恋爱、相亲、结婚、不婚 | 观念、社交、控制、温度 |
| D 消费经济 | 花钱、买、贵、工资、存钱 | 经济、控制、观念 |
| E 家庭相处 | 打电话、回家、过节 | 温度、参与、沟通 |
| F 社交交友 | 朋友、出去玩、聚会 | 社交、控制、独立 |
| G 网络电子产品 | 游戏、手机、上网、熬夜 | 控制、焦虑、沟通 |
| H 健康生活习惯 | 吃饭、睡觉、运动、减肥 | 温度、控制、参与 |
| I 外表形象 | 穿着、打扮、化妆、纹身 | 观念、控制 |
| J 教育方式 | 择校、兴趣班、留学、学区房 | 焦虑、经济、期望、参与 |

每个场景下，不同维度档位对回应的具体影响规则详见 [SKILL.md](SKILL.md#五10-大场景--维度影响矩阵)。

---

## 📁 目录结构

```
chinese-parents-skill/
├── SKILL.md                  # 主技能定义文件（核心）
├── README.md                 # 中文文档
├── README-EN.md              # 英文文档
├── CHANGELOG.md              # 版本历史
├── CONTRIBUTING.md           # 贡献指南
├── CODE_OF_CONDUCT.md        # 行为准则
├── LICENSE                   # MIT 许可证
├── assets/
│   ├── logo.jpg              # 项目 logo
│   └── og-image.jpg          # 社交预览图
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md
    │   ├── feature_request.md
    │   └── scenario_suggestion.md
    └── PULL_REQUEST_TEMPLATE.md
```

---

## 🤝 贡献

欢迎贡献！请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 和 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。

- 🐛 发现 bug？提 [Issue](https://github.com/weed33834/chinese-parents-skill/issues/new?template=bug_report.md)
- 💡 有想法？提 [Feature Request](https://github.com/weed33834/chinese-parents-skill/issues/new?template=feature_request.md)
- 📖 有新场景？提 [Scenario Suggestion](https://github.com/weed33834/chinese-parents-skill/issues/new?template=scenario_suggestion.md)

## 📄 许可

[MIT](LICENSE) © 2026 badhope