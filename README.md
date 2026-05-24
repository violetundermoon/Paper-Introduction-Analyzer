# Paper Introduction Analyzer

一个用于 Codex 的本地 skill 插件，面向英文论文 Introduction 的精读与写作结构分析。插件会用中文输出分析结果，重点拆解作者如何建立研究背景、提出研究意义、梳理已有研究、指出 research gap、引出本文工作，并提炼可迁移到自己论文写作中的句型和结构方法。

## 功能

- 按自然段编号并精确定位原文依据
- 分析 Introduction 的整体写作结构
- 分层提取研究意义
- 拆解研究内容、研究对象、方法、变量和评价指标
- 识别已有研究基础、研究不足、gap 及本文回应方式
- 分析时态、语态和情态动词的写作功能
- 提炼功能性句型和可迁移模板
- 分析段落之间的逻辑衔接
- 给出简要评价和写作借鉴

## 适用范围

适用于任何学科英文论文的 Introduction，包括但不限于：

- 工程技术
- 能源与环境
- 医学与生命科学
- 材料、化学、物理
- 心理学、教育学、语言学、社会科学
- 计算机科学与人工智能
- 综述类、实验类、数值模拟类、理论模型类论文

## 插件结构

```text
paper-introduction-analyzer/
├─ .codex-plugin/
│  └─ plugin.json
└─ skills/
   └─ english-paper-introduction-analysis/
      └─ SKILL.md
```

## 使用方式

在 Codex 中启用该插件后，直接粘贴英文论文 Introduction，并提出类似请求：

```text
请使用英文论文 Introduction 精读与写作结构分析 skill，分析下面这段引言。
```

或者：

```text
帮我拆解这篇 Introduction 的结构、研究意义、gap、时态和功能句型。
```

## 输出框架

插件会按照以下八个部分输出：

1. 引言整体结构
2. 研究意义
3. 研究内容
4. 研究不足与 Gap
5. 时态使用
6. 功能性句型
7. 逻辑衔接分析
8. 简要评价与写作借鉴

## 本地安装思路

如果手动安装，可以将本仓库作为插件目录放入 Codex 的本地插件位置，确保保留 `.codex-plugin/plugin.json` 和 `skills/` 目录。

Windows 示例：

```powershell
git clone https://github.com/violetundermoon/Paper-Introduction-Analyzer.git "$env:USERPROFILE\.codex\plugins\local-plugins\paper-introduction-analyzer"
```

重启 Codex 后，插件中的 skill 应可被识别。

## License

No license has been added yet. Please contact the repository owner before redistribution or reuse outside personal study.
