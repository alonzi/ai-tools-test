
# AI Development Tools for Data Science vs Computer Science (Brown Bag Talk)

This document captures the full content developed during a conversation focused on preparing a brown‑bag talk for **master’s‑level data science students** about modern AI development tools (2026), with explicit contrasts to computer science perspectives.

---

## 1. Overview: Why This Topic Matters

AI tools for development now range from simple autocomplete to fully autonomous agents. Understanding **what kind of cognitive work is being delegated** is especially important for data scientists, where failure modes are often silent rather than explicit.

Key framing:
- AI collapses the cost of *execution*
- AI does **not** collapse the cost of *being wrong*

---

## 2. Major AI Coding & Development Tools (2026)

| Tool | Organization | Primary Interface | Core Idea | Strengths | Typical Use Cases |
|-----|--------------|------------------|-----------|-----------|-------------------|
| OpenAI Codex | OpenAI | Cloud agent, CLI, IDE | Autonomous coding agent | Long‑running tasks, multi‑agent workflows | Refactors, migrations, CI/CD, experiment automation |
| Claude Code | Anthropic | Terminal, IDE, desktop | Reasoning‑first collaborator | Deep context, explanation, critique | Architecture, refactoring, assumption audits |
| GitHub Copilot | GitHub / Microsoft | IDE plugin | AI pair programmer | Fast inline suggestions | Boilerplate, scripting, API usage |
| Cursor | Anysphere | AI‑native IDE | AI‑first editor | Project‑wide context | Multi‑file refactors, analysis consistency |
| Devin | Cognition AI | Cloud IDE | Autonomous software engineer | End‑to‑end execution | Delegated tickets, autonomy demos |
| Aider | Open source | CLI | Git‑centric assistant | Transparent diffs | Reproducibility, teaching version control |
| Gemini Code Assist | Google | IDE + CLI | Cloud‑native assistant | Multimodal reasoning | GCP data pipelines |

---

## 3. CS vs Data Science: Different Evaluation Lenses

| Dimension | Computer Science | Data Science |
|---------|-----------------|--------------|
| Core question | Does the code work? | Is the inference valid? |
| Failure mode | Loud (tests fail) | Silent (results look plausible) |
| Primary risk | Bugs | Bias, leakage, misuse |
| Role of AI | Speed of construction | Support for reasoning |

Key takeaway:
> CS students optimize for *correct execution*; DS students must optimize for *valid reasoning*.

---

## 4. Tool Families Reframed for Data Scientists

- **Copilot** → accelerates execution
- **Cursor** → enforces consistency across analyses
- **Claude Code** → supports reasoning, critique, explanation
- **Codex** → enables delegation at scale

These are not competing answers to the same question — they address *different cognitive tasks*.

---

## 5. Silent Failure Case Study

**Scenario:**
A student asks an AI tool to build a predictive model for student success.

**What goes right:**
- Clean train/test split
- High accuracy
- Well‑formatted plots

**What goes wrong (silently):**
- Post‑outcome variables leak into features
- Incorrect evaluation metric
- No causal justification

**Key point:**
> The model runs. The plots look good. The conclusion is wrong.

This is a *data science failure*, not a coding failure.

---

## 6. Decision Tree: Which Tool Should a Data Scientist Use?

### A. “I know what to do — I just need to write it.”
→ **GitHub Copilot**

### B. “This change touches many files or analyses.”
→ **Cursor**

### C. “I need to understand, justify, or critique this analysis.”
→ **Claude Code**

### D. “I’ve already designed this — I want it executed at scale.”
→ **OpenAI Codex**

**Rule:** Never delegate *scientific judgment* — only execution.

---

## 7. Slide‑Ready Outline (Summary)

1. AI tool landscape: from autocomplete to agents
2. CS vs DS evaluation differences
3. Tool families and cognitive roles
4. Silent failure example
5. Rule of thumb for data scientists

---

## 8. Rule of Thumb (Closing Slide)

- Delegate execution, not scientific judgment
- Use AI to run experiments, not design them
- AI raises the value of statistical expertise

> For data scientists, AI is a very fast research assistant — who never took statistics unless you teach it.

---

*Prepared for a master’s‑level data science brown‑bag talk, 2026.*
