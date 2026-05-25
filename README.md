# Mathegenic Writing Coach / AI 促进中小学生写作教练

A QoderWork skill that guides parents, teachers, and learners to use AI as a writing scaffold — not a ghostwriter — based on Mathegenic principles.

一款基于 Mathegenic（促进学习生成）原则的 QoderWork Skill，引导家长、教师和学习者将 AI 用作写作脚手架，而非代笔者。

> **Mathegenic** means "learning-generative." The educational value of a tool is not measured by the output it produces, but by the new understanding, strategies, reflection, and capabilities it helps students develop.
>
> **Mathegenic** 意为"促进学习生成的"。一个工具的教育价值不在于它产出了什么，而在于它帮助学生产生了什么新的理解、策略、反思和能力。

---

## What This Skill Does / 本 Skill 功能

When a user asks about AI-assisted writing, this skill:

当用户询问 AI 辅助写作相关问题时，本 Skill 会：

1. **Diagnoses / 诊断** — the user's role (parent / teacher / student), the learner's writing development stage, and the specific goal. 用户的角色（家长/教师/学生）、学习者所处的写作发展阶段、以及具体目标。
2. **Matches / 匹配** — the need to the right output type: prompt cards, printable worksheets, workflow plans, or evaluation tools. 将需求匹配到正确的输出类型：提示词卡、可打印学习单、操作流程或评估工具。
3. **Generates / 生成** — ready-to-use materials that follow the core rule: **AI must not write for the student. AI should ask questions, give feedback, compare options, or check structure.** 生成可直接使用的材料，遵循核心原则：**AI 不得替学生写作文，而应该提问、给反馈、提供比较选项、或检查结构。**

---

## Core Principle: The Two U-Curves / 核心原理：两条 U 型曲线

This skill is built on the intersection of two U-shaped curves:

本 Skill 建立在两条 U 型曲线的交叉分析之上：

- **Writing Development U-Curve / 写作能力发展 U 型曲线**：Children start as intuitive storytellers, hit a "restructuring dip" around age 11 when they become aware of structure but can't yet organize it well, and eventually develop reflective writing ability. 儿童从直觉性讲故事者起步，约 11 岁时进入"重构低谷"——开始意识到结构但尚不能良好组织，最终发展出反思性写作能力。
- **AI Cognitive Offloading U-Curve / AI 认知卸载 U 型曲线**：Using no AI = moderate learning depth. Naive offloading (letting AI write everything) = learning crash. Strategic offloading (using AI for feedback, comparison, planning) = amplified thinking. 完全不用 AI = 中等学习深度；天真式卸载（让 AI 写一切）= 学习崩塌；策略性卸载（用 AI 做反馈、比较、规划）= 思维放大。

**The danger / 危险**：Students in the restructuring dip who let AI ghostwrite skip the very mental work that would let them use AI successfully later. 正在经历重构低谷的学生如果让 AI 代写，会跳过未来能够成功使用 AI 所必需的心智劳动。

**The opportunity / 机遇**：AI can become a "dialogue partner, scaffold, mirror, and sparring partner" that helps students cross the dip with support. AI 可以成为"对话者、脚手架、镜子和陪练"，帮助学生借助支架穿越低谷。

---

## File Structure / 文件结构

```
mathegenic-writing-coach/
├── SKILL.md          # Core logic: diagnosis → match → generate / 核心逻辑
├── reference.md      # Knowledge base: 18 prompts, 6 worksheets, 4 rubrics, textbook cases, talk scripts / 知识库
├── examples.md       # Three annotated scenarios: parent, teacher, textbook conversion / 示例集
└── README.md         # This file / 本文件
```

---

## Quick Start / 快速开始

### For Parents / 给家长

Your 11-year-old is staring at a blank page. Instead of saying "let AI write it," try this:

你 11 岁的孩子盯着空白纸发呆。不要说"让 AI 帮你写"，试试这样做：

1. Have them **draw a map** of the story world (5 min) / 让孩子**画一张故事地图**（5 分钟）
2. Use the **Question-Asker Prompt** (in `reference.md`, Prompt 1.9) with ChatGPT — AI asks one question at a time / 使用 `reference.md` 中的**提问式提示词**，让 AI 一次只问一个问题
3. Write **one section per day** — beginning today, middle tomorrow, end the day after / **一天只写一段**——今天写开头，明天写中间，后天写结尾

### For Teachers / 给教师

Converting a textbook text into an AI-scaffolded writing task:

将课文转化为 AI 支架写作任务：

1. Identify the text's **core writing mechanism** (perspective? route? contrast?) / 识别课文的**核心写作机制**（视角？路线？对比？）
2. Apply the **8-Scaffold Model** from the textbook case study in `reference.md` / 应用 `reference.md` 中的**八支架模型**
3. Use the **Process Portfolio** approach: students submit 6-8 materials, not just one essay / 使用**过程作品集**方式：学生提交 6-8 份材料，而非仅一篇作文

---

## The 8-Scaffold Model (Textbook Case Example) / 八支架模型（教材案例示例）

Applied to "A Drop of Water Passes Through Lijiang" / 应用于《一滴水经过丽江》：

| # | Scaffold / 支架 | Function / 功能 | AI Role / AI 角色 |
|---|----------------|----------------|------------------|
| 1 | Text Writing Discovery / 文本写法发现 | Deconstruct how the text works / 拆解文本的写作机制 | Question-asker / 提问者 |
| 2 | Perspective Generator / 视角生成器 | Generate 8 non-human narrator options / 生成 8 个非人称叙述视角 | Option generator / 选项生成器 |
| 3 | Route Design / 游踪路线设计 | Plan the spatial/emotional journey / 规划空间/情感旅程 | Structure coach / 结构教练 |
| 4 | Detail Amplifier / 景物细节放大 | Push from "it's beautiful" to sensory specifics / 从"很美"推进到感官细节 | Detail追问器 |
| 5 | Language Pattern Lab / 语言模式实验室 | Design sentence templates for imitation / 设计可仿写的句式模板 | Pattern demonstrator / 模式演示者 |
| 6 | Text Roaming Engine / 文字漫游引擎 | Walk through the designed space interactively / 互动式漫步于设计的空间 | Experience generator / 体验生成器 |
| 7 | Structure Mirror / 结构镜子 | Check logic, consistency, emotional arc / 检查逻辑、一致性、情感弧线 | Logic checker / 逻辑检查员 |
| 8 | Revision Explainer / 修改说明支架 | Document why changes were made / 记录为什么这样修改 | Meta-cognition trainer / 元认知训练器 |

---

## License / 许可

MIT License — feel free to use, adapt, and share. If you create additional textbook cases or project models, contributions are welcome.

MIT 许可证 — 可自由使用、改编和分享。如果你创建了更多教材案例或项目模型，欢迎贡献。

---

## Credits / 致谢

Built on Mathegenic learning theory, the Writing Development U-Curve, and the AI Cognitive Offloading U-Curve. Designed for parents, educators, and self-directed learners who believe that AI's educational value lies not in bypassing difficulty, but in helping students cross it with better scaffolding.

基于 Mathegenic 学习理论、写作能力发展 U 型曲线和 AI 认知卸载 U 型曲线构建。为相信 AI 的教育价值不在于绕过困难、而在于帮助学生借助更好的支架穿越困难的家长、教育工作者和自主学习者而设计。
