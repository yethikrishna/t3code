```markdown
# t3code Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches the core development patterns and conventions used in the `t3code` TypeScript repository. You'll learn about file naming, import/export styles, and how to write and organize tests. The guide also provides suggested commands for common workflows, making it easier to maintain consistency and efficiency in your development process.

## Coding Conventions

### File Naming
- **PascalCase** is used for file names.
  - **Example:**  
    `MyComponent.ts`  
    `UserService.ts`

### Import Style
- **Relative imports** are preferred.
  - **Example:**  
    ```typescript
    import { UserService } from './UserService';
    ```

### Export Style
- Both **named** and **default exports** are used, depending on context.
  - **Named Export Example:**  
    ```typescript
    export function calculateSum(a: number, b: number): number {
      return a + b;
    }
    ```
  - **Default Export Example:**  
    ```typescript
    const UserService = { /* ... */ };
    export default UserService;
    ```

### Commit Patterns
- **Freeform commit messages** with no strict prefixing.
- **Average length:** ~59 characters.

## Workflows

### Adding a New Module
**Trigger:** When you need to add a new feature or utility.
**Command:** `/add-module`

1. Create a new file in PascalCase (e.g., `NewFeature.ts`).
2. Use relative imports for dependencies.
3. Export the main functionality (named or default as appropriate).
4. Add corresponding test file: `NewFeature.test.ts`.

### Refactoring Code
**Trigger:** When improving or restructuring existing code.
**Command:** `/refactor`

1. Identify code to refactor.
2. Rename files if needed, using PascalCase.
3. Update relative imports accordingly.
4. Ensure exports remain consistent.
5. Update or add tests to cover changes.

### Writing Tests
**Trigger:** When adding or updating features.
**Command:** `/write-test`

1. Create a test file named `FeatureName.test.ts` in the same directory as the module.
2. Follow the existing test structure (see Testing Patterns below).
3. Run tests to verify correctness.

## Testing Patterns

- **File Pattern:** Test files are named with the `.test.` infix, e.g., `MyComponent.test.ts`.
- **Framework:** Not explicitly detected; use standard TypeScript test patterns.
- **Example:**
  ```typescript
  import { calculateSum } from './CalculateSum';

  describe('calculateSum', () => {
    it('adds two numbers', () => {
      expect(calculateSum(2, 3)).toBe(5);
    });
  });
  ```

## Commands

| Command        | Purpose                                   |
|----------------|-------------------------------------------|
| /add-module    | Scaffold a new module with tests          |
| /refactor      | Refactor code and update naming/imports   |
| /write-test    | Create or update a test for a module      |
```
