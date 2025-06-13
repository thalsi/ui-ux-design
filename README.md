# 📘 UI/UX Design Guidelines for Web & Mobile

A practical reference guide covering typography, color, spacing, layout, buttons, icons, navigation, and accessibility for responsive web and mobile design.

---

## 1. 🔤 Typography

| Element       | Web                  | Mobile                | Notes                                |
|---------------|-----------------------|------------------------|---------------------------------------|
| Base font     | 16–18px               | 14–16px               | Never below 12px on mobile            |
| Headings      | H1: 32–48px<br>H2: 24–36px | H1: 24–32px<br>H2: 20–28px | Use a modular scale                  |
| Line height   | 1.4–1.6x font size    | Same                  | Improves readability                  |
| Font weight   | 400–700               | 400–700               | Avoid too many weight variations      |
| Font family   | Sans-serif (Inter, Roboto, SF Pro) | Same       | Web-safe and readable                 |

> 🧠 **Tip**: Stick to 2–3 font styles max (e.g., Regular, Medium, Bold)

---

## 2. 🎨 Color System

| Type            | Suggested Values                      | Notes                                   |
|------------------|----------------------------------------|------------------------------------------|
| Primary color   | Brand-specific, high contrast          | Main action/CTA                          |
| Secondary       | Complementary, neutral variant         | For less emphasis                        |
| Background      | #FFFFFF / #F9F9F9 / #FAFAFA            | Avoid harsh pure black                   |
| Text colors     | Dark: #111 / #333 / #444              | On light background                      |
| Accent colors   | Blue, green, red, etc.                | For alerts, links, and highlights        |
| Contrast ratio  | ≥ 4.5:1                               | WCAG AA standard for accessibility       |

> 🧠 **Tip**: Limit to 5–7 core colors and build shades/tints from those.

---

## 3. 📐 Grid & Layout

| Feature           | Web                                | Mobile                         |
|-------------------|-------------------------------------|--------------------------------|
| Grid columns      | 12-column, 1140–1440px max width   | 4-column, 320–420px wide       |
| Gutter width      | 24px                               | 16px                           |
| Margins/padding   | 24–32px side padding               | 16–20px side padding           |
| Breakpoints       | 576, 768, 1024, 1280, 1440         | Use media queries              |

> 🧠 **Tip**: Use a consistent 8pt or 4pt spacing system for pixel-perfect alignment.

---

## 4. 📏 Spacing & Sizing

| Use Case           | Value Range (px)        | Notes                             |
|--------------------|--------------------------|------------------------------------|
| Section spacing    | 32–64px                 | Between distinct UI blocks         |
| Component spacing  | 8–24px                  | Between cards, inputs, etc.        |
| Inline spacing     | 4–16px                  | Icons next to text, etc.           |
| Vertical rhythm    | 8px increments          | Maintain visual balance            |

> 🧠 **Tip**: Create spacing tokens like `space-4`, `space-8`, `space-16`, etc.

---

## 5. 🔘 Buttons

| Property    | Web            | Mobile         | Notes                                |
|-------------|----------------|----------------|---------------------------------------|
| Height      | 40–48px        | 44–56px        | At least 44px for tap areas           |
| Width       | Min 120px      | Same           | Responsive size recommended           |
| Padding     | 16–24px (H)    | 16–20px (H)    | Internal text spacing                 |
| Radius      | 4–8px          | 4–8px          | Avoid over-rounded unless stylistic   |

> 🧠 **Tip**: Buttons must have at least 44x44px tappable area for accessibility.

---

## 6. 📱 Inputs & Forms

| Feature           | Value                         | Notes                                |
|-------------------|-------------------------------|---------------------------------------|
| Input height      | 44–48px                       | Ensure easy touch targets             |
| Label size        | 14–16px                       | Consistent with base text             |
| Placeholder text  | #999 or #AAA                  | Never use as a replacement for labels |
| Field spacing     | 16–24px between inputs        | Avoid crowding                        |

> 🧠 **Tip**: Always provide visible error, success, and helper messages below inputs.

---

## 7. 👁️ Iconography

| Type         | Value                  | Notes                                |
|--------------|------------------------|---------------------------------------|
| Standard size| 16–24px                | Consistent across buttons & links     |
| Stroke width | 1.5–2px                | Clean and readable                    |
| Padding      | 8px from text or edges | Avoid cramping                        |
| File type    | SVG preferred          | Scalable and lightweight              |

> 🧠 **Tip**: Use consistent icon sets (e.g., Feather, Material Icons) and never mix styles.

---

## 8. 🧭 Navigation

| Element        | Web            | Mobile                  |
|----------------|----------------|--------------------------|
| Header height  | 64–80px        | 56–64px                  |
| Tab bar/nav bar| —              | 56–72px                  |
| Side nav width | 200–280px      | Off-canvas or hamburger  |
| Icon size      | 20–24px        | Same                     |

> 🧠 **Tip**: Sticky headers and bottom navs improve usability on small screens.

---

## 9. 🧪 Accessibility

| Feature             | Recommendation                       |
|----------------------|--------------------------------------|
| Contrast Ratio      | ≥ 4.5:1 (text), 3:1 (UI elements)    |
| Focus Indicators    | Always show                          |
| Keyboard Navigation | Full support (Tab, arrows)           |
| Alt Text            | For all images/icons                 |
| Language Tags       | Use `lang="en"` (or relevant)        |

---

## 10. 📱 Mobile-Specific Tips

- ❌ Avoid hover-only effects — mobile users can’t hover.
- ✅ Optimize tap targets — 44x44px minimum.
- 🚀 Prioritize speed — optimize assets and reduce layout shifts.
- 🤲 Use native gestures when possible (e.g., swipes, long-press).

---

## ✅ License

This cheat sheet is open for personal and professional use. Feel free to modify or extend it to match your design system.

---

