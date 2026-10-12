# 05 - Icon Button States

## Goal

Build understandable SVG controls for sighted, keyboard, and screen-reader users.

## Tasks

1. Style the text-and-icon download link as a clear button.
2. Style the icon-only button without removing its `aria-label`.
3. Make SVGs inherit the control's text color with `currentColor`.
4. Add distinct base, hover, active, and `:focus-visible` states.
5. Keep each pointer target at least `44px` in both dimensions.
6. Verify that decorative SVGs are hidden from assistive technology.

## Completion Check

Tab to both controls, inspect their accessible names, and verify that state
changes do not cause the controls to resize.
