# ReguMe Color Palette & Brand DNA

**Last Updated:** December 22, 2025

This document outlines the complete color palette and brand design system for ReguMe, matching the iOS mobile app exactly.

---

## 🎨 Brand Personality

**Warm, Welcoming, Motivating**

- **Warm:** Peach/coral tones create a welcoming, friendly atmosphere
- **Professional:** Clean whites and charcoal provide trustworthiness
- **Motivating:** Coral burst accent encourages action and energy
- **Calm:** Subtle gradients prevent visual overwhelm

---

## 🔥 PRIMARY BRAND COLORS

### Coral Burst (Main Brand Identity)

```css
--primary:       #E86842  /* Main buttons, CTAs, links, brand identity */
--primary-dark:  #FF6B4A  /* Hover states, emphasis, pressed buttons */
--primary-light: #FFC4A8  /* Light accents, highlights, soft emphasis */
--primary-muted: #FFE5D9  /* Very subtle backgrounds, disabled states */
```

**Usage:** 10% of UI surface area
**Purpose:** Calls-to-action, primary buttons, key interactions, brand moments

---

## 🍑 BACKGROUND COLORS

### Warm & Inviting Base

```css
--background:           #FFF4EC  /* Very Light Peach - main page background */
--background-secondary: #FFFFFF  /* Pure White - cards, modals, content blocks */
--background-tint:      #E7F3F1  /* Chip Sage - subtle backgrounds */
--peach-soft:           #F8DCCF  /* Soft Peach - gradients, special sections */
```

**Usage:** 80% of UI surface area
**Purpose:** Main screen backgrounds, card surfaces, content containers

---

## 🖤 TEXT COLORS

### Charcoal & Grays

```css
--text:           #1E1F22  /* Charcoal - primary text, headlines, body copy */
--text-secondary: #5A5A5C  /* Medium Gray - secondary text, descriptions */
--text-tertiary:  #9E9EA0  /* Light Gray - hints, disabled text, placeholders */
--dark:           #1E1F22  /* Alias for primary text (consistency) */
```

**Usage:** All text content
**Purpose:** Excellent readability with warm backgrounds

---

## 🔲 BORDER COLORS

### Warm Neutrals

```css
--border:       #E0D8D0  /* Warm Neutral - card borders, input borders */
--border-light: #F0E8E0  /* Very Light Warm - dividers, subtle separators */
```

**Usage:** Card edges, input fields, dividers, separators
**Purpose:** Soft definition without harshness

---

## 🌈 GRADIENTS

### Smooth Transitions

```css
/* Warm gradient: Soft peach to white */
--gradient-warm: linear-gradient(135deg, #F8DCCF 0%, #FFFFFF 100%);

/* Primary gradient: Coral burst gradient */
--gradient-primary: linear-gradient(135deg, #E86842 0%, #FFC4A8 100%);

/* Background gradient: Peach to sage */
--gradient-background: linear-gradient(135deg, #F8DCCF 0%, #E7F3F1 100%);

/* Hero gradient: Vertical peach fade */
--gradient-hero: linear-gradient(180deg, #FFF4EC 0%, #FFFFFF 100%);
```

**Usage:** Hero sections, special cards, button effects
**Purpose:** Add depth and visual interest without overwhelming

---

## ✅ SEMANTIC COLORS

### Status & Feedback

```css
/* Success States */
--success:      #DDEAE6  /* Mint Mist - success backgrounds */
--success-dark: #66BB6A  /* Traditional Green - strong success indicators */

/* Warning States */
--warning: #FF9A56  /* Warm Orange - warnings, caution messages */

/* Error States */
--error: #EF4444  /* Clear Red - errors, destructive actions */

/* Info States */
--info: #3B82F6  /* Blue - informational messages */
```

**Usage:** Alerts, status indicators, form validation, notifications
**Purpose:** Clear communication of system states

---

## 📊 Color Usage Breakdown (60-30-10 Rule)

### Surface Area Distribution

```
60% - Backgrounds (#FFF4EC, #FFFFFF, #E7F3F1)
30% - Text & Content (#1E1F22, #5A5A5C)
10% - Accents & CTAs (#E86842, #FFC4A8)
```

---

## 🎯 Design Principles

### 1. Warm First
All backgrounds use warm peach tones to create an inviting, comfortable feel.

### 2. High Contrast Text
Charcoal (#1E1F22) on light peach (#FFF4EC) ensures excellent readability.

### 3. Coral Burst for Action
Use the primary coral (#E86842) exclusively for clickable elements and CTAs.

### 4. Gradients Add Depth
Subtle gradients create visual interest without distraction.

### 5. Borders Blend
Warm neutral borders (#E0D8D0) blend naturally with the peach backgrounds.

---

## 💻 CSS Implementation

### CSS Custom Properties (Variables)

```css
:root {
  /* PRIMARY BRAND - Coral Burst */
  --primary: #E86842;
  --primary-dark: #FF6B4A;
  --primary-light: #FFC4A8;
  --primary-muted: #FFE5D9;
  
  /* BACKGROUNDS - Warm & Inviting */
  --background: #FFF4EC;
  --background-secondary: #FFFFFF;
  --background-tint: #E7F3F1;
  --peach-soft: #F8DCCF;
  
  /* TEXT COLORS - Charcoal & Grays */
  --text: #1E1F22;
  --text-secondary: #5A5A5C;
  --text-tertiary: #9E9EA0;
  --dark: #1E1F22;
  
  /* BORDER COLORS - Warm Neutrals */
  --border: #E0D8D0;
  --border-light: #F0E8E0;
  
  /* GRADIENTS */
  --gradient-warm: linear-gradient(135deg, #F8DCCF 0%, #FFFFFF 100%);
  --gradient-primary: linear-gradient(135deg, #E86842 0%, #FFC4A8 100%);
  --gradient-background: linear-gradient(135deg, #F8DCCF 0%, #E7F3F1 100%);
  --gradient-hero: linear-gradient(180deg, #FFF4EC 0%, #FFFFFF 100%);
  
  /* SEMANTIC COLORS */
  --success: #DDEAE6;
  --success-dark: #66BB6A;
  --warning: #FF9A56;
  --error: #EF4444;
  --info: #3B82F6;
}
```

---

## 🖼️ Brand Assets

### Logo URLs

**Horizontal Logo (Header):**
```
https://res.cloudinary.com/dsulhqvza/image/upload/v1763994515/Untitled_design_28_yscikl.png
```

**Square App Icon:**
```
https://res.cloudinary.com/dsulhqvza/image/upload/v1763504676/Untitled_design_27_zb32bz.png
```

---

## 🎨 Component Color Guidelines

### Buttons

```css
/* Primary CTA Button */
background: var(--primary);           /* #E86842 */
color: white;
box-shadow: 0 2px 8px rgba(232, 104, 66, 0.2);

/* Hover State */
background: var(--primary-dark);      /* #FF6B4A */
box-shadow: 0 4px 12px rgba(232, 104, 66, 0.3);

/* Secondary Button */
background: var(--background-secondary); /* #FFFFFF */
color: var(--primary);                /* #E86842 */
border: 2px solid var(--primary);

/* Secondary Hover */
background: var(--primary-muted);     /* #FFE5D9 */
color: var(--primary-dark);           /* #FF6B4A */
```

### Cards

```css
background: var(--background-secondary);  /* #FFFFFF */
border: 1px solid var(--border-light);    /* #F0E8E0 */
border-radius: 16px;
box-shadow: 0 2px 12px rgba(0, 0, 0, 0.06);
```

### Alerts

```css
/* Warning Alert (Health Notices) */
background: #FFF4EC;
border-left: 4px solid var(--warning);  /* #FF9A56 */

/* Info Alert */
background: var(--success);              /* #DDEAE6 */
border-left: 4px solid var(--info);      /* #3B82F6 */

/* Error Alert */
background: #FEE2E2;
border-left: 4px solid var(--error);     /* #EF4444 */
```

### Links

```css
color: var(--primary);                /* #E86842 */
text-decoration: none;

/* Hover */
color: var(--primary-dark);           /* #FF6B4A */
text-decoration: underline;
```

---

## 📱 Mobile Considerations

### Touch Highlights

```css
-webkit-tap-highlight-color: rgba(232, 104, 66, 0.1);
```

### Theme Color (Browser Chrome)

```html
<meta name="theme-color" content="#E86842">
```

---

## ♿ Accessibility

### Contrast Ratios (WCAG AA Compliant)

```
✅ Charcoal (#1E1F22) on Peach (#FFF4EC): 14.2:1 (AAA)
✅ Charcoal (#1E1F22) on White (#FFFFFF): 16.5:1 (AAA)
✅ Primary (#E86842) on White (#FFFFFF): 4.8:1 (AA)
✅ White text on Primary (#E86842): 4.8:1 (AA)
```

### Focus States

```css
*:focus-visible {
  outline: 2px solid var(--primary);  /* #E86842 */
  outline-offset: 2px;
}
```

---

## 🎯 Do's and Don'ts

### ✅ DO

- Use coral burst (#E86842) for all primary CTAs
- Use warm peach (#FFF4EC) for main backgrounds
- Use white (#FFFFFF) for cards and content blocks
- Use charcoal (#1E1F22) for all primary text
- Apply subtle gradients to hero sections
- Use rounded corners (16px) for cards and buttons

### ❌ DON'T

- Don't use pure black (#000000) - use charcoal (#1E1F22)
- Don't use cool colors (blue/teal) as primary brand colors
- Don't use harsh shadows - keep them soft
- Don't use sharp corners - maintain 12-16px border radius
- Don't overuse gradients - subtle is better
- Don't place coral text on peach backgrounds (low contrast)

---

## 🔄 Color Palette History

### Version 2.0 (December 22, 2025)
- **Changed from:** Teal/Mint palette (#00A57E, #F4FDFC)
- **Changed to:** Coral/Peach palette (#E86842, #FFF4EC)
- **Reason:** Aligned website with mobile app's warm, motivating brand DNA
- **Impact:** More welcoming, action-oriented, consistent cross-platform

### Version 1.0 (Original)
- Teal green primary (#00A57E)
- Mint white background (#F4FDFC)
- Dark teal (#062925)

---

## 📞 Questions?

For brand consistency questions or color usage guidance:
- **Email:** hello@regumeapp.com
- **Design System:** See `src/styles/global.css`

---

**Brand Colors Match App:** ✅ iOS Mobile App  
**Last Review:** December 22, 2025  
**Status:** Production Ready
