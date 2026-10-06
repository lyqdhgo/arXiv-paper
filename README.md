<div align="center">

# 📄 arXiv-paper

**AI 方向的 arXiv 论文阅读与要点归档**

![arXiv](https://img.shields.io/badge/arXiv-cs.AI%20%7C%20cs.CL%20%7C%20cs.LG-B31B1B?style=flat-square&logo=arxiv&logoColor=white)
![Notes](https://img.shields.io/badge/形式-阅读笔记%20%7C%20速览%20%7C%20复现记录-4D6BFE?style=flat-square)
![Status](https://img.shields.io/badge/状态-持续更新中-yellow?style=flat-square)

[怎么记](#怎么记) · [笔记索引](#笔记索引) · [速览模板](#速览模板) · [推荐论文源](#推荐论文源)

</div>

---

## 这个仓库是什么

把读过的 AI 论文按主题整理成**可检索的短笔记**：这篇解决什么问题、核心方法是什么、和已有工作差在哪、对我自己的 RAG / Agent 项目有什么可借鉴的。

不以「读完就忘」为目的，所以每篇笔记都强制回答四个问题（见下面的模板）。

> 📌 本仓库正在建设中，笔记会持续补充。

---

## 怎么记

每篇论文一个 Markdown 文件，命名 `年份-会议-短标题.md`，例如：

```
2024-NeurIPS-SelfRAG.md
2025-ACL-Adaptive-Retrieval.md
```

放在按主题分的目录下：

```
arXiv-paper/
├── rag/                检索增强生成
├── agent/              智能体 · 工具调用 · 规划
├── llm-training/       预训练 · 微调 · 对齐
├── evaluation/         评测 · 基准 · 幻觉检测
└── README.md
```

---

## 笔记索引

| 主题 | 论文 | 一句话结论 | 日期 |
| --- | --- | --- | --- |
| — | _待补充_ | — | — |

---

## 速览模板

复制下面这段开一篇新笔记。**四个问题答不上来，说明还没读懂。**

```markdown
# 论文标题

- **arXiv**：https://arxiv.org/abs/xxxx.xxxxx
- **会议 / 年份**：
- **代码**：

## 1. 解决什么问题
（一句话。它针对的是现有方法的哪个具体缺陷？）

## 2. 核心方法
（两三句话 + 关键公式或结构图。不要抄摘要。）

## 3. 和已有工作的差别
（对比表或几句话：它改了什么、为什么这样改会更好。）

## 4. 对我在做的项目有什么用
（能落到某个具体项目里的点。落不了地就直说"暂时用不上"。）

## 疑问 / 没读懂的地方
```

---

## 推荐论文源

- [arXiv cs.AI](https://arxiv.org/list/cs.AI/recent) · [cs.CL](https://arxiv.org/list/cs.CL/recent) · [cs.LG](https://arxiv.org/list/cs.LG/recent)
- [Papers with Code](https://paperswithcode.com/) —— 找带实现的论文
- [Hugging Face Daily Papers](https://huggingface.co/papers) —— 每天的热门论文
- [alphaXiv](https://www.alphaxiv.org/) —— 带讨论的 arXiv 阅读界面

---

<div align="center">

<sub>读一篇，记一篇 · 让读过的东西能被检索</sub>

</div>
