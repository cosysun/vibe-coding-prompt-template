# 🚀 Vibe-Coding Workflow: AI-Powered MVP Development

<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Last Updated](https://img.shields.io/badge/Updated-December%202025-blue.svg)](README.md)

**Build an MVP in hours, not months – guided by the latest AI coding agents**

</div>

---

## 🎯 What This Does

Transform any app idea into working code through 5 AI-powered stages using the latest 2025 AI models:

| # | Stage | Goal | Output |
|---|-------|------|--------|
| 1️⃣ | **Research** | Validate market & tech landscape | Research findings |
| 2️⃣ | **Define** | Clarify product scope | PRD (Product Requirements) |
| 2.5️⃣ | **Visual Design** *(Optional)* | Create UI mockups & design system | Figma designs |
| 3️⃣ | **Design** | Decide how to build | Technical Design doc |
| 4️⃣ | **Generate AI Agent Instructions** | Convert docs into agent blueprints | AGENTS.md + tool-specific config files |
| 5️⃣ | **Build** | Generate & test code | Working MVP |

---

## 🏃 Quick Start

<div align="center">

### ✨ **New: Automated Web App Workflow** ✨

**Skip the manual copy-pasting!**
We now have an interactive web app that automates the entire process for you.

[![Launch Vibe-Coding Webapp](https://img.shields.io/badge/🚀_Launch-Vibe_Coding_Webapp-blue?style=for-the-badge&logo=vercel)](https://vibeworkflow.app/#/vibe-coding)

</div>

<details>
<summary><b>🔥 All-in-One Generator (Fastest - NEW!)</b></summary>

### Complete Your MVP Blueprint in One Session

Use the **Part 0 - MVP Generator** to run through ALL stages in a single AI conversation (30-60 minutes):

1. Copy the entire `part0-mvp-generator.md` file
2. Paste into Claude Pro, Gemini 3 Pro, or ChatGPT Plus (needs 100K+ context)
3. Answer questions as guided (ONE conversation covers all 5 stages)
4. Get ALL documents at once:
   - Research findings
   - PRD document
   - Design brief (optional)
   - Technical design
   - AGENTS.md + all config files
5. Start building immediately!

**Best for**: Quick turnaround, clear ideas, focused sessions, streamlined experience

**Time**: 30-60 minutes total (vs 60-90 min doing stages separately)

</details>

<details>
<summary><b>⚡ Manual Workflow Guide (The Classic Way)</b></summary>

| Step | What You Do | Time | Result |
|:---:|-------------|:----:|--------|
| 📚 | Copy prompts → Answer questions | 20 min | Research doc |
| 📝 | Define your app idea | 15 min | PRD doc |
| 🎨 | *(Optional)* Design UI with Figma AI | 10-20 min | Figma mockups |
| 🏗️ | Choose technical approach | 15 min | Tech Design doc |
| 🤖 | Generate AI instructions | 10 min | AGENTS.md + agent config |
| 💻 | Tell the AI agent: *"Read AGENTS.md and build the MVP"* | 1-3 hrs | **Working MVP!** |

</details>

---

## ✅ Prerequisites

<details>
<summary><b>🤖 AI Platform (Required - Choose One)</b></summary>

### Best Free Options
- **[AI Studio](https://aistudio.google.com)** ⭐ - Gemini 3 Pro free tier with the full 1,048,576-token context ([see model details](https://ai.google.dev/gemini-api/docs))
- **[Claude.ai](https://claude.ai)** - Claude Sonnet 4.5 with 200K default / 1M beta context ([see current versions](https://docs.anthropic.com))
- **[ChatGPT](https://chat.openai.com)** - ChatGPT 5.1 via the Responses interface ([see OpenAI docs](https://developers.openai.com))

### Premium Options (Better for Complete Apps)
- **[Claude Pro](https://claude.ai)** - Sonnet 4.5 with higher rate limits and 1M-token projects ([pricing](https://claude.ai))
- **[Gemini Advanced](https://gemini.google.com)** - Gemini 3 Pro/Flash Ultra access with priority throughput ([pricing](https://gemini.google.com))
- **[ChatGPT Plus](https://chat.openai.com)** - ChatGPT 5.1 with higher allocations ([pricing](https://openai.com/chatgpt))

</details>

<details>
<summary><b>💻 AI Coding Agent/IDE (Required - Choose One)</b></summary>

### Terminal-Based Agents (Advanced)
- **[Claude Code](https://claude.ai/docs/claude-code)** ⭐ - Project-aware CLI with session memory.
  ```bash
  curl -fsSL https://claude.ai/install.sh | bash
  claude init # Generates CLAUDE.md; import AGENTS.md via @AGENTS.md
  ```
- **[Gemini CLI](https://github.com/google/gemini-cli)** - Free & open source with Gemini 3 Pro.
   ```bash
   npm install -g @google/gemini-cli
   gemini login
   # Uses GEMINI.md; import AGENTS.md via @AGENTS.md
   ```
- **[Aider](https://aider.chat)** - CLI tool, requires explicit context loading.
   ```bash
   python -m pip install aider-install
   aider --read AGENTS.md
   ```
- **[GitHub Copilot CLI](https://docs.github.com/en/copilot)** - Terminal interface for Copilot.
   ```bash
   npm install -g @github/copilot
   copilot --context AGENTS.md
   ```
- **[OpenAI Codex CLI](https://developers.openai.com/codex/cli/)** - An open-source, terminal-based coding agent (TUI) that can read, edit, and run code in your repo. ([docs](https://platform.openai.com/docs))
   ```bash
   npm i -g @openai/codex
   codex exec "Summarize AGENTS.md"
   ```

### Async/Cloud Agents
- **[Jules by Google](https://jules.google/docs)** ⭐ - Vertex AI-connected async agent.
- **[GitHub Copilot Agent](https://github.com/features/copilot)** - VS Code extension; enable `chat.useAgentsMdFile` to read AGENTS.md.

### IDE-Based Tools (Beginner Friendly)
- **[Cursor](https://cursor.com)** ⭐ - AI editor that automatically reads `AGENTS.md`.
- **[Windsurf](https://codeium.com/windsurf)** ⭐ - IDE by Codeium; reads `AGENTS.md` and `.windsurf/rules`.
- **[Cline](https://docs.cline.dev)** - VS Code extension; reads `AGENTS.md` and `.clinerules`.
- **[Google Antigravity](https://antigravity.google)** - Agent-first IDE; manually add `AGENTS.md` content to Knowledge Base.

### No-Code Platforms (Easiest)
- **[Bolt.new](https://bolt.new)** ⭐ - Instant Next.js/Supabase apps.
- **[Lovable](https://lovable.dev)** - Fullstack builder; add `AGENTS.md` to "Custom Knowledge".
- **[v0 by Vercel](https://v0.dev)** - UI composition; add `AGENTS.md` to "Project Instructions".

</details>

<details>
<summary><b>🛠 Basic Requirements</b></summary>

- Any modern browser
- 2-4 hours of time
- Basic computer skills (no coding required!)
- Optional: Node.js 22+ for terminal tools

</details>

---

## 📋 The 5-Step Workflow

### 0️⃣ All-in-One MVP Generator 🔥 *(NEW - Fastest Option)*
<details>
<summary><b>Complete all stages in one AI conversation</b> • 30-60 min • Creates everything at once</summary>

**What this does:** Runs you through ALL stages sequentially in one session - from research to complete AGENTS.md setup.

**How it works:**
1. Copy the entire `part0-mvp-generator.md` file
2. Paste into Claude Pro, Gemini 3 Pro, or ChatGPT Plus (requires 100K+ context)
3. Answer guided questions through all 5 stages in one conversation
4. AI generates all documents automatically:
   - Research findings
   - Complete PRD
   - Design brief (optional)
   - Technical design document
   - AGENTS.md + all agent_docs/ files
   - Tool-specific configs

**💡 Pro Tip:** Use Claude Pro for best results - it handles long contexts exceptionally well.

**When to use:**
- ✅ You have 45-60 minutes of focused time
- ✅ Your idea is relatively clear
- ✅ You want maximum speed and convenience
- ✅ You prefer a guided, streamlined experience

**When to skip:**
- Need to pause between stages for team review
- Want maximum control and iteration at each stage
- Collaborating with multiple stakeholders
- Idea needs deep, extended research

</details>

### 1️⃣ Deep Research 🔍
<details>
<summary><b>Validate your idea with AI-powered market research</b> • 20-30 min • Creates <code>research-*.txt</code></summary>

**What this does:** Analyzes market opportunity, competitors, and technical feasibility using the latest AI models.

**How it works:**
1. Copy the entire `part1-deepresearch.md` file
2. Paste into AI Studio (for Gemini 3 Pro), Claude.ai (for Claude Sonnet 4.5), or ChatGPT (for ChatGPT 5.1)
3. Answer 5-6 questions tailored to your experience level
4. AI generates comprehensive research with:
   - Market analysis & size
   - Competitor breakdown
   - Technical recommendations
   - Cost estimates
   - **Platform review risk assessment** (for App Store/Google Play submissions)
5. Save output as `research-[YourAppName].txt`

**💡 Pro Tip:** Use Gemini 3 Pro for better research (1,048,576-token context window).

**🔒 New: Review Risk Check** - If targeting mobile app stores, the research automatically includes compliance analysis and rejection risk mitigation strategies.
</details>

### 2️⃣ Product Requirements (PRD) 📝
<details>
<summary><b>Define exactly what you're building</b> • 15-20 min • Creates <code>PRD-*.md</code></summary>

**What this does:** Transforms your idea into clear, actionable product specifications.

**How it works:**
1. Copy `part2-prd-mvp.md` into a new AI chat
2. Attach your research findings when prompted
3. Answer questions about:
   - Core features (3-5 must-haves)
   - Target users
   - Success metrics
   - UI/UX vision
4. AI creates professional PRD document
5. Save as `PRD-[YourAppName]-MVP.md`

</details>

### 2.5️⃣ Visual Design with AI Design Tools 🎨 *(Optional)*
<details>
<summary><b>Generate UI mockups and design systems</b> • 10-20 min • Creates Figma designs</summary>

**What this does:** Uses AI-powered design tools to generate professional UI mockups, design systems, and visual components based on your PRD.

**Choose from multiple AI design tools:**
- **Figma** - Industry standard with AI features and plugins
- **Uizard** - Text-to-design, fastest for complete mockups
- **Galileo AI** - High-quality designs from text descriptions
- **v0 by Vercel** - Generate React/Tailwind components directly
- **Framer** - Design + prototype + publish in one tool
- **Adobe XD + Firefly** - Adobe's AI design suite
- **Canva** - Beginner-friendly quick mockups

**Why this helps:**
- **Visual clarity** - See your app before coding
- **Design consistency** - AI generates a cohesive design system
- **Faster iteration** - Test layouts and flows visually
- **Developer handoff** - Export designs to code with AI tools

**How it works:**
1. Copy `part2.5-visual-design.md` into a new AI chat
2. Attach your PRD document
3. Choose your preferred design tool (Figma, Uizard, Galileo AI, v0, Framer, Adobe XD, or Canva)
4. Answer questions about design style, colors, typography, components
5. AI generates:
   - Complete design brief with design system specs
   - Tool-specific prompts ready to paste
   - Screen inventory and component specifications
6. Use the generated prompts in your chosen design tool
7. Export designs and design tokens for developers

**💡 Pro Tips:**
- Let AI recommend the best tool for your needs if unsure
- Generate multiple design variations to compare
- Export design tokens as CSS/JSON for developers
- v0 by Vercel generates code directly - no separate mockups needed!

**When to skip this step:**
- Building CLI tools or headless services
- Using no-code platforms (they handle design)
- Want to iterate in code directly (developer preference)

</details>

### 3️⃣ Technical Design 🏗️
<details>
<summary><b>Plan the technical architecture</b> • 15-20 min • Creates <code>TechDesign-*.md</code></summary>

**What this does:** Decides the best tech stack and implementation approach for 2025.

**How it works:**
1. Copy `part3-tech-design-mvp.md` into a new AI chat
2. Attach your PRD (required) and research (optional)
3. Answer questions about:
   - Platform (web/mobile/desktop)
   - Complexity tolerance
   - Budget constraints
   - Timeline
4. AI recommends optimal stack from:
   - No-code: Bolt.new, Lovable, Bubble
   - Low-code: Next.js + Supabase
   - Full-code: Your preferred framework
5. Save as `TechDesign-[YourAppName]-MVP.md`

</details>

### 4️⃣ Generate AI Agent Instructions 🤖
<details>
<summary><b>Create blueprints for your AI coding assistant</b> • 5-10 min • Creates <code>AGENTS.md</code> + agent configs</summary>

**What this does:** Converts all docs into step-by-step coding instructions for AI agents.

**How it works:**
1. Copy `part4-notes-for-agent.md` into a new AI chat
2. Attach PRD and Technical Design documents
3. AI generates:
   - `AGENTS.md` - Universal instructions (renamed from NOTES.md in v2.0.0)
   - Tool-specific configs (based on your choice):
     - `CLAUDE.md` for Claude Code
     - `GEMINI.md` for Gemini CLI & Antigravity
     - `.aider.conf.yml` for Aider
     - `.clinerules` for Cline
     - `.cursorrules` for Cursor
     - `.windsurfrules` for Windsurf
4. Save all files in your project root

</details>

### 5️⃣ Build with AI Agent 💻
<details>
<summary><b>Let AI build your MVP</b> • 1-3 hrs • Creates working application</summary>

#### Setup by Tool Type

<details>
<summary><b>Terminal Agents (Claude Code, Gemini CLI)</b></summary>

```bash
# Claude Code
npm install -g @anthropic-ai/claude-code
cd your-project
claude init
# Add CLAUDE.md to project root
claude "Read CLAUDE.md and AGENTS.md, then build the MVP"

# Gemini CLI
npm install -g @google-gemini/cli
gemini login
# Add GEMINI.md to project root
gemini "Read GEMINI.md and AGENTS.md, then implement"
```

</details>

<details>
<summary><b>IDE Tools (Cursor, Windsurf)</b></summary>

1. Open your project folder in the IDE
2. Add configuration file:
   - Cursor: `.cursorrules` or `.cursor/rules.mdc`
   - Windsurf: `.windsurfrules`
3. Start with: *"Read AGENTS.md and build the MVP step by step"*

</details>

<details>
<summary><b>No-Code Platforms (Bolt.new, Lovable)</b></summary>

1. Go to platform website
2. Paste your PRD content
3. Say: *"Build this MVP following the specifications"*
4. Deploy instantly with one click

</details>

#### Essential Prompts for Building

**Starting prompts by experience level:**
| Level | First Prompt |
|-------|--------------|
| **Vibe-coder** | *"Read AGENTS.md and agent_docs. Build the MVP step by step. Test after each feature."* |
| **In-Between** | *"Read AGENTS.md and the docs folder. Build core features first, test, then add polish."* |
| **Developer** | *"Review AGENTS.md and architecture. Implement Phase 1 with proper patterns and test coverage."* |

**Follow-up prompts for all levels:**
- *"What's done and what's left?"*
- *"Test [feature] and fix any issues"*
- *"Make it work on mobile"*
- *"Deploy to [platform]"*

</details>

---

## 📁 Final Project Structure

```
your-app/
├── docs/
│   ├── research-YourApp.txt
│   ├── PRD-YourApp-MVP.md
│   ├── designs/                # Optional: Figma exports
│   │   ├── mockups/
│   │   ├── design-tokens.json
│   │   └── assets/
│   └── TechDesign-YourApp-MVP.md
├── agent_docs/                # Detailed context for AI agents
│   ├── tech_stack.md
│   ├── code_patterns.md
│   ├── product_requirements.md
│   ├── design_system.md       # If using Figma designs
│   ├── testing.md
│   └── resources.md           # Curated repos & patterns
├── AGENTS.md                  # Universal AI instructions
├── CLAUDE.md                  # Claude Code config (if using)
├── GEMINI.md                  # Gemini CLI & Antigravity config (if using)
├── .aider.conf.yml            # Aider config (if using)
├── .clinerules                # Cline config (if using)
├── .cursorrules               # Cursor config (if using)
├── .windsurfrules             # Windsurf config (if using)
├── README.md                  # Setup instructions (AI-generated)
├── .env.example               # Environment variables
└── src/                       # Your application code
```

---

## 🆕 What's New in 2025

<details>
<summary><b>Latest AI Models & Capabilities</b></summary>

- See the [v2.0.0 release](https://github.com/KhazP/vibe-coding-prompt-template/releases/tag/v2.0.0) for full tool ecosystem + AGENTS.md updates.

### Model Updates
- **Claude Sonnet 4.5** – September 2025 release with 200K default / 1M beta context and top-tier architecture reasoning
- **Claude Opus (2025 snapshot)** – Handles massive monorepos and multi-hour planning sessions with improved tool use
- **Gemini 3 Pro** – 1,048,576-token input and 65,536-token output windows for deep research and synthesis
- **ChatGPT 5.1** – Responses API with adjustable reasoning effort, faster tool orchestration, and lower latency

### New Tools
- **Claude Code** - Anthropic's project-aware terminal agent with session memory and automated test orchestration
- **Jules** - Google's asynchronous coding agent that can work independently across Vertex AI projects
- **Gemini CLI** - Open-source CLI with direct Gemini 3 Pro/Flash access, live context streaming, and MCP integrations
- **GitHub Copilot Agent Mode** - Workspace automation for scoped plans, PRs, and deployment checklists
- **OpenAI CLI (Responses API)** - Terminal workflow for ChatGPT 5.1 tool-calling pipelines

### Platform Updates
- **Cursor** - Version 2.1 adds improved plan mode, AI code reviews, and instant grep.
- **Windsurf** - Now supports `AGENTS.md` automatically for project context.
- **Cline** - Manages context in three layers (immediate, project, persistent) with auto-truncation.
- **GitHub Copilot CLI** - Version 0.0.365 adds `--silent` option for cleaner output.
- **Bolt.new** - Instant Next.js/Supabase deployments with scheduled automations.
- **Lovable** - "Custom Knowledge" tab for project-wide context.

### Advanced Patterns (Round 2)
- **Anti-Vibe Quality Rules** - Templates now generate strict engineering constraints (type safety, architectural governance) to prevent common AI code mistakes
- **Visual Verification** - Generate-Render-Inspect-Refine loop patterns for UI testing
- **Self-Healing Tests** - Playwright failure auto-repair with ARIA snapshots
- **PER Architecture** - Planner-Executor-Reviewer loop guidance for complex features
- **MCP Integration** - Database, Git, and Memory server configuration patterns
- **Curated Resources** - agent_docs/resources.md with notable repos (awesome-cursorrules, healing-agent)

</details>

---

## 💡 Pro Tips for 2025

<details>
<summary><b>Tool Selection Guide</b></summary>

| Persona | Best Tool Stack | Why it fits | What to watch | Setup time |
|---------|-----------------|-----------|--------------|------------|
| Complete beginner | Lovable • Bolt.new | Paste your idea, get a hosted app. Use "Custom Knowledge" for guidelines. | Daily credit caps; hosted code. | 2–5 min |
| Learning hobbyist | Copilot Agent • Cline | Copilot edits files; Cline manages context layers for you. | Copilot requires subscription; Cline needs API key. | 5–10 min |
| Experienced developer | Cursor • Windsurf | Cursor 2.1 has instant grep; Windsurf reads AGENTS.md automatically. | Usage-based credits; new IDE workflows. | 5–10 min |
| Budget-limited builder | Cline • Gemini CLI | Free to install; Gemini CLI uses free tier API. | Less hand-holding; requires more prompting. | 5–10 min |
| Need-it-today founder | Lovable • v0 | Fastest path to MVP. Use "Project Instructions" for v0 context. | Watch credit burn; plan for security review. | 2–5 min |
| Mobile-first product team | v0 • Flutter + Gemini | v0 sketches mobile UI; Gemini CLI helps with native code. | Mobile features are evolving. | 45–60 min |
| Complex logic engineer | Claude Code • Windsurf | Claude Code has session memory; Windsurf handles deep context. | Claude Code is CLI-based. | 10–15 min |
| Security/compliance lead | Cline (client-side) | All code stays local; persistent context is managed locally. | You define the policy. | 10–20 min |
| Offline/privacy-focused dev | Gemini CLI • Cline | Works with local models (Ollama) or private keys. | Offline mode depends on hardware. | 10–30 min |
| Open-source maintainer | Cline • Aider | Aider explicitly reads AGENTS.md; Cline merges rule files. | Terminal-first or VS Code extension. | 5–10 min |

**Quick Picks (Plain English)**
- Need an MVP tonight? Use Lovable or Bolt.new, then plan a follow-up pass for polish and security.
- Working inside an editor? Cursor or Copilot Agent can code for you—open Cline when you want to double-check every change.
- Huge legacy repo? Bring in Claude Code or Windsurf so the agent “remembers” more of your code at once.
- No budget? Stick with Cline + Gemini CLI and the generous free request limits.
- Mobile-first? Preview flows in v0 Mobile or build native screens with Flutter + Gemini’s suggestions.

**Pricing Guardrails (Nov 2025)**
- Free forever: Gemini Code Assist (6K code reqs/day), Copilot Free (2K completions + 50 chats), Windsurf Free (25 prompts).
- Best under $20: Windsurf Pro $15/mo (500 credits), Copilot Pro $10/mo (Agent Mode), Cursor Pro $20/mo (credit pool + parallel agents).
- Power tiers: Copilot Pro+ $39/mo (1.5K premium calls), Cursor Ultra $200/mo (20× credits), Bolt Pro 200 $200/mo (120M tokens).

**MCP Watch**
- Model Context Protocol (MCP) is a shared standard that lets your AI talk to extra tools (think CI pipelines, databases, ticket queues).
- Cline, Cursor, Claude Code, and Gemini CLI all plug into MCP, but treat those connections like production credentials.

**Caution Flags**
- Claude consumer accounts now offer opt-in data sharing; stick to org workspaces or API keys for sensitive repos.
- Replit Agent 3 can run 200-minute autonomous loops—enable guardrails so retries cannot nuke production data.

**When Not to Use These Tools**
- Native mobile or hardware builds: prefer Flutter + traditional toolchains with AI pairing.
- Regulated workloads needing SOC2/FedRAMP/HIPAA: lean on Copilot Enterprise, Cline with strict policies, or self-hosted stacks.
- Safety-critical or real-time systems: require deterministic, human-led engineering.
- Fundamentals practice: hand-code portions to avoid skipping core concepts.

</details>

<details>
<summary><b>Common Pitfalls & Solutions</b></summary>

| ❌ Pitfall | ✅ Solution |
|-----------|------------|
| Skipping discovery work | Run the Part I research prompt first so the PRD and tech design aren’t guesses |
| Letting agents ship code alone | Ask agents to show their plan, review the diff, and run tests before anything merges |
| Sticker-shock bills | Check credit dashboards weekly and keep a backup stack (Cline + Gemini) that stays free |
| Publishing auto-generated UIs without checks | Test accessibility, security, and performance before launch day |
| Building sensitive apps with personal accounts | Use business plans or API workspaces, switch off data sharing, and keep secrets in vaults |
| Forcing one tool to do everything | Mix and match (IDE + terminal + builder) so each tool covers what it does best |

</details>

---

## 🚨 Troubleshooting

<details>
<summary><b>Quick Fixes for Common Issues</b></summary>

| Problem | Solution |
|---------|----------|
| **"AI ignores my documents"** | Start with: *"First read AGENTS.md, PRD, and TechDesign. Summarize key requirements before coding."* |
| **"Code doesn't match PRD"** | Say: *"Re-read the PRD section on [feature], list acceptance criteria, then refactor accordingly."* |
| **"AI is overcomplicating"** | Add to config: *"Prioritize MVP scope. Offer the simplest working implementation before optimizations."* |
| **"Lost track of progress"** | Ask: *"Update the AGENTS.md progress log and map remaining tasks to implementation phases."* |
| **"Deployment failing"** | Request: *"Walk through deployment checklist, verify env vars, then run the platform-specific health command."* |

</details>

---

## 🤝 Contributing

PRs & issues welcome! Help us improve:
- 🐛 Report issues with prompts
- 💡 Share your success stories
- 🔧 Add new tool configurations
- 📚 Submit example MVPs built with this workflow

---

## 📜 License

Released under the [MIT License](LICENSE).

---

**The best time to build your idea was yesterday.**  
**The second best time is now.** 🚀

*Last updated: November 2025 | Created by the vibe-coding community*

</div>
