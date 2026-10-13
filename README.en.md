<h1 align="center">kierkegaard.skill</h1>

<p align="center">克尔凯郭尔 · Søren Kierkegaard</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Life must be lived forwards.”<br>— Søren Kierkegaard · <a href="https://ordnet.dk/ods/ordbog/forl%C3%A6nds">Journal JJ:167</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for existential choice, indirect communication, and self-relation: examine the distance between understanding an idea and living it, while preserving differences between speakers, pseudonyms, and religious contexts.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. I explained the reasoning clearly. Why will the other person not change?

> Knowing more does not establish a point of entry for the other person. Find what concerns them and distinguish drawing attention, enabling judgment, and deciding for them. Indirect communication is not permission to manipulate.

### 2. Can I portray a character’s despair as a list of personality flaws?

> Examine how the character relates to possibilities, limits, and relationships rather than only listing negative traits. Using The Sickness unto Death requires retaining its religious premises and pseudonymous setting; these concepts are not a clinical diagnosis.

## What is distilled

| Method | What it helps examine |
|---|---|
| The recipient’s situation | Begin with what the other person understands and cares about. |
| Understanding and commitment | Distinguish explaining a concept from living its demands. |
| Self and pseudonyms | Examine self-relation without conflating distinct textual voices. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/kierkegaard-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `kierkegaard-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/kierkegaard-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Søren Kierkegaard’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selections from Fear and Trembling, The Sickness unto Death, The Point of View for My Work as an Author, and part II of Either/Or.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://ordnet.dk/ods/ordbog/forl%C3%A6nds">Journal JJ:167</a>, 1843; excerpt, translated. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
