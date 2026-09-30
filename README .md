# First Agent Lab

> A beginner-friendly classroom Skill for helping university students build their first simple AI Agent — before learning the theory.

**First Agent Lab** 是一套面向零基础大学生的游戏化 Agent 入门 Skill，适用于《计算与人工智能概论》、AI 通识课、计算思维导入课。

核心理念：

> **先体验，再命名；先做出来，再解释为什么。**

学生不需要先理解 Goal、Workflow、Tools、Human-in-the-loop 等术语，而是先亲手“训练”一个 AI 小助手：完成真实任务、故意让它翻车、再给它加规则，最后才理解“原来这就是 Agent”。

---

## Why First Agent Lab?

很多零基础学生第一次接触 Agent 时，会觉得它是“更厉害的 ChatGPT”“很复杂的 AI 框架”或“需要编程才能做”。

First Agent Lab 不从定义开始，而是让学生先经历：

**任务 → 路线 → 技能 → 命名 → 实战 → 翻车 → 修改 → 理解 Agent**

目标不是“听懂 Agent”，而是：

> **我自己做过一个 Agent。**

---

## Classroom Mission

### 30 分钟造一个替你干活的 AI

课堂开始时，学生只需要回答：

> 如果现在有一个 AI 实习生，你最想让它替你干掉哪件麻烦事？

例如：整理 PPT、提取班群通知、背单词、安排作业、检查代码、解释文章、帮忙做选择，或任何自己的想法。

---

## Learning Flow

```text
LEVEL 1  我最想偷懒什么？
        ↓
LEVEL 2  教 AI 怎么帮我
        ↓
LEVEL 3  给 AI 装 3 个技能
        ↓
BONUS    给它起个名字
        ↓
LEVEL 4  第一次上岗
        ↓
LEVEL 5  想办法整它一下
        ↓
给它加一条新规则
        ↓
MISSION COMPLETE
原来这就是 Agent
        ↓
My First Agent Card
```

---

## What Students Learn

| 学生刚才做的事 | 最后揭晓的概念 |
|---|---|
| 我想让它干什么 | Goal |
| 我给它什么 | Input |
| 先做 A，再做 B | Workflow |
| 给它搜索 / 阅读 / 检查能力 | Tools |
| 不确定的时候先问我 | Human-in-the-loop |
| 故意让它翻车 | Testing |
| 给它加一条新规则 | Iteration |

学生第一次看到这些术语时，会产生一种重要的感觉：

> “原来这个我刚才已经做过了。”

---

## Skill Cards

学生最多只能给自己的 Agent 安装 **3 个能力**：

- 搜索
- 阅读
- 看图
- 总结
- 出题
- 检查
- 追问
- 比较
- 规划
- 记偏好

限制为 3 个，是为了让学生理解：

> **Agent 的能力应该围绕任务设计，而不是“什么都会”才最好。**

---

## Beginner-friendly Design

如果学生不知道“流程怎么拆”，Skill 不会直接替学生定稿，而是提供两个版本：

```text
路线 A：极简版
2–3 个步骤

路线 B：完整版
4–6 个步骤
```

例如 PPT 复习助手：

```text
路线 A
PPT → 总结重点 → 出题

路线 B
PPT → 找知识点 → 解释重点 → 出题 → 学生回答 → 检查错题
```

学生自己选择或修改。

---

## The Fun Part: Break Your Agent

第一次测试结束后，学生的任务不是继续夸 AI，而是：

> **想办法让它翻车一次。**

可以尝试少给信息、说得模糊、给乱材料、加奇怪要求、故意放错误信息。

测试后，学生必须自己给 Agent 增加至少一条规则，例如：

> 不知道就先问我，不允许乱猜。

> 重要结论必须告诉我依据。

> 做完后先自查一遍再交给我。

这一步把 AI 局限、测试、调试、人类监督变成了一次实际体验。

---

## Final Output

每位学生最终会得到一张 **My First Agent Card**，其中包含：

- Agent 名字
- 它替我干什么
- 我给它什么
- 工作路线
- 安装的 3 个技能
- 第一次实战
- 它最笨的地方
- 新增规则
- 学生自己对 Agent 的理解

可用于课堂展示、截图提交、学习档案和课程反思。

---

## Repository Structure

```text
first-agent-lab/
├── README.md
├── SKILL.md
├── references/
│   └── agent-ideas.md
└── templates/
    └── agent-card.html
```

`SKILL.md`：核心课堂流程与行为规则。  
`references/agent-ideas.md`：学生卡住时的选题与路线灵感。  
`templates/agent-card.html`：最终 Agent Card 的 HTML 模板。

---

## How to Use

教师将整个仓库安装到支持 Skill 的 Agent 环境中，然后让学生启动：

```text
使用 first-agent-lab
```

或者：

```text
我想做我的第一个 Agent
```

学生不需要会编程、写 Prompt 工程、调用 API、理解 Agent 框架，也不需要部署 App。

---

## Suggested Class Time

```text
LEVEL 1    3–5 min
LEVEL 2    5–8 min
LEVEL 3    3–5 min
BONUS      1–2 min
LEVEL 4    8–15 min
LEVEL 5    5–10 min
总结        5 min
```

总计约 **30–45 分钟**。

---

## Teaching Philosophy

First Agent Lab 不追求学生第一节课就理解复杂 Agent 架构。

它只关注三件事：

1. 学生有没有亲手完成一个真实任务？
2. 学生有没有发现 AI 会犯错？
3. 学生能不能自己说出 Agent 和普通聊天 AI 的区别？

如果这三件事发生了，第一节 Agent 课就已经成功。

---

## Version

Current version: `v1.1`

V1.1 主要改进：

- 增加“极简版 / 完整版”路线二选一
- 技能改为卡片式选择，每人最多 3 个
- 增加 Agent 命名环节
- 最终输出升级为 My First Agent Card

---

## Course Context

本项目最初设计用于大学课程：

**《计算与人工智能概论》**

目标不是把课程变成“教学生玩 ChatGPT”，而是通过一次真实 Agent 体验，让学生第一次感受到：

> **计算思维、AI、人机协作和任务流程设计，其实可以变成一个真正会工作的东西。**
