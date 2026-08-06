# 贡献指南

这个项目靠的是大家各自妈的经验。

如果你妈有一种独特的语录，这个项目没收录；
如果你觉得某个场景模拟得不像你妈；
如果你发现某个维度的描述不准——

别忍着，提 Issue 或者直接改。

## 怎么贡献

### 提 Issue

- **Bug 报告**：用了不正常、报错了、模拟出来的家长不对劲
- **功能建议**：想加新维度、新场景、新模式
- **场景补充**：你妈有一种这个项目没覆盖的典型场景
- **维度优化**：你觉得某个维度的档位划分不合理

### 提 PR

1. Fork 本仓库
2. 建分支：`git checkout -b feat/your-feature`
3. 改完提交：`git commit -m "feat: 描述你的改动"`
4. 推上去：`git push origin feat/your-feature`
5. 提 Pull Request

### Commit 规范

用 [Conventional Commits](https://www.conventionalcommits.org/) 格式：

| 类型 | 什么时候用 |
|------|-----------|
| `feat:` | 加了新东西 |
| `fix:` | 修了 bug |
| `docs:` | 改文档 |
| `style:` | 格式调整 |
| `refactor:` | 重构 |

## 改 SKILL.md 的注意事项

SKILL.md 是核心文件，改的时候注意：

- 维度描述要准确，不要加主观价值判断（不说哪种家长"好"或"坏"）
- 场景示例要真实，来源于生活观察，不要编
- 新增内容需同步更新中英文 README
- 经典语录要有辨识度，不要写太泛的话

## 开发流程

```
提 Issue 讨论 → 确认方案 → 实现 → Review → Merge
```

重大改动（比如新增维度、改诊断逻辑）先提 Issue 讨论，不要直接提 PR。

## 行为准则

看 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。简单说就是：尊重所有人，不要搞歧视和人身攻击。
