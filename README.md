# Tech Stack Notes: AI Tools Landscape

This repository contains working notes for an orientation level brown bag talk on the AI coding tools.

## Cursor, and codex, and claude code ... oh my!

Are you finding it hard to keep up with all the developments in AI coding? It seems like every month there is a new tool. Well, this Thursday (4/2) is your chance to eat some lunch and catch up on the latest developments. (Yes it will obsolete before you graduate, but practicing keeping up is going to be a key skill going forward 🙂).

<p align="center">
  <img src="images/ltb.webp" alt="ltb" />
</p>


## Picking up from where we left off
**Two years ago...**
* Ask chatGPT a question and copy and past the answer into your code

**A year ago...**
1. Code to Code
2. Comment to Code
3. Chat to Code

and

"Claude code ... agentic coding tool" ~anthtopic

**Today...**

we are going to talk about the progress to the current paradigm of ***Agentic coding*** and how to evolve your workflow.

### Outline
1. Survey of Landscape
2. Today: What's my use case
3. Homework




## Survey of Landscape

### Tools
| Tool | Company | Category | Release Quarter | Popularity |
|------|---------|----------|-----------------|------------|
| GitHub Copilot | GitHub / Microsoft | IDE assistant (autocomplete) | 2021 Q2 | High |
| Aider | Open source | CLI (git-centric) | 2023 Q2 | Medium |
| Claude Code | Anthropic | Agentic coding (CLI/IDE) | 2025 Q1 | Medium |
| Code Llama | Meta | Open model (self-hosted) | 2023 Q3 | Medium |
| Cursor | Anysphere | AI-native IDE | 2023 | Medium |
| Gemini Code Assist / CLI | Google | IDE + CLI assistant | 2024 Q2 | Medium |
| JetBrains AI Assistant | JetBrains | IDE assistant | 2023 Q2 | Medium |
| OpenAI Codex | OpenAI | Agentic coding (cloud/CLI) | 2021 Q3 | Medium |
| Replit Ghostwriter | Replit | Cloud IDE assistant | 2022 Q4 | Medium |
| Tabnine | Tabnine | Autocomplete (privacy/on-prem) | 2018 Q4 | Medium |
| Continue (AI checks) | Open source / commercial | PR/CI AI checks | 2023 Q2 | Emerging |
| Devin | Cognition AI | Autonomous agent | 2024 Q1 | Emerging |
| OpenClaw | Open source | Agent tooling ecosystem | — | Emerging |
| Windsurf (Cascade) | Codeium / Exafunction | Agentic IDE | 2024 Q4 | Emerging |

*Sources: see [`sources.md`](sources.md#tools-release-quarter).*

### Jargon
| Term | Definition | Year of first appearance | Popularity |
|------|------------|--------------------------|------------|
| Human-in-the-loop | Workflow where a person approves/reviews critical steps (edits, runs, merges) | 1998 | High |
| Autocomplete tools | Inline completion/suggestion focused assistants (speeding up typing/boilerplate) | 1950s | High |
| Agentic coding | Task-oriented workflows where the system plans and executes multi-step changes | 2024 | Medium |
| AI-native IDE | Editor designed around AI workflows (repo-aware chat/edit), not just an add-on | 2023 | Medium |
| Multi-file refactor | A change spanning many files coordinated by the tool/agent | 1999 | Medium |
| Repo-wide context | Understanding/operating across a whole codebase, not a single file | 2023 | Medium |
| Sandbox execution | Running tasks/commands in an isolated environment for safety/reproducibility | — | Medium |
| Autonomous agent | Higher-autonomy system that can carry a ticket end-to-end with minimal supervision | 2024 | Emerging |
| Multi-agent workflow | Delegating sub-tasks to multiple coordinated agents/tools | 2023 | Emerging |
| Policy-as-markdown | Expressing workflow/quality/security rules as versioned text (often enforced in PR/CI) | 2017 | Emerging |
| PR checks (AI checks) | Automated review/gating on pull requests using AI-defined rules | 2026 | Emerging |

*Sources: see [`sources.md`](sources.md#jargon-year-of-first-appearance).*


### Cowork vs. Claude Code
### Copilot vs. Cursor
### Claude Code vs. Cursor
### Claude Code vs. OpenClaw

**Sources for Survey tables (tools + jargon)**: `from-cursor/AI_Tools_Landscape_Brown_Bag_2026.md`, `from-copilot/Major_AI_Coding_and_Development_Tools_2026.md`, `from-copilot/AI_Tools_DS_vs_CS_Brown_Bag.md`, `from-chatGPT/summary-table.md`, `from-chatGPT/evolution.md`.

**Web-scan candidates to add (not yet pulled from `from-*` sources)**:
- Amazon Q Developer (AWS-focused assistant)
- Cody (Sourcegraph) (large-codebase search + assistant)
- Qodo (AI code review / PR-quality tooling)
- Snyk Code (AI-assisted/security-oriented code scanning mentioned alongside AI dev tooling)
- Bolt (`bolt.new`) (browser-based AI app builder)
- Lovable (browser-based prompt-to-app builder)

### Purpose


## Steps from Chat Copy Pasta to Integrated AI Environment to Agentic

**Two years ago...**
Autocomplete tools (e.g. Copilot)


**One year ago...**
AI-native IDEs (e.g. Cursor)


**Today...**
Agentic systems (e.g. Claude Code)

### Trends
* from suggesting code to doing tasks
* from file level context to repo-level context (and even integration - think OpenClaw)
* from micro to macro (think delegation - especially with Plan mode, more to come)

### What the AI "says"
“Copilot helps you type faster, Cursor helps you think across files, Claude Code helps you delegate entire tasks.” ~ChatGPT



## Today: What's my use case?

### AI strong on middle to middle, not end to end.
* Goals and problem definition live with the human.
* Project milestones and execution live with the AI.
* Evaluations live with the human.

* E.G.: You can spend your time as a designer and architech and let the AI build.


### quick notes
What do you wish you didn't have to do / end of the day low energy brain tasks 
Requires your expertise and judgement and review, but is repetitive the .... Codify and scale


It has to do the repetative stuff - not the top of the job description

## Today: How to get it done?
### Plan mode


### Skills and MD profiles/configuration/rules
[The-Complete-Guide-to-Building-Skill-for-Claude.pdf](https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf)




### Human in the loop - trust but verify - tests


### The 3 core permissions

"We give you two out of three rights. Agentic systems can access sensitive information, it can execute code, and it can communicate externally."

"We could keep things safe if we gave you two out of those three capabilities at any time, but not all three."[^1]

[^1]: [Jensen Huang: NVIDIA - The $4 Trillion Company & the AI Revolution | Lex Fridman Podcast #494](https://www.youtube.com/watch?v=vif8NQcjVf0)


# Homework ... where do we go from here
<p align="center">
  <img src="images/ybr.webp" alt="ybr" />
</p>


Homework
Pick a workflow (repetative, draining)
Write out the steps
Determine the 80% that's routine
The 20% that requires judgement
Build the system



Eg for me - publication quality plots
Paper
Screen
Projection
80% standard
Then I interested the last 20%


