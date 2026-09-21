# Academic Writing · 学术论文写作

An academic writing skill for shaping research stories, highlighting contributions, and refining scholarly prose.

面向研究者的学术论文写作技能：围绕核心贡献组织故事，改善篇章衔接，并以专业、有重点的语言呈现研究价值。

Start with what readers should remember, then organize the problem, key ideas, experiments, and findings so that each section advances their understanding.

从读者应当记住的认识出发，安排问题、关键思路、实验与发现，使每一节推进理解，让摘要、引言和讨论充分表达工作的意义。

**Language / 语言：** This README is bilingual. The skill instructions are written in Chinese and support discussion and revision of Chinese and English manuscripts.

本 README 为中英文对照说明；skill 指令以中文编写，可用于中英文稿件的写作讨论与修订。

## What it helps with · 适用任务

| Task | 任务 | Focus / 重点 |
|---|---|---|
| Research story and contributions | 故事与贡献提炼 | Clarify the central insight and its significance. / 提炼核心认识，突出重要性与独特价值。 |
| Drafting and section revision | 论文起草与章节改写 | Organize abstracts, introductions, results, discussions, and related work. / 组织摘要、引言、结果、讨论与相关工作。 |
| Logic and academic language | 逻辑与语言精修 | Improve conceptual order, transitions, emphasis, and terminology. / 改善概念顺序、句间关系、重点表达与术语一致性。 |
| Revision from feedback | 写作意见落实 | Apply feedback to the relevant passages within the requested scope. / 在指定范围内，将反馈落实到相关段落。 |
| Repeated revision | 多轮修订 | Revisit recurring feedback and address unresolved reading difficulties. / 回看重复反馈，解决尚未消除的阅读障碍。 |
| Concision | 篇幅压缩 | Remove repetition while preserving useful context and transitions. / 减少重复，保留必要上下文与承接。 |

## Usage · 使用

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

Adapt phrasing to the author's requirements and the manuscript's style.

具体句式和措辞按作者要求与稿件风格调整。

## Installation · 安装

Place this repository's contents in a folder named `academic-writing` under either your project's `.agents/skills/` directory or your personal `~/.agents/skills/` directory. For a project installation, the entry file should be `.agents/skills/academic-writing/SKILL.md`.

将本仓库内容放入名为 `academic-writing` 的文件夹，再将该文件夹放到项目的 `.agents/skills/` 或个人的 `~/.agents/skills/` 目录下。项目安装后的入口应为 `.agents/skills/academic-writing/SKILL.md`。

See the [official skill documentation / 官方技能文档](https://learn.chatgpt.com/docs/build-skills) for discovery and invocation details.

## Repository layout · 仓库结构

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

## Writing references · 写作参考

- [Jennifer Widom — Tips for Writing Technical Papers](https://cs.stanford.edu/people/widom/paper-writing.html#abstract)

  Guidance on the roles of abstracts, introductions, and other paper sections.

  关于摘要、引言及论文各部分内容职责的写作建议。

- [Dan Fu — How I Structure Introductions to Research Papers](https://danfu.org/notes/25-01-07-intro-bullets/)

  A five-question approach to outlining an introduction, illustrated with a research paper.

  通过五个问题组织引言思路，并以具体论文解释其应用。

[Reference notes](references/writing-guides.md) summarize how these articles inform the skill. The questions guide content and organization; the manuscript and venue determine the final paragraph structure and contribution format.

[参考资料说明](references/writing-guides.md)概括两篇文章的用途。五个问题用于检查内容和组织思路，成稿的段落数与贡献形式由论文需要及投稿规范决定。

## License · 许可

This repository is distributed under the [MIT License](LICENSE). Copyright © 2026 Honghan Wang.

本仓库采用 [MIT 许可证](LICENSE)。Copyright © 2026 Honghan Wang。

Linked reference articles remain subject to their respective authors' rights and terms.

链接指向的参考文章仍适用各自作者的版权与许可条款。
