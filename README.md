# SlashLogic

SlashLogic is a curated knowledge base of high-performance AI workflows.
It centralizes practical command patterns, reasoning frameworks, and execution templates so prompts become repeatable, structured logic instead of one-off requests.

## What This Project Is

SlashLogic is designed for people who use multiple LLMs and want a single place to:

- Discover proven prompt command patterns quickly
- Reuse strategic thinking frameworks across tools
- Standardize output quality for coding, QA, writing, and planning
- Reduce prompt trial-and-error with reusable structures

## Current Contents

This repository currently includes three model-focused references:

- ChatGPT command patterns and reusable prompt templates
- Claude frameworks, command references, and usage modes
- Gemini triggers, workflow tools, and persona controls

### File Map

| File | Purpose |
|---|---|
| `ChatGPT_AI_Codes.md` | Prompt-command library for analysis, coding, writing, learning, and planning |
| `Claude_AI_Codes.md` | Expanded reference for Claude frameworks, slash commands, and thinking modes |
| `Gemini_AI_Codes.md` | Gemini ecosystem guide with triggers, technical commands, and productivity frameworks |

## How To Use SlashLogic

1. Pick your model reference file.
2. Select a framework or command based on your task type.
3. Apply the usage template below.
4. Iterate by combining multiple commands for better results.

### Universal Prompt Template

```text
[command or framework]
Context:
<your problem, constraints, and relevant details>

Output format:
<table, checklist, code, plan, etc.>

Success criteria:
<how you will evaluate whether the response is useful>
```

### Example

```text
/testcases + /bdd
Context:
Login API with JWT auth and refresh token rotation.

Output format:
Given/When/Then scenarios in a table.

Success criteria:
Includes positive, negative, and edge-case coverage.
```

## Recommended Workflow

- Start broad with an analysis framework (`SWOT`, `OODA`, `5 Whys`)
- Shift to execution commands (`/plan`, `/checklist`, `/roadmap`)
- Add quality gates (`/testcases`, `/security-test`, `/review`)
- Refine final outputs (`/summarize`, `/doc`, `/table`)

## Who This Is For

- Developers and QA engineers
- Product managers and founders
- Technical writers and analysts
- Anyone building repeatable AI-assisted workflows

## Contribution Guidelines

Contributions are welcome. If you want to improve this repository:

1. Add new command libraries with clear categories.
2. Include practical examples for every major command set.
3. Keep terminology consistent across model files.
4. Prefer concise, reusable templates over long prose.

## Roadmap

- Add an automation scripts folder for executable workflow helpers
- Add domain packs (backend, frontend, QA, documentation)
- Add benchmark prompts for quality comparison across models
- Add versioned changelog for command updates

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
