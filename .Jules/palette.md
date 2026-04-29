## 2024-06-25 - Missing aria-expanded on Toggle Buttons

**Learning:** React state variables controlling expansion/collapse (like `isExpanded` or `expanded`) are frequently implemented without corresponding `aria-expanded` attributes on the trigger buttons. This makes it impossible for screen reader users to know the current state of collapsible sections like file trees, logs, or plan previews.
**Action:** When reviewing or creating components with expand/collapse functionality, always ensure the trigger button explicitly uses `aria-expanded={stateVariable}` to bind the visual state to the accessibility tree.
