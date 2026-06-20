## 2024-05-18 - Missing ARIA labels on Icon-only buttons with `title` attributes
**Learning:** Native `title` attributes are often considered insufficient for screen readers on icon-only interactive elements like buttons, and standard tooltips with explicit `aria-label`s on the trigger elements are preferred in this codebase for proper accessibility context.
**Action:** Always prefer `aria-label` + `Tooltip` over a native `title` attribute for icon-only buttons to guarantee screen reader compatibility and visual tooltip consistency.
