# Emera Brand System

This repository is the single source of truth for Emera's design system, brand tokens, and visual identity. It is used as the design system source for Claude Design.

**Website:** [emera.co.za](https://emera.co.za)  
**Built on:** Webflow  
**Last updated:** June 2026  

---

## Repository Structure

```
emera-brand/
├── README.md                    ← This file
├── brand-guidelines.md          ← Full brand guidelines (voice, personality, usage rules)
├── design-tokens.css            ← CSS custom properties — all color and typography tokens
├── components.md                ← UI component specifications
└── assets/
    ├── logo-dark.svg            ← EMERA wordmark — dark on transparent
    ├── logo-light.svg           ← EMERA wordmark — white on transparent
    └── logo-dark-bg.svg         ← EMERA wordmark — white on dark background
```

---

## Quick Reference

### Brand in one sentence
Emera is an AI brand and growth studio — we combine deep brand strategy with AI-powered execution. Editorial aesthetic, minimal execution, always intentional.

### Colors
| Token | Hex | Use |
|-------|-----|-----|
| `--emera-dark` | `#0f0f0f` | Primary black — headlines, buttons, dark sections |
| `--emera-text` | `#1a1a1a` | Body text |
| `--emera-sub` | `#5a5a5a` | Subdued text, captions |
| `--emera-light` | `#f7f7f5` | Off-white background |
| `--emera-accent` | `#f0f191` | Yellow-green accent — sparingly |
| `--emera-white` | `#ffffff` | Pure white |
| `--emera-border` | `#e0e0dc` | Borders, dividers |

### Fonts
- **Headings:** Cormorant Garant (serif) — [Google Fonts](https://fonts.google.com/specimen/Cormorant+Garant)
- **Body:** DM Sans (sans-serif) — [Google Fonts](https://fonts.google.com/specimen/DM+Sans)

---

## Usage in Claude Design

This repo is connected to Claude Design as the organisation's design system. When creating any project, Claude Design will automatically apply:
- Emera's color tokens
- Cormorant Garant + DM Sans typography
- Component specs from `components.md`
- Brand voice and personality from `brand-guidelines.md`
