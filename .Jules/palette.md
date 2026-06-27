## 2024-05-18 - Replace native `title` on icon-only buttons with Tooltips

**Learning:** Native `title` attributes on icon-only buttons do not consistently announce to all screen readers and create an inconsistent visual experience compared to standard tooltip components. Explicit `aria-label` combined with a standard tooltip provides robust accessibility and a cohesive UI.
**Action:** Always prefer explicit `aria-label`s combined with the standard `<Tooltip>` component over native `title` attributes for icon-only buttons to guarantee screen reader compatibility and visual consistency.
