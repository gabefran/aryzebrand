# Aryze Brand Guidelines

## Company Overview

Aryze is a Danish B2B fintech company building core payment infrastructure for the next generation of money movement

Headquartered in Copenhagen. Enterprise-grade. Built on Mastercard payment rails.

Primary audiences: iGaming operators, crypto exchanges, digital marketplaces, and payment-sensitive merchants across Europe and the UK.

---

## Visual Identity

### Aesthetic Direction

**Scandinavian realism.** Copenhagen aesthetic. Pale surfaces, flat Nordic daylight, generous whitespace. Clean without being cold. Precise without being sterile.

Reference points: Stripe, Linear, Vercel — adapted for Nordic fintech. Enterprise SaaS quality, never startup flashy.

### Color System

All values defined in `tokens/tokens.json`. Key usage rules:

| Token | Value | Usage |
|---|---|---|
| `color.background` | `#F7F9FA` | Page background — never pure white |
| `color.foreground` | `#001E2B` | All primary text, headings |
| `color.brand-blue` | `#00AFE7` | Primary CTAs, links, interactive highlights |
| `color.secondary` | `#BFD9EF` | Soft fills, secondary backgrounds |
| `color.accent` | `#D9F5EA` | Success-adjacent, sidebar highlights |
| `color.muted` | `#E3E8EB` | Dividers, subtle backgrounds |
| `color.muted-foreground` | `#122D47` | Secondary text, captions |
| `color.border` | `#BFD9EF` | All borders — soft, never harsh |
| `color.destructive` | `#DC2626` | Error states only |
| `color.white` | `#FFFFFF` | Cards, inputs, modal surfaces |

**Critical rules:**
- `color.brand-blue` (`#00AFE7`) is for CTAs and product marketing only — never use as background fill for large areas
- `color.foreground` (`#001E2B`) is for text and dark surface backgrounds only
- Borders should always feel soft — `#BFD9EF`, never black or dark grey
- Never use pure black (`#000000`) anywhere in the UI

### Typography

**Font:** Geist (sans-serif) for all UI, marketing, and documents. Geist Mono for code and data strings.

```
H1: 48px / Bold (700) / tracking -0.02em / leading 1.15
H2: 36px / SemiBold (600) / tracking -0.02em / leading 1.15
H3: 28px / SemiBold (600) / tracking -0.02em / leading 1.2
H4: 22px / Medium (500) / tracking 0 / leading 1.3
Body LG: 18px / Regular (400) / leading 1.75
Body: 16px / Regular (400) / leading 1.5
Body SM: 14px / Regular (400) / leading 1.5
Label: 12px / Medium (500) / tracking 0.04em / uppercase
```

### Spacing & Layout

Base unit: **4px**. All spacing is a multiple of 4.

- Default card padding: `24px`
- Section vertical padding: `64px` (desktop), `48px` (mobile)
- Max content width: `1280px`
- Column gutter: `24px`

### Border Radius

- Badges, chips, tags: `4px`
- Inputs, buttons, cards: `6px`
- Modals, dialogs: `8px`
- Large feature cards: `12px`
- Pill: `9999px`

### Shadows

```
Default card:  0 1px 3px rgba(0, 30, 43, 0.08)
Dropdown:      0 4px 12px rgba(0, 30, 43, 0.10)
Modal:         0 8px 24px rgba(0, 30, 43, 0.12)
```

---

## Component Patterns

### Buttons

| Variant | Background | Text | Border |
|---|---|---|---|
| Primary | `#00AFE7` | `#FFFFFF` | none |
| Secondary | `#FFFFFF` | `#001E2B` | `#BFD9EF` |
| Ghost | transparent | `#001E2B` | none |
| Destructive | `#DC2626` | `#FFFFFF` | none |

- Border radius: `6px`, Padding: `10px 20px`, Font: 14px Medium

### Cards

- Background: `#FFFFFF`, Border: `1px solid #BFD9EF`, Radius: `6px`, Padding: `24px`

### Inputs

- Background: `#FFFFFF`, Border: `1px solid #BFD9EF`, Radius: `6px`
- Focus: `#007599` 2px, Error: `#DC2626`, Placeholder: `#B8C1C7`

### Badges

| State | Background | Text |
|---|---|---|
| Active | `#D9F5EA` | `#006282` |
| Info | `#BFD9EF` | `#001E2B` |
| Error | `#FEE2E2` | `#DC2626` |
| Neutral | `#E3E8EB` | `#122D47` |

---

## Iconography

- Line icons, 1.5px stroke, Geist icons preferred, Lucide fallback
- Sizes: 16px inline, 20px standalone, 24px feature
- Never use emoji in UI

---

## Do / Don't

### Do
- Use generous whitespace
- Lead with conversion framing
- Keep surfaces pale (`#F7F9FA`, `#FFFFFF`)
- Use `#00AFE7` for CTAs only
- Use soft borders (`#BFD9EF`) consistently

### Don't
- Use pure black anywhere
- Use harsh shadows
- Use emoji in UI
- Use decorative gradients
- Use fonts other than Geist
- Frame card payments negatively (Mastercard is a partner)
- Presume the prospect's current setup or pain
