

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
