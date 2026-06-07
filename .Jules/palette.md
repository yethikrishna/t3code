## 2025-02-02 - Tree Component Accessibility
**Learning:** Adding screen reader support for deeply nested custom tree view interactions (like file explorers) significantly improves usability. Both expanding states and button intentions need distinct context.
**Action:** Always ensure custom tree-node buttons (for both expanding branches and selecting leaf nodes) announce their state (`aria-expanded`) and exact target intent (`aria-label`) dynamically based on node data.
