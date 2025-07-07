## 4. 📏 Spacing & Sizing

| Use Case           | Value Range (px)        | Notes                             |
|--------------------|--------------------------|------------------------------------|
| Section spacing    | 32–64px                 | Between distinct UI blocks         |
| Component spacing  | 8–24px                  | Between cards, inputs, etc.        |
| Inline spacing     | 4–16px                  | Icons next to text, etc.           |
| Vertical rhythm    | 8px increments          | Maintain visual balance            |

> 🧠 **Tip**: Create spacing tokens like `space-4`, `space-8`, `space-16`, etc.

---
















# 📐 Responsive UI Sizing & Spacing System (Web & Mobile)

A practical and consistent UI system to ensure a smooth design experience across **Web** and **Mobile** platforms. This includes button sizes, icon sizes, spacing tokens, and accessibility-ready touch targets.

---

## 🖥️ Web UI Sizing System

### 🎯 Element Sizes

| Element      | Size         | Notes                                |
|--------------|--------------|--------------------------------------|
| Icon XS      | 12×12 px     | Inline text icons                    |
| Icon SM      | 16×16 px     | Navigation, buttons                  |
| Icon MD      | 20×20 px     | Default UI icon                      |
| Icon LG      | 24×24 px     | Page actions                         |
| Button SM    | 32 px height | Tag, secondary CTA                   |
| Button MD    | 40 px height | Default button                       |
| Button LG    | 48 px height | Hero/CTA button                      |
| Input Field  | 40–48 px     | Forms and search fields              |

### 📦 Spacing (Margin & Padding)

| Token       | Size  | Use Case                                  |
|-------------|--------|-------------------------------------------|
| `spacing-4` | 4 px   | Icon + text gap, chip padding             |
| `spacing-8` | 8 px   | Inside button, spacing within forms       |
| `spacing-12`| 12 px  | Card content spacing                      |
| `spacing-16`| 16 px  | Between form blocks, sections             |
| `spacing-24`| 24 px  | Card margin, group blocks                 |
| `spacing-32`| 32 px  | Page gutter                               |
| `spacing-40`| 40 px  | Large block sections                      |

---

## 📱 Mobile UI Sizing System

### 🎯 Element Sizes

| Element      | Size         | Notes                                         |
|--------------|--------------|-----------------------------------------------|
| Icon XS      | 12×12 px     | Tag, metadata                                |
| Icon SM      | 16×16 px     | Inside input, card icon                      |
| Icon MD      | 20×20 px     | Universal mobile icon                        |
| Icon LG      | 24×24 px     | Header, tab bar                              |
| Icon XL      | 32×32 px     | Onboarding, splash                           |
| Button SM    | 36 px height | Chip/button                                  |
| Button MD    | 44 px height | Most common button size (Apple & Material)   |
| Button LG    | 48 px height | CTA, full-width buttons                      |
| Input Field  | 44–48 px     | Mobile-friendly fields                       |
| Touch Target | Min 44×44 px | WCAG accessible tap zone                     |

### 📦 Spacing (Margin & Padding)

| Token       | Size  | Use Case                                  |
|-------------|--------|-------------------------------------------|
| `spacing-4` | 4 px   | Icon-text, inside label spacing           |
| `spacing-8` | 8 px   | Between controls, small button padding    |
| `spacing-12`| 12 px  | Between stacked items                     |
| `spacing-16`| 16 px  | Section spacing, card content             |
| `spacing-20`| 20 px  | Full-width card gutters                   |
| `spacing-24`| 24 px  | Main section separation                   |
| `spacing-32+`| 32+ px| Hero, splash screens, modal inner padding |

---

## 🧩 Button Design (Web vs Mobile)

| Platform | Size  | Padding H | Font Size | Border Radius | Font Weight |
|----------|-------|-----------|-----------|----------------|-------------|
| Web SM   | 32 px | 12 px     | 14 px     | 6 px           | 500         |
| Web MD   | 40 px | 16 px     | 16 px     | 8 px           | 600         |
| Web LG   | 48 px | 20 px     | 18 px     | 8–12 px        | 600         |
| Mobile MD| 44 px | 16–20 px  | 16 px     | 12 px          | 600         |
| Mobile LG| 48 px | 20–24 px  | 18 px     | 12–16 px       | 600         |

---

## 🧠 Best Practices

- Use **8pt or 4pt spacing** for alignment consistency.
- Maintain **minimum 44×44 px** touch areas on mobile.
- Keep spacing consistent with typography line height.
- Match these rules with a typography & color system for full design tokens.

---