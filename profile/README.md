<div align="center">

<img src="https://github.com/Intelligent-Internet.png" width="96" alt="Intelligent Internet logo" />

# Intelligent Internet

### First Principles Sovereign AI

*Most AI companies rent intelligence and compete at the UI.*
*We ship the control points that turn intelligence into owned, verifiable work — in the open.*

<br/>

[![Website](https://img.shields.io/badge/Website-ii.inc-1B2A63?style=for-the-badge)](https://ii.inc)
[![Blog](https://img.shields.io/badge/Blog-Research%20%26%20Releases-1B2A63?style=for-the-badge)](https://ii.inc/web/blog)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models%20%26%20Datasets-FFD21E?style=for-the-badge&labelColor=1B2A63)](https://huggingface.co/Intelligent-Internet)
[![Symbioism](https://img.shields.io/badge/Symbioism-A%20Third%20Path-C9A227?style=for-the-badge&labelColor=1B2A63)](https://symbioism.com)

</div>

---

## 🏭 The Agentic Production Line

Agents don't fail for lack of intelligence — they fail when knowledge is stale, retrieval is expensive, output is unverified, and capability never reaches a surface users can own. So we build **every stage of the line**, not one layer of it:

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#f7f4ec','primaryTextColor':'#1b2a63','primaryBorderColor':'#1b2a63','lineColor':'#c9a227','fontSize':'14px'}}}%%
flowchart LR
    A["🧪 <b>Capability<br/>Foundry</b><br/><i>train specialist models</i>"] --> B["📚 <b>Governed<br/>Context</b><br/><i>knowledge as supply</i>"]
    B --> C["🔎 <b>Retrieval<br/>Fabric</b><br/><i>search before every action</i>"]
    C --> D["⚙️ <b>Work<br/>Harness</b><br/><i>verify, gate, replan</i>"]
    D --> E["🚀 <b>Owned<br/>Surfaces</b><br/><i>ship it to people</i>"]
```

| | Control point | Why it matters | Open source |
|---|---|---|---|
| **01** | **Capability Foundry** — create capability, not wrappers | If you only rent frontier APIs, your ceiling is someone else's roadmap | [II-Medical](https://huggingface.co/Intelligent-Internet/II-Medical-8B) · [II-Search](https://huggingface.co/Intelligent-Internet/II-Search-4B) · [II-Thought](https://github.com/Intelligent-Internet/ii-thought) |
| **02** | **Governed Context** — turn raw knowledge into machine-usable supply | Agents fail when knowledge is scattered, stale, or outside source boundaries | [II-Commons](https://github.com/Intelligent-Internet/II-Commons) · [II-Commons-Skills](https://github.com/Intelligent-Internet/II-Commons-Skills) |
| **03** | **Retrieval Fabric** — make search cheap, local, inspectable | Context is useless if agents can't search before every decision, tool call, or handoff | [psql_bm25s](https://github.com/Intelligent-Internet/psql_bm25s) |
| **04** | **Work Harness** — completion under gates, not just generation | Agent output isn't work until it survives validators, evidence review, and replanning | [II-Agent](https://github.com/Intelligent-Internet/ii-agent) · [II-Researcher](https://github.com/Intelligent-Internet/ii-researcher) · [Zenith](https://github.com/Intelligent-Internet/zenith) |
| **05** | **Owned Surfaces** — land capability where work happens | Capability only compounds when people can run, fork, and extend it | [CommonGround](https://github.com/Intelligent-Internet/CommonGround) · [CG-Cardbox](https://github.com/Intelligent-Internet/CG-Cardbox) · [opencode-a2a](https://github.com/Intelligent-Internet/opencode-a2a) |

> **Models can be rented. UIs can be copied. Control points compound.**

---

## 🚀 Flagship Projects

| Project | | What it does |
|---|---|---|
| **[II-Agent](https://github.com/Intelligent-Internet/ii-agent)** | ![Stars](https://img.shields.io/github/stars/Intelligent-Internet/ii-agent?style=flat-square&logo=github&label=%E2%AD%90&color=1B2A63) | Open general agent framework — browser, code, files, sandboxed execution, documents, slides, multi-model routing |
| **[II-Researcher](https://github.com/Intelligent-Internet/ii-researcher)** | ![Stars](https://img.shields.io/github/stars/Intelligent-Internet/ii-researcher?style=flat-square&logo=github&label=%E2%AD%90&color=1B2A63) | Deep-research agent: query decomposition, search generation, context compression, self-critique, cited reports — **84.1 on FRAMES** |
| **[Zenith](https://github.com/Intelligent-Internet/zenith)** | ![Stars](https://img.shields.io/github/stars/Intelligent-Internet/zenith?style=flat-square&logo=github&label=%E2%AD%90&color=1B2A63) | Continuous-improvement harness for long-running agent tasks — turns Claude Code, Codex, or Hermes into a multi-agent mission orchestrator via MCP/ACP |
| **[CommonGround](https://github.com/Intelligent-Internet/CommonGround)** | ![Stars](https://img.shields.io/github/stars/Intelligent-Internet/CommonGround?style=flat-square&logo=github&label=%E2%AD%90&color=1B2A63) | From isolated agents to shared work — records, evidence, handoffs, and decisions that persist beyond one run |
| **[psql_bm25s](https://github.com/Intelligent-Internet/psql_bm25s)** | ![Stars](https://img.shields.io/github/stars/Intelligent-Internet/psql_bm25s?style=flat-square&logo=github&label=%E2%AD%90&color=1B2A63) | Postgres-native exact BM25: mutable indexes, crash recovery, replication-friendly storage, SQL-native permissions |
| **[II-Commons](https://github.com/Intelligent-Internet/II-Commons)** | ![Stars](https://img.shields.io/github/stars/Intelligent-Internet/II-Commons?style=flat-square&logo=github&label=%E2%AD%90&color=1B2A63) | The knowledge supply chain: Wikipedia, PD12M, arXiv, PubMed — parsed, embedded, indexed, and served with provenance |

---

## 🧠 Open Models & Datasets

Everything on the [🤗 Hugging Face hub](https://huggingface.co/Intelligent-Internet) — weights, data, and benchmark traces included.

| Release | Type | Highlight |
|---|---|---|
| [II-Medical-8B](https://huggingface.co/Intelligent-Internet/II-Medical-8B) | Model | Specialist medical reasoning — SFT, RL, and safety stages |
| [II-Search-4B](https://huggingface.co/Intelligent-Internet/II-Search-4B) | Model | Multi-hop search and tool-use behavior in a small model |
| [II-Thought-RL-v0](https://huggingface.co/datasets/Intelligent-Internet/II-Thought-RL-v0) | Dataset | **341,795 verified, machine-checkable RL problems** across math, code, science, medicine |
| [II-Medical-Reasoning-SFT](https://huggingface.co/datasets/Intelligent-Internet/II-Medical-Reasoning-SFT) | Dataset | Part of **2.2M medical reasoning rows** behind the II-Medical series |
| [wikipedia_en](https://huggingface.co/datasets/Intelligent-Internet/wikipedia_en) · [arxiv](https://huggingface.co/datasets/Intelligent-Internet/arxiv) · [pd12m](https://huggingface.co/datasets/Intelligent-Internet/pd12m) | Datasets | Public knowledge, processed for agents — with citations and source boundaries |

---

## 📊 At a Glance

<div align="center">

| ⭐ **5,000+** | 🧪 **341K** | 🏥 **2.2M** | 🤗 **9 + 20** | 🏭 **5/5** |
|:---:|:---:|:---:|:---:|:---:|
| GitHub stars across the org | verified RL problems, open | medical reasoning rows | open models + datasets | production-line stages shipped, all open |

</div>

---

## 🧭 Why Open?

We publish the research, the data pipelines, the retrieval infrastructure, the harnesses, and the philosophy — because an intelligence economy only compounds when its production line is inspectable and forkable. Our long-form thesis lives at [**Symbioism — A Third Path for the Intelligence Age**](https://symbioism.com) ([source](https://github.com/Intelligent-Internet/Symbioism-Nextra), naturally).

Earlier experiments — [CoT-Lab](https://github.com/Intelligent-Internet/CoT-Lab-Demo), [Common Chronicle](https://github.com/Intelligent-Internet/Common_Chronicle), [CommonGround-legacy](https://github.com/Intelligent-Internet/CommonGround-legacy) — are archived in public. Every stage of the line started as an open experiment; the ones that worked became infrastructure.

---

<div align="center">

### *Intelligence is our greatest resource. Together, we make it abundant.*

**[ii.inc](https://ii.inc)** · **[Blog](https://ii.inc/web/blog)** · **[🤗 Hugging Face](https://huggingface.co/Intelligent-Internet)** · **[Symbioism](https://symbioism.com)**

</div>
