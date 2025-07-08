# 🔤 Typography Roles – Design System Guide

Supports **Web & Mobile UI** with scalable tokens and style roles.


# Typography Roles Table (Beginner & Pro)

| Role            | Token         | Size (Desktop / Mobile) | Weight         | Line Height | Spacing   | Font Family       |
|-----------------|---------------|-------------------------|----------------|-------------|-----------|-------------------|
| Display         | text/display  | 56px / 40px            | Bold (700)     | 1.1         | -0.02em   | Inter, sans-serif |
| H1 (Page Title) | text/h1       | 40px / 32px            | Bold (700)     | 1.2         | -0.01em   | Inter, sans-serif |
| H2 (Subheader)  | text/h2       | 32px / 24px            | SemiBold (600) | 1.25        | 0em       | Inter, sans-serif |
| H3 (Tertiary)   | text/h3       | 24px / 20px            | Medium (500)   | 1.3         | 0em       | Inter, sans-serif |
| Body (Paragraph) | text/body    | 16px / 14px            | Regular (400)  | 1.5         | 0.01em    | Inter, sans-serif |
| Small (Caption) | text/caption  | 14px / 12px            | Light (300)    | 1.4         | 0.02em    | Inter, sans-serif |
| Label (UI)      | text/label    | 14px / 12px            | Medium (500)   | 1.2         | 0.01em    | Inter, sans-serif |
| Button Text     | text/button   | 16px / 14px            | Medium (500)   | 1.2         | 0.04em    | Inter, sans-serif |
| Code/Mono       | text/code     | 14px / 13px            | Regular (400)  | 1.5         | 0em       | Fira Code, mono   |

| Role            | Usage Examples (Expanded)                              | Pro Tips                                      |
|-----------------|-------------------------------------------------------|-----------------------------------------------|
| Display         | - Full-width hero banners<br>- Product launch headlines<br>- Logotype in marketing collateral | Use dark-on-light for maximum impact.         |
| H1 (Page Title) | - Dashboard primary titles<br>- Blog post headlines<br>- Full-screen modal titles | Add 32px bottom margin for breathing room.    |
| H2 (Subheader)  | - Pricing plan names<br>- Settings panel sections<br>- Feature comparison tables | Perfect for 2-column layouts.                 |
| H3 (Tertiary)   | - FAQ item questions<br>- Form step indicators<br>- Card subtitles (e.g., "Recommended") | Ideal for 3-level hierarchies.                |
| Body (Paragraph) | - Product descriptions<br>- Error message details<br>- User onboarding instructions | Max 70 characters per line for readability.   |
| Small (Caption) | - Photo credits in galleries<br>- Timestamps in comments ("Posted 2h ago")<br>- Disabled state hints | Combine with 50% opacity for subtlety.        |
| Label (UI)      | - Form field labels (e.g., "Password")<br>- Filter dropdown titles<br>- Toggle switch labels | Right-align for numeric inputs.               |
| Button Text     | - Primary actions ("Buy Now")<br>- Destructive actions ("Delete")<br>- Floating action buttons ("+") | Add 12px horizontal padding minimum.         |
| Code/Mono       | - API endpoint examples<br>- CLI command snippets<br>- JSON configuration previews | Use #f8f8f8 background for blocks.            |

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





# 🎨 Typography Tokens / Variables for Design Systems

Tokens help define reusable styles in design and code. Here's a standard set of **typography tokens**:

---

## 📐 Font Size Tokens

| Token Name        | Value (px) | Use Case               |
|-------------------|------------|-------------------------|
| `font-size-display` | 56px       | Hero titles             |
| `font-size-h1`      | 48px       | Page headings           |
| `font-size-h2`      | 36px       | Section titles          |
| `font-size-h3`      | 30px       | Sub-section titles      |
| `font-size-h4`      | 24px       | Card titles             |
| `font-size-h5`      | 20px       | Smaller titles          |
| `font-size-body-lg` | 18px       | Body large              |
| `font-size-body`    | 16px       | Base paragraph text     |
| `font-size-caption` | 14px       | Captions, notes         |
| `font-size-overline`| 12px       | Labels, overline        |

---

## 📏 Line Height Tokens

| Token Name           | Value | Description                 |
|----------------------|--------|-----------------------------|
| `line-height-tight`   | 1.2    | For headings                |
| `line-height-default` | 1.5    | For body text               |
| `line-height-loose`   | 1.75   | For spacious layouts        |

---

## 🧱 Font Weight Tokens

| Token Name          | Value | Use Case                  |
|---------------------|--------|----------------------------|
| `font-weight-regular` | 400    | Body text                  |
| `font-weight-medium`  | 500    | Labels, slightly bold text |
| `font-weight-semibold`| 600    | Subheadings                |
| `font-weight-bold`    | 700    | Headlines                  |

---

## ✍️ Font Family Tokens

| Token Name         | Value                          | Use Case           |
|--------------------|--------------------------------|---------------------|
| `font-family-base` | `'Inter', sans-serif`          | Main font           |
| `font-family-alt`  | `'Lora', serif`                | Optional secondary  |

---

## 🔠 Letter Spacing Tokens

| Token Name               | Value    | Use Case         |
|--------------------------|----------|------------------|
| `letter-spacing-tight`   | -0.5px   | For display text |
| `letter-spacing-normal`  | 0px      | Body text        |
| `letter-spacing-loose`   | +0.5px   | Captions, labels |

---

## 🎯 Example Use in CSS Variables

```css
:root {
  --font-size-h1: 48px;
  --line-height-default: 1.5;
  --font-weight-bold: 700;
  --font-family-base: 'Inter', sans-serif;
}
```
---
