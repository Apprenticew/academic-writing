# ✍️ Academic Writing · 学术论文写作

- 🛡️ **还在为 AI 反复添加无谓的自我辩解、把贡献越写越弱而头疼？**  
  Tired of AI weakening your contribution with unnecessary caveats and preemptive justifications?

- 🔗 **每句话单看都懂，连起来却缺少逻辑，读完仍不知道重点在哪里？**  
  Does every sentence make sense on its own, yet the paragraph leaves you wondering how the ideas connect and what matters most?

- 🖋️ **明明想要专业、自然的论文表达，得到的却是生硬搭配和口语化总结？**  
  Asking for natural academic prose, only to get awkward phrasing and summaries that sound like casual conversation?

- 🧭 **实验做了不少，论文却像工作汇报，读者依然看不出你究竟发现了什么？**  
  Have you done the experiments, yet your paper still reads like a progress report that leaves the central insight buried?

**Academic Writing** 将这些困扰整理成四类可选的修改方向。你决定重点改什么、改动多大，再让 AI 针对问题动笔，让文章的逻辑、表达和研究价值更清楚。

**Academic Writing** offers four focused ways to improve an AI-assisted draft. Choose what needs work and how far to revise, then use the skill to make your reasoning, language, and contribution clearer.

**Language / 语言：** This README is bilingual. The skill instructions are written in Chinese and support discussion and revision of Chinese and English manuscripts.

本 README 为中英文对照说明；skill 指令以中文编写，可用于中英文稿件的写作讨论与修订。

## 🎯 Choose a focus · 选择修改重点

| Option | 功能 | Focus / 重点 |
|---|---|---|
| 1. Defensive language | 减弱防御性写作 | Reduce unnecessary self-deprecation and preemptive justifications. / 减少无必要的自我削弱、预先辩解和防御性铺垫。 |
| 2. Logical flow | 改善逻辑关联 | Improve transitions, emphasis, and connections between sentences and paragraphs. / 改善句段承接、连接词、副词、重音和前后呼应。 |
| 3. Academic expression | 改善词语与学术表达 | Refine awkward or colloquial wording using natural disciplinary language. / 改善生硬、口语化的措辞和搭配，使用自然的领域表达。 |
| 4. Research story and structure | 改善故事与篇章组织 | Clarify contributions, the role of experiments, and the progression of concepts and sections. / 改善贡献表达、实验叙述、概念顺序与章节组织。 |

If the focus is unspecified, the skill presents these four options before reading the manuscript and waits for the author's selection. Multiple options can be combined. A clear existing request does not need to go through the menu again.

未说明修改重点时，skill 先展示这四项，收到作者选择后再读稿；可以多选。已有明确要求时，直接沿用，不重复询问。

Each option is applied only when selected, including defensive language. No editing category is enabled by default. Clear, effective passages stay intact; reviewing the whole paper does not mean rewriting every paragraph.

四项均只在选中后处理，包括防御性写作。不设置默认必改项；已有清楚、有效的表达应保留，全文检查不意味着每段都要改写。

Where revision is needed, the skill encourages explicit transitions, connective words, adverbs, and clauses that help human readers follow the argument. It favors complete, connected sentences and preserves the context and emphasis readers need, even when this takes a few more words.

在需要修改的位置，鼓励充分使用过渡语、连接词、副词、从句和状语从句，帮助人类读者理解关系、把握重点。保留有始有终的完整表达，避免短促、孤立的单句；为说明关系而适当增加字数是允许的。

## 🚀 Usage · 使用

Provide the manuscript or research materials and describe the task, including any constraints on structure, length, or editing scope. In Codex, invoke the skill with `$academic-writing`.

提供相关稿件或研究材料，并说明任务及结构、篇幅、修改范围等要求。在 Codex 中可使用 `$academic-writing` 调用。

### Polish a paragraph · 段落润色

> Use $academic-writing to polish the following English paragraph. Preserve its scientific meaning and information order while improving transitions, emphasis, and natural phrasing.

> 使用 $academic-writing 润色以下英文段落。保留科学含义与信息顺序，改善衔接、重点表达和自然程度。

### Draft an introduction · 引言起草

> Use $academic-writing to outline an introduction from the research materials. Explain why the problem matters, what makes it interesting and difficult, and the key idea, then draft the introduction in English.

> 使用 $academic-writing 根据研究材料设计引言提纲，说明问题的重要性、值得追问之处、技术困难和关键思路，再起草英文引言。

### Improve the research story · 故事诊断

> Use $academic-writing to identify the central insight readers should remember. Find where the manuscript feels flat or disconnected, and suggest specific improvements to the contribution statements and progression between sections.

> 使用 $academic-writing 阅读稿件，提炼最值得读者记住的核心认识，分析当前故事哪里平淡或割裂，给出贡献表达与章节推进的具体改法。

Choose light edits or more substantial revision when the extent is unclear and would affect the approach. Reviewing the whole manuscript does not automatically mean applying every option or restructuring the paper.

改动幅度尚未明确且会影响改法时，再选择小改或大改。全文修订只表示覆盖范围，不自动启用全部功能或重构文章。

Length limits, established structure, and previous feedback guide the selected work; they are not additional default workflows.

篇幅要求、已认可的结构和历史反馈作为修订约束处理，不另设默认执行的流程。

## 📦 Installation · 安装

Place this repository's contents in a folder named `academic-writing` under either your project's `.agents/skills/` directory or your personal `~/.agents/skills/` directory. For a project installation, the entry file should be `.agents/skills/academic-writing/SKILL.md`.

将本仓库内容放入名为 `academic-writing` 的文件夹，再将该文件夹放到项目的 `.agents/skills/` 或个人的 `~/.agents/skills/` 目录下。项目安装后的入口应为 `.agents/skills/academic-writing/SKILL.md`。

See the [official skill documentation / 官方技能文档](https://learn.chatgpt.com/docs/build-skills) for discovery and invocation details.

## 🗂️ Repository layout · 仓库结构

```text
academic-writing/
├── README.md
├── LICENSE
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── storycraft.md
    ├── sections.md
    ├── language.md
    ├── writing-guides.md
    └── revision-review.md
```

`README.md` is documentation for repository visitors, and `LICENSE` states the reuse terms. The skill's writing instructions are in [SKILL.md](SKILL.md) and the relevant files in `references/`; `agents/openai.yaml` provides display and invocation metadata.

`README.md` 面向仓库读者，`LICENSE` 说明使用许可；skill 的写作指令保存在 [SKILL.md](SKILL.md) 和 `references/` 的相关文件中，`agents/openai.yaml` 提供展示与调用信息。

[SKILL.md](SKILL.md) selects references according to the task. [Repeated revision guidance](references/revision-review.md) helps revisit original feedback when the same problems persist across revisions.

[SKILL.md](SKILL.md) 根据任务选择相关指导；同类问题在多轮修改中反复出现时，[多轮修订](references/revision-review.md)帮助回看原始意见并定位尚未解决的问题。

## 📚 Writing references · 写作参考

- [Jennifer Widom — Tips for Writing Technical Papers](https://cs.stanford.edu/people/widom/paper-writing.html#abstract)

  Guidance on the roles of abstracts, introductions, and other paper sections.

  关于摘要、引言及论文各部分内容职责的写作建议。

- [Dan Fu — How I Structure Introductions to Research Papers](https://danfu.org/notes/25-01-07-intro-bullets/)

  A five-question approach to outlining an introduction, illustrated with a research paper.

  通过五个问题组织引言思路，并以具体论文解释其应用。

[Reference notes](references/writing-guides.md) summarize how these articles inform the skill. The questions guide content and organization; the manuscript and venue determine the final paragraph structure and contribution format.

[参考资料说明](references/writing-guides.md)概括两篇文章的用途。五个问题用于检查内容和组织思路，成稿的段落数与贡献形式由论文需要及投稿规范决定。

## 📄 License · 许可

This repository is distributed under the [MIT License](LICENSE). Copyright © 2026 Honghan Wang.

本仓库采用 [MIT 许可证](LICENSE)。Copyright © 2026 Honghan Wang。

Linked reference articles remain subject to their respective authors' rights and terms.

链接指向的参考文章仍适用各自作者的版权与许可条款。
