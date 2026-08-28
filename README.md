## Oliver Sick

Mathematician by training. I build AI systems for large, business-critical enterprise IT —
and these repositories are where I try out what has to hold up there later.

In my work I am owning an AI platform as an architect, enabling large projects with dozen of team with agentic environments for large SaFE Value Streams.

---

### What I work on

**Legacy modernization with agents**
How do you move a legacy system to a modern architecture when the business logic was never
documented? In 2025 we did exactly that — 50,000 lines, with agents reconstructing the
domain rules from the existing code. These repos are the tooling behind it.

- [archaeocode](https://github.com/osick/archaeocode) — automated software archaeology: agents excavate business-readable user stories and dependency maps from COBOL, Smalltalk, Fortran and Pascal

**Context for AI assistants**
The model is rarely the problem. The context is.

- [repo-ctx](https://github.com/osick/repo-ctx) — MCP server giving AI assistants searchable access to any Git repository: symbols, dependency graphs, architecture analysis across 12 languages
- [ctx.skills](https://github.com/osick/ctx.skills) — agent skills for what LLMs are notoriously bad at: time, structured knowledge, very large context
- [semrag](https://github.com/osick/semrag) — local-first enterprise RAG with semantic chunking and retrieval
- [knowledge-mcp](https://github.com/osick/knowledge-mcp) — MCP server for structured knowledge management

**Verify, don't hope**
Twenty-five years of owning quality in critical systems leave a mark: what you don't
measure doesn't work. And an agent you cannot constrain is not a tool, it is a risk.

- [mcp-zerotrust](https://github.com/osick/mcp-zerotrust) — zero-trust security gateway for MCP: default-deny capability profiles, human-in-the-loop escalation, audit logging. One Go binary between your AI host and its MCP servers
- [urllm](https://github.com/osick/urllm) — privacy and security audit for any URL. Deterministic extraction first, LLM second, with a `--fail-on` gate for CI/CD
- [SpecBench](https://github.com/osick/SpecBench) — benchmarking spec-driven development frameworks


**Mathematics**
Mathematics is my education and still my love, now working on the combination of AI and math
Currently competing in the [Mathematics Distillation Challenge](https://competition.sair.foundation/)
run by the SAIR Foundation — see [SAIRmcp](https://github.com/osick/SAIRmcp). So small outcomes were (more to come)

- [SAIRmcp](https://github.com/osick/SAIRmcp)  — A mcp server supporting to communicate with the docs https://docs.sair.foundation/docs/ of the SAIR Challenges API
- [magmaexplorer](https://github.com/osick/magmaexplorer)  — exploring finite magmas and equational theories

**Chess**
My passion when I don't work on AI and math. A small selection of my work on it

- [ChessMG](https://github.com/osick/ChessMG) — chess move generation at engine speed, with a Python API
- [helpmate-tablebase](https://github.com/osick/helpmate-tablebase) — exhaustive helpmate tablebases for problem composers, evaluating hundred of billion positions in highly compressed databases


---

Python · Go · C++ · MCP · RAG and GraphRAG · AWS Bedrock · Neo4j · Qdrant
Daily driver: Claude Code, GitHub Copilot, Codex, AWS Kiro.

[LinkedIn](https://www.linkedin.com/in/oliversick/) · [Hugging Face](https://huggingface.co/osick)
