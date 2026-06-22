---
name: academic-writing-bank
slug: academic-writing-bank
version: 1.0.0
displayName: 学术写作语料库
summary: 学术论文写作的章节模板、短语库与过渡词体系，解决"每个段落怎么写、用什么词"的核心问题。
description: >
  学术写作语料库（Academic Writing Bank）—— 中英文学术论文写作的全流程语料与模板引擎。
  
  提供三大核心能力：
  1. **章节写作模板**：覆盖引言至结论共8章的段落骨架模板，用 {{PLACEHOLDER}} 标记填充位置
  2. **学术短语库**：6大功能类（立论/承转/定义/举证/对比/结论）中英双语学术短语，每条标注适用章节与正式程度
  3. **过渡词体系**：100+学术过渡词，按逻辑功能分类（因果/递进/转折/并列/总结/举例/强调），附使用频率建议
  
  另含中文学术写作规范（第一人称、语态、数字单位）及常见错误避坑指南。

  触发词（中）：学术写作、论文写作、章节模板、学术短语、过渡词、论文句式、学术表达、论文用语、写作规范、论文结构、段落骨架、怎么写论文
  触发词（英）：academic writing, thesis writing, chapter template, academic phrase, transition words, academic expression, paper structure, writing bank, paragraph skeleton, scholarly writing
  
  与已有技能的关系：
  - 本技能是「写作工具箱」—— 解决"怎么写"（What to write and how to phrase it）
  - `writing-polish` / `humanizer-zh` 解决"写好后怎么改"（How to polish and de-AI-ify）
  - `academic-writing` 提供通用学术写作框架，本技能在其基础上补充短语库与模板引擎
  - `academic-writing-refiner` 侧重CS顶会论文润色，本技能面向泛学术领域的中英文论文
---

# 学术写作语料库（Academic Writing Bank）

## 技能概述

本技能是学术论文写作的语料库与模板引擎，为论文撰写提供从"段落结构"到"遣词造句"的完整支持。无论你是初次撰写学术论文，还是希望提升学术表达的规范性和多样性，本技能都能提供即查即用的语料资源。

## 快速导航

| 资源 | 说明 | 路径 |
|------|------|------|
| 章节模板 | 论文8章段落骨架与常用句式 | [chapter-templates.md](references/chapter-templates.md) |
| 学术短语库 | 6类功能短语（中英双语） | [phrase-bank.md](references/phrase-bank.md) |
| 过渡词库 | 100+过渡词，按逻辑功能分类 | [transition-library.md](references/transition-library.md) |
| 中文规范 | 中文学术写作特有规范 | [chinese-conventions.md](references/chinese-conventions.md) |
| 常见错误 | 各章高频错误与修改建议 | [common-pitfalls.md](references/common-pitfalls.md) |

## 核心能力

| 能力 | 覆盖范围 | 使用场景 |
|------|----------|----------|
| 章节模板引擎 | 引言→结论8章，每章3-5个段落骨架 | 规划论文结构、填充章节内容 |
| 学术短语库 | 6大功能类 × 10-15条双语短语 | 替换平庸表达、提升学术语感 |
| 过渡词体系 | 7大逻辑类别 × 100+过渡词 | 段落衔接、逻辑连贯性优化 |
| 中文写作规范 | 人称/语态/数字/图表/混排 | 中文学术论文规范自查 |
| 避坑指南 | 各章8类高频错误 | 初稿自查、导师反馈前的修改 |

## 触发词

**中文**：学术写作、论文写作、章节模板、学术短语、过渡词、论文句式、学术表达、论文用语、写作规范、论文结构、段落骨架、怎么写论文、论文初稿、论文润色前的准备

**英文**：academic writing, thesis writing, chapter template, academic phrase, transition words, academic expression, paper structure, writing bank, paragraph skeleton, scholarly writing

## 与已有技能的关系

```
你的需求                         适用技能
─────────────                   ─────────
"这章不知道怎么写"    ──────→   academic-writing-bank（本技能）— 提供模板和句式
"写好了但读起来很AI"   ──────→   humanizer-zh — 去除AI痕迹
"英文论文想润色"     ──────→   writing-polish — 通用润色
"CS顶会论文需要专门润色" ────→   academic-writing-refiner — 专业润色
"整体学术写作框架不了解" ────→   academic-writing — 通用框架指导
```

- **本技能** = 写作工具箱（模板 + 短语 + 过渡词），解决 **"写什么、怎么写"**
- **humanizer-zh / writing-polish** = 润色工具，解决 **"写好后怎么改"**
- **academic-writing / academic-writing-refiner** = 框架与领域润色，互补使用

## 使用方式

1. **开始写作前**：先查阅 [chapter-templates.md](references/chapter-templates.md) 规划各章骨架
2. **写作过程中**：打开 [phrase-bank.md](references/phrase-bank.md) 和 [transition-library.md](references/transition-library.md) 作为侧边参考，随时替换平庸表达
3. **初稿完成后**：对照 [common-pitfalls.md](references/common-pitfalls.md) 逐章自查
4. **中文论文**：额外查阅 [chinese-conventions.md](references/chinese-conventions.md) 规范细节
