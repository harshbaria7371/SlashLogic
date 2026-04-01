# Gemini AI: Ultimate Reference Guide (2026)

A comprehensive directory of "codes," triggers, and frameworks to maximize the Gemini 3 ecosystem across development, creative, and professional workflows.

---

## 1. Official Google Workspace Extensions (`@` Triggers)
These commands allow Gemini to interact directly with your personal data and live services.

| Trigger | Description | Example Usage |
| :--- | :--- | :--- |
| **@Gmail** | Summarize or search emails. | "@Gmail find the latest feedback on the UI draft." |
| **@Drive** | Analyze files or extract data. | "@Drive summarize the PDF in the 'Project Beta' folder." |
| **@Calendar** | Manage and check your schedule. | "@Calendar find a free slot for a 1-hour focus session." |
| **@Docs** | Create, edit, or summarize documents. | "@Docs draft a 500-word intro for the new manual." |
| **@Sheets** | Process data and export tables. | "@Sheets create a quarterly budget table from this list." |
| **@Tasks** | Add items to your to-do list. | "@Tasks add 'Fix CSS bug' to my high-priority list." |
| **@YouTube** | Search videos and get transcripts. | "@YouTube summarize the key points of the 2026 AI Keynote." |
| **@GoogleMaps** | Real-time directions and travel info. | "@GoogleMaps plan a 3-day itinerary for Tokyo." |

---

## 2. Coding & QA (Technical Triggers)
Specifically for developers and testers using the Gemini CLI or IDE extensions (VS Code, IntelliJ).

* **`/bug`**: Triggers a deep-scan of the current code block to identify logic errors or vulnerabilities.
* **`/debug`**: Prints the model’s internal reasoning/API payload for a specific code generation.
* **`/refactor`**: Rewrites code for better readability or performance (DRY/KISS) without changing logic.
* **`Plan Mode`**: (CLI) Instructions Gemini to generate a step-by-step execution plan *before* modifying files.
* **`TDD`**: (Framework) Instructs Gemini to write unit tests (e.g., PyTest, Jest) *before* the actual function code.
* **`[thinking_level: high]`**: Forces deep reasoning for complex algorithms or multithreaded logic issues.
* **`/mcp`**: Connects to the **Model Context Protocol** to pull in data from local databases or Jira.

---

## 3. Creativity & Ideation (Generative Modes)
Codes used to push Gemini beyond standard responses into lateral thinking and original creation.

* **`SCAMPER`**: A structured brainstorming framework (Substitute, Combine, Adapt, Modify, Put to other use, Eliminate, Reverse).
* **`Six Hats`**: Forces Gemini to analyze an idea from 6 specific perspectives (e.g., Emotional, Critical, Optimistic).
* **`/remix`**: Changes the medium of your input (e.g., "Remix this technical doc into a 1-minute video script").
* **`/muse`**: Sets a "Creative Partner" persona that offers abstract metaphors and "What if?" questions instead of direct answers.
* **`Reverse Brainstorming`**: Asks Gemini to figure out how to *fail* at a goal, helping you see hidden risks.
* **`Canvas Mode`**: Opens a side-by-side interactive space for co-writing or visual prototyping.

---

## 4. Productivity & Planning (Workflow Tools)
Strategic codes for high-level management and time-saving automation.

* **`OODA`**: (Observe, Orient, Decide, Act) Ideal for rapid tactical decision-making.
* **`Eisenhower`**: Automatically sorts your provided task list into the **Urgent/Important Matrix**.
* **`GTD`**: (Getting Things Done) Breaks a massive project into "Next Physical Actions."
* **`/plan`**: Generates a professional project roadmap with milestones, risks, and resource requirements.
* **`Deep Research`**: Triggers a multi-step browsing session to compile a detailed report with verified citations.
* **`5 Whys`**: Root-cause analysis framework to solve persistent workflow bottlenecks.

---

## 5. Persona & Logic "Slash" Commands
General shorthand to shift the AI’s fundamental persona.

* **`/dev`**: **Senior Developer**. No fluff, code-centric, highly efficient.
* **`/tutor`**: **Socratic Guide**. Asks questions to help you learn rather than giving direct answers.
* **`/critic`**: **Steel-Man Critic**. Tries to find every logic gap in your current argument or plan.
* **`/ghost`**: **Discreet Observer**. Mimics the clinical, background-analysis style of "Claude Ghost" mode.
* **`/silent`**: Event-driven mode. Gemini stays silent unless it detects a specific error or condition you set.

---

## 6. System Parameters (Gemini 3 Meta-Codes)
Add these in brackets at the end of a prompt to tune the hardware/software performance.

| Parameter | Function |
| :--- | :--- |
| **`[thinking_level: high/low]`** | Controls the depth of the reasoning engine (Chain-of-Thought). |
| **`[media_res: high]`** | Maximizes vision resolution for analyzing dense images/schematics. |
| **`[creativity: 0.8]`** | (API users) Adjusts the randomness (Temperature) of the output. |
| **`[stateless: true]`** | Wipes the current chat context for a fresh start without closing the tab. |

---