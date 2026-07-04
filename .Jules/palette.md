## 2024-11-21 - Standardizing Tooltips for Icon-only Buttons
**Learning:** For icon-only buttons, using the native `title` attribute provides an inconsistent and often inaccessible experience compared to custom tooltips. Custom tooltips ensure proper styling, accessibility, and consistency across the app.
**Action:** Always wrap icon-only `<Button>`s in a standard `<Tooltip>` component. Move the tooltip text to `<TooltipPopup>` and ensure the `render` prop on `<TooltipTrigger>` has an appropriate `aria-label`.
