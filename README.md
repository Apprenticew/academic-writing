# ✍️ Academic Writing

**English** | [简体中文](README.zh-CN.md)

- 🛡️ **Tired of AI weakening your contribution with unnecessary caveats and preemptive justifications?**

- 🔗 **Does every sentence make sense on its own, yet the paragraph leaves you wondering how the ideas connect and what matters most?**

- 🖋️ **Asking for natural academic prose, only to get awkward phrasing and summaries that sound like casual conversation?**

- 🧭 **Have you done the experiments, yet your paper still reads like a progress report that leaves the central insight buried?**

**Academic Writing** is a skill for guiding AI-assisted paper revision around your choices. It asks what you want to improve and whether you prefer light edits or substantial revision, then addresses those concerns while preserving passages that already work.

## 🚀 Prompt guide

In Codex or a web-based AI assistant that can read GitHub content, start with one of the prompts below.

### ⚡ Quick start

> Use https://github.com/Apprenticew/academic-writing to help revise my paper.

The assistant should read the repository's `SKILL.md`, follow its workflow to ask for your choices, and use the relevant reference files. **Only “Reduce defensive language” is suggested initially. Before reading or editing the manuscript, it asks you to confirm or change the selection and choose light edits or substantial revision.**

### 🎯 Choose a focus

> Read SKILL.md in https://github.com/Apprenticew/academic-writing and make light edits to improve logical flow in Section 2 only. Preserve the paragraph structure and the connective words and clauses that help readers follow the argument.

### 🧭 Allow broader revision

> Read SKILL.md in https://github.com/Apprenticew/academic-writing and focus on the introduction's research story and structure. Substantial revision, including reordering and rewriting paragraphs that need work, is welcome. Leave the other sections unchanged.

Clear choices carry forward without repeated questions or added default options. You can provide the manuscript with your request or after confirming your choices.

Using the link supplies guidance for the current conversation. For repeated use in Codex, see the installation instructions below. If your assistant cannot read the repository, download it and attach `SKILL.md` and the files in `references/`.

**Start with a passage you want to improve, choose your focus, and give it a try.**

## 🎯 What would you like to improve?

| Option | Focus |
|---|---|
| 🛡️ **1. Reduce defensive language** | Reduce unnecessary self-deprecation, preemptive justifications, and defensive framing. |
| 🔗 **2. Improve logical flow** | Improve transitions, connective wording, emphasis, and connections between sentences and paragraphs. |
| 🖋️ **3. Refine academic expression** | Refine awkward or colloquial wording using natural disciplinary language. |
| 🧭 **4. Develop the research story and structure** | Clarify the central insight and contribution, and connect experiments, concepts, and sections into a coherent argument. |

You can combine options or choose only another focus; reducing defensive language is also your choice.

## 🎛️ You decide how much changes

- **Light edits:** Keep the existing story, section structure, and effective sentences, making local changes where needed.
- **Substantial revision:** Rework passages within your chosen focus; you decide whether that includes reshaping the story, repositioning contributions, or reorganizing sections.

When the revision extent is unclear and affects the approach, the skill asks first. Even when reviewing the whole paper, it edits only passages that need work within your chosen focus and preserves effective writing elsewhere.

Where revision is needed, the skill encourages retaining and adding meaningful transitions, connective words, adverbs, and subordinate clauses so human readers can follow causes, contrasts, purposes, and conditions. It favors complete, connected sentences over short, isolated statements and allows more words when they help explain the relationship.

## 📦 Use regularly in Codex

Place this repository's contents in a folder named `academic-writing` under your project's `.agents/skills/` or your personal `~/.agents/skills/` directory. For a project installation, the entry file should be `.agents/skills/academic-writing/SKILL.md`. See the [official skill documentation](https://learn.chatgpt.com/docs/build-skills) for installation and discovery details.

Once installed, invoke it with:

> Use $academic-writing to help revise my paper. First ask me to choose the focus and revision extent.

The skill instructions are written in Chinese and support discussion and revision of Chinese and English manuscripts.

## 📚 Writing references

- [Jennifer Widom — Tips for Writing Technical Papers](https://cs.stanford.edu/people/widom/paper-writing.html#abstract)

  Guidance on the roles of abstracts, introductions, and other paper sections.

- [Dan Fu — How I Structure Introductions to Research Papers](https://danfu.org/notes/25-01-07-intro-bullets/)

  A five-question approach to outlining an introduction, illustrated with a research paper.

[Reference notes](references/writing-guides.md) summarize how these articles help organize ideas and check coverage; the manuscript and venue determine the final paragraph structure and contribution format.

## 📄 License

This repository is distributed under the [MIT License](LICENSE). Copyright © 2026 Honghan Wang. Linked reference articles remain subject to their respective authors' rights and terms.
