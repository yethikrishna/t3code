## 2025-02-23 - Screen reader context for expandable lists

**Learning:** Found an expandable work log section that visually indicates its state (Show more/less) but completely lacked screen reader context about whether the section was expanded (`aria-expanded`) and what content it controlled (`aria-controls`). This is a common pattern for "show more" buttons that needs explicit linking.
**Action:** Always pair `aria-expanded` with `aria-controls` on the toggle button, and ensure the controlled container has a matching `id`. This explicitly ties the button's state to the content it reveals.
