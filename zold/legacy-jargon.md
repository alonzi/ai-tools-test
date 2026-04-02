# Legacy / general jargon (moved from Survey)

These terms were moved out of the main Survey jargon table in `README.md` in favor of newer AI-coding-specific jargon.

| Term | Definition | Year of first appearance | Popularity |
|------|------------|--------------------------|------------|
| Human-in-the-loop | Workflow where a person approves/reviews critical steps (edits, runs, merges) | 1998 | High |
| Autocomplete | Predictive inline completion in the editor (and related “finish this line” UX); the main UX of many IDE assistants. | 1950s | High |
| IDE assistant | AI help embedded in a traditional IDE (plugin or first-party) rather than a separate “AI-first” editor. | — | — |
| CLI-first (git-centric) AI | Terminal-oriented assistant that applies edits and tracks them with git (diffs, commits, undo). | — | — |
| Open model (self-hosted) | Code-capable model weights you can run or host yourself (on-prem / VPC) instead of only a vendor API. | — | — |
| Cloud IDE assistant | AI coding features inside a browser-hosted IDE (quick start, shared environment). | — | — |
| IDE + CLI assistant | Same product family offers both editor integrations and a CLI for headless or scriptable workflows. | — | — |
| PR / CI AI checks | Automated review or policy gates on pull requests using AI-defined or AI-assisted checks. | 2026 | Emerging |
| Multi-file refactor | A change spanning many files coordinated by the tool/agent | 1999 | Medium |
| Repo-wide context | Understanding/operating across a whole codebase, not a single file | 2023 | Medium |
| Sandbox execution | Running tasks/commands in an isolated environment for safety/reproducibility | — | Medium |
| Policy-as-markdown | Expressing workflow/quality/security rules as versioned text (often enforced in PR/CI) | 2017 | Emerging |
| Agent tooling ecosystem | Loosely coupled open tools, plugins, and runtimes that let you wire agents into IDEs, CLIs, chat, and your own infra (often self-hosted or swappable). | — | — |

*Sources for dates: see [`sources.md`](../sources.md).*
