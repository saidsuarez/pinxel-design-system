# Pinxel UI Instructions for AI

Use this file as the operational entry point before designing or coding any Pinxel interface.

## Required Source Files

Read these files before generating a Pinxel product, app, website, dashboard, flow, or component:

1. `brandbook/pinxel-brandbook.md`
2. `about/about-pinxel.md`
3. `uikit/component-registry.md`
4. `uikit/index.html`
5. `uikit/css/pinxel-uikit.css`
6. The relevant component HTML and CSS files inside `uikit/components/` and `uikit/css/components/`

## Core UI Rules

- Use the Pinxel design system as the source of truth.
- Use Inter as the primary typeface.
- Use light theme by default.
- Support dark mode only when the product context benefits from reduced brightness, such as dashboards, long tools, or technical workflows.
- Keep the interface clean, minimal, precise, and useful.
- Favor Apple-like restraint: typography-led hierarchy, clean surfaces, generous spacing, and fully rounded buttons.
- Use Pinxel color functionally:
  - Purple `#5E4595` for brand, primary actions, focus, selected states, and main decisions.
  - Orange `#F59B1B` for commercial emphasis, promotional moments, and energetic highlights.
  - Teal `#4EBBB8` for progress, success, live states, positive statuses, and operational clarity.
  - Charcoal `#333333` for text, icons, structure, and neutral UI.
- Do not use teal as a main button variant.
- Do not invent new colors, radii, shadows, or component variants unless the product requirement cannot be solved with the existing system.

## Layout Rules

- Use an 8px spacing rhythm.
- Use white or very light gray surfaces by default.
- Use cards as work surfaces, not decoration.
- Do not place cards inside other cards.
- Design card grids for 2, 3, or 4 columns when possible.
- For operational apps and dashboards, prioritize organized density over marketing-style hero sections.
- For product personalization flows, always make the customizable object, preview, options, customer data, and confirmation visible or clearly sequenced.

## Component Rules

- Use existing UIKit classes and patterns whenever possible.
- Use pill buttons for primary, secondary, tertiary, and important actions.
- Use full button states: default, hover, active, focus, disabled, and loading when applicable.
- Use 48px form controls for standard inputs and selects.
- Selects must align visually with text inputs.
- Use visible labels for all form fields.
- Use clear helper text when a disabled or invalid state is not self-explanatory.
- Use badges and alerts with text, never color alone.
- Use circular slider navigation buttons only for local previous/next navigation inside carousels, galleries, previews, horizontal collections, or onboarding slides.
- Use icon-only buttons only when the meaning is obvious and always include `aria-label`.

## Accessibility Rules

- Preserve visible focus states.
- Use semantic HTML first.
- Use native `<button>` for in-page actions.
- Use `<a>` for navigation.
- Use `aria-current="page"` for active navigation.
- Use `aria-busy="true"` for loading states that block repeated actions.
- Use `aria-disabled="true"` only when the control cannot use native `disabled`.
- Do not communicate state only through color.

## Content Rules

- Write short, active, concrete UI copy.
- Avoid corporate jargon and vague technology claims.
- Make AI feel practical and useful, not abstract.
- When showing automation, expose the flow, message, status, or result.
- Pinxel is about personalized experiences powered by technology, not just products.

## Default Prompt Pattern

When asking an AI to generate a Pinxel interface, use this structure:

```txt
Use the Pinxel design system as the source of truth.

Read and follow:
- brandbook/pinxel-brandbook.md
- about/about-pinxel.md
- ai/pinxel-ui-instructions.md
- uikit/component-registry.md
- uikit/index.html
- uikit/css/pinxel-uikit.css
- the relevant files in uikit/components/ and uikit/css/components/

Build the requested UI using existing Pinxel tokens, layout rules, components, states, spacing, typography, accessibility rules, and content tone.

Do not invent new visual patterns unless the existing UIKit does not cover the need.
Use light theme by default.
Use Inter.
Use purple for primary actions, orange for commercial emphasis, teal for progress/success/live states, and charcoal for text/structure.
Use pill buttons, visible focus, labeled form fields, and complete component states.
```
