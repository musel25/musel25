# Müsel Tabares

**AI Research Engineer · agentic systems, LLMs, applied optimization · open to EU roles from September 2026**

AI Research Engineer at Orange Labs (Paris), building autonomous AI agents that can independently negotiate, pay for, and activate real infrastructure services from other agents — no human in the loop. My work spans the emerging agentic-web protocol stack (Google A2A, MCP), smart-contract escrow on Foundry, and SDN control of containerized networks. Background: Erasmus Mundus MSc in AI & Optimization (UTC, France); thesis defense September 2026.

Throughline: agent architectures, multi-agent coordination, RAG / LLM systems, and applied optimization — taken from a notebook to something that actually runs. Research rigor, production discipline, no buzzword bingo.

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**ollama-agent-simulation**](https://github.com/musel25/ollama-agent-simulation) | **Thesis PoC** — a consumer agent and a provider agent negotiate a bandwidth service, settle payment on-chain for an ERC-721 access credential, and that credential is enforced at runtime by an SDN controller. | Python · FastAPI · MCP · A2A · Foundry/Solidity · Ollama · Docker |
| [**srl-gnmi-bandwidth-poc**](https://github.com/musel25/srl-gnmi-bandwidth-poc) | The SDN activation layer: pushes a QoS policer to a Nokia SR Linux PE router over gNMI, enforces it with Linux `tc`, verifies with iperf3 — all exposed as MCP tools an agent can call directly. | Python · gNMI/pygnmi · Containerlab · Nokia SR Linux · MCP |
| [**multi-agent-mcp-demo**](https://github.com/musel25/multi-agent-mcp-demo) | Two Claude agents coordinate a buy/sell transaction through a shared MCP server — no orchestrator, pure message-passing, no human after startup. | Python · MCP (FastMCP) · SSE |
| [**telemetry-rag**](https://github.com/musel25/telemetry-rag) | Local-first RAG over network-telemetry docs (YANG modules, gNMI captures, snapshots) — Qdrant vector store, Ollama or OpenAI backends, a small `index` / `ask` CLI. | Python · Qdrant · Ollama · OpenAI |
| [**Instruction-Preference-FineTuning-Pipeline**](https://github.com/musel25/Instruction-Preference-FineTuning-Pipeline) | Reproducible Hydra pipeline for LLM supervised fine-tuning (LoRA / QLoRA) and preference alignment (DPO / ORPO), wired for DeepSpeed/FSDP, W&B/MLflow and LightEval / lm-eval. | Python · PyTorch · TRL · PEFT · Hydra · DeepSpeed |
| [**claude-usage-widget**](https://github.com/musel25/claude-usage-widget) | Linux desktop widget + terminal CLI showing claude.ai usage limits — GTK3 GUI, truecolor dashboard, local response cache. | Python · GTK3 / PyGObject |

## What I'm working on now

- **MSc thesis (defense Sept 2026)** — one of the first end-to-end tokenized service exchanges between mutually untrusted AI agents: on-chain settlement for an ERC-721 access credential, enforced at runtime by an SDN controller. → [ollama-agent-simulation](https://github.com/musel25/ollama-agent-simulation) · [srl-gnmi-bandwidth-poc](https://github.com/musel25/srl-gnmi-bandwidth-poc)
- **Governed multi-agent network automation** — separating intent synthesis from execution authority behind an explicit, immutably-recorded approval boundary. → [zero-trust-agentic-network-telemetry](https://github.com/musel25/zero-trust-agentic-network-telemetry)
- **Foundations** — working through LLM internals, RAG, and fine-tuning / alignment pipelines from scratch alongside the applied work.

## Tech stack

`Python` · `PyTorch` · `LangChain` · `Qdrant` · `Docker` · `Foundry / Solidity` · `Linux` · `gNMI · Containerlab` · `FastAPI` · `Git`

## Looking for

Full-time **Research Engineer / ML Engineer** roles in the EU, available **September 2026**.

## Contact

- Email — `museltabarespardo@gmail.com`
- LinkedIn — [linkedin.com/in/musel](https://www.linkedin.com/in/musel/)
- Web — [musel.dev](https://musel.dev)

---

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=musel25&show_icons=true&hide_border=true&include_all_commits=true&theme=default" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=musel25&layout=compact&hide_border=true&langs_count=8&theme=default" alt="Top languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=musel25&hide_border=true&theme=default" alt="GitHub streak" />
</p>
