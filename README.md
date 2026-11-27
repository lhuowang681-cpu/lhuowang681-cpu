# Hi, I'm Xiongtai Yang 👋

🎓 M.S. student in Computer Science at **Sichuan University**  
🤖 Focused on **LLM Agents, Agent Evaluation, RAG, and Multimodal Learning**  
🛠️ Building agent systems with durable state, controlled tool use, and traceable evidence.

## Featured Projects

### 🧠 [Job Agent · Stateful & Evidence-Grounded Workbench](https://github.com/lhuowang681-cpu/stateful-job-agent)

A long-horizon job-search and interview workbench built with **React, FastAPI, and LangGraph**, connecting resume facts, job requirements, project code, and interview feedback.

- Resume import, fact review, constrained rewriting, versioned PDF export, and application tracking.
- Public-knowledge and code-aware retrieval with source, snapshot, hash, and quotation checks.
- Bounded agent execution with tool permissions, budgets, checkpoint / resume, and background-task recovery.
- Reproducible tests and frozen evaluation artifacts, with retrieval results separated from factual support and model quality.

[Source & quick start](https://github.com/lhuowang681-cpu/stateful-job-agent#快速体验) · [Current specification](https://github.com/lhuowang681-cpu/stateful-job-agent/blob/main/docs/tech-specs/CURRENT_SPEC.md)

### 🧪 [Agent Eval · Trajectory Evaluation & Failure Attribution](https://github.com/lhuowang681-cpu/agent-eval-project)

A trajectory-driven evaluation and diagnosis project connecting **agent runs, execution traces, evidence review, and failure analysis**.

- Trace extraction and asynchronous diagnostic workers across TypeScript services, Python analysis, and PostgreSQL.
- Evidence review that checks source identity and quotations, and distinguishes local faults, task outcomes, and causal claims.
- Optional semantic sidecars with explicit budgets, plus event deduplication, failure-pattern grouping, and representative traces.
- Validated PostgreSQL integration across 11 scenarios, compared rules and evidence review on 40 synthetic traces, and analyzed six real-model development requests.

[Architecture & offline demo](https://github.com/lhuowang681-cpu/agent-eval-project#快速体验) · [Experiments & results](https://github.com/lhuowang681-cpu/agent-eval-project#验证与实验结果)

### 🖼️ Multimodal Learning Research

Working on **multi-turn multimodal reasoning and visual grounding**.

- Built a benchmark for state-dependent visual instance grounding.
- Fine-tuned **Qwen3-VL** with LoRA and conducted controlled evaluation.
- 📄 [First-author preprint on arXiv](https://arxiv.org/abs/2608.14148)

## Current Interests

- **LLM Agents** — runtime control, tool use, memory, and long-horizon workflows.
- **Agent Evaluation** — trace analysis, evidence review, failure attribution, and reproducible comparisons.
- **RAG & Grounding** — code-aware retrieval, provenance, quotation verification, and factual support.
- **Multimodal Learning** — visual grounding, stateful interaction, and parameter-efficient fine-tuning.

## Tech Stack

| Area | Tools |
| --- | --- |
| Languages & application | Python · TypeScript · React · Next.js · FastAPI · Pydantic |
| Agents & retrieval | LangGraph · MCP · FAISS · Qwen Embedding · BM25 · RRF |
| State & engineering | SQLite · PostgreSQL · Redis · asyncio · Git · Linux |
| Multimodal research | PyTorch · Transformers · PEFT · LoRA |

## Engineering Principles

- Keep candidate generation separate from evidence verification.
- Treat state transitions, recovery, and tool side effects as explicit contracts.
- Compare systems under the same inputs and preserve failures alongside successful runs.
- State what was tested: unit, integration, synthetic evaluation, or real-model execution.

## Contact

- 📧 Email: `1114869935@qq.com`
- 💻 GitHub: [@lhuowang681-cpu](https://github.com/lhuowang681-cpu)
