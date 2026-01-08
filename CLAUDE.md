# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **prompt template repository** for the Vibe-Coding workflow - a comprehensive AI-powered process for building MVPs. The repo contains structured prompt templates, not executable code. These templates guide users through:

**0. All-in-One Generator** *(NEW)* - Complete workflow in single session (part0-mvp-generator.md)

**Or individual stages:**
1. **Research** - Market/tech validation (part1-deepresearch.md)
2. **Define** - Product Requirements Document creation (part2-prd-mvp.md)
3. **Visual Design** *(Optional)* - UI mockups & design systems with Figma AI (part2.5-visual-design.md)
4. **Design** - Technical architecture planning (part3-tech-design-mvp.md)
5. **Generate Instructions** - AI agent configuration generation (part4-notes-for-agent.md)
6. **Build** - Actual MVP development (using generated AGENTS.md + tool configs)

## Repository Structure

```
.
├── part0-mvp-generator.md       # NEW: All-in-one workflow generator (meta-prompt)
├── part1-deepresearch.md        # Stage 1: Research prompt builder
├── part2-prd-mvp.md             # Stage 2: PRD generation prompt
├── part2.5-visual-design.md     # Stage 2.5: Figma AI design prompt (optional)
├── part3-tech-design-mvp.md     # Stage 3: Tech design prompt
├── part4-notes-for-agent.md     # Stage 4: Agent config generator
├── README.md                    # Main documentation & workflow guide
├── CONTRIBUTING.md              # PR guidelines & scope
├── SECURITY.md                  # Security best practices for users
└── .github/
    └── ISSUE_TEMPLATE/          # Bug report & feature request templates
```

## Key Architecture Concepts

### All-in-One Generator (Part 0)
The new **part0-mvp-generator.md** is a meta-prompt that orchestrates all workflow stages in a single AI conversation:

**Key Design Decisions:**
- **Sequential Flow**: Runs stages 1-5 in order, building context progressively
- **Context Requirements**: Needs 100K+ token context (Claude Pro, Gemini 3 Pro, ChatGPT Plus)
- **Validation Gates**: Performs "Validation Echo" before generating each major document
- **One-Question-at-a-Time**: Prevents overwhelming users despite being comprehensive
- **Complete Output**: Generates ALL documents (research, PRD, design brief, tech design, AGENTS.md, agent_docs/) in one session

**When Users Should Use Part 0 vs Individual Stages:**
- Part 0: Quick turnaround, clear ideas, focused time blocks, streamlined experience
- Individual Stages: Team collaboration, deep research needs, iterative refinement, learning the process

### Progressive Disclosure System
The Part 4 prompt (part4-notes-for-agent.md) implements a **modular documentation strategy** to prevent context window overload:

1. **AGENTS.md** - High-level roadmap, current state, meta-instructions
2. **agent_docs/** - Detailed implementation specs:
   - `tech_stack.md` - Libraries, versions, setup commands
   - `code_patterns.md` - Coding standards, error handling, naming conventions
   - `product_requirements.md` - PRD content, user stories, success metrics
   - `design_system.md` - Design tokens, component specs (if Figma AI used)
   - `testing.md` - Testing strategy and tools
   - `resources.md` - Curated repos & patterns for advanced projects
3. **Tool-specific configs** - Concise pointers (CLAUDE.md, GEMINI.md, .cursorrules, etc.)

### User Experience Levels
All prompts adapt questioning & output based on three personas:
- **A) Vibe-coder** - Non-technical, needs concept explanations & "what to do next"
- **B) Developer** - Experienced, wants architecture patterns & best practices
- **C) In-Between** - Learning while building

### Meta-Cognitive Instructions
Part 4 generates **high-order thinking prompts** for AI agents:
- "Understand Intent First" before answering
- "Plan Before Coding" with approval gates
- "Test After Changes" for verification loops
- Anti-patterns (what NOT to do)
- Anti-Vibe rules (strict engineering constraints for production quality)

## Common Development Tasks

### Testing the All-in-One Generator (Part 0)
When modifying part0-mvp-generator.md:

1. **Test the flow**: Run through the entire conversation with a test idea
   ```bash
   # Use a real AI platform to validate
   # Expected time: 45-60 minutes
   # Verify all documents are generated correctly
   ```

2. **Check validation gates**: Ensure "Validation Echo" appears before each major document generation

3. **Verify document quality**: Check that generated docs match templates from individual stages

4. **Test different user levels**: Try as Vibe-coder (A), Developer (B), and In-Between (C)

5. **Context management**: Ensure conversation doesn't hit token limits prematurely

### Improving Prompt Templates
When editing part1-4 files (including part2.5):

1. **Read the context**: Review the entire prompt file to understand question flow
   ```bash
   # View the prompt structure
   cat part2.5-visual-design.md
   ```

2. **Preserve the format**: Maintain the user/AI instructions separation
   - Top section: User-facing instructions & platform recommendations
   - `<details>` sections: AI assistant instructions & generation rules

3. **Test the logic**: Ensure question paths (A/B/C) lead to appropriate outputs

4. **Update cross-references**: If changing stage outputs, verify downstream stages still align
   - E.g., if modifying Design Brief format in part2.5, check part4 still extracts design tokens correctly
   - **Important**: If updating individual stage prompts, check if part0-mvp-generator.md needs corresponding updates

### Adding Support for New Design Tools
When adding Figma alternatives (e.g., Uizard, Galileo AI):

1. **Update part2.5-visual-design.md** - Add to tool recommendations table
2. **Add specific prompts** - Include prompt templates for the new tool
3. **Update README.md** - Mention in Stage 2.5 description
4. **Test the workflow** - Verify generated design docs work with part4

### Maintaining Design Tool References
Design AI tools evolve rapidly. When updating:

```bash
# Check current tool mentions
grep -i "figma\|uizard\|galileo\|v0.dev" part2.5-visual-design.md README.md

# Verify URLs are still valid
grep -o "https://[^)]*" part2.5-visual-design.md
```

### Adding New AI Tools/Platforms
When adding support for new coding tools:

1. **Update README.md** - Add to relevant sections:
   - Prerequisites → AI Coding Agent/IDE
   - Tool Selection Guide table
   - Pricing Guardrails

2. **Update part4-notes-for-agent.md** - Add tool option & config generation logic

3. **Test the workflow** - Verify generated config files work with the new tool

### Documentation Updates

```bash
# Check for broken links (no automated tests yet)
grep -r "https://" *.md | cut -d: -f2 | sort -u

# Verify all stage prompts reference current model versions
grep -i "claude\|gemini\|chatgpt" part*.md
```

## Important Constraints

### What This Repo IS
- ✅ Prompt templates for AI-assisted MVP development
- ✅ Workflow documentation & best practices
- ✅ AI tool configuration generators

### What This Repo IS NOT
- ❌ NOT executable application code
- ❌ NOT a code hosting platform for user projects
- ❌ NOT vendor-specific (remains neutral across AI platforms)

### Contribution Scope
See CONTRIBUTING.md for details:
- **In scope**: Prompt clarity, workflow improvements, new tool support, typo fixes
- **Out of scope**: Project-specific prompts, vendor marketing, production code

## Security Considerations

When reviewing changes:
- Ensure prompts don't encourage insecure practices (e.g., hardcoded secrets)
- Verify API key management guidance remains current
- Check that generated AGENTS.md templates include security warnings
- See SECURITY.md for full best practices

## Testing Changes

Since this is a prompt template repository:

1. **Manual validation**: Copy modified prompts to an AI platform and test the question flow
2. **Output verification**: Ensure generated documents (PRD, TechDesign, AGENTS.md) contain expected sections
3. **Cross-tool testing**: If changing Part 4, test that configs work with multiple tools (Cursor, Claude Code, etc.)

## Key Files to Understand First

Before making significant changes, read these in order:
1. **README.md** - Full workflow overview & user journey
2. **part0-mvp-generator.md** - All-in-one generator (newest addition, comprehensive meta-prompt)
3. **part4-notes-for-agent.md** - The most complex individual stage prompt with modular output logic
4. **CONTRIBUTING.md** - Scope & PR guidelines

## Version Notes

- **v2.0.0** introduced AGENTS.md (replacing NOTES.md) + agent_docs/ structure + tool ecosystem
- Models & tools evolve rapidly - last major update: November 2025
- Check README badges for current status
