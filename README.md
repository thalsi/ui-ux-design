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

# 📐 Responsive Typography Scale Guide (Web & Mobile)

This guide compares **8 popular typography scales** used in real-world UI/UX design systems — optimized for both **web and mobile platforms**. Use these as a foundation for your Figma design tokens, Tailwind config, or CSS system.

---

## ✅ 1. Minimal Product UI Scale

**Best For:** SaaS apps, dashboards, startup UIs

| Style   | Web Size | Mobile Size | Line Height | Weight | Use Case       |
|---------|----------|-------------|-------------|--------|----------------|
| H1      | 48px     | 36px        | 56 / 44px   | 700    | Page title     |
| H2      | 36px     | 28px        | 44 / 36px   | 600    | Section header |
| H3      | 24px     | 20px        | 32 / 28px   | 600    | Card title     |
| Body    | 16px     | 14px        | 28 / 24px   | 400    | Paragraph      |
| Caption | 12px     | 12px        | 20px        | 400    | Meta/Notes     |
| Button  | 16px     | 14px        | 20px        | 600    | CTA/Button     |

---

## 🧱 2. Material Design 3 (Google)

**Best For:** Android, Google apps, Material UI

| Style           | Web Size | Mobile Size | Weight | Use Case           |
|------------------|----------|-------------|--------|--------------------|
| Display Large    | 57px     | 45px        | 400    | Hero/Banner        |
| Headline Large   | 32px     | 28px        | 400    | Section Title      |
| Title Medium     | 16px     | 16px        | 500    | Card/Form Title    |
| Body Large       | 16px     | 14px        | 400    | Content            |
| Label Small      | 11px     | 11px        | 500    | Labels/Chips       |
| Button           | 14px     | 14px        | 500    | Buttons/CTAs       |

---

## 🍎 3. Apple Human Interface (HIG)

**Best For:** iOS/macOS apps and mobile-first UX

| Style        | Size (pt) | Weight | Use Case       |
|--------------|-----------|--------|----------------|
| Large Title  | 34pt      | Bold   | Page Top Title |
| Title 1      | 28pt      | Bold   | Section Title  |
| Title 2      | 22pt      | Semi   | Subheader      |
| Body         | 17pt      | Regular| Body Text      |
| Footnote     | 13pt      | Regular| Small Notes    |
| Caption      | 12pt      | Regular| Meta Info      |

---

## 🎯 4. Tailwind CSS Typography

**Best For:** Utility-first design, web projects

| Class       | Font Size |
|-------------|-----------|
| text-xs     | 12px      |
| text-sm     | 14px      |
| text-base   | 16px      |
| text-lg     | 18px      |
| text-xl     | 20px      |
| text-2xl    | 24px      |
| text-3xl    | 30px      |
| text-4xl    | 36px      |
| text-5xl    | 48px      |
| text-6xl+   | 60–96px   |

Use responsive variants: `sm:text-xl`, `lg:text-3xl`, etc.

---

## 🚀 5. Atlassian Design System

**Best For:** B2B tools like Jira, Confluence, Trello

| Style       | Size     | Weight | Use Case      |
|-------------|----------|--------|---------------|
| Heading XL  | 30px     | 600    | Page Title    |
| Heading LG  | 24px     | 600    | Section Header|
| Heading SM  | 18px     | 500    | Card Header   |
| Body        | 14–16px  | 400    | Content Text  |
| Caption     | 12px     | 400    | Notes/Labels  |

---

## 🏢 6. IBM Carbon Design System

**Best For:** Large-scale enterprise UIs

**Expressive (marketing)**  
- Display: 32–72px  
- Headline: 32px  
- Subtitle: 20px  
- Body: 16px  
- Label: 14px  

**Productive (app UI)**  
- H1–H6: 20–48px  
- Body/Small: 14–16px  

---

## 🛒 7. Shopify Polaris

**Best For:** Admin panels, eCommerce dashboards

| Style      | Size   | Weight | Use Case       |
|------------|--------|--------|----------------|
| Display    | 40px   | 500    | Hero Titles    |
| Heading    | 24px   | 500    | Section Titles |
| Subheading | 20px   | 500    | Card Headings  |
| Body       | 16px   | 400    | Text Content   |
| Caption    | 13px   | 400    | Meta Text      |

---

## ☁️ 8. Salesforce Lightning Design System (SLDS)

**Best For:** Enterprise platforms, dense UIs

| Style       | Size   | Weight | Use Case        |
|-------------|--------|--------|-----------------|
| Display     | 44px   | 700    | Page Hero       |
| Heading     | 24px   | 600    | Section Header  |
| Subheading  | 20px   | 500    | Card/Subsection |
| Body        | 16px   | 400    | Content         |
| Label       | 12px   | 400    | UI Labels       |

---

## 📱 Mobile & Web Usage

All scales above are **responsive**.  
Use **Figma variants**, **media queries**, or `clamp()` in CSS for smooth typography across breakpoints.

Example (CSS):
```

| System     | Best For                | Platform     |
| ---------- | ----------------------- | ------------ |
| Minimal UI | Web apps, startups      | Web + Mobile |
| Material   | Android, PWA            | Web + Mobile |
| Apple HIG  | iOS/macOS apps          | Mobile + Web |
| Tailwind   | Utility-first dev       | Web          |
| Atlassian  | B2B productivity        | Web + Mobile |
| Carbon     | Enterprise content & UI | Web + Mobile |
| Polaris    | Shopify admin tools     | Web + Mobile |
| SLDS       | Salesforce enterprise   | Web + Mobile |

```


