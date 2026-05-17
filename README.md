# non-ai-design-skill-pack

[한국어](README-KR.md)

A portable design skill pack for AI coding agents.

`non-ai-design-skill-pack` helps AI coding agents create web interfaces that feel intentional, product-specific, accessible, and production-ready instead of generic, over-decorated, or visibly AI-generated.

It is designed for frontend coding, UI redesign, interface review, design-system guidance, landing pages, dashboards, SaaS products, browser extension pages, portfolio sites, technical tools, and AI-assisted web apps.

## Why This Exists

AI-generated UI often fails in predictable ways:

- Generic purple-blue gradients
- Repeated bento grids
- Random glassmorphism
- Decorative neural-network motifs
- Fake dashboard metrics
- Weak information hierarchy
- Overused rounded cards
- Default component-library appearance
- Poor mobile behavior
- Missing hover, focus, loading, empty, and error states
- Interfaces that look like prompt output rather than product design

This skill pack gives an AI agent a stricter design and implementation framework so generated UI has a clear visual thesis, consistent design tokens, usable structure, accessible interactions, and reviewable quality standards.

## Core Idea

Good AI-assisted design should look like a product decision, not a prompt result.

A strong interface should have:

- A specific design direction
- Clear product logic
- Strong visual hierarchy
- Consistent visual tokens
- Accessible controls
- Responsive behavior
- Realistic component states
- Maintainable frontend code

The goal is not to make every interface visually loud. The goal is to make every interface feel authored, coherent, useful, and specific to its product context.

## File Structure

```txt
non-ai-design-skill-pack/
├─ README.md
├─ README-KR.md
├─ SKILL.md
├─ DESIGN.md
├─ references/
│  └─ UI_REVIEW_CHECKLIST.md
└─ examples/
   └─ vibe-coding-platform.html
```

## Files

### `SKILL.md`

The main agent skill file.

Use this file when asking an AI coding agent to:

- Build a web interface
- Redesign an existing UI
- Improve frontend polish
- Remove generic AI aesthetics
- Create production-quality frontend code
- Review interface quality
- Apply a design system to code

It defines:

- When the skill should activate
- What design mistakes to avoid
- How to choose a design direction
- How to structure layout, typography, color, components, and motion
- How to implement accessible and maintainable frontend code
- How to review the result before final output

### `DESIGN.md`

The design-system guidance file.

This file gives the AI agent a persistent visual identity to follow. It includes:

- Color tokens
- Typography tokens
- Spacing tokens
- Radius values
- Shadow values
- Motion timings
- Component styling rules
- Layout principles
- Accessibility rules
- Responsive behavior
- Dark-mode guidance

The default design system is named **Crafted Engineering**.

It is optimized for:

- Technical products
- Engineering tools
- Developer tools
- AI product interfaces
- Data-heavy dashboards
- Browser extension pages
- Portfolio sites
- Documentation-style websites
- Polished MVP interfaces

You can replace or modify `DESIGN.md` to match a different brand, product, or visual direction.

### `references/UI_REVIEW_CHECKLIST.md`

A structured UI review checklist.

Use it when asking an AI agent to audit:

- UI quality
- Product fit
- Visual hierarchy
- Accessibility
- Responsiveness
- Component states
- Code quality
- Performance
- Anti-AI aesthetic issues
- Release readiness

### `examples/`

Ready-made example pages built with this skill pack.

Use these as a reference for what a finished implementation looks like — design decisions, token usage, component states, and responsive layout all applied in a real context.

- [`vibe-coding-platform.html`](examples/vibe-coding-platform.html) — Course platform landing page. Single-file HTML with the Crafted Engineering design system applied end-to-end.

## Recommended Usage

### 1. Add the skill pack to your project

Place the folder somewhere your AI coding tool can read.

Example:

```txt
your-project/
├─ app/
├─ components/
├─ public/
├─ package.json
└─ non-ai-design-skill-pack/
   ├─ SKILL.md
   ├─ DESIGN.md
   └─ references/
      └─ UI_REVIEW_CHECKLIST.md
```

### 2. Tell your AI agent to use it

Example prompt:

```txt
Use `non-ai-design-skill-pack/SKILL.md` and `non-ai-design-skill-pack/DESIGN.md`.

Redesign this landing page so it no longer looks like a generic AI-generated SaaS template. Keep the existing product concept, but improve hierarchy, typography, layout, component states, accessibility, and responsive behavior.

After implementation, review the result using `references/UI_REVIEW_CHECKLIST.md`.
```

### 3. Apply it during implementation or review

Good tasks:

```txt
Build a polished technical dashboard using this skill pack.
```

```txt
Refactor this React component to follow DESIGN.md and remove generic AI-looking visual patterns.
```

```txt
Create a landing page for a browser extension. Use the Crafted Engineering visual direction but adjust it for a compact utility product.
```

```txt
Audit this UI using UI_REVIEW_CHECKLIST.md and return prioritized fixes.
```

## Installation Patterns

Different AI tools load project instructions differently. Use the option that matches your workflow.

### Generic Project Usage

Works with most chat-based or IDE-based AI agents.

```txt
1. Put the skill pack in your project.
2. Reference `SKILL.md`, `DESIGN.md`, and `UI_REVIEW_CHECKLIST.md` in your prompt.
3. Ask the agent to follow them strictly.
```

### Agent Skills Style

For tools that support Agent Skills-style folders:

```txt
skills/
└─ non-ai-design/
   ├─ SKILL.md
   ├─ DESIGN.md
   └─ references/
      └─ UI_REVIEW_CHECKLIST.md
```

### Project Instructions Style

For tools that do not automatically load skills:

```txt
Use this order:
1. Paste or attach `SKILL.md`.
2. Paste or attach `DESIGN.md`.
3. Use `UI_REVIEW_CHECKLIST.md` only during review or refinement.
```

## Suggested Workflow

### Build Flow

```txt
1. Define the product context.
2. Choose one visual direction.
3. Read DESIGN.md.
4. Plan the layout and information architecture.
5. Implement the interface.
6. Add real component states.
7. Check mobile, tablet, and desktop behavior.
8. Run the UI review checklist.
9. Revise anything that still looks generic.
```

### Review Flow

```txt
1. Inspect the interface visually.
2. Identify generic AI patterns.
3. Check accessibility.
4. Check responsive behavior.
5. Check component states.
6. Check code maintainability.
7. Propose concrete changes.
8. Apply fixes.
```

## What This Pack Avoids

Avoid these patterns unless there is a clear product reason:

- Purple-blue gradient hero sections
- Random glass cards
- Generic AI brain graphics
- Decorative neural-network lines
- Repetitive icon-card grids
- Unexplained glow effects
- Fake analytics panels
- Placeholder-only forms
- Unlabeled inputs
- Low-contrast text
- Excessive rounded corners
- Default component-library appearance with no adaptation
- Unstructured bento layouts
- Landing pages that could describe any product

## What This Pack Encourages

Use:

- Product-specific visual logic
- Clear information architecture
- Intentional typography
- Token-based styling
- Accessible controls
- Real component states
- Purposeful motion
- Useful density
- Strong layout rhythm
- Realistic content structure
- Maintainable frontend architecture

## Design Philosophy

This pack follows a practical principle:

> Do not start from decoration. Start from the job of the interface.

Before styling, define:

- What the interface is for
- Who uses it
- What the user must accomplish first
- What emotional tone is appropriate
- What should be memorable
- What should remain invisible and utilitarian

Then choose one clear visual direction and execute it consistently.

## Default Visual Direction

The included `DESIGN.md` uses the **Crafted Engineering** visual direction.

It combines:

- Warm editorial surfaces
- Restrained technical typography
- Strong layout rhythm
- Precise data treatment
- Minimal accent color
- Accessible interaction states
- Production-oriented component rules

It works especially well for technical products, engineering interfaces, dashboards, documentation-style websites, developer tools, browser extensions, and AI-assisted utilities.

## Customizing `DESIGN.md`

To adapt the pack for another brand, edit:

- `name`
- `description`
- `colors`
- `typography`
- `spacing`
- `radius`
- `shadow`
- `motion`
- `components`
- Markdown rationale sections

Recommended rule:

```txt
Change the design thesis first, then adjust tokens.
Do not randomly change colors or fonts without updating the rationale.
```

## Example Prompt: Full Page Build

```txt
Use the non-ai-design skill pack.

Task:
Create a responsive landing page for a technical browser extension.

Requirements:
- Use `SKILL.md` as the main design and implementation instruction.
- Use `DESIGN.md` as the visual system.
- Avoid generic AI/SaaS visual clichés.
- Include hero, product explanation, feature section, workflow section, proof section, and final CTA.
- Implement responsive behavior for mobile, tablet, and desktop.
- Include hover, focus, loading, empty, and error states where relevant.
- After building, review the result using `references/UI_REVIEW_CHECKLIST.md`.
```

## Example Prompt: UI Refactor

```txt
Use the non-ai-design skill pack.

Refactor the current React UI so it feels more product-specific and less AI-generated.

Keep:
- Existing core functionality
- Existing routing
- Existing data flow

Improve:
- Layout hierarchy
- Typography
- Color system
- Component spacing
- Button states
- Form accessibility
- Mobile responsiveness
- Empty/loading/error states

Follow `DESIGN.md`.
Use `UI_REVIEW_CHECKLIST.md` before finalizing.
```

## Example Prompt: Design Review

```txt
Use `references/UI_REVIEW_CHECKLIST.md`.

Review this interface and return:
1. Overall status
2. Design thesis
3. Top 5 issues by severity
4. Accessibility problems
5. Responsive problems
6. Anti-AI aesthetic problems
7. Concrete implementation fixes

Do not give vague design feedback. Every issue must include a specific fix.
```

## Example Prompt: Dashboard Build

```txt
Use the non-ai-design skill pack.

Build a responsive analytics dashboard for a technical product.

Requirements:
- Use `DESIGN.md` for visual tokens.
- Avoid decorative fake metrics.
- Include realistic loading, empty, and error states.
- Use tabular numbers for metrics.
- Right-align numeric table values.
- Include filters and clear active states.
- Make the mobile layout usable, not just compressed.
- Review the final result using `UI_REVIEW_CHECKLIST.md`.
```

## Example Prompt: Browser Extension Landing Page

```txt
Use the non-ai-design skill pack.

Create a landing page for a browser extension.

The page should feel like a compact, trustworthy technical utility rather than a generic SaaS landing page.

Include:
- Hero section
- Extension workflow
- Feature explanation
- Browser compatibility section
- Privacy/security section
- FAQ
- Final CTA

Follow `DESIGN.md`.
Avoid generic AI visual patterns.
```

## Compatibility

This pack is intentionally plain Markdown.

It can be used with:

- AI coding agents that support skill folders
- IDE assistants
- Chat-based AI tools
- Project instruction files
- Repository-level coding guidelines
- Manual copy-paste workflows

If your tool does not support automatic skill loading, paste the relevant file contents into the prompt or project instructions.

## Recommended Use Cases

Best for:

- Landing pages
- SaaS dashboards
- Admin panels
- Developer tools
- Browser extension pages
- Portfolio sites
- AI product interfaces
- Technical documentation sites
- Data-heavy interfaces
- Engineering tools
- MVP UI polish
- Vibe-coded frontend refinement

Less suitable for:

- Pure backend tasks
- General prose writing
- Brand identity creation from scratch
- Print design
- Motion-heavy creative coding
- Native mobile app design without additional platform-specific rules

## Review Standard

A finished result should satisfy three tests.

### Product Test

A user should understand what the product does and what to do next.

### Design Test

A designer should be able to identify the visual thesis and see it applied consistently.

### Engineering Test

A developer should be able to maintain the code without reverse-engineering arbitrary styling choices.

## Limitations

This skill pack does not replace:

- A real brand strategy
- A full product design process
- User research
- Accessibility testing with real assistive technologies
- Visual QA in actual browsers
- Performance profiling
- Design review by an experienced designer

It is a practical instruction layer for AI-assisted frontend design and review.

## Publishing Checklist

Before publishing this repository, confirm:

- `README.md` exists.
- `README-KR.md` exists if Korean documentation is needed.
- `SKILL.md` has valid front matter.
- `DESIGN.md` has a clear design thesis and consistent tokens.
- `references/UI_REVIEW_CHECKLIST.md` is included.
- Example prompts are accurate.
- The license is selected.
- No private project details remain.
- No paid fonts, private assets, or restricted brand assets are included.

## License

MIT License. See [LICENSE](LICENSE) for details.

## Credits

This pack is inspired by modern Agent Skills workflows, AI coding-agent instruction patterns, design-system documentation practices, and frontend UI review checklists.

It is not tied to a single AI model or vendor.
