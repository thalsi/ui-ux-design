
# 🧱 Design System Foundations – Full Guide

A comprehensive documentation of all design system foundations essential for building consistent, scalable, and professional UI/UX across platforms.

---

## 📚 Index

1. [Color System](#1-color-system)  
2. [Typography System](#2-typography-system)  
3. [Spacing System](#3-spacing-system)  
4. [Sizing System](#4-sizing-system)  
5. [Elevation / Shadow System](#5-elevation--shadow-system)  
6. [Border Radius (Corner Radius)](#6-border-radius-corner-radius)  
7. [Border / Stroke System](#7-border--stroke-system)  
8. [Opacity Tokens](#8-opacity-tokens)  
9. [Grid / Layout System](#9-grid--layout-system)  
10. [Breakpoints / Responsive System](#10-breakpoints--responsive-system)  
11. [Motion / Animation Tokens](#11-motion--animation-tokens)  
12. [Iconography](#12-iconography)  
13. [Typography Scale (Modular)](#13-typography-scale-modular)  
14. [Z-Index / Layer System](#14-z-index--layer-system)  
15. [Tone & Voice](#15-tone--voice)  
16. [Accessibility Tokens](#16-accessibility-tokens)  
17. [Localization & Internationalization](#17-localization--internationalization)

---
## 🎨 1. Color System

### 📦 Categories

1. **Primary Colors** – Brand identity (e.g., `primary-500`)
2. **Secondary Colors** – Supportive, accent colors (e.g., `secondary-500`)
3. **Neutral Colors** – Backgrounds, borders, text (e.g., `gray-50` to `gray-900`)
4. **Semantic Colors** – Status indicators (e.g., `success`, `warning`, `error`, `info`)
5. **Surface Colors** – Card backgrounds, containers
6. **State Colors** – Hover, focus, disabled, selected

### 🎯 Example Primary Scale

| Token          | Hex       | Use Case              |
|----------------|-----------|------------------------|
| primary-50     | #E3F2FD   | Background             |
| primary-100    | #BBDEFB   | Hover background       |
| primary-500    | #2196F3   | Primary buttons        |
| primary-700    | #1976D2   | Button hover           |
| primary-900    | #0D47A1   | Active/selected        |

### ✅ Best Practices

- Ensure contrast meets WCAG AA (4.5:1)
- Stick to one or two accent colors
- Use semantic tokens instead of raw hex in code

---


## 🔤 2. Typography System

### 🔡 Font Settings

- **Font Family:** `Roboto`, `Inter`, `sans-serif`
- **Font Weights:** 400 (Regular), 500 (Medium), 700 (Bold)
- **Letter Spacing:** Slight for headings, normal for body
- **Line Height:** 1.4–1.6 for readability

### 📝 Role-Based Examples

| Role               | Size (Mobile / Desktop) | Weight | Use Case               |
|--------------------|-------------------------|--------|------------------------|
| Display / Hero     | 32px / 48px             | 700    | Marketing headers      |
| Page Title (H1)    | 24px / 36px             | 700    | Page-level heading     |
| Section Heading (H2)| 20px / 28px            | 600    | Section divider        |
| Subheading (H3)    | 18px / 24px             | 500    | Subsections            |
| Body Base          | 16px / 16px             | 400    | Main content           |
| Body Bold          | 16px / 16px             | 600    | Emphasis in body       |
| Caption            | 12px / 12px             | 400    | Labels, hints          |

### 📌 Rules

- Maintain vertical rhythm using spacing system
- Avoid using too many font sizes or weights
- Use typography tokens (`font-xl`, `font-body`, etc.)

---


## 🔢 3. Spacing System

### 🌐 Token Scale

| Token     | Value (px) | Usage |
|-----------|------------|-------|
| space-0   | 0px        | None |
| space-xxs | 2px        | Micro spacing |
| space-xs  | 4px        | Icon spacing |
| space-sm  | 8px        | Small padding |
| space-md  | 12px       | Body spacing |
| space-lg  | 16px       | Section spacing |
| space-xl  | 24px       | Card spacing |
| space-2xl | 32px       | Layout spacing |
| space-3xl | 40px       | Section gaps |
| space-4xl | 64px       | Hero block gaps |

---

## 📏 4. Sizing System

| Token    | Value | Usage |
|----------|-------|-------|
| size-xxs | 16px  | Dots, small icons |
| size-xs  | 24px  | Small buttons |
| size-sm  | 32px  | Normal icons |
| size-md  | 40px  | Inputs |
| size-lg  | 56px  | Cards |
| size-xl  | 80px  | Avatars |
| size-2xl | 120px | Big elements |

---

## 🕶️ 5. Elevation / Shadow System

| Token       | Shadow Value                        | Usage |
|-------------|-------------------------------------|-------|
| elevation-0 | none                                | Flat |
| elevation-100 | 0 1px 2px rgba(0,0,0,0.04)         | Inputs |
| elevation-200 | 0 2px 4px rgba(0,0,0,0.06)         | Cards |
| elevation-300 | 0 4px 8px rgba(0,0,0,0.08)         | Dropdowns |
| elevation-400 | 0 8px 16px rgba(0,0,0,0.12)        | Modals |
| elevation-500 | 0 12px 24px rgba(0,0,0,0.16)       | Dialogs |

---

## 🟢 6. Border Radius (Corner Radius)

| Token         | Value   | Usage |
|---------------|---------|-------|
| radius-none   | 0px     | Sharp corners |
| radius-sm     | 2px     | Chips, tags |
| radius-md     | 4px     | Buttons |
| radius-lg     | 8px     | Cards |
| radius-xl     | 16px    | Containers |
| radius-pill   | 9999px  | Pills |
| radius-circle | 50%     | Avatars |

---

## ➖ 7. Border / Stroke System

| Token           | Value  | Usage |
|-----------------|--------|-------|
| border-none     | 0px    | No border |
| border-hairline | 0.5px  | iOS style dividers |
| border-sm       | 1px    | Inputs |
| border-md       | 2px    | Emphasis |
| border-lg       | 4px    | Focus ring |

---

## 🧊 8. Opacity Tokens

| Token       | Value | Usage |
|-------------|-------|-------|
| opacity-0   | 0%    | Invisible |
| opacity-25  | 25%   | Disabled |
| opacity-50  | 50%   | Overlay |
| opacity-75  | 75%   | Hover |
| opacity-100 | 100%  | Fully visible |

---

## 🔲 9. Grid / Layout System

- Grid: 12-column desktop, 4-column mobile  
- Gutter: 16–24px  
- Max Width: 1440px  
- Layouts: Fixed (dashboards), Fluid (apps)

---

## 📱 10. Breakpoints / Responsive System

| Token | Width Range  | Devices |
|-------|--------------|---------|
| bp-xs | < 480px      | Tiny phones |
| bp-sm | 481–767px    | Phones |
| bp-md | 768–1024px   | Tablets |
| bp-lg | 1025–1440px  | Laptops |
| bp-xl | > 1440px     | Desktops |

---

## 🌀 11. Motion / Animation Tokens

| Token           | Value     | Usage |
|-----------------|-----------|-------|
| duration-fast   | 150ms     | Quick feedback |
| duration-normal | 300ms     | Modal open |
| duration-slow   | 500ms     | Toasts |
| easing-standard | ease-in-out | General |
| easing-bounce   | cubic-bezier(...) | Special |

---

## 🖼️ 12. Iconography

- Sizes: 16px, 24px, 32px  
- Stroke: 1.5px, 2px  
- Style: Line / Solid  
- Grid system: 24x24px

---

## 🔠 13. Typography Scale (Modular)

| Token     | Size | Usage |
|-----------|------|-------|
| font-xs   | 12px | Small text |
| font-sm   | 14px | Body |
| font-md   | 16px | Base |
| font-lg   | 20px | Subheading |
| font-xl   | 24px | Heading |
| font-2xl  | 30px | Page title |
| font-3xl  | 36px | Hero |

---

## 📚 14. Z-Index / Layer System

| Token      | Value | Usage |
|------------|-------|-------|
| z-base     | 1     | Default |
| z-dropdown | 100   | Menus |
| z-modal    | 1000  | Dialogs |
| z-toast    | 2000  | Toasts |
| z-overlay  | 3000  | Full screens |

---

## 🗣️ 15. Tone & Voice

- Friendly, clear, helpful  
- Use active voice  
- Avoid technical jargon  
- Examples:  
  - ❌ "An error occurred"  
  - ✅ "Oops! Something went wrong."

---

## ♿ 16. Accessibility Tokens

- Contrast: WCAG AA or better  
- Focus visible for all inputs  
- Keyboard navigation mandatory  
- Min font: 14px

---

## 🌐 17. Localization & Internationalization

- Use `t('label.key')` format  
- Avoid hardcoded strings  
- Support RTL layouts  
- Handle plural, currency, date/time

---


## 🧩 UI Components

| Component        | Web Size / Spec                 | Mobile Size / Spec              | Use Case                          | Description                                                          |
|------------------|----------------------------------|----------------------------------|-----------------------------------|----------------------------------------------------------------------|
| Button (Primary) | 44–56px height, 16px padding    | 40–48px height, full width      | Main CTAs                         | Submit, Save, Sign Up                                                |
| Button (Secondary)| 44px height, outline/bg        | Same                             | Less important actions            | Cancel, Reset                                                        |
| Icon Button      | 32–40px                        | 32px                             | Compact actions                   | Delete, edit, share                                                  |
| Inputs           | 44px height, 12–16px padding    | 40px height, bigger touch zone  | Forms, search                     | Include label + error state                                          |
| Textarea         | Min 80px height, scalable       | 3–5 lines default                | Feedback, comments                | Expands on input                                                     |
| Checkbox / Radio | 16–20px                        | 20px                             | Forms, filters                    | Include label + active/focus state                                   |
| Select / Dropdown| 44px height                     | Same or full width              | Choose item                       | With search or native selector                                       |
| Card             | 300–500px width                 | Full width                      | Display product, item info        | Includes padding, shadow, image/text                                 |
| Modal            | 480–600px width                 | Full screen or center modal     | Confirmation, input form          | Block background, keyboard esc dismiss                               |
| Avatar           | 32, 40, 56px                   | 32, 40px                         | User icons                        | Initials, user photo, status dot                                     |
| Chip / Badge     | 20–28px height, 12–16px padding| Same                             | Tags, status                      | Filter labels, categories, statuses                                  |
| Toast / Alert    | 300–400px, 3s timeout           | Same, bottom or top             | Error, success feedback           | Auto-dismiss or dismissable                                          |
| Tab / Nav        | 48–56px height, underline style | 40–48px height                  | Section switcher                  | Active + hover state                                                 |

---

## 📐 Layout & Patterns

| Pattern / Layout  | Web Spec                         | Mobile Spec                     | Use Case                     | Description                                                       |
|-------------------|-----------------------------------|----------------------------------|------------------------------|-------------------------------------------------------------------|
| Navbar            | 64–80px height                   | 56–64px                         | Top-level navigation         | Logo, links, CTA, user avatar                                     |
| Sidebar           | 250–320px width                  | Hidden or collapsible          | Dashboard & app navigation   | Left-aligned, vertical stack of links                             |
| List / Table      | Column layout, 40–64px row height| Scrollable cards                | Data, user lists             | Table for web, list/card for mobile                               |
| Form Layout       | 1 or 2 columns                   | 1 column                        | Login, input details         | Aligned inputs, validation, spacing                               |
| Empty State       | Centered graphic + text          | Same                            | No content, 0 results        | Helpful icons + message                                           |
| Success State     | Green icon + confirm text        | Same                            | Order complete, saved        | Checkmark + CTA or continue button                                |
| Error State       | Red icon + fix guidance          | Same                            | Failed actions               | Instructional, avoid user frustration                             |
| Dashboard         | Grid of cards, sidebar + header  | Stacked cards                   | Admin, Analytics             | Status widgets, summary blocks                                    |

---

## 🎯 States & Interaction

| State           | Visual Spec                      | Description                                               |
|-----------------|----------------------------------|-----------------------------------------------------------|
| Hover           | Color darken/lighten, shadow     | Feedback on interaction possibility                      |
| Focus           | Blue outline, border change      | Accessibility: keyboard navigation                        |
| Active          | Pressed effect, depth down       | Button pressed or nav link tapped                         |
| Disabled        | Opacity reduced, no pointer      | Inactive but visible element                              |
| Loading         | Spinner or skeleton              | Indicate API or delayed content                           |
| Empty           | Icon + short text                | Shows “nothing here” in a friendly way                    |
| Error           | Red + icon + help text           | Shows input or system error clearly                       |
| Success         | Green + icon                     | Positive feedback, e.g., "Saved successfully"             |

---
