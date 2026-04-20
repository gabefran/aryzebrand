# Aryze Brand Repository

This repository contains all brand assets, design tokens, and guidelines for Aryze ApS. Aryze is a Danish fintech company developing Pay by Bank solutions for UK merchants with a focus on real-time payment processes, practical payment operations, and simple pricing that teams can plan around.

---

## Repository Structure

```
aryzebrand/
├── tokens/
│   └── tokens.json          # All design tokens — colors, typography, spacing, radius, shadow, motion
├── fonts/
│   └── Geist-*.woff2        # Geist font family (Regular, Medium, SemiBold, Bold)
├── logos/
│   ├── aryze-logo-dark.svg  # Primary logo — dark on light backgrounds
│   ├── aryze-logo-light.svg # Reversed logo — light on dark backgrounds
│   └── aryze-icon.svg       # Icon/mark only
├── guidelines/
│   ├── brand-guidelines.md  # Full visual identity: colors, type, components, do/don't
│   ├── messaging.md         # Tone of voice, copy rules, audience personas
│   └── visual-direction.md  # Photography, layout, and aesthetic direction
└── references/
    └── (screenshots of existing Aryze assets for visual reference)
```

---

## Quick Reference

**Primary brand color:** `#00AFE7` (CTAs, interactive elements, product marketing)  
**Page background:** `#F7F9FA`  
**Primary text:** `#001E2B`  
**Font:** Geist (all weights)  
**Aesthetic:** Scandinavian realism — Copenhagen aesthetic, pale surfaces, flat Nordic daylight

---

## Design System Summary

Aryze's visual identity is enterprise-grade and Scandinavian in character. Clean without being cold. Precise without being sterile. The reference point is Stripe or Linear adapted for Nordic fintech.

### Key design rules
- Always use `#F7F9FA` as the page background, never pure white
- Brand Blue (`#00AFE7`) is for CTAs and highlights only — not large background fills
- All borders use `#BFD9EF` — soft and never harsh
- Typography is exclusively Geist — no other fonts
- Shadows are minimal: `0 1px 3px rgba(0, 30, 43, 0.08)` default
- Border radius: `6px` on inputs/cards, `4px` on badges, `8px` on modals
- Icons: Geist icons or Lucide — line style, never emoji

### Key messaging rules
- Never frame card payments negatively — Mastercard is a partner
- Use "built on Mastercard payment rails" — not "trust and infrastructure of Mastercard"
- Lead with conversion/drop-off framing, not cost assumptions
- Don't presume the prospect's current setup or pain

---

## For Claude Design

Point Claude Design at this repository during design system setup. It will extract:
- Color tokens from `tokens/tokens.json`
- Typography from `tokens/tokens.json`
- Spacing, radius, shadow, and motion tokens from `tokens/tokens.json`
- Component and aesthetic guidance from `guidelines/brand-guidelines.md`
- Visual direction from `guidelines/visual-direction.md`

---

## Maintained by

Aryze Marketing — Copenhagen  
Primary contact: Gabe Fran
