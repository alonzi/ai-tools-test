# AI Tools Landscape for Coding (Brown Bag, Master's Audience)

Last updated: 2026-04-01

This one-pager is designed for a graduate-level brown bag on how AI coding tools are changing software development work.

- The landscape is shifting from autocomplete to agentic workflows.
- The biggest change is not just "faster coding," but delegation of multi-step implementation and review tasks.
- Tool choice should match the cognitive task: drafting, refactoring, research, review, or automation.

## Current Tool Comparison

| Tool | Company / Open-source | Primary Interface | Best At | Limits / Risks | Good Fit For Master's Students | Typical Cost Tier |
| --- | --- | --- | --- | --- | --- | --- |
| OpenAI Codex | OpenAI (open-source CLI + hosted ecosystem) | Terminal CLI, cloud tasks, integrations | End-to-end coding tasks with subagents and local command execution | Can over-edit without tight constraints; needs good prompts and validation | Large project refactors, reproducible implementation workflows, rapid prototyping | Paid plans (some included in ChatGPT tiers) |
| Claude Code | Anthropic | Terminal, IDE extensions, desktop/web | Reasoning-heavy code work, planning, multi-file edits, explanation | Strong outputs can still hide wrong assumptions; requires review discipline | Thesis/project architecture decisions, debugging with explanation, critique loops | Paid subscription or enterprise |
| GitHub Copilot | GitHub / Microsoft | IDE, GitHub, CLI | Low-friction coding support, inline suggestions, PR workflow support | Suggestion quality varies by context; easy to accept mediocre code quickly | Daily coding speedups, boilerplate, test scaffolding, PR assistance | Free tier + paid individual/org plans |
| Cursor | Anysphere | AI-native editor, cloud agents | Integrated agentic development in editor, multi-file work, parallel tasking | Workflow can become tool-dependent; still needs human design control | Fast iteration for capstones, full-stack class projects, codebase understanding | Free + paid tiers |
| Windsurf (Cascade) | Codeium / Exafunction | AI-native editor and JetBrains plugin | Agentic write/chat workflows, tool calling, real-time collaboration with your edits | Auto-execution features require careful guardrails; verify terminal actions | Teams experimenting with agent-assisted implementation pipelines | Free + paid tiers |
| OpenClaw | Open-source community project (fast-moving ecosystem) | Primarily open-source agent tooling + integrations | Local-first experimentation, custom automation, extensibility | Fragmented docs/branding depending on fork; quality and security vary by setup | Research-minded students exploring agent architectures and local workflows | Free/open-source (compute/API costs vary) |
| Aider | Open-source | Terminal CLI (git-centric) | Transparent edit diffs, commit-oriented coding with many model backends | Less "managed UX" than IDE-native tools; setup quality affects outcomes | Reproducible research code changes, pair-programming in git-first workflows | Free/open-source (API/model costs) |
| Continue (AI checks) | Open-source + commercial offering | PR checks and policy-as-markdown workflows | Standardized AI quality checks on pull requests | Not a full coding IDE agent by itself; needs workflow integration | Lab/group standards, repeatable review criteria, code quality gates | Free/open-source + paid offerings |

## What Is Changing in the Landscape

1. **From completion to delegation:** tools now plan, edit, run commands, and sometimes review outcomes.
2. **From single surface to multi-surface:** the same agent now appears in IDE, terminal, web, CI, and chat.
3. **From one model to model routing:** users increasingly choose tools by workflow UX and guardrails, not only by base model.
4. **From individual productivity to team governance:** policies, MCP/tool access, hooks, and auditable workflows are now central.

## Quick Selection Heuristic for Master's Students

- Use **Copilot** when you mostly know what to build and want speed.
- Use **Claude Code** or **Cursor/Windsurf** when tasks span many files and require planning.
- Use **Aider** when you want transparent, git-native, reproducible change history.
- Use **OpenClaw** when your goal is experimentation with open agent stacks and local control.
- Add **Continue-style checks** when your group needs consistent quality rules on PRs.

## Important Note

Capabilities and pricing change quickly. For any high-stakes use (thesis code, publishable results, production systems), verify current docs and validate all AI-generated outputs with tests and domain checks.
