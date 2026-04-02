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




# Survey of Landscape

### Tools
| Tool | Company | Category | Release Quarter | Popularity |
|------|---------|----------|-----------------|------------|
| GitHub Copilot | GitHub / Microsoft | IDE assistant (autocomplete) | 2021 Q2 | High |
| Aider | Open source | CLI (git-centric) | 2023 Q2 | Medium |
| Claude Code | Anthropic | Agentic coding (CLI/IDE) | 2025 Q1 | Medium |
| Code Llama | Meta | Open model (self-hosted) | 2023 Q3 | Medium |
| Cursor | Anysphere | AI-native IDE | 2023 | Medium |
| Gemini Code Assist / CLI | Google | IDE + CLI assistant | 2024 Q2 | Medium |
| OpenAI Codex | OpenAI | Agentic coding (cloud/CLI) | 2021 Q3 | Medium |
| Replit Ghostwriter | Replit | Cloud IDE assistant | 2022 Q4 | Medium |
| Devin | Cognition AI | Autonomous agent | 2024 Q1 | Emerging |
| OpenClaw | Open source | Agent tooling ecosystem | — | Emerging |
| Windsurf (Cascade) | Codeium / Exafunction | Agentic IDE | 2024 Q4 | Emerging |

*Sources: see [`sources.md`](sources.md#tools-release-quarter).*

### Jargon
| Term | Definition |
|------|------------|
| Agentic coding | Task-oriented workflows where the system plans and executes multi-step changes across your repo. |
| AI-native IDE | Editor built around AI from the start (repo-wide chat/edits), not only a plugin on a classic IDE. |
| Autonomous agent | System that can carry a ticket or task end-to-end with little step-by-step prompting. |
| Multi-agent workflow | Several specialized agents or tools coordinated to split work (planner, coder, reviewer). |
| Agent tooling ecosystem | Loosely coupled open tools, plugins, and runtimes that let you wire agents into IDEs, CLIs, chat, and your own infra (often self-hosted or swappable). |

*Sources: see [`sources.md`](sources.md#jargon). Older / general terms: [`zold/legacy-jargon.md`](zold/legacy-jargon.md).*


### Claude Cowork vs. Claude Code

* Cowork - broader audience
* Code - built for programming tasks
* Cowork - app based, Code - CLI based
### Copilot vs. Cursor
### Claude Code vs. Cursor
### Claude Code vs. OpenClaw



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



# Today: What's my use case?

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


