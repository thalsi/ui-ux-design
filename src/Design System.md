

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
