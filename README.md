

# 🧱 What Is a Design System?
A design system is a set of standards, reusable components, and guidelines used for building consistent UI across products

## 🧩 Design System Building Blocks

Category	Description	Examples
Foundations	Core styling tokens and rules	Colors, Typography, Spacing, Grid
Components	UI building blocks	Button, Input, Modal, Dropdown
Patterns	Reusable solutions for common problems	Form validation, Nav, Toast pattern
Guidelines	Rules for usage and behavior	Accessibility, Writing, Layout rules
Assets	Icons, logos, illustrations	SVG sets, brand assets
Documentation	Guide for using components and design rules	Storybook, Figma file, Markdown

---

## 🧩 Design System Building Blocks

A design system is made of several interconnected parts. Below are the core building blocks:

| Block            | Description                                              | Examples                             |
|------------------|----------------------------------------------------------|--------------------------------------|
| **Foundations**   | Core tokens and rules that define visual language       | Color, Typography, Spacing, Grid     |
| **Components**    | UI elements built using foundation tokens               | Button, Input, Modal, Card           |
| **Patterns**      | Reusable interaction and layout strategies              | Form Validation, Navigation, Alerts  |
| **Icons & Assets**| Brand visuals used across UI                            | Icons, Logos, Illustrations          |
| **Guidelines**    | Rules on usage, accessibility, writing, and behaviors   | Do/Don't, Voice & Tone, UX Writing   |
| **Themes**        | Mode-based or brand-based variations                    | Light, Dark, Multi-brand             |
| **Documentation** | Where everything is explained for designers & devs      | Storybook, Figma, GitHub, Markdown   |

---

# 🧱 Foundations of a Design System

A complete list of foundational elements used in modern design systems for consistency, scalability, and accessibility.

| No. | Foundation              | Description                                                                 | Examples / Tokens                                  | Use In                        |
|-----|--------------------------|-----------------------------------------------------------------------------|----------------------------------------------------|-------------------------------|
| 1   | Color                   | Core palette for UI elements, branding, and accessibility                   | Primary, Secondary, Neutral, Error, Success        | Backgrounds, Text, Buttons    |
| 2   | Typography              | Font styles, sizes, weights, and line spacing                               | Font families, Sizes, Weights, Line height         | Headings, Body text           |
| 3   | Spacing                 | Consistent space units for padding and margins                              | 4px, 8px, 16px, 24px… (Spacing scale)              | Layout, Card, Form fields     |
| 4   | Sizing                  | Width/height rules for UI elements                                          | Button: 40px, Icon: 24px                           | Buttons, Inputs, Icons        |
| 5   | Elevation / Shadow      | Depth levels to show hierarchy or layering                                  | Elevation levels (e.g., 1–5), Shadow tokens        | Cards, Modals, Overlays       |
| 6   | Radius (Border Radius)  | Corner rounding values                                                      | 4px, 8px, 12px… (e.g., sm, md, lg)                 | Cards, Inputs, Buttons        |
| 7   | Border / Stroke         | Thickness and styles of borders                                             | 1px, 2px; solid, dashed                            | Inputs, Dividers, Tables      |
| 8   | Opacity                 | Transparency levels for different UI states                                 | 100%, 80%, 60%                                     | Disabled states, overlays     |
| 9   | Grid / Layout           | Structure for placing and aligning elements                                 | 8pt Grid, 12-column layout, breakpoints            | Page layout, Containers       |
| 10  | Breakpoints             | Responsive rules for different screen sizes                                 | sm (480px), md (768px), lg (1024px), xl (1440px)   | Responsive layout             |
| 11  | Motion / Animation      | Timing and easing rules for interactions                                    | Ease-in, ease-out, 300ms, spring                   | Transitions, Interactions     |
| 12  | Iconography             | Icon system with size, stroke, style                                        | 24px outlined, filled icons                        | Actions, Navigation           |
| 13  | Typography Scale        | Hierarchical font size scale for headings and body                          | h1, h2, h3, body, caption                          | Consistent UI text            |
| 14  | Z-Index / Layering      | Layer positioning for UI elements                                           | z-10, z-20, z-30…                                  | Modals, Dropdowns             |
| 15  | Tone / Voice            | Guidelines for writing UI copy                                              | Friendly, clear, inclusive                         | Microcopy, Notifications      |
| 16  | Accessibility (A11y)    | Rules ensuring usability for all users                                      | Color contrast, Focus states, Keyboard nav         | All components                |
| 17  | Localization            | Support for different languages and directions                              | RTL/LTR, date format                               | Global product design         |

---

# 1. 🎨 Design System Foundations – Color

Color plays a critical role in brand identity, visual hierarchy, accessibility, and interaction feedback. This foundation defines a structured color system using design tokens to ensure consistency and scalability across platforms.

---

## 🧱 Color Categories

| Category       | Description                             | Use Cases                                 |
|----------------|-----------------------------------------|-------------------------------------------|
| Primary        | Core brand color                        | Buttons, links, highlights                |
| Secondary      | Supportive accent color                 | Cards, illustrations, secondary buttons   |
| Neutral        | Greyscale tones                         | Backgrounds, borders, text                |
| Background     | UI surfaces                             | Pages, containers, overlays               |
| Text           | Foreground text                         | Headings, body, muted text                |
| Semantic       | Status indication                       | Success, warning, error, info             |
| Action States  | UI feedback                             | Hover, focus, pressed, disabled           |

---

## 🌗 Theme-Based Color Tokens

### 🔅 Light Mode

```css
--color-primary: #E91E63;
--color-primary-hover: #D81B60;
--color-secondary: #F8BBD0;
--color-background: #FFFFFF;
--color-surface: #F9F9F9;
--color-text-primary: #212121;
--color-text-secondary: #616161;
--color-border: #E0E0E0;

--color-success: #4CAF50;
--color-warning: #FFC107;
--color-error: #F44336;
--color-info: #2196F3;

--color-disabled-bg: #F5F5F5;
--color-disabled-text: #BDBDBD;
--color-hover-overlay: rgba(0, 0, 0, 0.04);
```

# 2. ✍️ Typography Foundation
- Typography ensures visual hierarchy, readability, and brand consistency.

## 🧾 Typography Roles

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

### 1. Display / Hero Title
- **Use:** Largest text for landing pages, splash screens, or call-to-actions.
- **Font Size:** `font-4xl` (48px desktop / 36px mobile)
- **Font Weight:** `font-extrabold` (800)
- **Line Height:** `tight` (1.2)
- **Example:** “Design That Inspires”

---

### 2. Page Title (H1)
- **Use:** Main title for a screen or page.
- **Font Size:** `font-3xl` (40px / 28px)
- **Font Weight:** `font-bold` (700)
- **Line Height:** `tight` or `base`
- **Example:** “Typography Guidelines”

---

### 3. Section Heading (H2–H3)
- **Use:** Section headers to break up content.
- **Font Size:** `font-2xl` (32px / 24px) or `font-xl` (24px / 20px)
- **Font Weight:** `font-bold` or `font-semibold`
- **Line Height:** `base`
- **Example:** “Font Sizes”, “Line Height Settings”

---

### 4. Subheading
- **Use:** Subtitle under a heading or grouping content.
- **Font Size:** `font-lg` or `font-xl` (20–24px)
- **Font Weight:** `font-semibold` (600)
- **Line Height:** `base`
- **Example:** “Used in Cards or Info Blocks”

---

### 5. Body Text (Base)
- **Use:** Paragraphs, descriptive content.
- **Font Size:** `font-md` (18px / 16px)
- **Font Weight:** `font-regular` (400)
- **Line Height:** `base` (1.5)
- **Example:** Normal UI explanations or feature descriptions.

---

### 6. Body Text Bold / Strong
- **Use:** Emphasized phrases inside body.
- **Font Size:** `font-md`
- **Font Weight:** `font-semibold` or `font-bold` (600–700)
- **Line Height:** `base`
- **Example:** “Important notes or warnings.”

---

### 7. Body Small / Secondary
- **Use:** Descriptive text, card subtitles, muted UI text.
- **Font Size:** `font-sm` or `font-xs` (14–16px)
- **Font Weight:** `font-regular` (400)
- **Line Height:** `base` or `loose`
- **Example:** “Used in pricing cards or small footers.”

---

### 8. Link / Interactive Text
- **Use:** Text links, buttons, or clickable elements.
- **Font Size:** `font-md` or `font-sm`
- **Font Weight:** `font-regular` or `font-medium`
- **Color:** Primary theme color
- **Style:** Underline or color change on hover
- **Example:** “Learn more →”

---

### 9. Label (Form / UI)
- **Use:** Field labels, button labels, small titles.
- **Font Size:** `font-xs` or `font-sm`
- **Font Weight:** `font-medium` (500)
- **Letter Spacing:** `wide` (+0.5px)
- **Text Case:** Often UPPERCASE
- **Example:** “Email Address”, “Submit”

---

### 10. Helper Text / Hint
- **Use:** Below form fields, tooltips, soft instructions.
- **Font Size:** `font-xs` or `font-xxs` (12–14px)
- **Font Weight:** `font-regular`
- **Color:** Gray / muted
- **Example:** “We’ll never share your email.”

---

### 11. Caption / Metadata
- **Use:** Timestamps, authorship, subtitles.
- **Font Size:** `font-xs`
- **Font Weight:** `font-regular`
- **Color:** Light gray or secondary tone
- **Example:** “Updated July 7, 2025”

---

### 12. Tag / Chip / Badge
- **Use:** Status indicators, categories.
- **Font Size:** `font-xxs` or `font-xs` (10–12px)
- **Font Weight:** `font-medium` or `font-regular`
- **Background:** Colored (e.g. status-based)
- **Example:** “NEW”, “DRAFT”, “SUCCESS”

---

## 📚 Typography Foundation – Essentials Index

1. **Font Family**  
2. **Font Sizes (Type Scale)**  
3. **Font Weight**  
4. **Line Height**  
5. **Letter Spacing**  
6. **Text Transform**  
7. **Font Style**  
8. **Full Token Set**  
9. **Font Scale Ratios (Optional)**

---

## 1. Font Family

| Token                   | Value                           | Font Type     | Use Case              |
|-------------------------|----------------------------------|---------------|------------------------|
| `--font-family-base`    | `'General Sans', sans-serif`     | Sans-serif    | Body text, forms, UI   |
| `--font-family-heading` | `'Archivo', sans-serif`          | Sans-serif    | Headings, titles       |
| `--font-family-mono`    | `'Fira Code', monospace`         | Monospace     | Code, tables, numbers  |

---

## 2. Font Sizes (Type Scale)

| Level        | Token                   | Desktop     | Mobile     | px → rem   | Use Case             |
|--------------|--------------------------|-------------|------------|------------|-----------------------|
| Display      | `--font-size-display`    | 64px        | 48px       | 4rem       | Hero titles           |
| Heading 1    | `--font-size-h1`         | 48px        | 36px       | 3rem       | Page headings         |
| Heading 2    | `--font-size-h2`         | 36px        | 28px       | 2.25rem    | Section titles        |
| Heading 3    | `--font-size-h3`         | 28px        | 22px       | 1.75rem    | Subheadings           |
| Body Large   | `--font-size-body-lg`    | 18px        | 16px       | 1.125rem   | Articles, blog text   |
| Body Medium  | `--font-size-body-md`    | 16px        | 14px       | 1rem       | Paragraphs, forms     |
| Caption      | `--font-size-caption`    | 12px        | 12px       | 0.75rem    | Notes, metadata       |

---

## 3. Font Weight

| Token Name               | Value | Weight Name   | Use Case                          |
|--------------------------|--------|---------------|-----------------------------------|
| `--font-weight-thin`     | 100    | Thin          | Decorative, large headings only   |
| `--font-weight-extralight`| 200   | Extra Light   | Minimal UIs, large quiet headers  |
| `--font-weight-light`    | 300    | Light         | Placeholder, subtle captions      |
| `--font-weight-regular`  | 400    | Regular       | Default for body text             |
| `--font-weight-medium`   | 500    | Medium        | Form labels, subtle CTA           |
| `--font-weight-semibold` | 600    | Semibold      | Subheadings, selected states      |
| `--font-weight-bold`     | 700    | Bold          | Primary headings, CTA buttons     |
| `--font-weight-extrabold`| 800    | Extra Bold    | Landing pages, banner titles      |
| `--font-weight-black`    | 900    | Black         | Strong emphasis, display use      |

---

## 4. Line Height

| Token                   | Value | Equivalent | Use Case                  |
|-------------------------|--------|------------|---------------------------|
| `--line-height-tight`   | 1.1    | ~110%      | Hero titles, banners      |
| `--line-height-heading` | 1.2    | ~120%      | H1–H3 heading levels       |
| `--line-height-body`    | 1.5    | ~150%      | Paragraph, long-form text |
| `--line-height-caption` | 1.4    | ~140%      | Footnotes, small content  |

---

## 5. Letter Spacing

| Token                     | Value     | Tracking   | Use Case                   |
|---------------------------|-----------|------------|----------------------------|
| `--letter-spacing-tight`  | -0.02em   | Tight      | Large headings, logos      |
| `--letter-spacing-normal` | 0em       | Normal     | Paragraphs, UI text        |
| `--letter-spacing-loose`  | 0.02em    | Wide       | All-caps, badges, buttons  |

---

## 6. Text Transform

| Token                        | Value       | Output Style | Use Case              |
|------------------------------|-------------|---------------|------------------------|
| `--text-transform-uppercase` | `uppercase` | ALL CAPS      | Labels, buttons, tags  |
| `--text-transform-none`      | `none`      | As typed      | Headings, paragraphs   |

---

## 7. Font Style

| Token                   | Value    | Display     | Use Case             |
|-------------------------|----------|-------------|-----------------------|
| `--font-style-normal`   | `normal` | Straight    | Default everywhere    |
| `--font-style-italic`   | `italic` | Slanted     | Quotes, emphasis      |

---

## 8. Full Token Set

```css
--font-family-base: 'General Sans', sans-serif;
--font-family-heading: 'Archivo', sans-serif;
--font-family-mono: 'Fira Code', monospace;

--font-size-display: 64px;
--font-size-h1: 48px;
--font-size-h2: 36px;
--font-size-h3: 28px;
--font-size-body-lg: 18px;
--font-size-body-md: 16px;
--font-size-caption: 12px;

--font-weight-regular: 400;
--font-weight-medium: 500;
--font-weight-semibold: 600;
--font-weight-bold: 700;

--line-height-tight: 1.1;
--line-height-heading: 1.2;
--line-height-body: 1.5;
--line-height-caption: 1.4;

--letter-spacing-tight: -0.02em;
--letter-spacing-normal: 0em;
--letter-spacing-loose: 0.02em;

--text-transform-uppercase: uppercase;
--text-transform-none: none;

--font-style-normal: normal;
--font-style-italic: italic;
```
---

# 3. 📐 Spacing Foundation – Core Essentials Index

1. **Spacing Scale (Base Units)**  
2. **Inset Spacing (Padding)**  
3. **Stack Spacing (Vertical Gaps)**  
4. **Inline Spacing (Horizontal Gaps)**  
5. **Full Core Token Set**

---

## 1. Spacing Scale (Base Units)

| Token               | Value (px) | rem     | Use Case                            |
|---------------------|------------|---------|-------------------------------------|
| `--spacing-xs`      | 4px        | 0.25rem | Micro padding/margins, chips        |
| `--spacing-sm`      | 8px        | 0.5rem  | Small UI elements, icons            |
| `--spacing-md`      | 16px       | 1rem    | Default spacing for most components |
| `--spacing-lg`      | 24px       | 1.5rem  | Grid gaps, layout margin            |
| `--spacing-xl`      | 32px       | 2rem    | Section spacing, card groups        |

---

## 2. Inset Spacing (Padding)

| Token         | Value | Use Case                          |
|---------------|--------|-----------------------------------|
| `--inset-sm`  | 8px    | Button padding, card content      |
| `--inset-md`  | 16px   | Input fields, modals              |
| `--inset-lg`  | 24px   | Layout containers, dialog bodies  |

---

## 3. Stack Spacing (Vertical Gaps)

| Token         | Value | Use Case                         |
|---------------|--------|----------------------------------|
| `--stack-sm`  | 8px    | Between label and input          |
| `--stack-md`  | 16px   | Between sections                 |
| `--stack-lg`  | 24px   | Between cards, list items        |

---

## 4. Inline Spacing (Horizontal Gaps)

| Token          | Value | Use Case                      |
|----------------|--------|-------------------------------|
| `--inline-sm`  | 8px    | Icon/text spacing             |
| `--inline-md`  | 16px   | Gaps between buttons/cards    |

---

## 5. Full Core Spacing Token Set

```css
--spacing-xs: 4px;
--spacing-sm: 8px;
--spacing-md: 16px;
--spacing-lg: 24px;
--spacing-xl: 32px;

--inset-sm: 8px;
--inset-md: 16px;
--inset-lg: 24px;

--stack-sm: 8px;
--stack-md: 16px;
--stack-lg: 24px;

--inline-sm: 8px;
--inline-md: 16px;
```
---

# 4. 📏 Sizing Foundation – Core Essentials Index

1. **Sizing Scale (Base Sizes)**  
2. **Component Sizing**  
3. **Layout Sizing**  
4. **Full Core Token Set**

---

## 1. Sizing Scale (Base Sizes)

| Token             | Value | Use Case                             |
|-------------------|--------|--------------------------------------|
| `--size-xs`       | 16px   | Icons, indicators, tight content     |
| `--size-sm`       | 24px   | Small buttons, badges                |
| `--size-md`       | 40px   | Input height, default button size    |
| `--size-lg`       | 64px   | Large buttons, image previews        |
| `--size-xl`       | 96px   | Avatars, hero icons                  |

---

## 2. Component Sizing

| Component    | Token        | Value | Notes                    |
|--------------|--------------|--------|---------------------------|
| Button       | `--size-md`  | 40px   | Height                   |
| Input Field  | `--size-md`  | 40px   | Default height           |
| Avatar       | `--size-xl`  | 96px   | Profile/preview elements |

---

## 3. Layout Sizing

| Token               | Value  | Use Case                   |
|---------------------|--------|----------------------------|
| `--container-sm`    | 480px  | Mobile layout max width    |
| `--container-md`    | 768px  | Tablet layout max width    |
| `--container-lg`    | 1024px | Desktop layout max width   |

---

## 4. Full Core Sizing Token Set

```css
--size-xs: 16px;
--size-sm: 24px;
--size-md: 40px;
--size-lg: 64px;
--size-xl: 96px;

--container-sm: 480px;
--container-md: 768px;
--container-lg: 1024px;
```
---

# 5. ☁️ Elevation / Shadow Foundation – Core Essentials Index

1. **Shadow Scale**  
2. **Shadow Use Cases**  
3. **Full Shadow Token Set**

---

## 1. Shadow Scale

| Token              | Offset & Blur           | Use Case                    |
|--------------------|-------------------------|-----------------------------|
| `--shadow-xs`      | 0 1px 2px rgba(0,0,0,0.05)| Hairline, borders           |
| `--shadow-sm`      | 0 1px 4px rgba(0,0,0,0.08)| Inputs, buttons             |
| `--shadow-md`      | 0 4px 8px rgba(0,0,0,0.10)| Cards, dropdowns            |
| `--shadow-lg`      | 0 8px 16px rgba(0,0,0,0.12)| Modals, overlays            |

---

## 2. Shadow Use Cases

| Element       | Token         | Notes                         |
|---------------|---------------|-------------------------------|
| Button hover  | `--shadow-sm` | Slight elevation              |
| Card          | `--shadow-md` | Clear but soft shadow         |
| Modal         | `--shadow-lg` | Full depth, highest elevation |

---

## 3. Full Shadow Token Set

```css
--shadow-xs: 0 1px 2px rgba(0, 0, 0, 0.05);
--shadow-sm: 0 1px 4px rgba(0, 0, 0, 0.08);
--shadow-md: 0 4px 8px rgba(0, 0, 0, 0.10);
--shadow-lg: 0 8px 16px rgba(0, 0, 0, 0.12);
```
---


# 6.🔘 Radius (Border Radius) Foundation 

1. **Radius Scale**  
2. **Component Examples**  
3. **Full Radius Token Set**

---

## 1. Radius Scale

| Token               | Value | Use Case                       |
|---------------------|--------|--------------------------------|
| `--radius-xs`       | 2px    | Tags, inputs, fine borders     |
| `--radius-sm`       | 4px    | Buttons, cards                 |
| `--radius-md`       | 8px    | Modals, elevated containers    |
| `--radius-full`     | 9999px | Perfect circles (avatars)      |

---

## 2. Component Examples

| Component | Token           | Notes                      |
|-----------|------------------|----------------------------|
| Input     | `--radius-sm`    | Clean, modern look         |
| Card      | `--radius-md`    | Softened edge              |
| Avatar    | `--radius-full`  | Circular profile pic       |

---

## 3. Full Radius Token Set

```css
--radius-xs: 2px;
--radius-sm: 4px;
--radius-md: 8px;
--radius-full: 9999px;
```
---

# 7.📏 Border / Stroke Foundation 

1. **Border Width Tokens**  
2. **Border Use Cases**  
3. **Full Border Token Set**

---

## 1. Border Width Tokens

| Token                  | Value | Use Case                   |
|------------------------|--------|----------------------------|
| `--border-thin`        | 1px    | Input borders, outlines    |
| `--border-regular`     | 2px    | Buttons, cards             |
| `--border-thick`       | 4px    | Emphasis components        |

---

## 2. Border Use Cases

| Element     | Token              | Notes                      |
|-------------|--------------------|----------------------------|
| Input       | `--border-thin`    | Minimal distraction        |
| CTA Button  | `--border-regular` | Strong clickable UI        |
| Divider     | `--border-thick`   | Section separator          |

---

## 3. Full Border Token Set

```css
--border-thin: 1px;
--border-regular: 2px;
--border-thick: 4px;
```
---

# 🎨 8. Opacity Foundation – Core Essentials

### Opacity Tokens

| Token               | Value | Use Case                         |
|---------------------|--------|----------------------------------|
| `--opacity-disabled`| 0.4    | Disabled states (inputs, buttons)|
| `--opacity-muted`   | 0.6    | Subtext, placeholders            |
| `--opacity-default` | 1      | Fully visible elements           |

### Full Token Set

```css
--opacity-disabled: 0.4;
--opacity-muted: 0.6;
--opacity-default: 1;
```
---

# 🧱 9. Grid / Layout Foundation – Core Essentials

### Grid System

| Token               | Value     | Use Case                        |
|---------------------|-----------|---------------------------------|
| `--grid-columns`    | 12        | Standard column layout          |
| `--grid-gutter`     | 24px      | Space between columns           |
| `--grid-margin`     | 16px      | Outer container margin          |

### Full Token Set

```css
--grid-columns: 12;
--grid-gutter: 24px;
--grid-margin: 16px;
```
---

# 📐 10. Breakpoints Foundation – Core Essentials

### Responsive Breakpoints

| Token               | Value      | Device / Use Case               |
|---------------------|------------|---------------------------------|
| `--breakpoint-sm`   | 480px      | Mobile portrait                 |
| `--breakpoint-md`   | 768px      | Tablets                         |
| `--breakpoint-lg`   | 1024px     | Small laptops                   |
| `--breakpoint-xl`   | 1280px     | Large screens                   |

### Full Token Set

```css
--breakpoint-sm: 480px;
--breakpoint-md: 768px;
--breakpoint-lg: 1024px;
--breakpoint-xl: 1280px;
```
---

# 🎞️ 11. Motion / Animation Foundation – Core Essentials

### Timing & Easing

| Token                   | Value           | Use Case                   |
|-------------------------|------------------|-----------------------------|
| `--motion-duration-fast`| 150ms           | Button tap, hover           |
| `--motion-duration-mid` | 300ms           | Modals, slide transitions   |
| `--motion-ease-in-out`  | ease-in-out     | Default easing              |

### Full Token Set

```css
--motion-duration-fast: 150ms;
--motion-duration-mid: 300ms;
--motion-ease-in-out: ease-in-out;
```
---

# 🔣 12. Iconography Foundation – Core Essentials

### Icon Sizing & Style

| Token               | Value | Use Case                |
|---------------------|--------|-------------------------|
| `--icon-size-sm`    | 16px   | Inline with text        |
| `--icon-size-md`    | 24px   | Buttons, nav items      |
| `--icon-size-lg`    | 32px   | Cards, modals           |

### Icon Style Guidelines

- Use outlined or rounded icons
- Keep stroke widths consistent
- Align icons to 24px baseline grid

### Full Token Set

```css
--icon-size-sm: 16px;
--icon-size-md: 24px;
--icon-size-lg: 32px;
```
---

# 🔠 13. Typography Scale Foundation – Core Essentials

### Modular Scale System

| Token                  | Ratio  | Description                       |
|------------------------|--------|-----------------------------------|
| `--font-scale-minor`   | 1.125  | Subtle scale (compact UIs)        |
| `--font-scale-major`   | 1.25   | Balanced scale (most UIs)         |
| `--font-scale-golden`  | 1.618  | Large visual rhythm (hero UI)     |

### Full Token Set

```css
--font-scale-minor: 1.125;
--font-scale-major: 1.25;
--font-scale-golden: 1.618;
```
---

# 🗂️ 14. Z-Index / Layering Foundation – Core Essentials

### Z-Index Layers

| Token               | Value | Use Case                |
|---------------------|--------|-------------------------|
| `--z-base`          | 1      | Default stack           |
| `--z-dropdown`      | 100    | Menus, popovers         |
| `--z-modal`         | 1000   | Dialogs, overlays       |
| `--z-toast`         | 1100   | Notifications           |

### Full Token Set

```css
--z-base: 1;
--z-dropdown: 100;
--z-modal: 1000;
--z-toast: 1100;
```
---

# 🗣️ 15. Tone / Voice Foundation – Core Essentials

### Voice Traits

| Trait       | Value           | Description                        |
|-------------|------------------|------------------------------------|
| Tone        | Friendly         | Helpful and clear                  |
| Style       | Conversational   | Not robotic or overly casual       |
| Consistency | Always           | Same tone across all components    |

### Use Guidelines

- Avoid jargon
- Keep CTA short and action-driven (e.g., "Save", "Try Free")
- Write like you speak (human-centered)
- Match tone to the moment (e.g., errors vs success messages)

---

# ♿ 16. Accessibility (A11y) Foundation – Core Essentials

### Core Rules

| Area               | Rule                                    |
|--------------------|------------------------------------------|
| Contrast Ratio     | Minimum 4.5:1 for text                  |
| Focus Indicators   | Always visible, use `:focus-visible`    |
| ARIA Support       | Use labels, roles, landmarks properly   |

### Tokens

```css
--a11y-focus-ring: 2px solid #005fcc;
--a11y-contrast-min: 4.5;
```

# 🌐 17. Localization Foundation – Core Essentials

### Language & Locale Support

| Key Element       | Rule / Use Case                  |
|-------------------|----------------------------------|
| RTL Support       | Use `dir="rtl"` when needed      |
| Date/Time Format  | Use ISO or localized libraries   |
| Pluralization     | Handle via i18n logic            |

---



-------------

| **Text Style**           | **Mobile (px)** | **Desktop (px)** | **Font Weight** | **Line Height (%)** | **Letter Spacing (%)** | **Use Case**                      |
| ------------------------ | --------------- | ---------------- | --------------- | ------------------- | ---------------------- | --------------------------------- |
| **H1 / Page Title**      | 32px            | 40–48px          | 700             | 120%                | -2%                    | Main page heading, hero title     |
| **H2 / Section Title**   | 24px            | 32px             | 600             | 125%                | -1%                    | Major section breaks              |
| **H3 / Sub-section**     | 20px            | 24px             | 600             | 130%                | 0%                     | Sub-sections under H2             |
| **H4 / Card Title**      | 18px            | 20px             | 500             | 135%                | 0%                     | Card headlines, smaller titles    |
| **Body Large**           | 18px            | 20px             | 400             | 160%                | +1%                    | Lead paragraphs, intro text       |
| **Body / Paragraph**     | 16px            | 18px             | 400             | 165%                | +1%                    | Main body text                    |
| **Body Small / Caption** | 14px            | 16px             | 400             | 150%                | +2%                    | Supporting text, captions, labels |
| **Small / Meta**         | 12px            | 14px             | 400             | 150%                | +3%                    | Dates, meta info, copyright       |

---
Mobile Typography Scale

| Element          | Font Size | Line Height | Font Weight | Letter Spacing | Notes               |
| ---------------- | --------- | ----------- | ----------- | -------------- | ------------------- |
| **H1**           | 32px      | 130%        | 700         | -0.01em        | Readable hero       |
| **H2**           | 26px      | 130%        | 600         | 0em            | Section heading     |
| **H3**           | 22px      | 135%        | 600         | 0em            | Subsection heading  |
| **H4**           | 18px      | 145%        | 500         | 0.01em         | Minor heading       |
| **Body (P)**     | 16px      | 165%        | 400         | 0.01em         | Comfortable reading |
| **Small / Meta** | 13px      | 155%        | 400         | 0.02em         | Labels, footnotes   |
| **Button / CTA** | 15px      | 145%        | 600         | 0.05em         | Tap clarity         |
---
🖥️ Desktop Typography Scale

| Element          | Font Size | Line Height | Font Weight | Letter Spacing     | Notes                     |
| ---------------- | --------- | ----------- | ----------- | ------------------ | ------------------------- |
| **H1**           | 48px      | 120%        | 700         | -0.02em            | Main title / hero heading |
| **H2**           | 36px      | 125%        | 600         | -0.01em            | Section heading           |
| **H3**           | 28px      | 130%        | 600         | 0em                | Subsection heading        |
| **H4**           | 22px      | 135%        | 500         | 0em                | Minor heading             |
| **Body (P)**     | 18px      | 160%        | 400         | 0.01em             | Main paragraph text       |
| **Small / Meta** | 14px      | 150%        | 400         | 0.02em             | Captions, labels          |
| **Button / CTA** | 16px      | 140%        | 600         | 0.05em (uppercase) | Improve tap clarity       |

---
