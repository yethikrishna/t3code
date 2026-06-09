## 2026-06-09 - Accessibility of Icon Buttons Relying on Title Attributes

**Learning:** Found an accessibility issue pattern specific to this app's components where some icon-only buttons (`Undo2Icon` for reverting messages) were relying exclusively on the `title` attribute for tooltips and screen readers. While `title` displays a visual tooltip, it is often insufficient or inconsistently read by screen readers depending on user settings and context.
**Action:** When implementing or reviewing icon-only buttons, explicitly add `aria-label` even if a `title` attribute is present. Use `aria-label` for screen reader accessibility and `title` for visual tooltips to ensure a robust and accessible UX for all users.
