## 2024-06-24 - Tooltips Over Native Titles

**Learning:** Native `title` attributes on buttons can be inconsistent, lack proper accessibility integration in certain contexts, and cause visual discrepancies compared to custom design system Tooltips. Converting them to design system `<Tooltip>` components improves both visual polish and consistent accessibility for icon-heavy actions.
**Action:** Replace native `title` properties on buttons with explicit `<Tooltip>` component wrappers that implement `TooltipTrigger` and `TooltipPopup`, especially on primary project or git action buttons.
