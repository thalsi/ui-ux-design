# 🔤 Typography Roles – Design System Guide

Supports **Web & Mobile UI** with scalable tokens and style roles.

---

## 🔰 Beginner Typography Roles (8 Roles)

| # | Role             | Token             | Web Size | Mobile Size | Weight       | Line Height | Letter Spacing | Color Token      | ✅ Usage Example                        |
|---|------------------|-------------------|----------|-------------|--------------|-------------|----------------|------------------|----------------------------------------|
| 1 | Hero Title       | `font-display`    | 64px     | 40px        | ExtraBold    | 120%        | -0.5px         | `text-primary`   | Hero banners, splash screen titles     |
| 2 | Page Title       | `font-page-title` | 32px     | 24px        | Bold         | 120%        | -0.25px        | `text-primary`   | “Dashboard”, “Profile”                 |
| 3 | Section Title    | `font-section-title`| 24px   | 20px        | SemiBold     | 130%        | -0.15px        | `text-primary`   | Section blocks, page modules           |
| 4 | Subtitle         | `font-subtitle`   | 18px     | 16px        | Regular      | 140%        | 0px            | `text-secondary` | Sub-headings, block descriptions       |
| 5 | Body Text        | `font-body`       | 16px     | 16px        | Regular      | 150%        | 0px            | `text-body`      | Paragraphs, content blocks             |
| 6 | Small Text       | `font-body-sm`    | 14px     | 14px        | Regular      | 150%        | 0px            | `text-tertiary`  | Notes, light details                   |
| 7 | Button Text      | `font-button`     | 14–16px  | 14–16px     | Bold         | 120%        | 0.5px          | `text-on-primary`| Action buttons: “Save”, “Login”        |
| 8 | Caption / Label  | `font-caption`    | 12px     | 12px        | Regular      | 130%        | 0.25px         | `text-muted`     | Tooltips, input labels, field notes    |

---

## 💼 Professional Typography Roles (15 Roles)

| #  | Role              | Token               | Web Size | Mobile Size | Weight       | Line Height | Letter Spacing | Color Token      | ✅ Usage Example                      |
|----|-------------------|---------------------|----------|-------------|--------------|-------------|----------------|------------------|---------------------------------------|
| 1  | Display Title     | `font-display`      | 64px     | 40px        | ExtraBold    | 110%        | -0.5px         | `text-primary`   | Hero section, splash screen headline |
| 2  | H1 Page Title     | `font-h1`           | 48px     | 32px        | Bold         | 120%        | -0.25px        | `text-primary`   | Main page title                      |
| 3  | H2 Section Title  | `font-h2`           | 36px     | 28px        | SemiBold     | 125%        | -0.15px        | `text-primary`   | Big sections                         |
| 4  | H3 Subsection     | `font-h3`           | 28px     | 24px        | Medium       | 130%        | -0.1px         | `text-primary`   | Subsections inside cards             |
| 5  | H4 Card Title     | `font-h4`           | 20px     | 18px        | Medium       | 140%        | 0px            | `text-primary`   | Card headers, widget titles          |
| 6  | Subtitle          | `font-subtitle`     | 18px     | 16px        | Regular      | 140%        | 0px            | `text-secondary` | Description under headings           |
| 7  | Body Text         | `font-body`         | 16px     | 16px        | Regular      | 150%        | 0px            | `text-body`      | Main paragraph content               |
| 8  | Body Bold         | `font-body-bold`    | 16px     | 16px        | Bold         | 150%        | 0px            | `text-body`      | Emphasis in body text                |
| 9  | Body Small        | `font-body-sm`      | 14px     | 14px        | Regular      | 150%        | 0px            | `text-tertiary`  | Meta text, notes                     |
| 10 | Body Small Bold   | `font-body-sm-bold` | 14px     | 14px        | Bold         | 150%        | 0px            | `text-tertiary`  | Bold in small text                   |
| 11 | Caption           | `font-caption`      | 12px     | 12px        | Regular      | 130%        | 0.25px         | `text-muted`     | Tiny hints, tooltips                 |
| 12 | Button Text       | `font-button`       | 14–16px  | 14–16px     | Bold         | 120%        | 0.5px          | `text-on-primary`| Button labels                        |
| 13 | Link Text         | `font-link`         | 14–16px  | 14–16px     | Medium       | 140%        | 0px            | `text-link`      | Inline links, nav items              |
| 14 | Input Label       | `font-label`        | 14px     | 14px        | Medium       | 130%        | 0px            | `text-secondary` | Form field labels                    |
| 15 | Tag / Chip / Hint | `font-tag`          | 12px     | 12px        | Medium       | 130%        | 0.25px         | `text-muted`     | Filters, statuses, badges            |

---

## 🎨 Recommended Color Tokens

| Token Name         | Purpose                        | Example Color |
|--------------------|---------------------------------|----------------|
| `text-primary`     | Titles, major headings          | `#1A1A1A`      |
| `text-secondary`   | Subtitles, labels               | `#444444`      |
| `text-body`        | Paragraphs                      | `#333333`      |
| `text-tertiary`    | Small content, hints            | `#666666`      |
| `text-muted`       | Disabled, light captions        | `#999999`      |
| `text-link`        | Hyperlinks                      | `#007BFF`      |
| `text-on-primary`  | Text inside buttons             | `#FFFFFF`      |

---


## 1. 🔤 Typography Scale

| Element       | Web                  | Mobile                | Notes                                |
|---------------|-----------------------|------------------------|---------------------------------------|
| Base font     | 16–18px               | 14–16px               | Never below 12px on mobile            |
| Headings      | H1: 32–48px<br>H2: 24–36px | H1: 24–32px<br>H2: 20–28px | Use a modular scale                  |
| Line height   | 1.4–1.6x font size    | Same                  | Improves readability                  |
| Font weight   | 400–700               | 400–700               | Avoid too many weight variations      |
| Font family   | Sans-serif (Inter, Roboto, SF Pro) | Same       | Web-safe and readable                 |

> 🧠 **Tip**: Stick to 2–3 font styles max (e.g., Regular, Medium, Bold)
---






# 📐 Typography Levels of Text System

A consistent and scalable typography guide for responsive Web and Mobile UI/UX design.

---

### 📊 Typography Scale

| Level       | Purpose                             | Web Size   | Mobile Size | Weight       | Line Height | Letter Spacing | Text Transform   |
|-------------|-------------------------------------|------------|-------------|--------------|--------------|----------------|------------------|
| **Display** | Hero/banner title                   | 48–64px    | 32–48px     | Bold (700)   | 1.1–1.2      | -0.5px to 0px  | None             |
| **H1**      | Main page title                     | 32–48px    | 24–32px     | Bold (700)   | 1.2–1.3      | -0.2px         | None or Title Case |
| **H2**      | Section title                       | 24–32px    | 20–28px     | Semi-bold (600) | 1.3–1.4   | -0.2px         | None or Title Case |
| **H3**      | Subsection or card heading          | 18–24px    | 16–20px     | Medium (500) | 1.4          | 0px            | None             |
| **Body**    | Paragraph or content text           | 16–18px    | 14–16px     | Regular (400)| 1.5–1.6      | 0–0.2px        | Sentence Case    |
| **Caption** | Labels, tooltips, metadata          | 12–14px    | 12–14px     | Light (300–400)| 1.4–1.6    | 0.2–0.5px      | UPPERCASE or Sentence Case |
| **Button**  | Button/CTA text                     | 14–16px    | 14–16px     | Medium/Bold  | 1.2–1.4      | 0.5px (caps)   | UPPERCASE        |
| **Overline**| Small label above content sections  | 10–12px    | 10–12px     | Medium       | 1.2–1.4      | 0.5–1px        | UPPERCASE        |

---

## 🧩 Real UI Examples

### 📱 Mobile App: E-Commerce

- **Display**: `"Shop the New Summer Collection"` (Home banner)
- **H1**: `"Your Orders"` (Main section title)
- **H2**: `"Top Categories"` (Subsection)
- **H3**: `"Men's Footwear"` (Card title)
- **Body**: `"Free shipping on orders above ₹999"` (Paragraph)
- **Caption**: `"Last order: 3 days ago"` (Meta label)
- **Button**: `"Add to Cart"` (CTA)
- **Overline**: `"NEW"` (above card title)

### 🖥️ Web Dashboard: Admin Panel

- **Display**: `"Welcome Back, Aisha!"` (Hero greeting)
- **H1**: `"Admin Dashboard"` (Page title)
- **H2**: `"User Activity"` (Section title)
- **H3**: `"Active Users (Last 7 Days)"` (Subheading)
- **Body**: `"Here's what’s been happening recently."`
- **Caption**: `"Synced at 3:45 PM"` (Last updated)
- **Button**: `"Download Report"` (CTA)
- **Overline**: `"REPORTS"` (Above dashboard cards)

---

## ✅ Design Tips

- Use a modular scale (e.g., 1.25×: `16 → 20 → 25 → 32 → 40 → 48 → 64`)
- Apply `rem` or `clamp()` units in CSS for responsiveness
- Maintain contrast ratios (min. 4.5:1 for body text)
- Set up Figma styles or design tokens for each text level

---

## 🔧 Tools

- [Type Scale](https://type-scale.com)
- [Google Fonts](https://fonts.google.com)
- [Font Pair](https://fontpair.co)


---


## 💡 Example Usage (Paired with Typography)

| Component   | Text Style | Color Token         | Example                          |
|-------------|------------|---------------------|----------------------------------|
| Page Title  | H1         | Text Primary        | "Welcome to Dashboard"           |
| Subtitle    | H4         | Text Secondary      | "Here’s your weekly report"      |
| Description | Body       | Text Muted          | "You can manage your account..." |
| CTA Button  | Button     | Primary + Inverted  | "Get Started"                    |
| Card Title  | H3         | Text Primary        | "Total Revenue"                  |
| Error Text  | Small      | Error               | "Please enter a valid email."    |

---

## 📌 Best Practices

- ✅ Use consistent tokens in Figma/CSS.
- ✅ Maintain contrast ratio of **4.5:1** for accessibility (WCAG AA).
- ✅ Use `rgba()` or `opacity` for subtle text layers.
- ✅ Set up theme-switching using CSS variables or Figma modes.

---








# 📐 Responsive Typography Scale (Web & Mobile)

A modern and practical typography system for responsive UI/UX design. Optimized for Figma, web, and mobile apps. Includes font sizes, line height, letter spacing, font weight, and use case guidance.

---

## 🖥️ Web Typography Scale

| Level     | Font Size | Line Height | Letter Spacing | Font Weight       | Use Case             | Description                                                                 |
|-----------|-----------|-------------|----------------|--------------------|-----------------------|-----------------------------------------------------------------------------|
| Display 1 | 80px      | 88px        | -0.5px         | 800 (Extra Bold)   | Hero Banner Title     | Main headline on landing pages or large hero banners                        |
| Display 2 | 64px      | 72px        | -0.5px         | 700 (Bold)         | Section Intro Title   | Large section headers or pre-body titles                                   |
| H1        | 48px      | 56px        | -0.25px        | 700 (Bold)         | Page Title            | Primary page heading, usually once per page                                |
| H2        | 36px      | 44px        | -0.25px        | 600 (SemiBold)     | Section Title         | Headings for major sections on a page                                      |
| H3        | 28px      | 36px        | 0px            | 600 (SemiBold)     | Subsection Title      | Headings inside cards, panels, or subsections                              |
| H4        | 22px      | 32px        | 0px            | 500 (Medium)       | Subtitle / Group      | Group or block labels like “User Details”                                  |
| H5        | 18px      | 28px        | 0px            | 500 (Medium)       | Minor Headings        | Labels in sidebars, forms, or compact UIs                                  |
| H6        | 16px      | 24px        | 0px            | 500 (Medium)       | Small Headings        | Inline headings, tag groups, metadata blocks                               |
| Body      | 16px      | 28px        | 0px            | 400 (Regular)      | Paragraph Text        | General readable text blocks                                               |
| Small     | 14px      | 22px        | 0px            | 400 (Regular)      | Help / Hints          | Form help text, inline explanations, tooltips                              |
| Caption   | 12px      | 20px        | +0.2px         | 400 (Regular)      | Metadata              | Captions, timestamps, category tags                                        |
| Button    | 16px      | 20px        | +0.5px         | 600 (SemiBold)     | CTA Buttons           | Button labels, typically UPPERCASE for clarity                             |

---

## 📱 Mobile Typography Scale

| Level     | Font Size | Line Height | Letter Spacing | Font Weight       | Use Case             | Description                                                                 |
|-----------|-----------|-------------|----------------|--------------------|-----------------------|-----------------------------------------------------------------------------|
| Display 1 | 56px      | 64px        | -0.5px         | 800 (Extra Bold)   | Hero Banner Title     | Large mobile titles or splash screen headlines                             |
| Display 2 | 48px      | 56px        | -0.25px        | 700 (Bold)         | Section Header        | Main screen headers, visual sections                                       |
| H1        | 36px      | 44px        | -0.25px        | 700 (Bold)         | Page Title            | Major screen title (top of screen)                                         |
| H2        | 28px      | 36px        | 0px            | 600 (SemiBold)     | Section Title         | Subheaders, page section markers                                           |
| H3        | 22px      | 32px        | 0px            | 600 (SemiBold)     | Card Titles           | Card headers, FAQ titles, item blocks                                      |
| H4        | 18px      | 28px        | 0px            | 500 (Medium)       | Subtitles             | Minor headers for groups or settings                                       |
| H5        | 16px      | 24px        | 0px            | 500 (Medium)       | Form Titles           | Labels for inputs, dropdowns                                               |
| H6        | 14px      | 22px        | 0px            | 500 (Medium)       | Inline Headings       | Meta blocks, tags, field titles                                            |
| Body      | 14px      | 24px        | 0px            | 400 (Regular)      | Body Text             | Regular paragraph content                                                  |
| Small     | 12px      | 20px        | 0px            | 400 (Regular)      | Help Text             | Help and validation text for inputs                                        |
| Caption   | 12px      | 18px        | +0.2px         | 400 (Regular)      | Notes / Timestamps    | Small caption text, dates, time, info                                      |
| Button    | 14px      | 20px        | +0.5px         | 600 (SemiBold)     | Buttons               | Tap targets, short actions                                                 |

---

## ✅ Guidelines for Designers (Figma)

- Set all sizes in **pixels** (px)
- Use consistent font weights like 400, 500, 600, 700
- Apply proper **line height** for readability
- Use **letter spacing** only for small text or uppercase
- Name styles as: `Web/H1/48px`, `Mobile/Body/14px`, etc.

---

## 🔠 Popular Font Pairings

- Inter (Modern & UI-friendly)
- General Sans (Neutral & elegant)
- Roboto (Android default)
- SF Pro (iOS default)

---

## 💡 Tip

Limit to 3–4 heading levels per screen for clean design. Use body + caption + button text to keep UI light and readable.

---
















# 🧱 Minimal Responsive Typography Scale (Web & Mobile)

A clean, simple, and scalable typography system for modern web and mobile UI/UX design. Optimized for Figma, Tailwind, or any design system with only the most essential text styles.

---

## 🖥️ Web + 📱 Mobile Typography Table

| Level       | Web Font Size | Mobile Font Size | Line Height (W/M)  | Font Weight      | Use Case            | Notes                                |
|-------------|----------------|------------------|---------------------|------------------|----------------------|---------------------------------------|
| **H1**      | 48px           | 36px             | 56px / 44px         | 700 (Bold)       | Page Title           | Main heading, usually once per page  |
| **H2**      | 36px           | 28px             | 44px / 36px         | 600 (SemiBold)   | Section Title        | Major section or feature header      |
| **H3**      | 24px           | 20px             | 32px / 28px         | 600 (SemiBold)   | Card/Group Title     | Subsection headers inside blocks     |
| **Body**    | 16px           | 14px             | 28px / 24px         | 400 (Regular)    | Paragraph Text        | General content, readable everywhere |
| **Caption** | 12–14px        | 12px             | 20px                | 400 (Regular)    | Notes, Meta Text      | Use for dates, tags, tooltips        |
| **Button**  | 16px           | 14px             | 20px                | 600 (SemiBold)   | Action Buttons        | Consistent size, often UPPERCASE     |

---

## ✅ Why This System?

- 🧩 Only 3–4 heading levels → Simple & effective
- 📱 Adjusted for mobile readability
- 🎯 Easy to implement in design & code
- 🎨 Matches most modern fonts like **Inter**, **General Sans**, **Roboto**, or **SF Pro**

---

## 🔧 Figma Setup Tips

- Set font sizes in **pixels (px)**.
- Keep consistent **line heights** for rhythm.
- Create text styles like:
  - `Web/H1/48`
  - `Mobile/Body/14`
- Use **Auto Layout + Text Tokens** if using a design system.

---

## 💻 Dev-Ready Extensions

Want more?

- Tailwind-compatible class names
- Figma `.fig` styles
- JSON/SASS design tokens
- Responsive CSS snippets

Let me know, I’ll generate it! 😊

---









# 🎨 Responsive Color System Guide (Web & Mobile)

This guide summarizes **popular UI color palettes** used in modern design systems. It helps maintain consistent, accessible, and brand-friendly color usage in **web and mobile design** (Figma, Tailwind, CSS).

---

## ✅ 1. Minimal UI Color Palette

**Best For:** Clean, startup-style UIs (light mode)

| Role         | Color Example | Hex Code    | Use Case         |
|--------------|---------------|-------------|------------------|
| Primary      | ![#3B82F6](https://via.placeholder.com/15/3B82F6/000000?text=+) | `#3B82F6` | Buttons, links     |
| Secondary    | ![#64748B](https://via.placeholder.com/15/64748B/000000?text=+) | `#64748B` | Sub buttons, tags  |
| Background   | ![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+) | `#FFFFFF` | Page background    |
| Surface      | ![#F8FAFC](https://via.placeholder.com/15/F8FAFC/000000?text=+) | `#F8FAFC` | Cards, input areas |
| Text Primary | ![#111827](https://via.placeholder.com/15/111827/000000?text=+) | `#111827` | Headlines           |
| Text Muted   | ![#6B7280](https://via.placeholder.com/15/6B7280/000000?text=+) | `#6B7280` | Placeholder text   |
| Error        | ![#EF4444](https://via.placeholder.com/15/EF4444/000000?text=+) | `#EF4444` | Validation error   |

---

## 🧱 2. Material Design 3 (Google)

**Best For:** Android apps, PWA

| Role           | Hex Code   | Use Case     |
|----------------|------------|--------------|
| Primary        | `#6750A4`  | Core brand   |
| On Primary     | `#FFFFFF`  | Text on primary |
| Surface        | `#FFFBFE`  | Background   |
| On Surface     | `#1C1B1F`  | Text         |
| Secondary      | `#625B71`  | Chips, tags  |
| Tertiary       | `#7D5260`  | Accents      |
| Error          | `#B3261E`  | Alerts       |

[Material 3 Color Tool](https://m3.material.io/theme-builder)

---

## 🍎 3. Apple Human Interface (HIG)

**Best For:** iOS/macOS

| Role          | Apple Color       | Use Case          |
|---------------|-------------------|-------------------|
| System Blue   | `#007AFF`         | Buttons, links    |
| System Gray   | `#8E8E93`         | Disabled/Muted    |
| System Red    | `#FF3B30`         | Errors, delete    |
| System Green  | `#34C759`         | Success, confirm  |
| System Orange | `#FF9500`         | Warnings, notices |

System colors adapt to dark/light mode automatically in SwiftUI.

---

## 🎯 4. Tailwind CSS Color System

**Best For:** Web development, utility-first design

| Shade     | Blue         | Gray         | Red          |
|-----------|--------------|--------------|--------------|
| 50        | `#EFF6FF`    | `#F9FAFB`    | `#FEF2F2`    |
| 100       | `#DBEAFE`    | `#F3F4F6`    | `#FECACA`    |
| 500       | `#3B82F6`    | `#6B7280`    | `#EF4444`    |
| 900       | `#1E3A8A`    | `#111827`    | `#7F1D1D`    |

Tailwind supports dark mode with `dark:` variants.

---

## 🚀 5. Atlassian Palette

**Best For:** Jira, Confluence apps

| Role       | Hex Code   | Use Case     |
|------------|------------|--------------|
| Blue 500   | `#0052CC`  | Primary      |
| Red 400    | `#DE350B`  | Error        |
| Green 400  | `#36B37E`  | Success      |
| Yellow 400 | `#FFAB00`  | Warning      |
| Dark Text  | `#172B4D`  | Headings     |

---

## 🏢 6. IBM Carbon Colors

**Best For:** Enterprise apps

| Gray Scale     | Value     | Use Case         |
|----------------|-----------|------------------|
| Gray 100       | `#F4F4F4` | Background-light |
| Gray 900       | `#161616` | Text-dark        |
| Interactive 01 | `#0F62FE` | Primary button   |
| Support Error  | `#DA1E28` | Error message    |

---

## 🛒 7. Shopify Polaris Colors

**Best For:** eCommerce dashboards

| Role         | Hex Code   | Use Case        |
|--------------|------------|-----------------|
| Indigo       | `#5C6AC4`  | Primary         |
| Green        | `#50B83C`  | Positive alerts |
| Yellow       | `#EEC200`  | Warnings        |
| Red          | `#DE3618`  | Errors          |
| Text         | `#212B36`  | Main text       |

---

## ☁️ 8. Salesforce SLDS

**Best For:** Dense enterprise UI

| Role            | Hex Code   | Use Case         |
|-----------------|------------|------------------|
| Brand Blue      | `#1589EE`  | Buttons, headers |
| Neutral Gray    | `#747474`  | Labels           |
| Error Red       | `#C23934`  | Validation       |
| Success Green   | `#2E844A`  | Positive status  |

---

## 🌗 Dark Mode & Contrast Tips

- Always test colors using [WCAG Contrast Checker](https://webaim.org/resources/contrastchecker/)
- Use transparent overlays (`rgba()`) to soften tones in dark UI
- Tailwind `dark:` and Material tokens support light/dark auto-switching

---

## 📊 Summary Table

| System     | Best For                | Dark Mode Support | Notes                  |
|------------|-------------------------|-------------------|------------------------|
| Minimal UI | Modern startups         | Optional          | Simple + flexible      |
| Material   | Android apps            | ✅                 | Dynamic color system   |
| Apple HIG  | iOS/macOS               | ✅ (Auto)          | Uses system colors     |
| Tailwind   | Utility-first web dev   | ✅                 | Pre-built palette      |
| Atlassian  | B2B platforms           | ❌                 | Brand-focused          |
| IBM Carbon | Enterprise design       | ✅                 | Standardized tokens    |
| Polaris    | Shopify dashboards      | ✅                 | eCommerce ready        |
| SLDS       | Salesforce tools        | ✅                 | Large-scale systems    |

---
