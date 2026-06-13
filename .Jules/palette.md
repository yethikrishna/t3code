## 2024-03-24 - Accessibility improvements on tree toggles

**Learning:** When using `<button>` elements as toggles for expanding/collapsing sections (like directories in a file tree), it's critical to add the `aria-expanded` attribute correctly reflecting the current state (e.g. `aria-expanded={isExpanded}`). This ensures screen readers can announce whether the section is open or closed, dramatically improving usability over just reading the button's text or visual icon changes alone.

**Action:** Whenever implementing a toggle mechanism for collapsible content, always ensure the controlling element has a corresponding `aria-expanded` attribute.