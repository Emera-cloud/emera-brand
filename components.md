# Emera Component Specifications

All components use the design tokens defined in `design-tokens.css`.

---

## Buttons

### Primary Button
The main CTA. Used for "Start a conversation", "Let's Talk", "Get started".

- **Background:** `#0f0f0f`
- **Text:** `#ffffff`, DM Sans Medium, 15px
- **Padding:** 14px 28px
- **Border radius:** 4px (near-square — never pill-shaped)
- **Hover:** opacity 0.85

### Secondary Button
Used for softer actions like "See what we build".

- **Background:** transparent
- **Border:** 1.5px solid `#0f0f0f`
- **Text:** `#0f0f0f`, DM Sans Medium, 15px
- **Padding:** 14px 28px
- **Border radius:** 4px
- **Hover:** background `#0f0f0f`, text `#ffffff`

### Accent Tag / Badge
For category labels and service tags. Example: "AI BRAND & GROWTH STUDIO", "MOST POPULAR".

- **Background:** `#f0f191`
- **Text:** `#0f0f0f`, DM Sans Medium, 12px, UPPERCASE, letter-spacing 0.08em
- **Padding:** 6px 14px
- **Border radius:** 100px (pill)

---

## Navigation

- **Logo:** EMERA wordmark — Cormorant Garant Bold, uppercase, `#0f0f0f`
- **Nav links:** DM Sans Regular, 15px, `#0f0f0f`
- **CTA button:** Primary button style ("Let's Talk")
- **Background:** White/transparent, no border, clean
- **Mobile:** Hamburger menu, full-screen overlay

---

## Cards

### Service Card
Used in the "What We Build" section.

- **Background:** `#f7f7f5`
- **Border:** 1px solid `#e0e0dc`
- **Padding:** 40px
- **Border radius:** 4px
- **Icon:** Decorative symbol character (`✦`, `▽`, `◎`, etc.) in `#0f0f0f`
- **Title:** Cormorant Garant Medium, 28px, `#0f0f0f`
- **Body:** DM Sans Regular, 16px, `#1a1a1a`, line-height 1.65
- **No drop shadows**

### Pricing / Package Card
Used in the "How We Work" section.

- **Background (default):** `#f7f7f5`
- **Background (featured "Most Popular"):** `#0f0f0f`
- **Text (featured):** `#ffffff`
- **Tag (featured):** Accent badge `#f0f191` with `#0f0f0f` text
- **Padding:** 48px
- **Border radius:** 4px
- **Plan name:** DM Sans Medium, 12px, uppercase, tracked — `#5a5a5a` (or `rgba(255,255,255,0.5)` on dark)
- **Title:** Cormorant Garant Bold, 36px
- **Description:** DM Sans Regular, 16px, `#5a5a5a`
- **List items:** DM Sans Regular, 15px, with bullet or checkmark
- **CTA:** Full-width button at card bottom

---

## Stat Block

Used for metrics like "3×", "60%", "40%".

- **Number:** DM Sans Bold, 56–72px, `#0f0f0f`
- **Descriptor:** DM Sans Regular, 15px, `#5a5a5a`
- **Layout:** Number above, descriptor below
- **No border, no background** — sits inline in content

---

## Section Eyebrow / Label

Small uppercase label that introduces a section. Example: "THE PROBLEM", "OUR APPROACH".

- **Font:** DM Sans Medium, 12px
- **Color:** `#5a5a5a`
- **Case:** UPPERCASE
- **Letter spacing:** 0.12em
- **Margin bottom:** 16px before the section headline

---

## Dividers

### Hairline Rule
- 1px solid `#e0e0dc`
- Full width within its container
- Used to separate content sections within a surface

### Accent Rule
- 2px solid `#f0f191`
- Width: 32px (short — not full width)
- Used as a decorative punctuation mark before section titles
- Margin: 24px top and bottom

---

## Scroll Ticker / Marquee
Horizontal scrolling strip showing service categories.

- **Background:** `#0f0f0f`
- **Text:** `#ffffff`, DM Sans Medium, 13px, UPPERCASE, letter-spacing 0.08em
- **Separator:** `•` bullet in `#f0f191`
- **Height:** ~56px
- **Animation:** Continuous left-scroll, pauses on hover

---

## Page Layout Patterns

### Hero (Home)
- Full viewport height
- Centered content
- Large display headline: Cormorant Garant Bold, 80–120px
- Subheadline: DM Sans Regular, 20px, `#5a5a5a`
- Grid texture overlay (hairline lines `#e0e0dc`, 0.2 opacity)
- Animated word/letter entrance

### Two-Column Content Section
- Left: Large Cormorant Garant headline (H2)
- Right: DM Sans body text + optional stat blocks
- Split at ~40/60 or 50/50
- Vertical divider line `#e0e0dc` optional

### Numbered Process List
- Step number: DM Sans Medium, 13px, `#5a5a5a`, uppercase
- Title: Cormorant Garant Medium, 32px
- Body: DM Sans Regular, 16px, `#1a1a1a`
- Horizontal hairline rule `#e0e0dc` between items

### Dark CTA Section
- Background: `#0f0f0f`
- Headline: Cormorant Garant Bold, large, `#ffffff`
- Supporting copy: DM Sans Regular, `rgba(255,255,255,0.65)`
- Button: White text with `#ffffff` border (or accent `#f0f191` text)

---

## Footer

- **Background:** `#0f0f0f`
- **Logo: Logo:** EMERA wordmark, `#ffffff`
- **Tagline:** "Where brands emerge." — DM Sans Regular, `rgba(255,255,255,0.65)`
- **Email:** `hello@emera.co.za`
- **Link columns:** DM Sans Regular, 14px, `rgba(255,255,255,0.7)`, hover `#ffffff`
- **Copyright:** DM Sans Regular, 12px, `rgba(255,255,255,0.4)`
- **Divider above copyright:** 1px `rgba(255,255,255,0.12)`

---

## Forms

- **Input background:** `#ffffff`
- **Input border:** 1px solid `#e0e0dc`
- **Input border (focus):** 1px solid `#0f0f0f`
- **Input text:** DM Sans Regular, 16px, `#1a1a1a`
- **Label:** DM Sans Medium, 13px, `#0f0f0f`, uppercase
- **Placeholder:** `#5a5a5a`
- **Submit button:** Primary button style
- **Border radius:** 4px
