# Pinxel UIKit Component Registry

This registry tells AI agents which component references to read before generating Pinxel UI.

## Global Foundation

Read first:

- `brandbook/pinxel-brandbook.md`
- `about/about-pinxel.md`
- `ai/pinxel-ui-instructions.md`
- `uikit/index.html`
- `uikit/css/pinxel-uikit.css`

Global foundation includes tokens, typography, layout, spacing, color roles, documentation layout, tables, grids, stages, cards, and shared utilities.

## Buttons

Files:

- `uikit/components/buttons.html`
- `uikit/css/components/buttons.css`

Use for:

- Primary, secondary, tertiary, accent, and icon-only actions.
- Button sizes and full-width buttons.
- Button states: default, hover, active, focus, disabled, and loading.

Rules:

- Purple primary button is the default main CTA.
- Orange accent button is for commercial emphasis only.
- Teal is not a button variant.
- Icon-only buttons require `aria-label`.

## Forms

Files:

- `uikit/components/forms.html`
- `uikit/css/components/forms.css`

Use for:

- Inputs, selects, search fields, textareas, field groups, helper text, choices, and option cards.
- Product personalization forms and commerce data capture.

Rules:

- Standard inputs and selects are 48px tall.
- Inputs and selects must align visually.
- Use visible labels.
- Use helper text for guidance, errors, and unclear disabled states.

## Cards

Files:

- `uikit/components/cards.html`
- `uikit/css/components/cards.css`

Use for:

- Product cards, content cards, internal line cards, and repeated item grids.

Rules:

- Cards are work surfaces, not decoration.
- Use 2, 3, or 4 column grids when possible.
- Use real images or Lorem Picsum placeholders when visual context is needed.
- Do not nest cards inside cards.

## Badges And Alerts

Files:

- `uikit/components/badges-alerts.html`
- `uikit/css/components/badges-alerts.css`

Use for:

- Status labels, feedback messages, validation summaries, warnings, and system states.

Rules:

- Always pair color with text.
- Purple is information/selection.
- Teal is success/live/positive.
- Orange is warning/pending/commercial attention.
- Red is error/destructive feedback.

## Navigation And Tabs

Files:

- `uikit/components/navigation-tabs.html`
- `uikit/css/components/navigation.css`
- `uikit/css/components/tabs.css`

Use for:

- Top navigation, subbars, tabs, documentation navigation, and slider navigation buttons.

Rules:

- Use `aria-current="page"` for active navigation.
- Use pill tabs for filters, dashboard views, and editor modes.
- Use underline tabs for content sections and documentation.
- Use circular slider navigation buttons only for local previous/next movement inside carousels, galleries, previews, horizontal collections, or onboarding slides.

## Data

Files:

- `uikit/components/data.html`
- `uikit/css/components/data.css`

Use for:

- Metrics, progress, operational summaries, dashboards, and status lists.

Rules:

- Keep metrics clear and scannable.
- Use teal for progress and live/positive states.
- Use layout density appropriate for operational tools.

## Flows

Files:

- `uikit/components/flows.html`
- `uikit/css/components/flows.css`

Use for:

- Product personalization, commerce automation, WhatsApp/chatbot flows, and AI-assisted workflows.

Rules:

- Show the user where they are in the process.
- Make the product preview, options, customer data, and confirmation easy to follow.
- Show AI as a practical assistant through steps, messages, states, and results.

## When A Component Is Missing

If the requested UI needs a component that is not documented yet:

1. Reuse global tokens from `uikit/css/pinxel-uikit.css`.
2. Match the closest existing component behavior.
3. Keep the new pattern minimal.
4. Document the new component with anatomy, usage, states, accessibility, and code.
5. Add it to this registry.
