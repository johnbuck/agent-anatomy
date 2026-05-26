# Agent Anatomy

A visual tour of what makes a modern AI agent tick — head to toe, one part at a time.

**Live:** https://johnbuck.github.io/agent-anatomy/

A one-page explainer designed for non-technical audiences. It maps the moving parts of modern AI agents onto a humanoid figure, then walks through each piece one tab at a time:

- **Models** — the brain (Anthropic, OpenAI, Google, local) and how reasoning models think before they answer
- **Tokens** — the unit of measurement, what tokens actually cost, and KV caching
- **Context** — what fits in mind right now, context rot, compaction
- **Harness** — the scaffolding around the model, subagents, real-world harness examples (Claude Code, Cursor, ChatGPT, OpenClaw)
- **RAG** — retrieval-augmented generation and vector databases, explained simply
- **Memory** — persistent notes and AGENTS.md / CLAUDE.md house rules, plus where they go wrong
- **Skills** — markdown recipes loaded on demand, and how trigger descriptions can misfire
- **Plugins** — bundled tool/hook/skill extensions for a specific harness
- **MCP** — the open-standard protocol that lets any harness talk to any service
- **Data** — where your prompt actually goes, who logs it, what trains future models

Single static HTML file, no build step, no dependencies beyond Google Fonts. Open `index.html` in any browser.

## License

MIT — use freely.
