---
name: Crafted Engineering
version: 1.0.0
description: A practical visual identity for polished technical products, dashboards, tools, landing pages, and AI-assisted web interfaces that must avoid generic AI aesthetics.
colors:
  background: "#F6F3EE"
  backgroundSubtle: "#ECE7DE"
  surface: "#FFFFFF"
  surfaceRaised: "#FAF8F4"
  surfaceInverse: "#111315"
  border: "#D8D1C7"
  borderStrong: "#B8AEA2"
  text: "#15171A"
  textMuted: "#5F676F"
  textSubtle: "#8A929A"
  accent: "#B94A2F"
  accentHover: "#9E3E28"
  accentSoft: "#F1D8CF"
  focus: "#2457C5"
  success: "#18794E"
  warning: "#A15C00"
  danger: "#B42318"
  info: "#276EF1"
typography:
  display:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(2.75rem, 7vw, 6rem)"
    lineHeight: "0.94"
    fontWeight: 650
    letterSpacing: "-0.055em"
  h1:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(2.25rem, 5vw, 4.5rem)"
    lineHeight: "0.98"
    fontWeight: 650
    letterSpacing: "-0.045em"
  h2:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(1.75rem, 3vw, 3rem)"
    lineHeight: "1.04"
    fontWeight: 620
    letterSpacing: "-0.035em"
  h3:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.25rem"
    lineHeight: "1.25"
    fontWeight: 700
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1rem"
    lineHeight: "1.65"
    fontWeight: 400
  bodyCompact:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.9375rem"
    lineHeight: "1.5"
    fontWeight: 400
  label:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.75rem"
    lineHeight: "1"
    fontWeight: 700
    letterSpacing: "0.08em"
    textTransform: "uppercase"
  code:
    fontFamily: "JetBrains Mono, SFMono-Regular, Consolas, monospace"
    fontSize: "0.875rem"
    lineHeight: "1.45"
  numeric:
    fontFamily: "JetBrains Mono, SFMono-Regular, Consolas, monospace"
    fontSize: "0.9375rem"
    lineHeight: "1.2"
    fontVariantNumeric: "tabular-nums"
spacing:
  1: "0.25rem"
  2: "0.5rem"
  3: "0.75rem"
  4: "1rem"
  5: "1.25rem"
  6: "1.5rem"
  8: "2rem"
  10: "2.5rem"
  12: "3rem"
  16: "4rem"
  20: "5rem"
  24: "6rem"
  section: "clamp(4rem, 8vw, 8rem)"
radius:
  xs: "0.25rem"
  sm: "0.5rem"
  md: "0.875rem"
  lg: "1.25rem"
  xl: "1.75rem"
  full: "999px"
shadow:
  sm: "0 1px 2px rgba(17, 19, 21, 0.06)"
  md: "0 12px 30px rgba(17, 19, 21, 0.1)"
  lg: "0 24px 60px rgba(17, 19, 21, 0.14)"
motion:
  fast: "140ms ease-out"
  standard: "220ms cubic-bezier(0.2, 0.8, 0.2, 1)"
  slow: "420ms cubic-bezier(0.16, 1, 0.3, 1)"
breakpoints:
  sm: "640px"
  md: "768px"
  lg: "1024px"
  xl: "1280px"
components:
  buttonPrimary:
    background: "{colors.accent}"
    color: "#FFFFFF"
    hoverBackground: "{colors.accentHover}"
    radius: "{radius.full}"
    paddingInline: "{spacing.5}"
    paddingBlock: "{spacing.3}"
  buttonSecondary:
    background: "transparent"
    color: "{colors.text}"
    border: "1px solid {colors.borderStrong}"
    hoverBackground: "{colors.backgroundSubtle}"
    radius: "{radius.full}"
    paddingInline: "{spacing.5}"
    paddingBlock: "{spacing.3}"
  card:
    background: "{colors.surface}"
    border: "1px solid {colors.border}"
    radius: "{radius.lg}"
    shadow: "{shadow.sm}"
  input:
    background: "{colors.surface}"
    border: "1px solid {colors.borderStrong}"
    focusRing: "0 0 0 3px rgba(36, 87, 197, 0.22)"
    radius: "{radius.md}"
---

# Crafted Engineering Design System

## Overview

Crafted Engineering is a restrained, editorial-technical design system for interfaces that need to feel serious, precise, and human-made.

It is suitable for:

- Engineering tools
- AI product interfaces
- SaaS dashboards
- Technical landing pages
- Portfolio sites
- Browser extension pages
- Scientific or analytical web apps
- Developer-facing documentation
- Premium productivity products

The design avoids generic AI aesthetics by combining warm physical surfaces, editorial typography, precise data treatment, and restrained accent color.

## Visual Thesis

The interface should feel like a well-designed technical publication crossed with a modern engineering workstation.

It should not feel like:

- A generic SaaS template
- A decorative AI demo
- A default component library page
- A purple gradient landing page
- A soft glassmorphism dashboard
- A random bento grid

The system should communicate:

- Precision
- Trust
- Calm control
- Technical confidence
- Human authorship
- Durable product quality

## Color Usage

### Backgrounds

Use `background` as the main page color. It is a warm neutral, not pure white. This gives the interface a physical, editorial quality.

Use `backgroundSubtle` for large section separation, code preview backgrounds, quiet panels, or alternate page bands.

Use `surface` for cards, controls, tables, popovers, and content containers.

Use `surfaceRaised` when a surface needs slight emphasis without a heavy shadow.

Use `surfaceInverse` for dark technical panels, terminal-like blocks, or strong contrast sections.

### Accent

Use `accent` sparingly. It should drive action, not decoration.

Good uses:

- Primary call-to-action
- Active navigation state
- Selected filter
- Important metric highlight
- Small editorial rule
- Key diagram node

Bad uses:

- Every icon
- Large gradient backgrounds
- Random section decorations
- Unrelated badges
- Multiple competing buttons

### Status Colors

Use success, warning, danger, and info only for actual state.

Do not use status colors as decoration.

## Palette Variations

The default Crafted Engineering palette uses warm parchment and rust red. This combination works well for editorial, marketing, and general-purpose technical products. For other product contexts, three alternative palettes are defined below. Each replaces the background tone, accent, and surface-inverse — the three tokens that define a palette's identity — while keeping the neutral and status tokens stable.

### Crafted Warm (default)

The original palette. Warm parchment surfaces, rust-red accent, deep neutral inverse.

```css
background:     #F6F3EE
background-subtle: #ECE7DE
accent:         #B94A2F
accent-hover:   #9E3E28
accent-soft:    #F1D8CF
surface-inverse: #111315
text-muted:     #5F676F
text-subtle:    #8A929A
```

Best for: editorial landing pages, course platforms, portfolio sites, warm consumer products.

### Verdant

Forest green accent on warm off-white. Communicates growth, craft, and technical confidence without the urgency of red.

```css
background:     #F0EDE5
background-subtle: #E7E2D8
accent:         #1A6B46
accent-hover:   #155939
accent-soft:    #D1FAE5
surface-inverse: #0D1C14
text-muted:     #4F5A51
text-subtle:    #7E8A7F
```

Best for: learning platforms, productivity tools, sustainability products, developer tools with a calm, trustworthy tone.

### Precision

Cobalt blue accent on cool slate. Communicates data clarity, enterprise reliability, and analytical precision.

```css
background:     #F0F4F8
background-subtle: #E2EBF4
accent:         #1B4FDB
accent-hover:   #1840C4
accent-soft:    #DBEAFE
surface-inverse: #081428
border:         #C8D4E2
border-strong:  #9BB0C5
text-muted:     #48607A
text-subtle:    #7D97AC
```

Best for: SaaS dashboards, analytics products, admin panels, B2B tools, financial interfaces.

### Amber Press

Warm amber accent on aged parchment. Communicates editorial authority, premium print quality, and journalistic credibility.

```css
background:     #F5EDD5
background-subtle: #EDE4C5
surface:        #FDFAF0
surface-raised: #F9F4E3
accent:         #B07B13
accent-hover:   #946409
accent-soft:    #FEF3C7
surface-inverse: #1A1410
border:         #D9CFAF
border-strong:  #BAB08E
text-muted:     #5C5240
text-subtle:    #8A7E68
```

Best for: newsletters, publications, editorial blogs, documentation, premium content products.

### How to apply a variation

Replace the background tone, accent triplet (`accent`, `accent-hover`, `accent-soft`), and `surface-inverse` in the token block. Keep `focus`, `success`, `warning`, `danger`, and `info` unchanged — these carry semantic meaning and must remain accessible regardless of palette.

Change the design thesis first, then adjust tokens. Do not change tokens without updating the rationale for why the new palette fits the product.

## Typography Usage

### Display and Headings

Use the display and heading type for editorial emphasis. Headings should feel deliberate, not inflated.

Good patterns:

- Large compressed hero headline with short line length
- Strong section titles paired with concise body copy
- Editorial labels above sections
- Technical subheads in sans-serif

Avoid:

- Every card having oversized serif headings
- Excessively long display text
- Centered text everywhere
- Generic headline phrases

### Body Text

Body text should be clean, readable, and not too light.

Use muted text for supporting copy, metadata, timestamps, captions, and secondary descriptions.

Do not use low-contrast gray for core content.

### Numeric Text

Use the numeric style for:

- Dashboard metrics
- Price
- Time
- Percentages
- Version numbers
- Counts
- Measurements
- Financial values
- Engineering values

Use tabular numerals for all metric-heavy components.

## Layout Principles

### Grid

Use clear grid structures:

- 12-column grid for landing pages and dashboards
- 2-column editorial grid for content-heavy pages
- Sidebar + workspace layout for tools
- Dense table layout for admin interfaces
- Card grid only when cards represent comparable objects

Avoid equal-width columns when content importance is not equal.

### Spacing

Use generous spacing for marketing and portfolio pages.

Use tighter spacing for tools, dashboards, and admin interfaces.

Do not use the same spacing rhythm for every section. Important areas can breathe; operational areas should be compact.

### Section Structure

Each page should have:

- A clear entry point
- A primary user action
- A secondary path
- A scannable middle section
- A credible proof or detail section
- A final conversion or completion point when relevant

## Component Guidance

### Buttons

Primary buttons use the accent color and full radius.

Secondary buttons are transparent or quiet.

Avoid having multiple primary buttons in the same visual group.

Button labels must be action-specific:

- Good: "Generate report", "Export CSV", "Start audit"
- Bad: "Click here", "Learn more", "Submit" unless context is obvious

### Cards

Cards should not all look the same.

Use cards for:

- Grouped related content
- Product modules
- Data summaries
- Feature explanations
- Configuration panels
- Audit results

Avoid cards for:

- Every paragraph
- Pure decoration
- Artificial bento grids with no hierarchy

Card hierarchy should vary with content priority:

- Primary card: larger, richer, stronger composition
- Secondary card: compact, quiet
- Utility card: dense, functional

### Tables

Tables should prioritize scanning:

- Left-align text
- Right-align numbers
- Use tabular numerals
- Show units
- Use sticky headers when appropriate
- Provide empty and loading states
- Include sort/filter affordances when relevant

### Forms

Forms must be explicit:

- Visible label
- Helpful hint if needed
- Error message near the field
- Disabled state
- Loading state
- Success state
- Clear submit action

Avoid placeholder-only forms.

### Navigation

Navigation should reflect product architecture.

Use:

- Top navigation for marketing or simple products
- Sidebar navigation for dashboards and tools
- Segmented controls for local view switching
- Breadcrumbs for nested admin interfaces

Do not hide primary navigation behind decorative menus on desktop.

## Motion Principles

Motion should be subtle, useful, and fast.

Use motion for:

- Panel entrance
- Filter transition
- Disclosure
- Active state
- Toast notification
- Modal open/close
- Progress feedback

Avoid:

- Constant floating animation
- Infinite glow
- Unnecessary parallax
- Slow decorative transitions
- Motion that blocks task completion

Always support reduced-motion preferences.

## Dark Mode

Dark mode should not simply invert colors.

Dark mode rules:

- Use deep neutral backgrounds, not pure black by default.
- Reduce shadow reliance.
- Increase border visibility.
- Keep accent usage restrained.
- Preserve status contrast.
- Do not use excessive glow to compensate for weak hierarchy.

## Responsive Behavior

### Mobile

Mobile must be task-first:

- Prioritize primary action
- Collapse secondary metadata
- Avoid large empty hero sections
- Use sticky bottom actions only when useful
- Keep tap targets large enough
- Avoid horizontal scrolling except for intentional data tables

### Tablet

Tablet should not be treated as stretched mobile.

Use:

- Two-column layouts when content supports it
- Compact navigation
- Preserved dashboard hierarchy
- Better chart/table space than mobile

### Desktop

Desktop should use space productively.

Avoid:

- Over-wide text lines
- Centered narrow content on all pages
- Large empty dashboard regions
- Decorative side panels with no utility

## Accessibility Rules

Required:

- Sufficient text contrast
- Visible focus states
- Keyboard navigability
- Semantic structure
- Alt text for meaningful images
- Reduced-motion support
- Proper form labels
- ARIA only when needed
- No color-only status communication

## Implementation Notes

When using Tailwind CSS:

- Map these tokens into CSS variables or theme extension.
- Avoid arbitrary values unless they encode a deliberate design decision.
- Keep repeated values tokenized.

When using shadcn/ui:

- Restyle components to match this design system.
- Do not ship default component appearance unchanged.
- Ensure component states match this file.

When using plain CSS:

- Define tokens in `:root`.
- Use component classes with clear naming.
- Keep state styles explicit.

## Quality Standard

A finished interface should feel specific, useful, and intentional.

It should be possible to explain:

- Why this palette fits the product
- Why the typography fits the audience
- Why the layout supports the task
- Why the components are structured this way
- Why the design does not look like a generic AI-generated page
