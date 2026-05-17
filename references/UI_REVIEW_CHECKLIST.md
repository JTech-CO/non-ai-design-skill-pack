# UI Review Checklist

Use this checklist when reviewing, refactoring, or finalizing any interface created with the `non-ai-design` skill.

## Review Method

Review in this order:
1. Product fit 
2. Visual thesis
3. Information architecture
4. Accessibility
5. Responsiveness
6. Component states
7. Code quality
8. Performance
9. Anti-AI aesthetic check
10. Final release readiness

Classify findings as:
- Critical: Blocks usability, accessibility, security, or core functionality
- High: Major UX, layout, responsiveness, or maintainability issue
- Medium: Noticeable quality problem
- Low: Minor polish issue
- Note: Optional improvement

Each finding should include:
- Problem
- Why it matters
- Concrete fix
- Affected file or component when known

## 1. Product Fit

Pass if:
- The interface clearly communicates what product or tool it is.
- The primary user and primary task are obvious.
- The visual tone fits the product category.
- The interface does not feel like a generic template.
- The design supports the user journey.

Fail if:
- The page could belong to any product.
- The hero copy is vague.
- The UI is decorative but not useful.
- The visual style conflicts with the product purpose.
- Important actions are hidden or ambiguous.

Review questions:
- What is the first thing the user should do?
- Can that action be found within three seconds?
- Does the layout reflect real user priority?
- Is the visual style justified by the product?

## 2. Visual Thesis

Pass if:
- The interface has one clear design direction.
- Typography, spacing, color, surfaces, and motion support that direction.
- Important sections have distinct composition.
- Visual hierarchy is deliberate.
- Decorative elements are purposeful.

Fail if:
- The design uses generic gradient blobs.
- Cards, icons, and badges are repeated without hierarchy.
- Everything is equally emphasized.
- The palette feels random.
- The interface relies on glow, glass, or shadows to look polished.

Review questions:
- What is the design thesis in one sentence?
- Is that thesis visible in the actual UI?
- Which element is most memorable?
- Which element feels generic or unnecessary?

## 3. Information Architecture

Pass if:
- Navigation matches the product structure.
- Content is grouped logically.
- The page has clear section progression.
- Primary and secondary actions are visually distinct.
- Empty, loading, and error states are considered.

Fail if:
- Sections are arranged only for visual symmetry.
- Navigation labels are vague.
- Important controls are buried.
- The user cannot tell what changed after an action.
- Empty states are missing.

Review questions:
- Does each section have a job?
- Can users recover from error states?
- Does the URL reflect state when needed?
- Are filters, sorting, and view modes understandable?

## 4. Accessibility

Required checks:
- Use semantic HTML where possible.
- All interactive elements are keyboard-accessible.
- Focus states are visible.
- Forms have visible labels.
- Images have appropriate alt text.
- Icon-only buttons have accessible names.
- Color is not the only way to communicate status.
- Text contrast is sufficient.
- Motion respects reduced-motion preferences.
- Modals and popovers manage focus correctly.

Critical failures:
- Clickable `div` without keyboard support
- Missing form labels
- Invisible focus state
- Low contrast core text
- Modal that traps or loses focus
- Status shown only by color
- Important image with missing alt text

## 5. Responsiveness

Check at:
- 360px mobile
- 390px mobile
- 768px tablet
- 1024px small desktop
- 1440px desktop

Pass if:
- No unintended horizontal scrolling.
- Primary action remains available.
- Text lines are readable.
- Tables have a usable mobile strategy.
- Navigation adapts appropriately.
- Touch targets are large enough.
- The layout does not collapse into visual clutter.

Fail if:
- Hero sections consume too much mobile height.
- Cards become too narrow to read.
- Tables break the viewport.
- Buttons wrap badly.
- Fixed elements cover content.
- Desktop layout is just stretched mobile.

## 6. Component States

Every interactive component should define:
- Default
- Hover
- Focus-visible
- Active
- Disabled
- Loading
- Error when relevant
- Success when relevant
- Empty when relevant

Buttons:
- Primary and secondary actions are distinct.
- Button labels are specific.
- Loading state prevents duplicate actions.
- Disabled state explains why when necessary.

Inputs:
- Label is visible.
- Hint is present when helpful.
- Error message is clear.
- Required fields are clear.
- Autocomplete is used where appropriate.

Cards:
- Card purpose is clear.
- Clickable cards have visible affordance.
- Non-clickable cards do not look clickable.
- Card hierarchy reflects importance.

Tables:
- Numeric values align consistently.
- Units are visible.
- Sorting state is clear.
- Empty state is useful.
- Long content truncates safely.

## 7. Code Quality

Pass if:
- Components are named by purpose.
- Styling values are tokenized or systematic.
- Repeated patterns are componentized.
- Files are organized predictably.
- There are no unused imports.
- There is no dead code.
- State is not overcomplicated.
- Business logic and presentation logic are separated where useful.

Fail if:
- Arbitrary values are scattered everywhere.
- Components are too large to maintain.
- Styling depends on fragile nesting.
- Accessibility is patched with random ARIA.
- Fake data is mixed with production logic.
- The design system is duplicated in many files.

## 8. Performance

Check:
- Images have dimensions.
- Images are lazy-loaded where appropriate.
- Large lists are virtualized when needed.
- Animations use transform and opacity when possible.
- Layout thrashing is avoided.
- Expensive effects are not applied globally.
- Fonts are loaded responsibly.
- Bundle size is not inflated by unnecessary libraries.

Critical failures:
- Unoptimized large images
- Animation that triggers layout on many elements
- Heavy client-side rendering for static content
- Large dependency added for a trivial interaction
- Data table rendering thousands of rows without strategy

## 9. Anti-AI Aesthetic Check

Flag these patterns:
- Generic purple-blue gradient
- Random neural network lines
- AI brain motif without product reason
- Glass cards over gradient background
- Identical bento cards
- Floating sparkles
- Default shadcn appearance with no adaptation
- Too many rounded cards
- Unexplained dark mode glow
- Vague hero text
- Fake metrics
- Stock-style feature icons
- Unrelated abstract blobs
- Overuse of "seamless", "intelligent", "empower", "unlock"
- Layout that looks like a landing page template regardless of product

Fix by:
- Rebuilding the visual thesis
- Reducing decoration
- Making hierarchy content-driven
- Using product-specific data or diagrams
- Changing typography rhythm
- Making component states real
- Adding task-specific UI details

## 10. Final Release Readiness

Before final delivery, confirm:
- The interface runs without errors.
- The primary flow works.
- Mobile and desktop layouts are checked.
- Accessibility basics are satisfied.
- Loading, empty, and error states exist where needed.
- The design system is not contradicted.
- No unused assets or imports remain.
- The result does not look like a generic AI-generated interface.
- The user can maintain the code after handoff.

## Review Output Format

Use this format when reporting a review:

```txt
Design Review Summary

Overall status:
- Pass / Needs revision / Blocked

Design thesis:
- [One sentence]

Top issues:
1. [Severity] [Issue]
   Why it matters:
   Fix:

2. [Severity] [Issue]
   Why it matters:
   Fix:

3. [Severity] [Issue]
   Why it matters:
   Fix:

Accessibility:
- [Pass / Needs revision]
- Notes:

Responsive behavior:
- [Pass / Needs revision]
- Notes:

Code quality:
- [Pass / Needs revision]
- Notes:

Anti-AI aesthetic verdict:
- [Pass / Needs revision]
- Notes:

Recommended next action:
- [Specific next step]
```
