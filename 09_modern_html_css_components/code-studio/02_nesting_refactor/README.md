# 02 - Nesting Refactor

## Goal

Refactor the event card CSS with browser-native nesting while keeping selectors
shallow and understandable.

## Tasks

1. Move the title, metadata, link, and state rules inside `.event-card`.
2. Use `&` for hover and `:focus-within` states.
3. Nest the small-screen media query where it belongs.
4. Do not nest deeper than two selector levels.
5. Compare the final selector specificity with the original selectors.

The appearance should not change during the refactor.
