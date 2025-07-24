
To make `color-[role]-[state]` or extended `color-[category]-[role]-[state]` meaningful and scalable, you need to clearly define the three levels:

 ## 1. Category

 | Category  | Description                       | Examples                   |
| --------- | --------------------------------- | -------------------------- |
| `bg`      | Background colors                 | `color-bg-surface-default` |
| `text`    | Text or typography-related colors | `color-text-primary`       |
| `border`  | Border-related colors             | `color-border-default`     |
| `icon`    | Icon color                        | `color-icon-default`       |
| `overlay` | Overlays and masks                | `color-overlay-scrim`      |


## 2. Role (the purpose or meaning of the color)

| Role         | Description                         | Examples              |
| ------------ | ----------------------------------- | --------------------- |
| `primary`    | Main brand/action color             | `color-text-primary`  |
| `secondary`  | Secondary brand color               | `color-bg-secondary`  |
| `surface`    | UI surfaces such as cards or sheets | `color-bg-surface`    |
| `background` | Main background area                | `color-bg-background` |
| `accent`     | Emphasis or highlight color         | `color-border-accent` |
| `success`    | Indicates success state             | `color-text-success`  |
| `warning`    | Indicates caution or warning        | `color-bg-warning`    |
| `error`      | Indicates error or danger           | `color-border-error`  |
| `info`       | Neutral informative messages        | `color-icon-info`     |
| `disabled`   | UI elements not currently usable    | `color-text-disabled` |
| `muted`      | Less emphasized content             | `color-text-muted`    |


## 3. State (variant or UI state — optional)
| State      | Description                      | Examples                     |
| ---------- | -------------------------------- | ---------------------------- |
| `default`  | Base/default state               | `color-bg-primary-default`   |
| `hover`    | On hover interaction             | `color-bg-primary-hover`     |
| `active`   | On click or active state         | `color-bg-primary-active`    |
| `focus`    | On focus (like input focus)      | `color-border-primary-focus` |
| `disabled` | Disabled or inactive element     | `color-text-disabled`        |
| `subtle`   | Soft or lighter version          | `color-bg-warning-subtle`    |
| `strong`   | Strong/darker version            | `color-bg-warning-strong`    |
| `emphasis` | Extra importance                 | `color-text-error-emphasis`  |
| `selected` | Selected state (e.g., tab, chip) | `color-bg-surface-selected`  |

##  Minimum Recommended Counts

| Element    | Count | Example                                                             |
| ---------- | ----- | ------------------------------------------------------------------- |
| Categories | 3     | `bg`, `text`, `border`                                              |
| Roles      | 6     | `primary`, `secondary`, `success`, `error`, `surface`, `background` |
| States     | 4     | `default`, `hover`, `active`, `disabled`                            |
