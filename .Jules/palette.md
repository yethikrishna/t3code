## 2026-05-29 - ARIA label versus Title on Icon Buttons
**Learning:** Found an icon-only button with a `title` attribute but no `aria-label`. While `title` can provide a tooltip, it is not consistently exposed as an accessible name to screen readers across all environments. An explicit `aria-label` ensures robust accessibility for icon-only interactive elements.
**Action:** When auditing icon buttons, explicitly check for `aria-label`. Do not rely solely on `title` for screen reader accessibility.
