# shenn667 — AI Systems & Tooling Engineer

I build deterministic tooling for AI systems: context infrastructure, eval gates, and verifiable RAG.

Focus: MCP servers, LLM CI, offline retrieval. Python, PyPI-published, test-driven.

## Open Source

**1. [agent-context-bridge](https://github.com/shenn667/agent-context-bridge)** — MCP server for agent context management.
PyPI 0.3.2. 92 tests passing. 98.7% token reduction. Listed on the [official MCP Registry](https://registry.modelcontextprotocol.io/) (`io.github.shenn667/agent-context-bridge`) and [Glama](https://glama.ai/mcp/servers/shenn667/agent-context-bridge) (Discovery 92%).

**2. [llm-eval-ci](https://github.com/shenn667/llm-eval-ci)** — CI gate for LLMs and agents.
PyPI 0.1.0. 146 tests passing. 100% check coverage. Blocks regressions before merge.

**3. [cited-rag](https://github.com/shenn667/cited-rag)** — Offline hybrid RAG (BM25 + TF-IDF + RRF) with citations.
PyPI 0.1.0. 61 tests passing. Recall@5 = 1.00, MRR = 0.93. Refusal 12/12. No external API required.

**4. [claude-verified-agent](https://github.com/shenn667/claude-verified-agent)** — End-to-end showcase: verified agent loop (context → cited answer → PII/injection gate).
14 contract tests + 3 CI gates green in CI. Offline demo, no API key required.

## Benchmarks, Registry & Writing

- **Site & Eval Benchmarks**: [shenn667.github.io](https://shenn667.github.io/) · [Eval benchmarks](https://shenn667.github.io/eval/)
- **Dataset (Hugging Face)**: [SHENNN667/cited-rag-golden-52](https://huggingface.co/datasets/SHENNN667/cited-rag-golden-52)
- **Official MCP Registry**: [io.github.shenn667/agent-context-bridge](https://registry.modelcontextprotocol.io/) · **Glama**: [shenn667/agent-context-bridge](https://glama.ai/mcp/servers/shenn667/agent-context-bridge)
- **Technical article (DEV.to)**: [Zero-Dependency Verified Agents: Cited or Refused, Gated in CI](https://dev.to/shenn667/zero-dependency-verified-agents-cited-or-refused-gated-in-ci-3fnh)

## Contact

Open to AI infrastructure and tooling roles. Reach via GitHub.
