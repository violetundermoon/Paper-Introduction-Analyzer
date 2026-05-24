---
name: english-paper-introduction-analysis
description: 精读任何学科英文论文 Introduction，按自然段精确定位并分析整体结构、研究意义、研究内容、Gap、时态、功能句型、逻辑衔接和写作借鉴。
---

# 英文论文 Introduction 精读与写作结构分析

Use this skill when the user provides the original text of an English paper Introduction and asks for close reading, writing-structure analysis, gap analysis, tense analysis, functional sentence patterns, or help learning how to write an Introduction.

The response language should normally be Chinese. Quote short English fragments from the source Introduction to anchor each judgment.

## Scope

This skill applies to English paper Introductions in any discipline, including engineering, energy and environment, medicine and life sciences, materials, chemistry, physics, psychology, education, linguistics, social sciences, computer science, artificial intelligence, reviews, experiments, numerical simulations, and theoretical models.

The goal is not to summarize the paper content. The goal is to explain how the author performs Introduction-writing tasks:

- establishing background
- defining concepts or research objects
- explaining significance
- reviewing prior work
- identifying limitations
- formulating the research gap or question
- introducing the present study
- presenting the paper structure

## Input Handling

Before analysis, number the original Introduction by natural paragraphs:

- 第1段、第2段、第3段...
- If one paragraph is long, use finer labels such as 第1段开头, 第1段中部, 第1段后半部分, 第2段末尾.

Every claim must point back to a precise source location. Use formats such as:

- 第1段开头：“...”
- 第2段中部：“...”
- 第4段末尾：“...”
- 第5段：“From ... to ...”

Do not use vague references such as “文章前半部分” or “后面几段” when a more precise location can be given.

If the user does not provide the Introduction text, ask them to paste it first.

## Required Output

Always organize the final analysis with these eight sections.

### 1. 引言整体结构

Use a table:

| 结构层次 | 对应位置 | 主要内容 | 写作作用 |
| ---- | ---- | ---- | ---- |

Analyze the structure in a detailed but hierarchical way. Do not mechanically assign every sentence to a separate structure. Do not reduce everything to only “背景-不足-本文工作” if the original Introduction contains more nuanced steps.

Possible structure labels include:

- 研究背景与宏观意义
- 核心概念或研究对象界定
- 关键过程、机制或理论基础说明
- 已有研究方向概述
- 具体研究方法或技术路径综述
- 已有研究的贡献
- 已有研究的局限
- 研究空白或未解决问题
- 本文研究目的
- 本文方法或模型
- 本文分析内容或评价指标
- 本文创新点或理论贡献
- 文章结构安排

Adapt the labels to the actual paper rather than forcing all categories.

### 2. 研究意义

Use prose with numbered significance layers:

本文研究意义主要体现在以下几个方面。

第一，...
对应位置：第X段：“...”

第二，...
对应位置：第X段：“...”

第三，...
对应位置：第X段：“...”

总体来看，本文的研究意义不只是...，更在于...

Judge significance according to the paper, such as:

- 工程应用意义
- 理论意义
- 科学机理意义
- 方法学意义
- 模型改进意义
- 实验技术意义
- 数据或评价体系意义
- 现实社会意义
- 政策意义
- 临床意义
- 教育实践意义
- 环境与可持续发展意义

Do not write only “具有重要意义”. Explain why the study matters.

### 3. 研究内容

First identify where the research content appears:

本文研究内容主要集中在第X段：“...” 至 “...”

Then extract specific items:

1. 研究对象：...
2. 研究方法：...
3. 对比关系：...
4. 分析变量：...
5. 评价指标：...
6. 目标认识：...

If the original Introduction does not explicitly provide an item, say “原文未明确交代”.

Also summarize concrete tasks when possible:

- 作者建立、采用或设计了什么方法、模型、实验或框架
- 作者比较了哪些对象或条件
- 作者分析了哪些变量对哪些结果的影响
- 作者从什么角度解释机制
- 作者试图提供何种理论依据、方法支持或应用参考

### 4. 研究不足与 Gap

This is the most important section. Use a table:

| 已有研究基础 | 存在不足 | 不足带来的问题 | 本文回应方式 | 对应位置 |
| ------ | ---- | ------- | ------ | ---- |

Clearly separate:

- 已有研究做了什么
- 已有研究没做什么
- 已有研究为什么不够
- 这种不足会导致什么问题
- 本文如何回应这个不足

Common gap types include:

- 理论假设不足, such as over-simplified assumptions
- 方法能力不足, such as methods unable to capture key processes
- 尺度限制, such as temporal, spatial, sample, pore, or data-scale limits
- 变量考虑不充分, such as missing variables or missing coupled effects
- 结论不一致, such as controversial or inconsistent findings
- 应用场景不足, such as idealized scenarios or limited practical applicability

Do not merely say “缺少相关研究”. Explain what is missing and why it matters.

### 5. 时态使用

Use a table:

| 时态 | 对应位置 | 示例 | 使用原因 |
| -- | ---- | -- | ---- |

Include tense and voice choices where relevant:

- 一般现在时: facts, definitions, general mechanisms, current limitations, paper organization
- 现在完成时: accumulated prior research, recent trends, long-standing attention, transition from literature to gap
- 一般过去时: specific completed studies, specific models, specific experiments, completed work
- 被动语态: foregrounding methods, objects, results, and scientific objectivity
- 情态动词: possibility, necessity, research needs, cautious claims

After the table, add a short paragraph:

需要注意的语言问题包括...

Check, when relevant:

- 主谓一致
- 时态是否前后混乱
- research/studies 单复数
- redundant expressions such as “could be typically classified”
- data is/are consistency
- effect/affect
- due to/owing to/because
- compare with/compare to

Only flag actual or likely issues visible in the provided text.

### 6. 功能性句型

Use a table:

| 功能 | 对应位置 | 原文句型 | 写作作用 | 可迁移模板 |
| -- | ---- | ---- | ---- | ----- |

For each sentence pattern, explain why it appears there and how the user can reuse it.

Common functional patterns include:

- 引出研究背景: “X has attracted increasing attention due to...”
- 强调现实需求: “With the increasing demand for...”
- 定义核心概念: “X refers to...”
- 分类说明: “X can be classified into...”
- 从理想情况转向实际问题: “However, under practical conditions...”
- 描述机理过程: “The coupled effects of A and B lead to...”
- 总结已有研究方向: “Previous studies have mainly focused on...”
- 介绍具体文献: “Author et al. developed...”
- 对比不同方法: “Compared with..., ...”
- 指出方法局限: “However, these methods are limited in...”
- 提出研究空白: “The role of X remains unclear.”
- 说明不足后果: “As a consequence, ...”
- 提出研究必要性: “Therefore, it is necessary to...”
- 引出本文工作: “In this study, a ... was developed to...”
- 说明研究路径: “By analyzing..., ...”
- 强调贡献: “The results provide new insights into...”
- 介绍文章结构: “The remainder of this paper is organized as follows.”

Create transferable templates based on the actual sentence, not only generic templates.

### 7. 逻辑衔接分析

Begin with:

这篇引言的逻辑链条可以概括为：

...

Then explain paragraph transitions:

- 第1段到第2段的衔接是...
- 第2段到第3段的转折是...
- 第X段到第X段存在的问题是...

Focus on:

- how the author moves from background to problem
- how prior research leads to limitations
- how limitations lead to the present work
- whether there are jumps, repetitions, late gaps, or excessive literature listing

### 8. 简要评价与写作借鉴

Include:

1. 整体评价: explain the Introduction's overall logic and central thread.
2. 优点: state specifically where it is strong, such as focused background, clear concept definition, layered literature review, explicit gap, concrete research content.
3. 不足: state specifically where it is weak, such as overlong background, literature listing, late or weak gap, vague contribution, overlong paper-structure paragraph, tense or grammar issues.
4. 写作借鉴: give concrete expressions or moves the user can transfer to their own writing.

Possible borrowing points:

- using “However, under actual/practical conditions...” to shift from idealized background to real problems
- using “As a consequence...” to explain why a gap matters
- using “Therefore, it is necessary to develop...” to introduce the research need
- using “In this study...” to state model, comparison objects, evaluation metrics, and variables

## Execution Requirements

Follow these rules strictly:

1. Every judgment must return to the original text location.
2. Structure analysis must be detailed but not mechanically sentence-by-sentence.
3. Research significance must be layered and specific.
4. Research content must extract concrete methods, objects, variables, metrics, and aims.
5. Gap analysis must explain “已有研究做了什么-不足是什么-为什么重要-本文如何回应”.
6. Tense analysis must explain why each tense is used.
7. Functional sentence analysis must explain what each sentence accomplishes in the Introduction.
8. The final section must provide writing lessons the user can transfer to their own paper.
9. Do not limit analysis to one discipline. Adapt to the user's source text.
10. If the Introduction logic is weak, say so directly instead of beautifying it.
