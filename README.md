# shenn667 — AI Systems & Tooling Engineer

I build deterministic tooling for AI systems: context infrastructure, eval gates, and verifiable RAG.

Focus: MCP servers, LLM CI, offline retrieval. Python, PyPI-published, test-driven.

## Open Source

**1. [agent-context-bridge](https://github.com/shenn667/agent-context-bridge)** — MCP server for agent context management.
PyPI 0.3.0. 98.7% token reduction. 88 tests passing.

**2. [llm-eval-ci](https://github.com/shenn667/llm-eval-ci)** — CI gate for LLMs and agents.
100% check coverage. 146 tests passing. Blocks regressions before merge.

**3. [cited-rag](https://github.com/shenn667/cited-rag)** — Offline hybrid RAG (BM25 + TF-IDF + RRF) with citations.
Recall@5 = 1.00, MRR = 0.93. 61 tests passing. No external API required.

**4. [claude-verified-agent](https://github.com/shenn667/claude-verified-agent)** — End-to-end showcase: verified agent loop (context → cited answer → PII/injection gate).
14 tests + 3 eval gates green in CI. Offline demo, no API key required.

## Contact

Open to AI infrastructure and tooling roles. Reach via GitHub.
