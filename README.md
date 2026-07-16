## Yatin Arora

AI engineer in Germany. I build agentic systems that run in production — and, after
hours, native apps that turn out to be harder than they look.

Consultant AI Engineer at **CAPCO**, Frankfurt. Before that, three years at **CGI**
building LLM and RAG systems for enterprises across Europe. M.Sc. Data Science,
FAU Erlangen-Nürnberg.

### What I work on

- **Agentic systems** — LangGraph, CrewAI, AutoGen. Tool use, reflection, memory.
- **LLM + RAG** — Milvus, Pinecone, Neo4j, custom retrieval.
- **Finetuning** — LoRA, DPO, KTO on 7B models.
- **MLOps** — Azure, CI/CD, monitoring for production AI.

In practice that has meant multi-agent Jira and Azure DevOps automation that removed
about 75% of a manual workflow, a DORA-aligned ICT risk process roughly 10× faster than
the one it replaced, and a GenAI platform that reached ~90% internal adoption across
Europe.

### Things I've built

**[Task Manager for Mac](https://github.com/yatindma/task-manager-for-mac)** — the
Windows 11 Task Manager, running natively on macOS. All seven tabs, the heatmap, live
graphs. Native Swift, zero dependencies.

Most of the work was refusing to guess. macOS publishes no per-process GPU figure, no
startup impact, no CPU affinity — so those columns show an em-dash and a reason instead
of a plausible lie. The one that nearly shipped: `proc_taskinfo` reports CPU in mach
absolute time units, not nanoseconds, despite most of the internet saying otherwise. On
Apple Silicon the timebase is 125/3, so every process read **41× low** — a core pinned at
100% displayed as 2.4%, and looked entirely reasonable doing it. Caught by pinning a core
and comparing against `ps`.
[What macOS won't tell you](https://yatindma.github.io/task-manager-for-mac/limitations.html).

**[VedicMatch.in](https://vedicmatch.in)** — AI-assisted Vedic astrology compatibility
platform. Built solo: LLM workflows, subscriptions, payments, hosting. Live.

**[Awake](https://github.com/yatindma/Awake)** — macOS menu bar keep-awake toggle with a
self-healing sleep switch. Native Swift, one file.

**[youtube-transcript-mcp](https://github.com/yatindma/youtube-transcript-mcp)** —
self-hosted MCP server for YouTube transcripts and search. VPN-routed to dodge IP blocks,
no truncation, no API key needed.

### Elsewhere

[LinkedIn](https://linkedin.com/in/yatin-arora) ·
[Medium](https://medium.com/@spielmitdaten) ·
[yatin.arora@outlook.de](mailto:yatin.arora@outlook.de)
