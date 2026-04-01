# Claude AI Codes, Commands & Frameworks
> A complete reference guide for power users of Claude AI - covering prompt frameworks, slash commands, thinking triggers, and quick-use codes.

---

## Table of Contents

1. [Strategic Analysis Frameworks](#1-strategic-analysis-frameworks)
2. [Decision & Thinking Frameworks](#2-decision--thinking-frameworks)
3. [Writing & Structural Frameworks](#3-writing--structural-frameworks)
4. [Roleplay & Persona Codes](#4-roleplay--persona-codes)
5. [Claude Code - Built-in Slash Commands](#5-claude-code--built-in-slash-commands)
6. [Claude Code - Bundled Skills](#6-claude-code--bundled-skills)
7. [Thinking Depth Trigger Words (Claude Code Only)](#7-thinking-depth-trigger-words-claude-code-only)
8. [Quick Chat Codes (Works Anywhere)](#8-quick-chat-codes-works-anywhere)
9. [Coding & QA Commands](#9-coding--qa-commands)
10. [Creativity & Ideation Commands](#10-creativity--ideation-commands)
11. [Productivity & Planning Commands](#11-productivity--planning-commands)
12. [Important Notes & Tips](#12-important-notes--tips)

---

## 1. Strategic Analysis Frameworks

> Use these in the **Claude.ai chat interface** by typing them in plain language.

| Framework | How to Use | What It Does |
|---|---|---|
| **SWOT** | "Do a SWOT analysis of [topic]" | Strengths, Weaknesses, Opportunities, Threats |
| **PESTLE** | "PESTLE analysis of [industry]" | Political, Economic, Social, Tech, Legal, Environmental |
| **Porter's Five Forces** | "Porter's Five Forces for [business]" | Competitive landscape analysis |
| **BCG Matrix** | "BCG Matrix for [product portfolio]" | Growth vs. market share mapping |
| **SOAR** | "Run a SOAR analysis on [topic]" | Strengths, Opportunities, Aspirations, Results (positive alternative to SWOT) |
| **Ansoff Matrix** | "Apply Ansoff Matrix to [company]" | Product/market growth strategy grid |

---

## 2. Decision & Thinking Frameworks

> These instruct Claude *how* to reason, not just *what* to analyze.

| Framework | How to Use | What It Does |
|---|---|---|
| **OODA Loop** | "Apply OODA loop to [situation]" | Observe, Orient, Decide, Act - fast military-style decision cycle |
| **First Principles** | "Break this down to first principles" | Strip assumptions; rebuild from fundamentals |
| **Six Thinking Hats** | "Apply Six Thinking Hats to [problem]" | De Bono's parallel thinking across 6 perspectives |
| **5 Whys** | "Apply the 5 Whys to [problem]" | Drill down to root cause |
| **Socratic Method** | "Examine this Socratically" | Systematic questioning to stress-test reasoning |
| **Devil's Advocate** | "Play devil's advocate on [idea]" | Argue the strongest opposing view |
| **Steelman** | "Steelman this argument: [X]" | Build the *best possible* version of an argument |
| **Pre-mortem** | "Run a pre-mortem on [plan]" | Imagine failure; identify risks before they happen |
| **Second-Order Thinking** | "What are second-order effects of [X]?" | Think through consequences of consequences |
| **Inversion** | "Invert this problem: [X]" | Solve by thinking about what to *avoid* |
| **Rubber Duck** | "Be a rubber duck for [problem]" | Claude listens and asks questions to help you think aloud |

---

## 3. Writing & Structural Frameworks

> Use these to shape the *format and flow* of Claude's output.

| Code / Term | How to Use | What It Does |
|---|---|---|
| **STAR** | "Structure this as a STAR story" | Situation, Task, Action, Result - case studies & narratives |
| **AIDA** | "Write this using AIDA format" | Attention, Interest, Desire, Action - marketing/copy |
| **PAS** | "Use PAS structure for [copy]" | Problem, Agitate, Solution - persuasive writing |
| **BLUF** | "Use BLUF format" | Bottom Line Up Front - direct, military-style summary |
| **FAB** | "Present this as FAB" | Features, Advantages, Benefits - product writing |
| **SCQA** | "Frame this as SCQA" | Situation, Complication, Question, Answer - consulting structure |
| **ELI5** | "ELI5: [topic]" | Explain Like I'm 5 - radical simplification |
| **TL;DR** | "Add a TL;DR" | Force a short summary at the end |

---

## 4. Roleplay & Persona Codes

> Assign Claude a role or perspective to shift its entire mode of response.

| Code | Example Prompt | What It Does |
|---|---|---|
| **"Act as [role]"** | "Act as a skeptical VC investor" | Adopts a specific professional persona |
| **"Ghost writer mode"** | "Write this in my voice - [samples]" | Mimics your writing style |
| **"Red team this"** | "Red team this business plan" | Adversarially attacks/critiques a plan |
| **"Think step by step"** | "Think step by step about [X]" | Forces visible chain-of-thought reasoning |
| **"Show your reasoning"** | "Show your reasoning for [X]" | Makes Claude explain its logic transparently |
| **"Expert mode"** | "Assume I'm an expert in [field]" | Skips basics; uses technical depth |
| **"Contrarian mode"** | "Be contrarian about [topic]" | Challenges mainstream views |
| **"Mentor mode"** | "Be my mentor on [skill]" | Guides with questions and structured feedback |

---

## 5. Claude Code - Built-in Slash Commands

> These only work inside **Claude Code**, Anthropic's CLI terminal tool.

### Session Management

| Command | What It Does |
|---|---|
| `/help` | Shows all available commands |
| `/clear` | Wipes conversation history for a fresh start |
| `/compact` | Compresses context to save tokens |
| `/exit` | Exit the session (or use `Ctrl+D`) |
| `/status` | Shows version info and connectivity |
| `/cost` | Shows token cost of current session |
| `/context` | Visualizes current context usage |
| `/model` | Switch the Claude model in use |
| `/doctor` | Diagnose configuration issues |

### Workflow & Productivity

| Command | What It Does |
|---|---|
| `/init` | Set up CLAUDE.md and skills for the project |
| `/todos` | View and track tasks |
| `/diff` | Show code differences |
| `/effort` | Set reasoning effort level: `low` / `medium` / `high` / `max` |
| `/voice` | Enable voice input mode |
| `/color` | Toggle colored output |
| `/install-github-app` | Auto-review pull requests via GitHub |
| `/batch` | Orchestrate parallelizable changes across a codebase |
| `/pr-comments` | Fetch and display GitHub PR comments |
| `/review-pr` | Review a GitHub pull request with code analysis |
| `/security-review` | Comprehensive security vulnerability scan |
| `/schedule` | Schedule recurring tasks via cron triggers |

---

## 6. Claude Code - Bundled Skills

> Skills ship with Claude Code and can be invoked as slash commands. Unlike built-in commands, skills are **prompt-based** - Claude orchestrates the work using tools.

| Skill | What It Does |
|---|---|
| `/batch` | Run parallelizable large-scale codebase changes |
| `/simplify` | Simplify complex code or content |
| `/loop` | Schedule a recurring task using a cron expression |
| `/debug` | Diagnose and fix frozen or broken sessions |
| `/claude-api` | Reference guide for building with the Claude API |

---

## 7. Thinking Depth Trigger Words (Claude Code Only)

> These keywords are mapped to increasing **thinking budgets** in Claude Code's preprocessing layer. They do **not** work in the claude.ai web interface.

| Trigger Word | Token Budget | Best Used For |
|---|---|---|
| `think` | ~4,000 tokens | Moderate complexity; considered responses |
| `think hard` / `megathink` | ~10,000 tokens | Design decisions; multi-option evaluation |
| `think harder` / `ultrathink` | ~32,000 tokens | Architecture, hard bugs, deep analysis |

### Usage Examples

```
Ultrathink about why this auth flow keeps failing intermittently.

Think hard about the best database schema for this multi-tenant system.

Megathink through the trade-offs between these two API designs.
```

> ⚠️ **Warning:** Typing `ultrathink` in Claude.ai chat or the API has no special effect - it is just a regular word. These triggers are exclusive to **Claude Code (terminal)**.

---

## 8. Quick Chat Codes (Works Anywhere)

> These plain-language instructions work in **claude.ai chat**, the mobile app, and the API.

### Output Control

| Code | What It Does |
|---|---|
| `"Be concise"` | Short, tight response |
| `"Be exhaustive"` | Cover everything comprehensively |
| `"Format as a table"` | Structured tabular output |
| `"Use bullet points"` | List-style output |
| `"Give me 3 versions"` | Get multiple variants to choose from |
| `"Compress this"` | Shorten to the bare essentials |
| `"Expand on [X]"` | Go deeper on a specific point |

### Audience & Complexity

| Code | What It Does |
|---|---|
| `"ELI5"` | Explain Like I'm 5 - simple language |
| `"Assume I'm an expert"` | Skip basics; use technical depth |
| `"Use analogies"` | Explain with relatable comparisons |
| `"No jargon"` | Plain English only |

### Quality & Critique

| Code | What It Does |
|---|---|
| `"Critique this"` | Balanced, honest critical review |
| `"Find the flaws in [X]"` | Identify weaknesses or gaps |
| `"Fact-check this"` | Verify claims and flag uncertainty |
| `"What am I missing?"` | Identify blind spots |
| `"Push back on me"` | Argue against my position |

---

## 9. Coding & QA Commands

> Works as plain-language prompts in **Claude.ai chat**. Commands marked *(Claude Code)* require the terminal tool.

### Code Quality & Review

| Command / Phrase | What It Does |
|---|---|
| `"Review this code for bugs, inefficiencies, and style issues"` | Full code audit |
| `"Red team this code"` | Adversarial security/logic attack on your code |
| `"Security review"` / `/security-review` *(Claude Code)* | Scans for exploitable vulnerabilities |
| `"Find edge cases in [function]"` | Surfaces inputs that break the logic |
| `"Write unit tests for this"` | Auto-generates test cases |
| `"Write edge case tests"` | Tests extreme/unusual inputs |
| `"TDD this"` | Write tests first, then implementation |
| `"Refactor this for readability"` | Clean up code without changing behavior |
| `"Refactor for performance"` | Optimize speed and memory |
| `"Explain this code like I'm a junior dev"` | Plain-English walkthrough |

### Debugging

| Command / Phrase | What It Does |
|---|---|
| `"Rubber duck this bug"` | Claude questions as you explain - triggers your own insight |
| `"Debug this step by step"` | Systematic trace through the error |
| `"What could cause [error]?"` | Differential diagnosis of a bug |
| `ultrathink` *(Claude Code only)* | Max reasoning budget - best for hard-to-trace bugs |
| `/debug` *(Claude Code)* | Bundled skill to diagnose stuck/broken sessions |

### Architecture & Design

| Command / Phrase | What It Does |
|---|---|
| `"Design the architecture for [system]"` | High-level system design |
| `"Draw the API schema for [feature]"` | API structure and endpoints |
| `"What design pattern fits this?"` | Pattern recommendation (Factory, Observer, etc.) |
| `"Pre-mortem this architecture"` | Predict failure points before building |
| `"Scaffold [feature] from scratch"` | Generates a full code skeleton |

### Documentation

| Command / Phrase | What It Does |
|---|---|
| `"Write docstrings for this"` | Inline code documentation |
| `"Generate a README for this project"` | Full project documentation |
| `"Write API docs for this endpoint"` | Developer-facing reference docs |

---

## 10. Creativity & Ideation Commands

> All work in **Claude.ai chat** via plain language.

### Brainstorming Modes

| Command / Phrase | What It Does |
|---|---|
| `"Brainstorm 10 ideas for [X]"` | Wide divergent idea generation |
| `"Random brainstorm - no filters"` | Forces unconventional, wild ideas |
| `"Reverse brainstorm"` | "How could we *make this fail*?" - then invert for solutions |
| `"Give me 3 wild versions and 1 safe version"` | Spectrum from bold to safe |
| `"What would [person/brand] do?"` | Perspective-borrowing ideation |
| `"Worst possible idea"` | Deliberately bad ideas that often spark good ones |
| `"Random word association with [topic]"` | Free-association creative trigger |

### Creative Frameworks

| Command / Phrase | What It Does |
|---|---|
| `"Apply SCAMPER to [product/idea]"` | Substitute, Combine, Adapt, Modify, Put to other uses, Eliminate, Reverse |
| `"Lateral thinking on [problem]"` | De Bono's non-linear creative problem solving |
| `"What's the 10x version of this?"` | Forces moonshot thinking |
| `"Six Thinking Hats on [idea]"` | Creative + critical + emotional perspectives in parallel |
| `"Invert this problem"` | Solve by figuring out what to avoid |

### Writing & Storytelling

| Command / Phrase | What It Does |
|---|---|
| `"Write in the style of [author/brand]"` | Voice and style mimicry |
| `"Give me 5 plot twists within [constraint]"` | Constrained narrative ideation |
| `"Write a beat sheet for [story]"` | Story structure skeleton before full draft |
| `"Voice-lock this"` | Lock a distinctive writing style across a long piece |
| `"Time-box brainstorm: 3 rounds, rotating constraints"` | Sprint-style creative iteration |

---

## 11. Productivity & Planning Commands

> All work in **Claude.ai chat** via plain language. Commands marked *(Claude Code)* require the terminal tool.

### Task & Project Management

| Command / Phrase | What It Does |
|---|---|
| `"GTD process this list"` | David Allen's Getting Things Done - capture, clarify, organize, reflect |
| `"Time-block my day around [priorities]"` | Generates a structured daily schedule |
| `"MoSCoW prioritize this backlog"` | Must have, Should have, Could have, Won't have |
| `"Eisenhower Matrix this task list"` | Sort by Urgent/Important quadrants |
| `"Write a project brief for [X]"` | Scope, goals, stakeholders, timelines |
| `/todos` *(Claude Code)* | View and track tasks inside a session |

### Meeting & Communication

| Command / Phrase | What It Does |
|---|---|
| `"Write meeting notes in BLUF format"` | Bottom line up front - action items first |
| `"Turn this into an action list"` | Converts messy notes into trackable tasks |
| `"Draft a project status update"` | Concise stakeholder communication |
| `"OKR this goal"` | Objectives and Key Results framework |
| `"Write a one-pager for [project]"` | Executive summary format |

### Thinking & Reflection

| Command / Phrase | What It Does |
|---|---|
| `"Brain dump and organize"` | Freestyle input → structured output |
| `"Weekly review my notes"` | GTD-style reflection on progress and open loops |
| `"What am I missing in this plan?"` | Blind spot check |
| `"Second-order effects of [decision]"` | Long-range consequence mapping |
| `"Pre-mortem this plan"` | Identify risks before committing resources |

---

## 12. Important Notes & Tips

### Where Each Type Works

| Feature | Claude.ai Chat | Claude Code (Terminal) | API |
|---|---|---|---|
| Prompt Frameworks (SWOT, OODA, etc.) | ✅ | ✅ | ✅ |
| Slash Commands (`/clear`, `/compact`) | ❌ | ✅ | ❌ |
| `ultrathink` / thinking triggers | ❌ | ✅ | ❌ |
| Quick Chat Codes | ✅ | ✅ | ✅ |
| Custom Slash Commands (`.claude/commands/`) | ❌ | ✅ | ❌ |
| Coding & QA Prompts | ✅ | ✅ | ✅ |
| Creativity & Ideation Prompts | ✅ | ✅ | ✅ |
| Productivity & Planning Prompts | ✅ | ✅ | ✅ |

### Best Practices

- **Match depth to complexity** - Don't `ultrathink` a simple question; save it for architecture decisions and hard bugs.
- **Combine frameworks** - "Do a SWOT + Second-Order Thinking on [X]" works well.
- **Steelman before critiquing** - Ask Claude to steelman an argument before red-teaming it for balanced analysis.
- **Use `/effort max` for persistence** - Instead of typing `ultrathink` every prompt in Claude Code, set `/effort max` for the full session.
- **BLUF for busy readers** - Prefix any long output request with "BLUF format" to get the conclusion first.
- **Chain categories together** - "GTD process this list → MoSCoW prioritize → brainstorm solutions for top 3 using SCAMPER" runs a full planning + ideation workflow in one conversation.
- **Rubber duck before asking for a fix** - Explaining the bug to Claude often surfaces the answer before Claude even responds.
- **Use beat sheets before full drafts** - For any long creative piece, ask for a beat sheet first to lock structure before investing in prose.

---