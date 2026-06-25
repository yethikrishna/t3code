## 2025-02-23 - Accessibility Enhancements for Icon-Only Buttons
**Learning:** Relying on the native `title` attribute for icon-only buttons provides poor accessibility and inconsistent visual feedback compared to utilizing a dedicated Tooltip component with proper `aria-label` attributes.
**Action:** Always prefer wrapping icon-only buttons in the standard `<Tooltip>` component and assigning an explicit `aria-label` for screen readers.
