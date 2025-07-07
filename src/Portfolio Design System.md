# 🎨 Portfolio Design System – Web & Mobile

This is a lightweight and scalable design system for personal portfolios, optimized for both web and mobile. It includes a typography scale, color palette, component sizing, spacing scale, and layout grid guidance.

---

## ✍️ Typography Scale

| Level     | Web Font Size | Mobile Font Size | Line Height      | Weight | Use Case               |
|-----------|---------------|------------------|------------------|--------|------------------------|
| Display   | 64px          | 48px             | 72px / 56px      | 800    | Hero banners, name     |
| H1        | 48px          | 36px             | 56px / 44px      | 700    | Section titles         |
| H2        | 36px          | 28px             | 44px / 36px      | 600    | Project sections       |
| H3        | 28px          | 22px             | 36px             | 600    | Cards, modals          |
| Body      | 16px          | 16px             | 28px             | 400    | Paragraph content       |
| Small     | 14px          | 14px             | 22px             | 400    | Metadata, tooltips     |
| Button    | 16px          | 14px             | 20px             | 600    | CTA button text        |

---

## 🎨 Color Palette

| Token            | Hex Code    | Use Case                        |
|------------------|-------------|---------------------------------|
| Primary          | #2563EB     | Buttons, links, highlights      |
| Secondary        | #F97316     | Accent highlights, hover states |
| Text Primary     | #111827     | Main content text               |
| Text Secondary   | #6B7280     | Subtext, helper labels          |
| Background       | #FFFFFF     | Light backgrounds               |
| Surface          | #F9FAFB     | Cards, inputs                   |
| Border           | #E5E7EB     | Dividers, form fields           |
| Success          | #22C55E     | Alerts, confirmation states     |
| Error            | #EF4444     | Form errors, alerts             |

> ✅ Color tokens support light/dark themes.

---

## 📐 Spacing System

Consistent spacing scale using a 4px base grid:

```
4, 8, 12, 16, 24, 32, 40, 48, 64
```

---

## 🧩 UI Components

| Component        | Description                            | Mobile Variant       |
|------------------|----------------------------------------|----------------------|
| Button (Primary) | CTA like "View Projects", "Download CV"| Full-width button    |
| Button (Secondary)| Ghost or outlined button              | Full-width button    |
| Card             | Project, blog, or gallery item display | Stacked layout       |
| Modal            | Detailed view of a project             | Full screen modal    |
| Tag              | Skill or category indicator            | Scrollable row       |
| Navbar           | Logo, links, theme switcher            | Hamburger menu       |
| Footer           | Copyright + social icons               | Stack vertically     |
| Form             | Contact form (Name, Email, Message)    | Responsive layout    |

---

## 📱 Buttons & Icons

| Type        | Web Size          | Mobile Size       | Padding       |
|-------------|-------------------|-------------------|---------------|
| Primary     | 48px height       | 44px height       | 16px x 24px   |
| Secondary   | 44px height       | 40px height       | 12px x 20px   |
| Icon Button | 40px x 40px       | 32px x 32px       | Icon only     |

---

## 🔲 Layout Grid

| Breakpoint | Grid Columns | Max Width | Margin/Gutter |
|------------|--------------|-----------|---------------|
| Desktop    | 12 columns   | 1140px    | 24px          |
| Tablet     | 8 columns    | 720px     | 16px          |
| Mobile     | 4 columns    | 100%      | 16px          |

---

## 💡 Use Case Examples

### 🔹 Hero Section
- Display + H1 + Body
- Primary button: “View Projects”
- Background image or illustration

### 🔹 Project Grid
- Cards using H3 + tags
- Responsive layout: 3-column web, 1-column mobile

### 🔹 Contact Form
- Inputs: Name, Email, Message
- Primary CTA: “Send”
- Toast: “Message sent successfully”

---

## ✅ Features

- 🎯 Mobile-First & Responsive
- 🌗 Dark Mode Ready
- ♿ Accessible Color Contrast
- 🧩 Scalable Components
- 🧙‍♀️ Clean Visual Hierarchy

> This system is ideal for developers, designers, and creatives building a clean, responsive portfolio.
---
