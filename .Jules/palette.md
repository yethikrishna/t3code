## 2024-05-23 - Relying on title for icon-only buttons

**Learning:** Found multiple instances where icon-only buttons in the UI library used only a `title` attribute for accessibility. `title` attributes are insufficient for screen readers and must be accompanied by `aria-label` or explicit text for true accessibility.
**Action:** Always add explicit `aria-label` attributes to icon-only components in the design system, even when a `title` or tooltip is present.
