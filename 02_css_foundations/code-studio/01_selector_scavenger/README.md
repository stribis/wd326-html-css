# 01 - Selector Scavenger Hunt

## Goal

Complete ten styling targets without editing `index.html`. Choose the selector
that describes each target instead of adding a new class for every rule.

## Tasks

1. Style the page title using a type selector.
2. Style every card using the shared `.card` class.
3. Make only the featured card visually stronger.
4. Style external links that open in a new tab.
5. Style direct list items in the main navigation.
6. Style the first paragraph immediately after each article heading.
7. Style cards that contain an image with `:has()`.
8. Give empty status badges replacement text with `:empty` and `::before`.
9. Add a visible keyboard focus state with `:focus-visible`.
10. Use `:where()` for a low-specificity base link rule.

## Rules

- Edit only `styles.css`.
- Keep all focus indicators visible.
- Do not use inline styles or `!important`.
- Make each target visibly testable in the browser.

## Completion Check

Use DevTools to select one matching element for every rule. Confirm that the
base `:where()` rule is easy to override and that Tab navigation shows focus.
