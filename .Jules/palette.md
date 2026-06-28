## 2024-06-28 - Consistent Tooltip usage for Icon-only Buttons

**Learning:** React components using native `title` attributes for icon-only buttons create an inconsistent visual experience compared to using the custom `<Tooltip>` component. Relying solely on `title` also skips the explicit `aria-label` which is better for screen readers.
**Action:** Replace native `title` attributes on icon-only buttons with explicit `aria-label`s and wrap them in the standard `<Tooltip>` component using the `<TooltipTrigger render={<Button />} />` pattern.
