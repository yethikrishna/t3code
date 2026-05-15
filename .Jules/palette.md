## 2026-05-15 - Added missing aria-label for Revert Message button
**Learning:** Icon-only action buttons (e.g., using lucide-react icons inside a Button component) in toolbars like the MessagesTimeline sometimes rely on only a `title` attribute which is insufficient for screen readers.
**Action:** Always verify icon-only buttons include an `aria-label` alongside `title` for full accessibility support, especially in dense UI regions like message timelines.
