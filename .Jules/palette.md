## 2026-07-06 - Prefer design system Tooltip over native title attribute

**Learning:** Native `title` attributes on buttons for tooltips provide a subpar UX. They are delayed, often small/unreadable, and fail to match the overall design system. Wrapping icon-only or compact buttons in a custom `<Tooltip>` component provides a much more accessible and consistent experience.
**Action:** When adding explanatory text to buttons or toggles (especially those that only use icons), strictly avoid the native `title` attribute and instead use the designated `Tooltip` components alongside `aria-label` attributes.
