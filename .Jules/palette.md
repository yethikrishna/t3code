## 2024-05-28 - Icon-Only Button Accessibility

**Learning:** Adding a `title` attribute to an icon-only button is insufficient for screen readers; they explicitly require an `aria-label` attribute for full accessibility.
**Action:** Always verify that icon-only interactive elements contain an explicit `aria-label`, even if a tooltip or `title` is already provided.
