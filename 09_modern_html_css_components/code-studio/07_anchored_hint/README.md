# 07 - Anchored Hint

## Goal

Place a popover hint next to its form-field help button while preserving a
usable fixed-position fallback.

## Tasks

1. Give the help button an explicit anchor name.
2. Give the popover a baseline position outside `@supports`.
3. Test `position-area: right` and connect the popover to the anchor.
4. Add a placement fallback with `position-try-fallbacks`.
5. Test long content, 200% zoom, and a narrow viewport.
