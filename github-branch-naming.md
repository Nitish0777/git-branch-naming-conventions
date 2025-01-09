# GitHub Branch Naming Conventions

## General Principles

Branch names should be:
- Descriptive and meaningful
- Written in lowercase
- Use hyphens to separate words
- Start with a category/type prefix
- Include the ticket/issue number when applicable

## Common Prefixes

### Main Categories
- `feature/` - New features or enhancements
- `bugfix/` - Bug fixes
- `hotfix/` - Urgent fixes for production issues
- `release/` - Release preparation branches
- `chore/` - Maintenance tasks, dependency updates
- `docs/` - Documentation updates
- `test/` - Test-related changes
- `refactor/` - Code refactoring
- `style/` - Code style/formatting changes

## Naming Pattern

```
<type>/<ticket-number>-<brief-description>
```

## Examples

Good branch names:
- `feature/user-authentication`
- `feature/JIRA-123-add-login-page`
- `bugfix/broken-footer-links`
- `hotfix/security-vulnerability`
- `release/v2.1.0`
- `chore/update-dependencies`
- `docs/api-documentation`
- `refactor/payment-processing`

Poor branch names (avoid these):
- `new-stuff` (too vague)
- `bug` (not descriptive)
- `johns-feature` (person-specific)
- `Feature_User_Login` (incorrect casing/separators)
- `quick-fix` (not descriptive enough)

## Additional Guidelines

1. Keep names concise but descriptive
   - Aim for 2-4 words in the description
   - Maximum 50 characters total

2. Use ticket numbers when available
   - Place them after the type prefix
   - Use the format specified by your project management tool

3. Avoid personal names
   - Branch names should describe what the branch does
   - Don't use developer names like `john/feature`

4. Use meaningful verbs
   - `add-`, `update-`, `fix-`, `remove-`, etc.
   - Example: `feature/add-password-reset`

5. When working on specific components
   - Include the component name
   - Example: `bugfix/navbar-dropdown-alignment`

Remember to delete branches after they're merged to keep the repository clean and manageable.
