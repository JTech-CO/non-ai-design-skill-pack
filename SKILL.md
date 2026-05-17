---
name: non-ai-design
description: Use this skill when building, redesigning, or reviewing web interfaces, dashboards, landing pages, SaaS products, portfolio sites, apps, design systems, components, or visual UI code. It helps produce distinctive, production-quality design and code that avoids generic AI-looking layouts, vague gradients, default component dumps, and template-like aesthetics. Do not use for prose-only writing tasks.
---

# Non-AI Design Skill

## Purpose

Create digital interfaces that feel intentionally designed, technically sound, and production-ready.

This skill is for coding and design work, not general writing. It applies to HTML, CSS, JavaScript, TypeScript, React, Vue, Svelte, Next.js, Tailwind CSS, shadcn/ui, component libraries, dashboards, landing pages, web apps, browser extensions, design systems, and visual refactoring.

The goal is not to make everything visually loud. The goal is to make every interface feel authored, coherent, useful, and specific to its product context.

## Core Principle

Do not produce generic AI UI.

Avoid interfaces that look like a default prompt result:
- Centered hero section with vague gradient blobs
- Random glassmorphism
- Purple-blue SaaS gradients by default
- Oversized rounded cards everywhere
- Identical icon-card grids
- Unjustified shadows and glow
- Decorative elements that do not support hierarchy or meaning
- Components that look pasted from a generic template
- Interfaces with no product-specific visual logic

Instead, choose a clear design thesis and execute it consistently.

## Activation Criteria

Use this skill when the user asks to:
- Build a website, landing page, dashboard, app, admin panel, tool, or component
- Improve, redesign, polish, modernize, or professionalize UI
- Convert a rough idea, sketch, screenshot, or wireframe into code
- Create a design system or style guide
- Audit UI/UX, accessibility, responsiveness, or visual quality
- Make a product look premium, professional, editorial, technical, industrial, playful, minimal, luxury, brutalist, retro-futuristic, or brand-specific
- Remove "AI-looking" design from an interface

Do not use this skill when the task is only:
- Writing an article
- Summarizing text
- Translating prose
- Solving a non-UI programming problem
- Generating backend-only code with no user interface

## Required Inputs

Before implementation, infer or ask for the following only when necessary:
- Product type
- Target user
- Primary task the interface must support
- Brand tone
- Technical stack
- Existing constraints
- Target device sizes
- Accessibility expectations
- Whether an existing `DESIGN.md` is available

If the user provides incomplete information, make reasonable assumptions and state them briefly before implementation.

## Mandatory Workflow

### 1. Define the Product Context

Before designing, identify:
- What the interface is for
- Who uses it
- What the user must accomplish first
- What emotional tone is appropriate
- What should be memorable
- What should remain invisible and utilitarian

Do not start from decoration. Start from the job of the interface.

### 2. Choose a Design Direction

Select one strong visual direction. Examples:
- Editorial engineering
- Industrial control room
- Calm productivity system
- Premium technical documentation
- Financial terminal minimalism
- Retro-futuristic console
- Academic laboratory interface
- Dense professional dashboard
- Luxury restrained commerce
- Warm creator portfolio
- High-contrast brutalist tool
- Soft consumer utility
- Automotive-grade interface
- Archival newspaper layout
- Scientific instrument panel

Do not mix many unrelated styles. One strong direction is better than ten weak cues.

### 3. Check for `DESIGN.md`

If a `DESIGN.md` file exists:
- Treat its tokens as the source of truth.
- Use its color, typography, radius, spacing, and component rules.
- Do not invent a conflicting style.
- If a token is missing, extend the system minimally and consistently.

If no `DESIGN.md` exists:
- Create a compact design direction internally.
- Use no more than 1 primary accent and 1 secondary accent unless the product requires more.
- Define typography, spacing, density, surface, border, and motion logic before writing UI code.

### 4. Build the Information Architecture

Before styling, decide:
- Page hierarchy
- Navigation model
- Primary action
- Secondary actions
- Content density
- Empty states
- Loading states
- Error states
- Responsive structure
- State persistence when relevant

Every visible section must have a reason to exist.

### 5. Implement Production-Quality UI

Code must be functional, responsive, accessible, and maintainable.

Required implementation behavior:
- Use semantic HTML wherever possible.
- Use accessible labels and keyboard-operable interactions.
- Avoid layout shifts.
- Avoid hardcoded one-off styling when tokens or variables are appropriate.
- Use CSS variables or design tokens for repeated values.
- Use reusable components when the UI has repeated patterns.
- Include realistic content structure, not placeholder filler, unless the user specifically requests mock content.
- Ensure the design works at mobile, tablet, and desktop widths.
- Prefer clarity and hierarchy over visual noise.

### 6. Add Details That Make It Feel Designed

Use intentional details:
- Specific typography pairing
- Consistent spacing rhythm
- Realistic component states
- Clear contrast hierarchy
- Subtle texture only when useful
- Product-specific iconography or data treatment
- Strong section composition
- Useful microcopy
- Carefully placed metadata
- Meaningful motion
- Distinctive but restrained interaction states

Good UI often comes from precise spacing, hierarchy, rhythm, and state design, not from more decoration.

### 7. Review Before Final Output

Before presenting the result, check:
- Does the interface have a clear visual thesis?
- Does the hierarchy guide the eye correctly?
- Is the primary action obvious?
- Are the colors intentional and accessible?
- Are typography choices specific and consistent?
- Are there any generic AI visual clichés?
- Does the UI work without relying on ornamental gradients?
- Are mobile and desktop layouts both usable?
- Are hover, focus, loading, empty, and error states considered?
- Is the code maintainable?

If the design feels generic, revise before finalizing.

## Visual Design Rules

### Typography

Use typography as a design system, not decoration.

Rules:
- Define type roles: display, heading, body, caption, label, code, numeric.
- Use consistent font sizes and line heights.
- Use tabular numbers for metrics, prices, dashboards, and data tables.
- Use letter spacing intentionally for labels and metadata.
- Avoid using default browser font stacks without reason.
- Avoid using too many font weights.
- Avoid oversized text unless it supports hierarchy.

Preferred patterns:
- Editorial product: strong serif or humanist display + clean sans body
- Technical product: compact sans + monospaced numeric/data style
- Dashboard: readable sans + tabular numeric treatment
- Luxury product: restrained high-contrast type + generous whitespace
- Developer tool: monospace accents + precise interface typography

### Color

Use color as system logic.

Rules:
- Start with neutrals, then add accent.
- Use color to indicate action, status, category, selection, and risk.
- Avoid random rainbow palettes.
- Avoid gradients unless they carry brand or spatial meaning.
- Ensure text contrast is sufficient.
- Define light and dark mode behavior if relevant.
- Do not use pure black or pure white everywhere unless intentionally brutalist.

A strong palette usually has:
- Background
- Surface
- Surface elevated
- Border
- Muted text
- Primary text
- Accent
- Accent hover
- Success
- Warning
- Danger
- Focus ring

### Layout

Design layout from user tasks.

Rules:
- Use grid systems intentionally.
- Align edges and baselines.
- Avoid arbitrary card sizes.
- Avoid placing everything in centered cards.
- Do not overuse equal-width columns when content importance differs.
- Preserve whitespace around high-value content.
- Use density appropriate to the product.

Examples:
- Dashboard: dense but scannable, strong data grouping
- Landing page: narrative progression, strong conversion path
- Tool UI: persistent controls, clear workspace, minimal distraction
- Portfolio: curated sequence, strong project framing
- Admin panel: predictable navigation, efficient tables, robust states

### Components

Components must feel designed and useful.

For each component, define:
- Default state
- Hover state
- Focus state
- Active/pressed state
- Disabled state
- Loading state
- Empty state
- Error state
- Success state

Avoid:
- Generic card grids without hierarchy
- Buttons with no action priority
- Inputs without labels
- Tables without alignment rules
- Modals that trap users
- Icons without semantic purpose
- Badges that do not add meaning

### Motion

Use motion only when it improves understanding.

Rules:
- Prefer short, precise transitions.
- Use motion to show causality, hierarchy, or spatial continuity.
- Respect reduced-motion preferences.
- Avoid constant floating, pulsing, glowing, or bouncing.
- Avoid animation that delays task completion.
- Keep expensive animations off layout-triggering properties where possible.

### Imagery and Icons

Use visual assets as information, not filler.

Rules:
- Prefer custom-feeling diagrams, interface fragments, data visuals, product mockups, or abstracted system maps.
- Avoid generic 3D blobs, generic AI brain graphics, random neural-network lines, and stock-photo-looking visuals.
- Icons must share stroke width, corner logic, and visual weight.
- Avoid decorative icons beside every heading unless they clarify structure.

## Coding Rules

### General

- Write complete, runnable code when the user asks for implementation.
- Keep file structure maintainable.
- Do not create excessive abstraction for small projects.
- Use clear names for components, tokens, states, and utilities.
- Avoid dead code.
- Avoid unused imports.
- Avoid fake functionality unless explicitly marked.
- Prefer progressive enhancement where practical.

### React / Next.js

- Prefer small composable components.
- Keep state close to where it is used.
- Use semantic elements before custom div structures.
- Avoid unnecessary client-side rendering.
- Keep server/client boundaries explicit in Next.js.
- Use accessible button, input, dialog, and menu behavior.
- Use `aria-*` only when semantic HTML is insufficient.

### CSS / Tailwind

- Use tokens or CSS variables for repeated design values.
- Avoid arbitrary values unless they encode a specific design decision.
- Use responsive classes deliberately.
- Avoid applying large visual effects everywhere.
- Prefer consistent rhythm over one-off spacing.
- Ensure focus-visible states are present.
- Avoid contrast failures in dark mode.

### Data Interfaces

For dashboards, tables, analytics, finance, engineering tools, admin panels, or QA tools:
- Align numeric data to improve scanning.
- Use tabular numerals.
- Show units.
- Provide empty, loading, and error states.
- Make filters and sorting visible.
- Preserve state in URL when appropriate.
- Use compact but readable density.
- Avoid decorative charts with no analytical value.

### Forms

Forms must be reliable.

Required:
- Visible labels
- Input hints where needed
- Validation messages
- Error summary for complex forms
- Autocomplete where appropriate
- Proper input types
- Keyboard navigation
- Disabled/loading behavior
- Success confirmation

Avoid:
- Placeholder-only labels
- Hidden errors
- Ambiguous submit buttons
- Form reset without confirmation
- Decorative inputs with poor contrast

## Anti-AI Design Checklist

Before finalizing, remove or justify each of the following:
- Purple-blue gradient hero by default
- Floating glass cards with no reason
- "AI brain" or neural network decoration
- Random sparkles
- Generic bento grid
- Repeated icon cards with vague copy
- Fake analytics panels
- Overly rounded everything
- Glow-heavy dark UI
- Unrelated blob backgrounds
- Thin gray text with poor contrast
- Excessive whitespace that harms usability
- Dashboard cards with no interaction or data logic
- Hero sections that say nothing specific
- Identical section rhythm from top to bottom
- Components that ignore empty, loading, or error states

## Output Requirements

When creating or editing code:
1. Briefly state the assumed design direction.
2. Implement the interface.
3. Mention the main design decisions.
4. Mention any important limitations or next steps.
5. If reviewing code, provide prioritized issues and concrete fixes.

When writing files:
- Keep the design system centralized.
- Use `DESIGN.md` when available.
- Add or update tokens only when necessary.
- Do not invent external dependencies unless justified.
- Do not use paid fonts, licensed assets, or brand logos unless the user provides permission.

## Final Quality Bar

The result should pass this standard:

A professional designer should be able to tell what the product is, who it serves, what visual direction it follows, and why the interface is structured the way it is.

A developer should be able to maintain the code without reverse-engineering arbitrary styling decisions.

A user should be able to complete the primary task without fighting the interface.
