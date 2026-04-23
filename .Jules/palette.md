## 2024-05-18 - Semantic button states for file tree and options
**Learning:** Icon-only interactive tree elements and stateful select option buttons were missing standard semantic ARIA state representations (`aria-expanded`, `aria-pressed`, `aria-label`).
**Action:** Always verify custom component `<button>` implementations include full ARIA representations for their implicit states (especially `aria-expanded` and `aria-pressed`) to ensure proper screen reader communication.
