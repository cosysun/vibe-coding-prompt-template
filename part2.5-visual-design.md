# Part 2.5 - Visual Design with AI Design Tools *(Optional)*

This optional stage helps you generate professional UI mockups and design systems using AI-powered design tools before diving into technical implementation. Visual designs improve communication with developers and ensure a consistent user experience.

<details>
<summary><b>📁 Before We Start - Required Document</b></summary>

### Required:
- **PRD Document** (from Part II) - Contains your app's features, user flows, and UX requirements

### Optional but Helpful:
- **Research Findings** (from Part I) - Competitor UI analysis and design trends
- **Brand Guidelines** - If you have existing colors, logos, or style preferences

Please attach these files or paste their content.

</details>

<details>
<summary><b>🎨 When to Use This Step</b></summary>

### ✅ Do this step if:
- You're building user-facing apps (web, mobile, desktop)
- You want to validate UX flows before coding
- You're working with a team and need shared vision
- Your PRD includes complex interfaces or multiple user roles

### ⏭️ Skip this step if:
- Building APIs, CLI tools, or backend services
- Using no-code platforms (Bolt.new, Lovable) that generate UI automatically
- You prefer to iterate in code directly (developer workflow)
- Time-constrained and can design while coding

</details>

Once you've attached your PRD, please tell me:

**A) What's your technical level?**
- A) **Vibe-coder** - I want AI to design everything for me
- B) **Designer/Developer** - I'll guide the design with AI assistance
- C) **Somewhere in between** - Help me learn design basics

**B) Which design tool will you use?** (Choose one or say "help me decide")
- 1) **Figma** - Industry standard, AI features, great for teams
- 2) **Uizard** - Text-to-design, fastest for complete mockups
- 3) **Galileo AI** - High-quality designs from text descriptions
- 4) **v0 by Vercel** - Generate React/Tailwind components directly
- 5) **Framer** - Design + prototype + publish in one tool
- 6) **Adobe Firefly + XD** - Adobe's AI design suite
- 7) **Canva (Design AI)** - Beginner-friendly, quick mockups
- 8) **Help me decide** - Recommend based on my needs

Please attach your PRD and type your answers (e.g., "A, 1" or "B, help me decide"):

---

## Instructions for AI Assistant

<details>
<summary><b>🤖 AI Platform Recommendations for Design</b></summary>

### Best Platforms for Design Prompt Generation
- **Claude.ai** – Strong visual reasoning and design system logic
- **ChatGPT** – Good at generating design tool prompts and component descriptions
- **Gemini** – Handles complex design requirements with large context

### Design Tool Ecosystem & Selection Guide

| Tool | Best For | Learning Curve | Cost | Output Format |
|------|----------|----------------|------|---------------|
| **Figma** | Professional teams, design systems | Medium | Free + Pro ($12/mo) | Figma files, exports |
| **Uizard** | Complete app mockups fast | Low | Free + Pro ($12/mo) | PNG, Figma, code |
| **Galileo AI** | High-fidelity designs from text | Low | Waitlist/Paid | Figma files |
| **v0 by Vercel** | React components (code-first) | Medium | Free + Pro ($20/mo) | React/Tailwind code |
| **Framer** | Interactive prototypes | Medium | Free + Pro ($5/mo) | Live websites |
| **Adobe XD + Firefly** | Adobe ecosystem users | Medium | Creative Cloud | XD files, exports |
| **Canva** | Quick mockups, non-designers | Very Low | Free + Pro ($13/mo) | PNG, PDF |

### Tool Recommendation Logic

When user says **"Help me decide"**, recommend based on:

**For Vibe-coders (A):**
- **Primary**: Uizard (fastest, easiest)
- **Alternative**: Canva Design AI (most beginner-friendly)
- **If team collaboration**: Figma (industry standard)

**For Designers/Developers (B):**
- **Primary**: Figma (most powerful, best handoff)
- **Alternative**: v0 (if they want code directly)
- **If interactive prototypes needed**: Framer

**For In-Between (C):**
- **Primary**: Figma (good learning investment)
- **Alternative**: Uizard (faster results while learning)

**Consider PRD factors:**
- **Complex interactions?** → Framer or Figma
- **Design system needed?** → Figma
- **Want code output?** → v0 by Vercel
- **Time-constrained?** → Uizard or Canva
- **Team handoff required?** → Figma (industry standard)

</details>

Wait for the user to attach their PRD document and provide their technical level (A/B/C) and tool choice (1-8 or "help me decide").

**If user says "help me decide":**
1. Read their PRD for complexity assessment
2. Consider their technical level (A/B/C)
3. Recommend 2-3 tools with reasoning
4. Let them choose or pick the top recommendation

**After tool selection, read PRD thoroughly to understand:**
- Target users and their needs
- Core features and user flows
- UI/UX requirements mentioned
- Brand personality and "vibe" described

> **Important**: After reading the PRD, do a **Context Summary** before proceeding. Confirm you understand the app's purpose, key screens needed, and design priorities.

### Questions for ALL Users:

**Q1:** "Based on your PRD, what screens/views does your app need? Let me suggest a list, then you can adjust:
- [List 5-8 key screens based on PRD features]
- Did I miss anything important?"

**Q2:** "What's your design inspiration? Share any of these:
- Apps you admire (e.g., 'Clean like Linear', 'Fun like Duolingo')
- Links to designs you like
- Colors/moods (e.g., 'Professional blue', 'Warm and friendly')
- Or say 'Help me decide' and I'll suggest based on your PRD"

### Path A - Vibe-Coder Questions:

**Q3:** "Let's define your color palette! Pick one or tell me more:
- A) **Fresh & Modern** - Blue/teal with white space
- B) **Bold & Energetic** - Vibrant colors, high contrast
- C) **Professional & Trust** - Navy, gray, minimal
- D) **Warm & Friendly** - Orange, yellow, soft tones
- E) **Dark Mode First** - Dark backgrounds, neon accents
- F) **Custom** - Tell me your favorite colors"

**Q4:** "Typography vibe?
- A) **Clean & Modern** - Sans-serif, lots of breathing room
- B) **Friendly & Approachable** - Rounded fonts, casual
- C) **Professional & Serious** - Traditional, structured
- D) **Creative & Unique** - Mix of styles, personality
- E) **Help me decide** based on my app"

**Q5:** "Component style preference?
- A) **Minimal** - Flat, simple, no decorations
- B) **Soft** - Rounded corners, subtle shadows
- C) **Bold** - Strong borders, clear divisions
- D) **Glassmorphism** - Blur effects, transparency
- E) **Show me examples** of each"

**Q6:** "Do you need icons or illustrations?
- A) Simple line icons (minimal)
- B) Filled/solid icons (bold)
- C) Custom illustrations (unique)
- D) Photos/realistic images
- E) Mix of icons and illustrations
- F) I don't know what works best"

**Q7:** "Mobile-first or desktop-first?
- A) **Mobile-first** - Most users on phones
- B) **Desktop-first** - Primarily web app
- C) **Both equally** - Responsive across all devices
- D) **Help me decide** based on my users"

### Path B - Designer/Developer Questions:

**Q3:** "Design system requirements?
- Color palette: [Specify or need AI suggestions]
- Typography: [Font choices or need recommendations]
- Spacing scale: [8pt grid, 4pt, custom]
- Border radius: [Sharp, rounded, very rounded]
- Shadow strategy: [None, subtle, pronounced]
- Breakpoints: [Mobile/tablet/desktop or custom]"

**Q4:** "Component library approach?
- Using existing: [Material/Ant/Chakra/Shadcn/Custom]
- Building custom components
- Hybrid: Base library + custom components
- Need recommendations based on tech stack"

**Q5:** "Design deliverables needed?
- High-fidelity mockups for all screens
- Key user flows only
- Component library/design system
- Interactive prototype
- Design tokens (JSON/CSS variables)
- Figma Dev Mode ready assets
- What else?"

**Q6:** "Accessibility requirements?
- WCAG level: [A/AA/AAA]
- Color contrast ratios: [Will verify]
- Keyboard navigation: [Required]
- Screen reader support: [Level]
- Focus indicators: [Visible states]
- Reduced motion support: [Yes/No]"

**Q7:** "Animation and interaction preferences?
- Micro-interactions: [Hover/click/focus states]
- Transitions: [Page/component animations]
- Loading states: [Spinners/skeletons/progress]
- Empty states: [Illustrations/messaging]
- Error states: [Inline/toast/modal]
- Success feedback: [Visual confirmations]"

### Path C - In-Between Questions:

**Q3:** "Let's start with colors! Based on your PRD:
- Primary color (main actions, brand): [Suggest based on PRD or ask]
- Secondary colors (variety): [Suggest 1-2 options]
- Background/surface colors: [Light/dark preferences]
- Text colors: [Ensure good contrast]
- Does this palette feel right for your app?"

**Q4:** "Typography - let's keep it simple:
- Headings: [Suggest bold, clear font]
- Body text: [Suggest readable font]
- Sizes: [I'll recommend a scale]
- Sound good or want to customize?"

**Q5:** "How polished should it look?
- A) **MVP sketches** - Low-fidelity, just layout/flow
- B) **Professional mockups** - High-fidelity, ready to show users
- C) **Design system** - Reusable components for developers
- D) **Help me choose** what's right for my stage"

**Q6:** "Component style - pick what appeals to you:
- [Show 3 examples with images: Minimal, Soft/Rounded, Bold]
- Or describe the feeling you want (modern, playful, serious, etc.)"

**Q7:** "Which devices should I design for first?
- Primary: [Mobile/Desktop/Tablet]
- Also support: [Other devices]
- Need help deciding based on your users?"

---

## After All Questions - Generate Design Brief

<details>
<summary><b>🎨 Generation Template for AI Assistant</b></summary>

After completing the Q&A, generate a comprehensive **Design Brief** document with these sections:

### 1. Project Overview
```markdown
# Design Brief: [App Name]

## App Summary
[1-2 sentence summary from PRD]

## Target Users
[Primary user persona from PRD]

## Design Goals
- Goal 1: [e.g., "Make complex features feel simple"]
- Goal 2: [e.g., "Build trust through professional design"]
- Goal 3: [e.g., "Stand out from competitors with unique style"]
```

### 2. Design System

```markdown
## Color Palette

### Primary Colors
- **Primary**: #[HEX] - [Usage description]
- **Secondary**: #[HEX] - [Usage description]

### Neutral Colors
- **Background**: #[HEX]
- **Surface**: #[HEX]
- **Text Primary**: #[HEX]
- **Text Secondary**: #[HEX]
- **Border**: #[HEX]

### Semantic Colors
- **Success**: #[HEX]
- **Warning**: #[HEX]
- **Error**: #[HEX]
- **Info**: #[HEX]

[Include color swatches if possible]

## Typography

### Font Families
- **Headings**: [Font name] - [Why this choice]
- **Body**: [Font name] - [Why this choice]
- **Code/Mono** (if needed): [Font name]

### Type Scale
- **H1**: [size]px / [line-height] - [use case]
- **H2**: [size]px / [line-height] - [use case]
- **H3**: [size]px / [line-height] - [use case]
- **Body**: [size]px / [line-height]
- **Small**: [size]px / [line-height]

## Spacing & Layout
- **Base unit**: [4px/8px]
- **Spacing scale**: [4, 8, 16, 24, 32, 48, 64]px
- **Max content width**: [1200px/1440px]
- **Grid**: [12-column/16-column]

## Components Style
- **Border radius**: [0px/4px/8px/16px]
- **Shadows**: [None/Subtle/Pronounced]
- **Borders**: [Style and color]
- **Button style**: [Filled/Outlined/Ghost]
- **Input style**: [Rounded/Sharp/Underlined]
```

### 3. Screen Inventory

```markdown
## Key Screens to Design

[For each screen from Q1, provide:]

### [Screen Name]
**Purpose**: [What user accomplishes here]
**Priority**: [High/Medium/Low for MVP]
**Key components**:
- Component 1
- Component 2
- Component 3

**Layout notes**: [Any specific requirements]
**User flow**: [How user arrives/exits this screen]
```

### 4. Tool-Specific Design Prompts

Generate prompts tailored to the user's chosen tool:

```markdown
## [Tool Name] AI Prompts

[Generate 3-5 prompts specifically formatted for their chosen tool]

### For Figma Users:

#### Prompt 1: Design System Setup
\`\`\`
Create a design system for [App Name], a [app type] targeting [users].

Color palette:
- Primary: #[HEX] ([color name])
- Secondary: #[HEX] ([color name])
- Background: #[HEX]
- Text: #[HEX]

Typography:
- Headings: [Font name], bold, [sizes]
- Body: [Font name], regular, 16px

Components needed:
- Buttons (primary, secondary, ghost)
- Input fields (text, email, password)
- Cards with shadows
- Navigation bar
- [Other key components]

Style: [minimal/modern/playful/professional], [rounded/sharp] corners, [flat/subtle shadows]
\`\`\`

#### Prompt 2: [First Key Screen]
\`\`\`
Design a [screen name] for [App Name].

Layout:
- [Describe layout structure]

Elements needed:
- [List specific UI elements]

User flow:
- [Describe what happens on this screen]

Style: Follow the design system with [color] primary buttons, [style] cards, and [typography] headings.
\`\`\`

[Additional screen prompts...]

### For Uizard Users:

#### Main Project Prompt
\`\`\`
Create a [app type] called [App Name] for [target users].

Screens needed:
1. [Screen 1] - [purpose]
2. [Screen 2] - [purpose]
3. [Screen 3] - [purpose]
[...]

Style: [modern/minimal/playful/professional]
Colors: [primary color] primary, [secondary color] accents
Features:
- [Key feature 1]
- [Key feature 2]
- [Key feature 3]

Make it look like [reference app if mentioned] but with [unique differentiator].
\`\`\`

### For Galileo AI Users:

#### Prompt Template
\`\`\`
Design a [specific screen] for [App Name].

Context: This is a [app description] for [target users who want to solve X problem].

This screen should:
- [Purpose of screen]
- Include [specific UI elements]
- Feel [design mood/style]
- Use [color preferences]

User arrives here from [previous screen] and can [actions available].
Success state: [what user accomplishes]
\`\`\`

[Generate 5-8 screen-specific prompts]

### For v0 by Vercel Users:

#### Component Prompts
\`\`\`
Create a [component name] component using React and Tailwind CSS.

Features:
- [Feature 1]
- [Feature 2]
- [Feature 3]

Style:
- Colors: [use these hex codes]
- Spacing: [tight/normal/spacious]
- Border radius: [none/sm/md/lg]
- Shadow: [none/sm/md/lg]

Interactions:
- [Hover states]
- [Click behaviors]
- [Loading states if applicable]

Make it responsive for mobile and desktop.
\`\`\`

[Generate prompts for each major component]

### For Framer Users:

#### Project Setup Prompt
\`\`\`
Create an interactive prototype for [App Name].

Screens: [list main screens]

Interactions:
- [Screen A] → [Screen B] when [action]
- [Component X] has hover state showing [state]
- [Button Y] has click animation: [animation]

Design style:
- [Style description]
- Colors: [palette]
- Fonts: [typography]

Make transitions smooth and natural.
\`\`\`

### For Adobe XD + Firefly Users:

#### Firefly Generation Prompts
\`\`\`
[For each screen]

Generate a [screen type] interface for [App Name].

Include:
- [UI elements]
- [Layout structure]

Style: [mood], [era], [artistic reference]
Colors: [palette description]

Artistic direction: [inspirations]
\`\`\`

Then import to Adobe XD and:
- Add interactions
- Create component library
- Set up auto-layout

### For Canva Users:

#### Design Brief for Canva
\`\`\`
Create mockups for [App Name] screens.

For each screen, use:
- Template: [suggest Canva template type]
- Colors: [palette]
- Fonts: [font choices]
- Elements: [what to include]

Screens to create:
1. [Screen name] - [elements]
2. [Screen name] - [elements]
[...]

Export as PNG at 1920x1080 for desktop, 375x812 for mobile.
\`\`\`
```

```markdown
## Design Deliverables Checklist

After generating designs, export these for developers:

- [ ] **Design system documentation**
  - [ ] Color variables (CSS/JSON)
  - [ ] Typography scale (CSS)
  - [ ] Spacing tokens
  - [ ] Component specifications

- [ ] **Screen mockups**
  - [ ] All key screens in high-fidelity
  - [ ] Mobile and desktop versions (if responsive)
  - [ ] Different states (empty, loading, error, success)

- [ ] **Assets**
  - [ ] Logo (SVG + PNG)
  - [ ] Icons (SVG or icon font)
  - [ ] Illustrations (if custom)
  - [ ] Images (optimized)

- [ ] **Interactive prototype** (optional)
  - [ ] User flow connections
  - [ ] Clickable prototype for testing

- [ ] **Developer handoff**
  - [ ] Figma Dev Mode enabled
  - [ ] Component specs documented
  - [ ] Responsive breakpoints noted
  - [ ] Animation/interaction notes

## Next Steps

**Save this as** `DesignBrief-[AppName]-MVP.md` in your project's `docs/` folder.

Save all designs to:
\`\`\`
your-app/
├── docs/
│   └── designs/
│       ├── design-brief.md (this document)
│       ├── mockups/ (PNG/PDF exports)
│       ├── design-tokens.json
│       ├── assets/ (logos, icons, images)
│       └── figma-link.txt (link to Figma file)
\`\`\`

### Your Documents So Far:
1. ✅ Research findings (Part I)
2. ✅ PRD - what to build (Part II)
3. ✅ Design Brief - visual system (Part 2.5) ← **You are here**

### Next Step:
Proceed to **Part 3 - Technical Design** to plan the technical architecture with your visual designs ready!
```

</details>

---

## Final Instructions for AI Assistant

After generating the Design Brief document above, say:

"I've created your Design Brief document above. Here's what to do next:

## 📁 Save Your Design Brief

**Save this as** `DesignBrief-[AppName]-MVP.md` in your project's `docs/` folder.

Create this folder structure for your design assets:

```
your-app/
├── docs/
│   ├── research-[AppName].txt           (from Part I)
│   ├── PRD-[AppName]-MVP.md            (from Part II)
│   └── designs/
│       ├── DesignBrief-[AppName]-MVP.md  ← Save here
│       ├── mockups/                      (Figma exports go here)
│       ├── design-tokens.json            (Export from Figma)
│       ├── assets/                       (logos, icons, images)
│       └── figma-link.txt                (Your Figma file URL)
```

## 🎨 Using Your Chosen Design Tool

Now take the **[Tool Name] AI Prompts** from your Design Brief and:

### If you chose Figma (Option 1):
1. Open [Figma](https://figma.com) and create new design file
2. Use Figma AI chat or plugins (Genius by Diagram, Magician)
3. Paste the prompts from your Design Brief
4. Generate designs, iterate, export to `docs/designs/mockups/`

### If you chose Uizard (Option 2):
1. Go to [uizard.io](https://uizard.io)
2. Paste your main project prompt
3. Let Uizard generate all screens automatically
4. Edit as needed, export as PNG or Figma format

### If you chose Galileo AI (Option 3):
1. Go to [galileo.ai](https://galileo.ai)
2. Paste each screen prompt individually
3. Generate high-fidelity designs
4. Export as Figma files or images

### If you chose v0 by Vercel (Option 4):
1. Go to [v0.dev](https://v0.dev)
2. Generate each component with your prompts
3. Copy the React/Tailwind code directly
4. No need for separate mockups - you have code!

### If you chose Framer (Option 5):
1. Open [Framer](https://framer.com)
2. Use your project setup prompt
3. Build interactive prototype
4. Publish live preview link → save to `figma-link.txt`

### If you chose Adobe XD + Firefly (Option 6):
1. Use Adobe Firefly to generate initial designs
2. Import to Adobe XD
3. Add interactions and components
4. Export assets and share XD file link

### If you chose Canva (Option 7):
1. Go to [Canva](https://canva.com)
2. Use suggested templates from your Design Brief
3. Create each screen mockup
4. Export as PNG/PDF → save to `docs/designs/mockups/`

## 📦 Export Deliverables (when designs are ready):
- Mockups as PNG/PDF → save to `docs/designs/mockups/`
- Design tokens as JSON → save to `docs/designs/design-tokens.json` (if tool supports)
- Assets (logos, icons) → save to `docs/designs/assets/`
- Design file link → save URL to `docs/designs/figma-link.txt` (or tool-appropriate name)

## 📋 Your Documents So Far
1. ✅ Research findings (Part I)
2. ✅ PRD - what to build (Part II)
3. ✅ Design Brief - visual system (Part 2.5) ← **You are here**

## 🚀 Next Step
Proceed to **Part 3 - Technical Design** to plan your technical architecture!

**Note**: You can start Part 3 now and generate Figma designs in parallel, or complete the designs first - your choice. The Design Brief gives developers everything they need even without Figma mockups.

Would you like me to clarify anything in the Design Brief, or are you ready to move to Part 3?"

</details>

---

## Success Criteria

By the end of this stage, you should have:

✅ **Design Brief** document with complete design system specifications
✅ **Figma AI prompts** ready to generate your designs
✅ **Screen inventory** with all key views identified
✅ **Color palette** and typography defined
✅ **Component style guide** documented
✅ *(Optional)* **Figma mockups** generated and exported

**Time investment**: 10-20 minutes for brief creation + 20-40 minutes for design generation

---

## Pro Tips

💡 **Start with design system, then screens** - Consistency is easier when you define tokens first

💡 **Generate multiple variations** - AI tools can create 3-5 options quickly, pick the best

💡 **Test with users early** - Share mockups before coding to validate UX

💡 **Export design tokens** - Use Figma plugins to convert designs to CSS/JSON for developers

💡 **Keep it simple for MVP** - You can always polish later, focus on clarity over perfection

💡 **Document interactions** - Note hover states, animations, transitions for developers

---

## Common Pitfalls to Avoid

❌ **Designing too many screens** - Focus on core MVP flows only
❌ **Over-polishing** - Perfect pixels matter less than validated UX
❌ **Ignoring mobile** - Design responsive from the start
❌ **Forgetting states** - Remember loading, error, empty, success states
❌ **No design system** - Random colors/spacing creates inconsistency
❌ **Skipping accessibility** - Check color contrast and keyboard navigation

---

*This is an optional stage. If you prefer to design in code or use no-code platforms, skip to Part 3 - Technical Design.*
