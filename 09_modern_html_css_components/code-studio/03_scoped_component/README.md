# 03 - Scope a Component

## Goal

Style light and dark theme shells with `@scope`, then observe which scope wins
when one shell is nested inside the other.

## Tasks

1. Add one scope rooted at `.theme-light` and one at `.theme-dark`.
2. Style `:scope`, headings, and links inside each scope.
3. Keep the nested light card inside the dark shell.
4. Add a scope limit so card rules stop before `.unscoped-note`.
5. Explain why the nested card uses the light theme.

Add a simple unscoped fallback before the scoped rules.
