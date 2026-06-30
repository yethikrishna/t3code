## 2026-06-30 - Adding Tooltips to Primary Action Buttons

**Learning:** Tooltips for icon-only action buttons are critical for accessibility and usability. Utilizing the existing Tooltip components combined with dynamic label text provides consistent visual and screen-reader experience. The trigger component expects a render prop containing the target element, rather than wrapping it via asChild.
**Action:** Always wrap ambiguous or icon-only buttons with Tooltip and TooltipPopup and assign a meaningful aria-label synchronized with the tooltip label text.
