# Pinxel Brandbook

## Overview

Pinxel is a personalization and digital solutions ecosystem created by Said Suarez. It combines custom physical products, user experience design, web development, commerce automation, and artificial intelligence. The brand helps people and businesses turn ideas into real, useful, emotionally connected products and systems.

Pinxel's identity should feel precise, approachable, and built for systems. It combines the calm of a premium interface with the warmth of personalized creation. The result should feel minimal, useful, trustworthy, emotionally aware, and quietly energetic.

The closest visual reference is Apple: clean surfaces, typography-led hierarchy, fully rounded buttons, restrained layout, and disciplined use of color. Pinxel adapts that direction with a more expressive palette: purple for brand and direction, orange for creative/commercial momentum, teal for clarity and live states, and charcoal for structure.

The default theme is light. Dark mode is supported as a functional option for long interfaces, dashboards, technical tools, and contexts where lower brightness reduces visual fatigue. Dark mode should not become the primary brand expression.

**Key characteristics**

- Clean, low-friction interface with a strong sense of order.
- Buttons, fields, and chips use pill geometry or soft radii.
- Color works as a system: purple for brand and primary actions, orange for commercial emphasis, teal for positive states or live data, charcoal for text and structure.
- Spacious layout with an 8px rhythm.
- Reusable components for apps, web, commerce, and product personalization flows.
- Logos and graphics have moderate prominence: the brand supports the action instead of competing with it.

## AI Usage

This brandbook is the main source of truth for AI-generated Pinxel interfaces. AI agents should not rely on memory or generic design patterns when generating Pinxel UI.

Before designing or coding a Pinxel interface, read:

1. `brandbook/pinxel-brandbook.md`
2. `ai/pinxel-ui-instructions.md`
3. `uikit/component-registry.md`
4. `uikit/index.html`
5. `uikit/css/pinxel-uikit.css`
6. The relevant component files inside `uikit/components/` and `uikit/css/components/`

Use the recommended copy/paste prompt in `uikit/index.html` when asking an AI to generate a product, app screen, component, landing page, dashboard, or user flow.

## Brand Definition

Pinxel is the combination of:

- **A personalized product brand:** notebooks, apparel, accessories, pet records, portraits, and other customizable physical products.
- **A digital solutions lab:** branding, UX, web development, e-commerce, plugins, and scalable systems.
- **An AI-powered commerce automation platform:** WhatsApp sales flows, chatbots, lead generation, customer follow-up, and hybrid digital/physical experiences.

Core concept:

**Pinxel does not simply sell products. Pinxel creates personalized experiences powered by technology.**

## Product Lines

Pinxel organizes its offer into internal lines. These are strategic categories inside the same ecosystem, not independent brands and not separate websites by default.

### Paw Studio

Personalized products for pets, including physical and digital veterinary records. Paw Studio should feel useful, organized, warm, and emotionally connected to the bond between people and their pets.

### 4Corners

Custom frames and portraits for spaces, identity, memory, emotion, and personal style. 4Corners should feel visual, personal, decorative, and gift-ready without becoming overly ornate.

### Pinxel Lab

Design, development, and artificial intelligence for digital products and scalable systems. This includes WooCommerce plugins, branding and UX, web/e-commerce development, automated sales systems, WhatsApp/chatbot flows, courses, and digital products.

Tagline direction for Pinxel Lab:

**Where ideas become real products.**

## Brand Essence

### Personality

- **Clear:** explains without unnecessary decoration.
- **Precise:** every element has a visible purpose.
- **Approachable:** uses direct, human, easy-to-understand language.
- **Modular:** everything should scale across product, web, dashboard, or campaign surfaces.
- **Creative:** personalization should feel intentional, not generic.
- **Optimistic:** color appears as a signal of progress, not as excessive decoration.

### Voice

Pinxel speaks in short, active, concrete sentences. Avoid corporate solemnity, unnecessary jargon, and inflated promises.

The tone should balance three ideas: custom creation, useful technology, and human connection. Even when discussing AI or automation, the language should stay practical and user-centered.

**Use**

- "Customize your product"
- "Create a real product from your idea"
- "Automate your sales flow"
- "Connect WhatsApp to your store"
- "Your pet record is ready"

**Avoid**

- "We potentiate integral transformation solutions"
- "Experience a new digital dimension"
- "Click here to proceed"
- "AI-powered hyperpersonalized omnichannel revolution"

## Logo

### Assets

- Horizontal logo: `assets/pinxel-logo.svg`
- Symbol: `assets/pinxel-isotipo.svg`
- Favicon: `assets/favicon.png`

### Usage

The horizontal logo is the primary signature for navigation, headers, documents, and institutional pieces. The symbol is used when space is limited: favicon, avatar, launcher, app icon, loading states, or subtle watermarks.

### Clear Space

Keep free space around the logo equal to the height of the dot over the "i". For the symbol, use the width of one square module as the minimum clear space.

### Minimum Sizes

| Asset | Digital | Print |
| --- | ---: | ---: |
| Horizontal logo | 120px wide | 28mm wide |
| Symbol | 32px | 8mm |

### Do Not

- Do not distort proportions.
- Do not apply shadows, bevels, or 3D effects.
- Do not recolor the symbol outside the approved palette.
- Do not place the logo on backgrounds that reduce contrast.
- Do not wrap the logo in a card when it can live directly on the surface.

## Color

### Brand Core

| Token | Hex | Use |
| --- | --- | --- |
| `{colors.purple}` | `#5E4595` | Primary brand color, primary CTA, selection, main focus signal. |
| `{colors.orange}` | `#F59B1B` | Creative/commercial emphasis, energetic moments, non-destructive alerts. |
| `{colors.teal}` | `#4EBBB8` | Positive states, progress, live data, confirmations. |
| `{colors.charcoal}` | `#333333` | Main text, icons, navigation, structure. |

### Light Theme

| Token | Hex | Use |
| --- | --- | --- |
| `{colors.canvas}` | `#FFFFFF` | Base background. |
| `{colors.canvas-soft}` | `#F7F7FA` | Alternate bands, app backgrounds, secondary zones. |
| `{colors.surface}` | `#FFFFFF` | Cards, modals, menus, fields. |
| `{colors.surface-raised}` | `#FCFCFD` | Subtle raised surfaces. |
| `{colors.ink}` | `#333333` | Main text. |
| `{colors.ink-strong}` | `#1F1F24` | Headlines and highest-emphasis text. |
| `{colors.muted}` | `#6F6F78` | Secondary text. |
| `{colors.subtle}` | `#9A9AA3` | Placeholders, metadata, passive icons. |
| `{colors.hairline}` | `#E5E5EA` | Borders and dividers. |
| `{colors.hairline-soft}` | `#F0F0F3` | Soft dividers. |

### Dark Theme

| Token | Hex | Use |
| --- | --- | --- |
| `{colors.dark-canvas}` | `#121216` | Dark base background. |
| `{colors.dark-surface}` | `#1B1B22` | Cards and panels. |
| `{colors.dark-surface-raised}` | `#24242C` | Menus, popovers, sticky bars. |
| `{colors.dark-ink}` | `#F4F4F6` | Main text on dark surfaces. |
| `{colors.dark-muted}` | `#B8B8C2` | Secondary text on dark surfaces. |
| `{colors.dark-hairline}` | `#34343D` | Borders and dividers on dark surfaces. |

### Semantic

| Token | Hex | Use |
| --- | --- | --- |
| `{colors.success}` | `#4EBBB8` | Confirmations and correct states. |
| `{colors.warning}` | `#F59B1B` | Warnings, pending states, opportunities. |
| `{colors.error}` | `#D94A4A` | Errors and destructive actions. |
| `{colors.info}` | `#5E4595` | Highlighted information, tips, selection. |
| `{colors.focus}` | `#5E4595` | Accessible focus ring. |

### Color Principles

- Use purple as the primary accent, not as a dominant full-interface background.
- Reserve orange for punctual attention moments; if everything is orange, nothing is urgent.
- Use teal for progress, success, or activity signals.
- Keep charcoal as the visual anchor.
- For personalized physical products, let product imagery carry emotion; use UI color as guidance, not decoration.
- In light theme, the interface should be mostly white or very light gray.
- In dark theme, avoid pure black except for overlays or media; use nuanced dark surfaces.

## Iconography

Lucide is the default icon family for Pinxel interface design.

Use Lucide for:

- Product UI, websites, dashboards, WordPress themes, plugins, forms, toolbars, navigation, status states, and compact actions.
- Interface icons inside buttons, menu items, filters, empty states, alerts, and operational workflows.
- SVG-based implementation in web projects.

Do not treat Lucide as the complete brand illustration system. It is the functional UI icon base. Brand-specific symbols, campaign graphics, product-line marks, and expressive illustrations may be custom, but they should still feel compatible with Pinxel's geometry, stroke weight, and restrained visual tone.

### Technical Rules

- Use SVG as the primary icon format.
- For React, use `lucide-react` SVG components. Do not use icon fonts unless a legacy integration, client requirement, or external dependency requires them.
- For WordPress, prefer inline SVG, SVG sprite, or a theme/plugin icon helper. Avoid icon fonts unless a legacy constraint requires them.
- For Illustrator, Photoshop, and other design tools, import Lucide icons as editable SVG vectors.
- Keep icon stroke visually consistent with Lucide's default outline style.
- Use `currentColor` for interface icons so color follows the component state.
- Use 18px icons when paired with button text and 18px to 20px icons inside icon-only buttons.
- Do not mix Lucide with unrelated icon styles in the same interface.
- Custom icons should be drawn to match Lucide's simple outline language before being added to the system.

## Typography

### Font Family

Pinxel's primary typeface is **Inter**. It is a free and open-source font designed for digital interfaces, with clean, modern, precise readability. It works especially well for Pinxel because it brings the brand closer to a premium, minimal, product-oriented tone, aligned with the Apple reference without depending on SF Pro.

```css
font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
```

For digital product work, use Inter across the whole interface to simplify the system and preserve consistency. If Inter is unavailable, the system stack is an acceptable fallback.

### Additional Font Recommendation

Do not add a second display typeface at this stage. Pinxel benefits from a simple typographic system: Inter for brand, UI, content, and navigation.

A secondary font is recommended **only for code, tokens, or technical data**:

```css
font-family: "SFMono-Regular", Consolas, "Liberation Mono", monospace;
```

This monospace font should be limited to snippets, variables, technical tables, IDs, paths, and component documentation. Do not use it for navigation, buttons, or headlines.

### Hierarchy

| Token | Size | Weight | Line Height | Use |
| --- | ---: | ---: | ---: | --- |
| `{typography.hero}` | 56px | 800 | 1.05 | Primary brand or product headline. |
| `{typography.display-lg}` | 40px | 700 | 1.12 | Section headers. |
| `{typography.display-md}` | 32px | 700 | 1.18 | Internal page titles. |
| `{typography.title-lg}` | 24px | 700 | 1.25 | Important card and panel titles. |
| `{typography.title-md}` | 20px | 700 | 1.3 | Subtitles and content blocks. |
| `{typography.body-lg}` | 18px | 400 | 1.55 | Leads and editorial text. |
| `{typography.body}` | 16px | 400 | 1.5 | Base UI and content text. |
| `{typography.body-sm}` | 14px | 400 | 1.45 | Metadata, help text, tables. |
| `{typography.caption}` | 12px | 700 | 1.35 | Labels, chips, secondary navigation. |
| `{typography.button}` | 15px | 700 | 1 | Buttons. |
| `{typography.micro}` | 11px | 700 | 1.2 | Badges and compact states. |

### Typography Principles

- Use 700 or 800 for headlines when a piece needs stronger presence. Prefer 700 in daily UI.
- Use 400 for body copy; help text, metadata, and secondary navigation may use 400, 500, or 600 depending on density.
- Avoid negative letter-spacing. Keep `letter-spacing: 0` for clarity.
- Use 16px as the body baseline; increase to 18px for editorial or explanatory text.
- Do not use all caps for paragraphs or buttons. Reserve all caps for micro-labels only.
- Use `font-variant-numeric: tabular-nums` for metrics, tables, and dashboards.
- Load only the useful weights for performance: 400, 500, 600, 700, and 800. Add 300 only if very light editorial content appears.

## Layout

### Spacing

Pinxel uses an 8px spacing scale with a few intermediate values for details.

| Token | Value |
| --- | ---: |
| `{spacing.2xs}` | 4px |
| `{spacing.xs}` | 8px |
| `{spacing.sm}` | 12px |
| `{spacing.md}` | 16px |
| `{spacing.lg}` | 24px |
| `{spacing.xl}` | 32px |
| `{spacing.2xl}` | 48px |
| `{spacing.3xl}` | 64px |
| `{spacing.section}` | 88px |

### Containers

| Token | Value | Use |
| --- | ---: | --- |
| `{layout.container-sm}` | 760px | Reading, legal pages, articles. |
| `{layout.container-md}` | 1040px | Brandbook and content pages. |
| `{layout.container-lg}` | 1240px | Web pages, grids, components. |
| `{layout.container-xl}` | 1440px | Dashboards and wide experiences. |

### Grid

- Marketing web: 12 columns on desktop, 6 on tablet, 1 to 2 on mobile.
- Product: sidebar + content when navigation density justifies it.
- Cards: 3 columns on desktop, 2 on tablet, 1 on mobile.
- Forms: maximum 680px for reading and decision tasks.

### Whitespace

The interface must breathe. Space is not decoration: it is the primary tool for separating decisions, reducing noise, and increasing trust.

## Shape

| Token | Value | Use |
| --- | ---: | --- |
| `{radius.none}` | 0px | Full-width sections, dividers. |
| `{radius.xs}` | 6px | Small badges, indicators. |
| `{radius.sm}` | 10px | Compact inputs, dense elements. |
| `{radius.md}` | 16px | Cards, panels, modals. |
| `{radius.lg}` | 24px | Featured cards, highlighted containers. |
| `{radius.pill}` | 999px | Buttons, chips, search, segmented tabs. |
| `{radius.full}` | 50% | Circular icon buttons, avatars. |

Primary buttons are always pill-shaped. This is a brand signal: action should feel friendly, clear, and tactile.

## Elevation

Pinxel uses very little shadow. Depth comes from surface contrast, fine borders, and functional blur.

| Token | Value | Use |
| --- | --- | --- |
| `{shadow.none}` | none | Most surfaces. |
| `{shadow.sm}` | `0 1px 2px rgba(31,31,36,.06)` | Fields, bars, controls. |
| `{shadow.md}` | `0 12px 32px rgba(31,31,36,.10)` | Menus, popovers, featured cards. |
| `{shadow.lg}` | `0 24px 60px rgba(31,31,36,.16)` | Modals and critical overlays. |

Do not apply strong shadows to all cards. If a card needs hierarchy, first adjust size, spacing, and content.

## Motion

Motion should feel fast and useful.

| Token | Value | Use |
| --- | ---: | --- |
| `{motion.fast}` | 120ms | Press states, toggles, icon buttons. |
| `{motion.base}` | 180ms | Hover, focus, light expansion. |
| `{motion.slow}` | 260ms | Modals, sheets, view changes. |
| `{motion.ease}` | `cubic-bezier(.2,.8,.2,1)` | Default easing curve. |

### Rules

- Buttons: `transform: translateY(-1px)` on hover and `scale(.98)` on active.
- Panels: short fade + vertical translate.
- Avoid infinite animations except for loading/progress.
- Respect `prefers-reduced-motion`.

## Components

The implementation reference for base components lives in the UIKit:

- General UIKit documentation: `uikit/index.html`
- Global tokens and shared styles: `uikit/css/pinxel-uikit.css`
- Component-specific CSS: `uikit/css/components/*.css`
- Independent component pages: `uikit/components/*.html`

Use the UIKit as the first practical source when generating Pinxel interfaces. The brandbook defines principles; the UIKit shows concrete HTML/CSS patterns.

### Button Hierarchy

Pinxel has a closed button hierarchy:

- **Primary:** purple filled button for the main decision.
- **Secondary:** white/outlined button for visible alternatives.
- **Tertiary:** transparent text-like button for low-emphasis contextual actions.
- **Accent:** orange filled button for punctual commercial emphasis.
- **Icon button:** circular icon-only tool button.

Do not create teal buttons as a base variant. Teal is reserved for progress, success badges, alerts, and positive status feedback. If a positive action needs a button, use the primary or secondary hierarchy and communicate success after the action.

### Primary Button

Purple pill for primary actions.

- Background: `{colors.purple}`
- Text: white
- Radius: `{radius.pill}`
- Height: 44px normal, 52px large
- Padding: 0 22px
- Font: `{typography.button}`
- Class: `.px-button .px-button--primary`

States:

- Default: background `#5E4595`, text white.
- Hover: background `#523B84`, translate up `-1px`.
- Active / pressed: background `#493176`, `transform: scale(.98)`.
- Focus visible: 3px outline using `rgba(94,69,149,.28)` with 3px offset.
- Disabled: background `#D8D1E7`, white text, `cursor: not-allowed`, no transform.
- Loading: use `aria-busy="true"`, show spinner, prevent duplicate submissions.

Use primary buttons for one main decision per block: create product, continue, confirm design, save, activate automation, or complete checkout. Do not place two primary buttons in the same decision group.

### Secondary Button

White pill with a soft border. Use for visible alternative actions that support the primary action without competing with it. Secondary buttons should feel available and reliable, but clearly less important than the primary button.

- Background: `{colors.surface}`
- Text: `{colors.charcoal}`
- Border: 1px solid `{colors.hairline}`
- Radius: `{radius.pill}`
- Class: `.px-button .px-button--secondary`
- Height: 44px default, 52px large, 36px small only in dense toolbars or tables.
- Padding: 0 22px default.
- Typography: `{typography.button}`.

States:

- Default: white surface, charcoal text, `#E5E5EA` hairline border.
- Hover: subtle purple-tinted border, soft shadow, translate up `-1px`.
- Active / pressed: soft purple background `rgba(94,69,149,.08)`, purple-tinted border, `transform: scale(.98)`.
- Focus visible: same global focus ring as primary, 3px outline using `rgba(94,69,149,.28)`.
- Disabled: soft canvas background, subtle text, hairline border, no elevation, `cursor: not-allowed`.
- Loading: use `aria-busy="true"` when saving or processing an alternative action. Show spinner and prevent duplicate submissions.

Use secondary buttons for:

- Cancel
- Save draft
- Review before confirming
- Back
- Edit
- Compare
- View preview
- Choose a non-primary path

Do not use secondary buttons for:

- The main conversion action in a block
- Quiet helper links
- Destructive actions unless paired with explicit warning language
- Multiple competing alternatives with equal visual weight

Recommended pairing:

- Primary + secondary: "Confirm design" + "Save draft"
- Primary + secondary: "Activate flow" + "Preview messages"
- Primary + secondary: "Continue checkout" + "Edit product"

### Tertiary Button

Transparent low-emphasis action. It behaves like a button, but visually reads closer to an action link with a generous touch target. Use tertiary buttons for contextual actions that should remain available without adding visual weight.

- Background: transparent
- Text: `{colors.purple}` by default
- Border: none
- Radius: `{radius.pill}`
- Class: `.px-button .px-button--tertiary`
- Legacy alias: `.px-button .px-button--ghost`
- Padding: 0 14px default
- Height: 44px default

States:

- Default: transparent background, purple text.
- Hover: soft purple background `rgba(94,69,149,.09)`, translate up `-1px`.
- Active / pressed: stronger soft purple background `rgba(94,69,149,.14)`, `transform: scale(.98)`.
- Focus visible: same global focus ring as primary.
- Disabled: transparent background, subtle text, no transform.
- Loading: allowed only when the tertiary action performs async work; prefer secondary if the operation is important.

Tertiary variants:

- `.px-button--tertiary`: purple text for brand-aligned contextual actions.
- `.px-button--tertiary-neutral`: charcoal text for quiet utility actions.
- `.px-button--tertiary-danger`: red text for low-emphasis destructive actions such as "Remove" inside a confirmation context.

Use tertiary buttons for:

- View details
- Skip
- Edit later
- Open help
- Learn more
- Remove an optional item after confirmation context is visible

Do not use tertiary buttons for:

- Required next steps
- Primary commerce actions
- Final confirmation
- Main checkout actions
- Destructive actions without confirmation or clear context

Recommended pairing:

- Primary + tertiary: "Personalize now" + "View details"
- Secondary + tertiary: "Save draft" + "Edit later"
- In dense rows: icon button + tertiary text action when the action needs a label.

### Accent Button

Orange filled button for punctual commercial or promotional emphasis. It must not replace the primary button in critical product flows. The accent button should be rare enough to keep its energy.

- Class: `.px-button .px-button--accent`
- Background: `{colors.orange}` / `#F59B1B`
- Text: charcoal / `#1F1F24`
- Border: transparent
- Radius: `{radius.pill}`
- Height: 44px default, 52px large
- Padding: 0 22px default

States:

- Default: orange background, charcoal text.
- Hover: darker orange `#DF8810`, translate up `-1px`.
- Active / pressed: `transform: scale(.98)`.
- Focus visible: same global focus ring.
- Disabled: pale orange background `#F8D9A7`, muted charcoal text.
- Loading: allowed for commercial operations such as publishing or boosting; use `aria-busy="true"`.

Use accent buttons for:

- Boost sale
- Promote product
- Open offer
- Highlight limited commercial opportunity
- Start a marketing action

Do not use accent buttons for:

- Checkout confirmation
- Saving user data
- Generic navigation
- Success confirmation
- Error/destructive action

### Icon Button

Circular icon-only tool button for compact actions.

- Class: `.px-icon-button`
- Size: 44px by default.
- Border: 1px solid `{colors.hairline}`.
- Background: `{colors.surface}`.
- Icon: 18px to 20px.
- Radius: `{radius.full}`.

States:

- Default: white surface, charcoal icon, hairline border.
- Hover: subtle purple-tinted border, soft shadow, translate up `-1px`.
- Active / pressed: soft purple surface, purple icon, `transform: scale(.96)`.
- Focus visible: same global focus ring.
- Disabled: soft canvas background, subtle icon, no elevation.

- Accessibility: every icon-only button must include an `aria-label`.
- Minimum touch target: 44x44px.

Use icon buttons for:

- Search
- Filter
- Edit
- Close
- Download
- Open menu

Do not use icon buttons for:

- Actions whose meaning is unclear without text
- Primary conversion actions
- Long labels hidden inside tooltips
- Destructive actions unless the icon is inside a clearly labeled destructive context

### Button Sizes

- Small: 36px height, `.px-button--small`; only for dense toolbars or tables.
- Default: 44px height; use for most UI actions.
- Large: 52px height, `.px-button--large`; use for hero, checkout, onboarding, or high-importance flows.
- Full width: `.px-button--full`; use in mobile, forms, checkout cards, or narrow panels.

### Button Accessibility Rules

- Use native `<button>` for in-page actions and `<a>` only for navigation.
- Always set `type="button"` unless the button submits a form.
- If a link must appear disabled, use `aria-disabled="true"` and remove or prevent navigation behavior in the implementation.
- Do not communicate disabled state only through opacity; use disabled styles and nearby helper text when the reason is not obvious.
- Use `aria-busy="true"` for loading states and prevent duplicate submissions.
- Icon-only buttons require `aria-label`.
- Preserve visible focus. Never remove focus outlines without a replacement.

### Top Navigation

Clean top bar with logo on the left, navigation in the center or right, and the primary CTA at the end.

- Height: 72px desktop, 60px mobile
- Background: canvas with optional blur when sticky
- Bottom border: 1px solid `{colors.hairline-soft}`
- Logo: 120px to 144px wide

### Tabs

Use pill tabs or underline tabs depending on context.

- Pill tabs: filters, dashboard views, editor modes.
- Underline tabs: documentation, content pages, secondary navigation.

### Slider Navigation Buttons

Use circular icon-only controls for local previous/next navigation inside product carousels, image galleries, previews, horizontal collections, and onboarding slides.

- Size: 44px minimum touch target.
- Shape: full circle.
- Icon: centered chevron arrow, no visible text.
- Surface: `{colors.surface}` with `{colors.hairline}` border.
- Hover: subtle lift, stronger border, light shadow.
- Active: slight scale down and soft purple background.
- Focus: visible purple focus ring.
- Disabled: soft gray surface, muted icon, no shadow or movement.
- Accessibility: always include `aria-label`, such as `View previous item` or `View next item`.
- Placement: center vertically over the slider viewport on desktop.
- Mobile: move controls below the image or to the bottom of the viewport if they cover important content.

Do not use slider navigation buttons for page navigation, form actions, checkout decisions, or primary CTAs.

### Cards

Cards are work surfaces, not decoration.

- Background: `{colors.surface}`
- Border: 1px solid `{colors.hairline}`
- Radius: `{radius.md}`
- Padding: 24px
- Shadow: none by default

Use shadow only for floating or interactive cards.

### Form Fields

Clean, rounded inputs with visible focus.

- Height: 48px
- Radius: `{radius.pill}` for search and primary single-line fields
- Radius: `{radius.sm}` for dense technical forms
- Border: 1px solid `{colors.hairline}`
- Focus: purple border + soft ring

### Search

Global search is a prominent pill.

- Height: 48px to 56px
- Leading icon
- Clear placeholder
- Optional trailing action or filter when relevant

### Badges

Compact badges for status.

- Success: teal with dark or white text depending on contrast.
- Warning: orange with charcoal text.
- Info: soft purple.
- Neutral: light gray.

### Alerts

Alerts should be clear, not aggressive.

- Success: teal border/icon.
- Warning: orange border/icon.
- Error: red border/icon.
- Info: purple border/icon.

### Data Cards

For dashboards and metrics.

- Use tabular numbers.
- Include label, value, delta, and time context.
- Avoid communicating trend through color alone.

### Footer

Restrained footer with logo, links, and legal data.

- Light background: `{colors.canvas-soft}`
- Dark background: `{colors.dark-surface}`
- Simple columns
- Small but legible text

## App Patterns

### Marketing Web

- Simple hero with a strong headline, short subtitle, and no more than two CTAs.
- Avoid card-heavy first screens.
- Show the product, an interface, or a real visual signal from Pinxel.
- For physical product pages, show the actual customizable object early.
- For Pinxel Lab pages, show the system, workflow, automation, or interface being built.

### SaaS / Dashboard

- Use side or top navigation depending on density.
- Toolbars should use icons and labels only when labels help.
- Use contained cards, clean tables, visible filters.
- Empty states should include a direct action.

### E-Commerce / Personalization

- The customer should feel they are participating in creation, not just selecting a SKU.
- Keep customization steps visible: product, options, preview, customer details, confirmation.
- Use large previews for personalized objects.
- Use clear labels for options such as color, format, size, pet data, portrait style, or delivery channel.
- For WhatsApp-driven flows, make the next action explicit and human: continue, confirm, send, review.

### AI Automation

- Present AI as a practical assistant, not as magic.
- Explain what the automation will do, when it will act, and what the user can control.
- For chatbots and follow-up systems, show status, owner, last interaction, and next step.
- Avoid abstract AI visuals when a workflow, message, or result can be shown.

### Mobile

- CTAs must be at least 44px tall.
- Use bottom bars for persistent actions.
- Use large, easy-to-touch inputs.
- Reduce columns to one vertical reading flow.

## Accessibility

- Minimum AA contrast for normal text.
- Visible focus on every interactive control.
- Do not communicate states through color alone.
- Minimum touch target: 44x44px.
- Real labels on inputs.
- Icon buttons must have `aria-label`.
- Respect `prefers-reduced-motion`.

## Do's And Don'ts

### Do

- Use plenty of white space and typographic hierarchy.
- Keep primary buttons pill-shaped.
- Use purple for primary decisions.
- Use orange and teal as punctual signals.
- Design light theme first.
- Build components with complete states: default, hover, active, focus, disabled, and loading.

### Don't

- Do not turn the entire interface purple.
- Do not use decorative gradients as a base resource.
- Do not fill pages with shadows or nested cards.
- Do not use hard corners on CTAs.
- Do not mix too many icon styles.
- Do not create dark mode as an automatic inversion without reviewing contrast.

## CSS Design Tokens

```css
:root {
  --pinxel-purple: #5e4595;
  --pinxel-orange: #f59b1b;
  --pinxel-teal: #4ebbb8;
  --pinxel-charcoal: #333333;

  --color-canvas: #ffffff;
  --color-canvas-soft: #f7f7fa;
  --color-surface: #ffffff;
  --color-ink: #333333;
  --color-ink-strong: #1f1f24;
  --color-muted: #6f6f78;
  --color-subtle: #9a9aa3;
  --color-hairline: #e5e5ea;

  --radius-sm: 10px;
  --radius-md: 16px;
  --radius-lg: 24px;
  --radius-pill: 999px;

  --shadow-sm: 0 1px 2px rgba(31, 31, 36, .06);
  --shadow-md: 0 12px 32px rgba(31, 31, 36, .10);

  --font-sans: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  --font-mono: "SFMono-Regular", Consolas, "Liberation Mono", monospace;
}

[data-theme="dark"] {
  --color-canvas: #121216;
  --color-canvas-soft: #17171d;
  --color-surface: #1b1b22;
  --color-ink: #f4f4f6;
  --color-ink-strong: #ffffff;
  --color-muted: #b8b8c2;
  --color-subtle: #888894;
  --color-hairline: #34343d;
}
```
