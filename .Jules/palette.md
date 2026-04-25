## 2024-03-24 - [ChangedFilesTree Accessibility]

**Learning:** Tree view components displaying file structures frequently lack adequate screen reader support for directory expansion states and file/directory name declarations. Relying purely on visual layout (indentation and icons) obscures the file structure for non-visual users.
**Action:** Ensure all tree view items (files and directories) include `aria-label`s declaring their names and types, and that expandable items use `aria-expanded` to communicate their current state.
