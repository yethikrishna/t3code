## 2025-01-20 - Add aria-expanded to collapsible components

**Learning:** Discovered that many collapsible elements (like directories in ChangedFilesTree) are missing `aria-expanded` attributes which makes it impossible for screen readers to know their state.
**Action:** Add `aria-expanded={isExpanded}` to collapsible elements to improve accessibility.
