
## 2026-04-26 - Added aria-expanded to expandable sections
**Learning:** Found several buttons acting as toggles for expanding content sections that lacked the `aria-expanded` structural ARIA attribute.
**Action:** When adding or discovering expandable content sections, explicitly ensure their toggling buttons have an `aria-expanded` attribute mapped to their open/closed state to make them accessible to screen readers.
