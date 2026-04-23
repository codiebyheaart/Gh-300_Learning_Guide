# 🤖 GitHub Copilot Certification (GH-300) — Complete Study Guide

> **Exam Code:** GH-300 | **Provider:** GitHub + Microsoft  
> **Price:** ~$99 USD | **Format:** MCQ + Scenario-based | **Retake:** 24 hrs after first fail  
> 📌 Register Here → https://examregistration.github.com/

---

## 📊 Exam Domain Weightage

| Domain | Weight |
|--------|--------|
| Core Knowledge & Responsible AI | ~22% |
| Plans, Features & IDE Integration | ~15% |
| Prompt Engineering | ~20% |
| Developer Productivity Use Cases | ~20% |
| Agents, CLI, Code Review & Emerging Features | ~23% |

---

## 📚 Main Topics — Detailed Breakdown

### 1️⃣ Core Knowledge & Responsible AI (22%)
- How GitHub Copilot works internally (prompt → filter → suggestion pipeline)
- AI hallucinations — what they are, how to handle
- Bias in AI-generated code — identification & mitigation
- Responsible AI principles (fairness, transparency, accountability)
- Content exclusions & intellectual property safeguards
- Duplication detector — what it does, when to enable it
- Telemetry and data collection policies

### 2️⃣ Plans, Features & IDE Integration (15%)
- **Free Plan** — limited completions, basic chat
- **Pro Plan** — unlimited completions, advanced models
- **Business Plan** — org-level policy, audit logs, seat management
- **Enterprise Plan** — fine-tuned models, Copilot Knowledge Bases, advanced security
- Supported IDEs: VS Code, Visual Studio, JetBrains, Neovim, Eclipse, Xcode
- Organization-wide policy management
- Audit logs — how to search & review Copilot Business events
- Seat management via REST API

### 3️⃣ Prompt Engineering (20%)
- **Zero-shot prompting** — no examples, direct instruction
- **Few-shot prompting** — give examples before asking
- Inline comments as prompts (`// function to parse JSON`)
- Context window — what Copilot sees (open files, cursor position)
- **Slash Commands:**
  - `/fix` — fix a bug in selected code
  - `/explain` — explain what code does
  - `/tests` — generate unit tests
  - `/doc` — generate documentation
  - `/optimize` — refactor for performance
- **Chat participants (@ symbols):**
  - `@workspace` — context of entire project
  - `@vscode` — VS Code specific questions
  - `@terminal` — terminal command help
- **Prompt file reuse** — `.github/prompts/` folder for consistent responses
- `copilot-instructions.md` — repo-level behavior customization

### 4️⃣ Developer Productivity Use Cases (20%)
- Code completion (inline ghost text suggestions)
- Code refactoring and modernization
- Debugging assistance — error explanation
- Documentation generation
- Unit & integration test generation
- Sample/dummy data generation
- Multi-language support (30+ languages)
- App modernization (.NET/Java)
- Measuring productivity via Copilot metrics API

### 5️⃣ Agents, CLI, Code Review & Emerging Features (23%)

#### 🤖 Agent Mode
- Agent Mode = Copilot can autonomously complete multi-step tasks
- Can: open PRs, update code, respond to review comments, run terminal commands
- **Sub-Agents** — delegate subtasks for optimized context usage
- **Agent Sessions** — manage ongoing autonomous workflows
- Generally Available (GA) since Sept 2025
- Supported in VS Code, Visual Studio (with MCP tools)

#### 🖥️ Copilot CLI
- `gh copilot suggest` — get shell command suggestions
- `gh copilot explain` — explain a shell command
- Image input using `@` symbol
- Direct shell commands with `!`
- Supports switching AI models (including Claude Sonnet)
- Enhanced enterprise authentication
- New CLI (preview) is replacing `gh-copilot` extension

#### 👀 Copilot Code Review
- AI-powered PR code review — Generally Available (GA)
- Configurable review standards via `.github/` instructions files
- Org-level policy to enable/disable code review
- Works on github.com and IDE
- Customizable review standards per repository

#### 🌐 Copilot Spaces
- Shared project context for teams — GA since Sept 2025
- Create a "space" with files, docs, and context
- Team members get consistent Copilot responses based on shared context

#### 🔌 MCP (Model Context Protocol)
- Extends Copilot with external tool integrations
- MCP servers connect Copilot to external services
- Used in Agent Mode and Edit Mode workflows

#### ✏️ Edit Mode
- Copilot edits multiple files simultaneously based on one instruction
- Different from Agent Mode: Edit Mode = you control, Agent = autonomous

---

## 🔗 Official & Free GitHub Resources

| Resource | Link |
|----------|------|
| 🎓 Official Certification Page | https://learn.microsoft.com/en-us/credentials/certifications/github-copilot/ |
| 📖 GH-300 Study Guide | https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-300 |
| 💬 GitHub Community Exam Prep | https://github.com/orgs/community/discussions/144939 |
| 📚 Study Guide Repo (Berezhnyk) | https://github.com/Berezhnyk/github-copilot-certification-study-guide |
| 🛠️ Cert Prep Repo (Timothy Warner) | https://github.com/timothywarner-org/copilot-cert-prep |
| 🧪 Exam Sandbox (Try before buy) | https://learn.microsoft.com/en-us/credentials/certifications/github-copilot/ |
| 📝 Exam Registration | https://examregistration.github.com/ |

---

## ❓ Q & A — Important Questions for Exam

### 🤖 Why Agents? (Agent Mode)

**Q: Why was Agent Mode introduced in GitHub Copilot?**  
A: Agent Mode was introduced to allow Copilot to autonomously complete complex, multi-step development tasks — like creating files, running tests, opening pull requests — without the developer manually triggering each step. It transforms Copilot from a reactive suggestion tool into a proactive AI coding partner.

**Q: What is the difference between Agent Mode and Edit Mode?**  
A: Edit Mode allows Copilot to edit multiple files simultaneously based on a single instruction, but the developer stays in control. Agent Mode is fully autonomous — Copilot creates a plan, executes steps (including terminal commands), and can open PRs with minimal human intervention.

**Q: What are Sub-Agents?**  
A: Sub-Agents are delegated tasks within an Agent Session. When a task is complex, the main agent can break it into subtasks handled by sub-agents to optimize context usage and parallel processing.

---

### 🖥️ Why Copilot CLI?

**Q: What is the purpose of GitHub Copilot CLI?**  
A: Copilot CLI brings AI assistance directly into the terminal. Developers can use `gh copilot suggest` to get shell command recommendations and `gh copilot explain` to understand complex commands — without switching to a browser or IDE.

**Q: What are the key CLI commands to know for the exam?**  
A: 
- `gh copilot suggest` → suggest a shell command for a task
- `gh copilot explain` → explain what a command does
- `!` prefix → run direct shell commands
- `@` prefix → reference image files as input

**Q: How do you switch AI models in Copilot CLI?**  
A: The new Copilot CLI supports model switching directly in the terminal interface — you can select models like Claude Sonnet or GPT-5 based on your plan and task requirements.

---

### 👀 Why Code Review?

**Q: What is GitHub Copilot Code Review?**  
A: Copilot Code Review is an AI-powered feature that automatically reviews pull requests, identifies bugs, suggests improvements, and checks code against customizable standards — reducing manual review time.

**Q: How can organizations customize Copilot Code Review standards?**  
A: Organizations can configure review standards by placing instructions files in the `.github/` directory of their repositories. These files tell Copilot what coding standards, security rules, or style guides to enforce.

**Q: Is Copilot Code Review available on all plans?**  
A: Code Review policies can be enabled/disabled at the organization level. It's generally available on Business and Enterprise plans and works both on github.com and within supported IDEs.

---

### 🔧 General Exam Q&A

**Q: What is the Copilot Duplication Detector?**  
A: A feature that identifies when Copilot suggestions closely match existing public code. Enabling it helps organizations protect against unintentional code duplication and intellectual property issues.

**Q: What is a `copilot-instructions.md` file?**  
A: A file placed at `.github/copilot-instructions.md` in a repository that customizes Copilot's behavior — like enforcing coding styles, preferred frameworks, or domain-specific instructions for all developers in that repo.

**Q: What is prompt engineering in the context of Copilot?**  
A: Prompt engineering is the practice of crafting effective natural language instructions or code comments to get better, more accurate suggestions from GitHub Copilot. Techniques include zero-shot prompting, few-shot prompting, using slash commands, and controlling context via open files.

**Q: What is Copilot Spaces?**  
A: Copilot Spaces is a collaboration feature where teams create a shared project context (files, docs, instructions) so all team members get consistent and relevant Copilot responses based on the team's specific project.

**Q: How does Copilot handle data privacy?**  
A: GitHub Copilot does not use your private code to train its models by default on Business/Enterprise plans. Organizations can configure content exclusions to prevent specific files or directories from being used as context.

**Q: What is MCP (Model Context Protocol)?**  
A: MCP is a protocol that allows Copilot to connect with external tools and services (databases, APIs, project management tools) through MCP servers — extending what Copilot can do in Agent Mode and Edit Mode.

**Q: How is Copilot's productivity impact measured?**  
A: Via the GitHub Copilot Metrics API — organizations can track completion acceptance rates, active users, suggestions shown vs. accepted, and other productivity indicators to quantify ROI.

**Q: What are the three Copilot Chat modes?**  
A: 
1. **Inline Chat** — opened with `Ctrl+I` / `Cmd+I` directly in the code editor
2. **Panel Chat** — sidebar chat interface in VS Code
3. **Quick Chat** — quick input without opening the full panel

---

## ⚡ Quick Reference Cheat Sheet

| Feature | Shortcut / Command |
|---------|-------------------|
| Open Inline Chat | `Ctrl+I` (Win) / `Cmd+I` (Mac) |
| Accept Suggestion | `Tab` |
| Reject Suggestion | `Esc` |
| Next Suggestion | `Alt+]` |
| Previous Suggestion | `Alt+[` |
| Open Chat Panel | `Ctrl+Alt+I` |
| CLI Suggest | `gh copilot suggest` |
| CLI Explain | `gh copilot explain` |
| Fix Code | `/fix` |
| Generate Tests | `/tests` |
| Explain Code | `/explain` |
| Generate Docs | `/doc` |
| Workspace Context | `@workspace` |
| VS Code Help | `@vscode` |
| Terminal Help | `@terminal` |

---

## 📅 Study Plan (2 Weeks)

| Week | Topics | Resources |
|------|--------|-----------|
| **Week 1** | Core Knowledge, Responsible AI, Plans & Features | Microsoft Learn Modules 1–5 |
| **Week 1** | Prompt Engineering, Slash Commands, Chat Participants | Berezhnyk Repo: 02-prompt-engineering.md |
| **Week 2** | Agent Mode, CLI, Code Review, Spaces, MCP | GH-300 Study Guide + Emerging Features docs |
| **Week 2** | Practice Tests (4 full tests) | Berezhnyk Repo: practice-test-1.md & 2.md |
| **Exam Day** | Quick Reference Cheat Sheet | QUICK-REFERENCE.md (timothywarner repo) |

---

## ✅ Pre-Exam Checklist

- [ ] Read official GH-300 Study Guide completely
- [ ] Completed all Microsoft Learn modules
- [ ] Practiced all slash commands in VS Code
- [ ] Tried Agent Mode on a real project
- [ ] Used Copilot CLI (`suggest` + `explain`)
- [ ] Reviewed PR with Copilot Code Review
- [ ] Understood plan differences (Free/Pro/Business/Enterprise)
- [ ] Know MCP and Copilot Spaces concepts
- [ ] Taken 2+ full practice tests
- [ ] Registered exam with personal MSA account (NOT work account)

---

> 💡 **Pro Tip:** Register with a **personal Microsoft account (MSA)**, NOT your work/organization account. If you use a work account and leave the company, your certification records will be lost permanently.

---

*Made with 💙 after completing GitHub Copilot Certification | GH-300*
