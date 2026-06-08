## 2024-05-24 - Icon-only buttons lacking ARIA labels

**Learning:** Some icon-only buttons rely solely on `title` attributes for screen readers, which is insufficient for accessibility.
**Action:** Always add explicit `aria-label` attributes to icon-only buttons, even when a `title` is present, to ensure proper screen reader support.
