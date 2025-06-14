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
# 🎨 Responsive Color System (Web & Mobile)

A modern, accessible, and scalable color system designed for responsive UI/UX across Web and Mobile. Supports **light** and **dark** themes, and aligns perfectly with common typography scales.

---

## ✅ 1. Core Brand Colors

| Name      | Light HEX | Dark HEX  | Use Case                          |
|-----------|-----------|-----------|-----------------------------------|
| Primary   | #0057FF   | #3B82F6   | Main actions: buttons, links      |
| Secondary | #FF6B00   | #F97316   | Accent areas, secondary CTAs      |
| Accent    | #FFD500   | #FACC15   | Highlights, pricing, notifications|
| Success   | #22C55E   | #4ADE80   | Success messages, confirmations   |
| Warning   | #F59E0B   | #FBBF24   | Warnings, caution states          |
| Error     | #EF4444   | #F87171   | Errors, validation messages       |

---

## 🧱 2. Grayscale / Neutral Colors

| Name      | Light HEX | Dark HEX  | Use Case                          |
|-----------|-----------|-----------|-----------------------------------|
| Black     | #000000   | #000000   | Strong text, shadows               |
| Gray 900  | #111827   | #F9FAFB   | Primary titles, headers            |
| Gray 700  | #374151   | #E5E7EB   | Section headings, active states    |
| Gray 500  | #6B7280   | #9CA3AF   | Body text, general UI text         |
| Gray 300  | #D1D5DB   | #4B5563   | Borders, input outlines            |
| Gray 100  | #F3F4F6   | #1F2937   | Backgrounds, containers            |
| White     | #FFFFFF   | #111827   | Surfaces, page backgrounds         |

---

## 🧩 3. Backgrounds & Surfaces

| Name        | Light HEX | Dark HEX  | Use Case                         |
|-------------|-----------|-----------|----------------------------------|
| Background  | #FFFFFF   | #0F172A   | App background                   |
| Surface     | #F9FAFB   | #1E293B   | Cards, modals, inner sections    |
| Surface Alt | #F3F4F6   | #334155   | Side panels, nested containers   |
| Divider     | #E5E7EB   | #475569   | Borders, section separators      |

---

## 📝 4. Text Colors

| Name           | Light HEX | Dark HEX  | Use Case                        |
|----------------|-----------|-----------|---------------------------------|
| Text Primary   | #111827   | #F9FAFB   | Titles, headings (H1–H3)        |
| Text Secondary | #374151   | #D1D5DB   | Body, subtitles (H4–H6)         |
| Text Muted     | #6B7280   | #9CA3AF   | Captions, help text, metadata   |
| Text Inverted  | #FFFFFF   | #000000   | Button text on dark backgrounds |

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

## 🔗 Recommended Pairing

Pair this color system with your [Responsive Typography Scale](#) for perfect spacing, alignment, and readability on both mobile and web.

---

## 🛠️ Optional Token Export

Need tokens?

- `colors.css` for web projects
- `tailwind.config.js` for Tailwind setup
- `tokens.json` for Figma plugin or code

Let me know and I’ll generate it for you!

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
---

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

## 📎 Want Design Tokens?

- `tokens.json` – for Figma, Style Dictionary  
- `tailwind.config.js` – if using Tailwind CSS  
- `scss/variables.scss` – for web projects

Let me know and I’ll generate it for you!

---
# 🎨 Design System: Complete Checklist (Web + Mobile)

## 🧱 Design Foundations (Tokens)

| Token Type       | Web Example                    | Mobile Example                  | Use Case                                 | Description                                                                 |
|------------------|--------------------------------|----------------------------------|------------------------------------------|-----------------------------------------------------------------------------|
| Font Sizes       | 12–80px                        | 12–56px                          | Typography scale                         | Sizes for headings, body, labels, captions                                 |
| Line Heights     | 18–88px                        | 18–64px                          | Paragraph & heading rhythm               | Ensures readable spacing between lines                                      |
| Letter Spacing   | -0.5px to +0.5px               | -0.5px to +0.5px                 | Improved legibility                      | Fine-tunes character spacing                                                |
| Font Weights     | 400, 500, 600, 700, 800        | 400, 500, 600, 700, 800          | Emphasis control                         | Bolder weights for headings/buttons                                         |
| Colors           | Primary, Surface, Text, Error  | Same                             | Brand identity & states                  | Color system for base UI + states                                           |
| Spacing Scale    | 4, 8, 12, 16, 24, 32, 40, 64px | Same                             | Margin & padding                         | Scalable spacing based on 4pt grid                                          |
| Border Radius    | 4px, 8px, 16px                  | 4px, 8px                         | Rounded corners for inputs/buttons/cards | Enhances visual appeal, soft UI feel                                        |
| Shadows / Elev.  | 0px 1px 3px, 0px 4px 6px        | Same                             | Card or modal elevation                  | Layering depth, hierarchy                                                   |
| Grid System      | 12 columns (web)               | 4–8 columns (mobile)             | Layout alignment                         | Helps structure responsive UI                                               |

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

📁 Design System
│
├── 🧱 Foundations
│   ├── Colors
│   ├── Typography
│   ├── Spacing Scale
│   ├── Grid & Layout
│   └── Elevation (Shadow, Z-index)
│
├── 🔤 Text Styles
│   ├── Display (Web & Mobile)
│   ├── Headings (H1–H6)
│   ├── Body, Caption, Small
│   ├── Button Text
│   └── Labels / Tags
│
├── 🎨 Color Styles
│   ├── Primary / Secondary
│   ├── Text Colors
│   ├── Background / Surface
│   ├── State (Success, Error, Warning)
│   └── Dark Mode Variants
│
├── 📐 Layout Grid
│   ├── Desktop
│   ├── Tablet
│   └── Mobile
│
├── 📦 Components
│   ├── Buttons (Primary, Secondary, Icon)
│   ├── Forms (Inputs, Selects, Checkbox, Radio)
│   ├── Cards (Project Card, Blog Card)
│   ├── Modals
│   ├── Tags / Chips
│   └── Nav & Footer
│
├── 🧩 UI Elements
│   ├── Icons
│   ├── Avatars
│   ├── Tooltips
│   └── Loaders / Progress
│
├── 📄 Examples / Templates
│   ├── Hero Section
│   ├── Projects Grid
│   ├── Contact Section
│   └── Blog Layout
│
└── 📝 Notes
    ├── Design Tokens Guide
    ├── Naming Convention
    └── Accessibility Guidelines

