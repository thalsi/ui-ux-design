# 🎨 Color System Methods – Design System Guide

A practical reference to create, organize, and scale a modern color system using different **methods and models** — covering brand, functional, semantic, and state-based approaches.

---

## 📚 Index

1. [Color Categories Overview](#1-color-categories-overview)  
2. [Base Color Scales (50–950)](#2-base-color-scales-50950)  
3. [Semantic Color Roles](#3-semantic-color-roles)  
4. [Functional Color Roles](#4-functional-color-roles)  
5. [State Colors (UI Feedback)](#5-state-colors-ui-feedback)  
6. [Surface and Background Layers](#6-surface-and-background-layers)  
7. [Text & Content Colors](#7-text--content-colors)  
8. [Tone Mapping & Accessibility](#8-tone-mapping--accessibility)

---

## 1. Color Categories Overview

Organize your color system into **4 main groups**:

| Category     | Description                          | Example         |
|--------------|--------------------------------------|------------------|
| 🎯 Brand      | Core branding colors                 | Primary, Accent |
| ⚙️ Functional | Reusable UI roles                    | Border, Text, Fill |
| ⚠️ Semantic   | Meaningful states and actions        | Error, Success, Warning |
| 🧩 Utility    | Greyscale, backgrounds, overlays     | Gray 100–900, Backdrop |

---

## 2. Base Color Scales (50–950)

Use **step-based tints & shades** from lightest (50) to darkest (950) — works for both **brand and grayscale** palettes.

### Example – Primary Color Scale

| Token           | Hex        | Use                           |
|------------------|------------|--------------------------------|
| primary-50       | #E0F7F6     | Background, hover light        |
| primary-100      | #B2EFED     | Surface tint                   |
| ...              | ...         | ...                            |
| primary-500 ✅    | #03A6A1     | Brand identity, buttons        |
| primary-900      | #014443     | Deep text, contrast overlays   |

> 💡 Tip: Maintain minimum contrast ratio of **4.5:1** for readability.

---

## 3. Semantic Color Roles

Use **meaningful color mappings** to describe UI state/intent:

| Role        | Default Example | Use Case                     |
|-------------|------------------|-------------------------------|
| `success`   | Green (#28A745)  | Toasts, status, confirmation  |
| `error`     | Red (#D91656)    | Errors, failed actions        |
| `warning`   | Orange (#FFB200) | Warnings, alerts              |
| `info`      | Blue (#254D70)   | Tips, neutral messages        |

> Semantic colors can also use scales: `error-100` to `error-900`.

---

## 4. Functional Color Roles

These abstract tokens describe **reusable UI functions**:

| Token Name        | Sample Color     | Description                   |
|-------------------|------------------|-------------------------------|
| `text-primary`     | #131D4F          | Main readable text            |
| `text-secondary`   | #666666          | Muted or low emphasis text    |
| `border-default`   | #D1D5DB          | Card or input border          |
| `fill-accent`      | #FFE3BB          | Accent fills, highlights      |
| `overlay-light`    | rgba(0,0,0,0.04) | Light hover / pressed states  |

---

## 5. State Colors (UI Feedback)

Specific **interactive** or **feedback states**:

| State        | Token Example      | Notes                         |
|--------------|---------------------|-------------------------------|
| Hover        | `primary-hover`     | Slightly darker/lighter tint |
| Pressed      | `primary-pressed`   | Even deeper tone             |
| Disabled     | `disabled-fill`     | Neutral gray, low opacity    |
| Focus        | `focus-ring`        | Outline ring (e.g., #03A6A1) |

---

## 6. Surface and Background Layers

Use **layered neutrals** for UI panels, cards, and contrast:

| Layer            | Example Color  | Use                            |
|------------------|----------------|---------------------------------|
| `surface-1`      | #FFFFFF         | Base background (cards, modals) |
| `surface-2`      | #F8F9FA         | Slight elevation               |
| `surface-3`      | #E9ECEF         | Further elevation              |
| `backdrop`       | rgba(0,0,0,0.4) | Modal/overlay dimming         |

---

## 7. Text & Content Colors

Text tokens should follow **contrast and clarity** rules:

| Token Name        | Color           | Use                           |
|-------------------|------------------|-------------------------------|
| `text-high`        | #131D4F          | Body, labels                  |
| `text-medium`      | #666666          | Secondary info                |
| `text-low`         | #999999          | Hints, disabled text          |
| `text-inverse`     | #FFFFFF          | Light-on-dark surfaces        |

---

## 8. Tone Mapping & Accessibility

- 🎚 **Tone ramping**: Use lighter tones for backgrounds, stronger for text and actions.
- 🦻 **Accessibility Tips**:
  - Text contrast ≥ **4.5:1**
  - Do not rely on color alone for meaning
  - Pair color with icon, label, or pattern
  - Provide both **light and dark theme support**

---

## ✅ Tools & Tips

- Use contrast checkers (WCAG AA/AAA)
- Build token systems in code (`SCSS`, `JS`, `Design Tokens`)
- Design in Figma with shared styles
- Tools: [ColorBox](https://www.colorbox.io), [Coolors](https://coolors.co), [Accessible Colors](https://accessible-colors.com)

----


# 🧾 Typography Roles – Design System Guide

A guide to the most commonly used typography roles in modern UI design systems, with mapped font tokens, sizes, weights, and use cases.

---

## 📚 Index

1. [Display / Hero Title](#1-display--hero-title)  
2. [Page Title (H1)](#2-page-title-h1)  
3. [Section Heading (H2–H3)](#3-section-heading-h2h3)  
4. [Subheading](#4-subheading)  
5. [Body Text (Base)](#5-body-text-base)  
6. [Body Text Bold / Strong](#6-body-text-bold--strong)  
7. [Body Small / Secondary](#7-body-small--secondary)  
8. [Link / Interactive Text](#8-link--interactive-text)  
9. [Label (Form / UI)](#9-label-form--ui)  
10. [Helper Text / Hint](#10-helper-text--hint)  
11. [Caption / Metadata](#11-caption--metadata)  
12. [Tag / Chip / Badge](#12-tag--chip--badge)

---

## 1. Display / Hero Title
- **Use:** Largest text for landing pages, splash screens, or call-to-actions.
- **Font Size:** `font-4xl` (48px desktop / 36px mobile)
- **Font Weight:** `font-extrabold` (800)
- **Line Height:** `tight` (1.2)
- **Example:** “Design That Inspires”

---

## 2. Page Title (H1)
- **Use:** Main title for a screen or page.
- **Font Size:** `font-3xl` (40px / 28px)
- **Font Weight:** `font-bold` (700)
- **Line Height:** `tight` or `base`
- **Example:** “Typography Guidelines”

---

## 3. Section Heading (H2–H3)
- **Use:** Section headers to break up content.
- **Font Size:** `font-2xl` (32px / 24px) or `font-xl` (24px / 20px)
- **Font Weight:** `font-bold` or `font-semibold`
- **Line Height:** `base`
- **Example:** “Font Sizes”, “Line Height Settings”

---

## 4. Subheading
- **Use:** Subtitle under a heading or grouping content.
- **Font Size:** `font-lg` or `font-xl` (20–24px)
- **Font Weight:** `font-semibold` (600)
- **Line Height:** `base`
- **Example:** “Used in Cards or Info Blocks”

---

## 5. Body Text (Base)
- **Use:** Paragraphs, descriptive content.
- **Font Size:** `font-md` (18px / 16px)
- **Font Weight:** `font-regular` (400)
- **Line Height:** `base` (1.5)
- **Example:** Normal UI explanations or feature descriptions.

---

## 6. Body Text Bold / Strong
- **Use:** Emphasized phrases inside body.
- **Font Size:** `font-md`
- **Font Weight:** `font-semibold` or `font-bold` (600–700)
- **Line Height:** `base`
- **Example:** “Important notes or warnings.”

---

## 7. Body Small / Secondary
- **Use:** Descriptive text, card subtitles, muted UI text.
- **Font Size:** `font-sm` or `font-xs` (14–16px)
- **Font Weight:** `font-regular` (400)
- **Line Height:** `base` or `loose`
- **Example:** “Used in pricing cards or small footers.”

---

## 8. Link / Interactive Text
- **Use:** Text links, buttons, or clickable elements.
- **Font Size:** `font-md` or `font-sm`
- **Font Weight:** `font-regular` or `font-medium`
- **Color:** Primary theme color
- **Style:** Underline or color change on hover
- **Example:** “Learn more →”

---

## 9. Label (Form / UI)
- **Use:** Field labels, button labels, small titles.
- **Font Size:** `font-xs` or `font-sm`
- **Font Weight:** `font-medium` (500)
- **Letter Spacing:** `wide` (+0.5px)
- **Text Case:** Often UPPERCASE
- **Example:** “Email Address”, “Submit”

---

## 10. Helper Text / Hint
- **Use:** Below form fields, tooltips, soft instructions.
- **Font Size:** `font-xs` or `font-xxs` (12–14px)
- **Font Weight:** `font-regular`
- **Color:** Gray / muted
- **Example:** “We’ll never share your email.”

---

## 11. Caption / Metadata
- **Use:** Timestamps, authorship, subtitles.
- **Font Size:** `font-xs`
- **Font Weight:** `font-regular`
- **Color:** Light gray or secondary tone
- **Example:** “Updated July 7, 2025”

---

## 12. Tag / Chip / Badge
- **Use:** Status indicators, categories.
- **Font Size:** `font-xxs` or `font-xs` (10–12px)
- **Font Weight:** `font-medium` or `font-regular`
- **Background:** Colored (e.g. status-based)
- **Example:** “NEW”, “DRAFT”, “SUCCESS”

---
