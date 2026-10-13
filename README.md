<h1 align="center">kierkegaard.skill</h1>

<p align="center">克尔凯郭尔 · Søren Kierkegaard</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“生活必须向前去活。”<br>— 克尔凯郭尔 · <a href="https://ordnet.dk/ods/ordbog/forl%C3%A6nds">日记 JJ:167</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将生存选择、间接传达与自我关系整理为思想分析 Skill，让 AI 看见理解一个道理与实际承担它之间的距离，并尊重说话者、假名与信仰处境的差别。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 我已经把道理解释得很清楚，为什么他还是不改变？

> 知道更多不等于找到了对方能够理解的入口。先看他实际担心什么，再区分引起注意、帮助判断与替他决定；间接传达不是隐瞒目的、操纵他人的许可。

### 2. 我可以把角色的绝望写成一串性格缺点吗？

> 可以先看角色怎样对待自己的可能性、限制和关系，而不是只列消极属性。若借用《致死的疾病》，还须保留其宗教前提与假名位置；这些概念不能充当临床诊断。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 接受者处境 | 从对方实际理解与关切出发寻找说明入口。 |
| 理解与承担 | 区分掌握概念与承担其生存要求。 |
| 自我与假名 | 检查关系中的自我，并保留不同文本声音的归属。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/kierkegaard-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `kierkegaard-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/kierkegaard-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用克尔凯郭尔的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《恐惧与战栗》选段；《致死的疾病》选段；《我的著述活动的观点》及《非此即彼》第二部选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://ordnet.dk/ods/ordbog/forl%C3%A6nds">日记 JJ:167</a>，1843 年，JJ:167 节选；丹麦语历史词典收录原句。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
