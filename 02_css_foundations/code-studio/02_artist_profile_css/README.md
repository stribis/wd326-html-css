# 02 - Artist Profile CSS

## Goal

Turn the semantic Nova Vale profile into a readable visual design while
practicing selector strategy, the cascade, modern units, and UI states.

## Rules

- For the first 20 minutes, edit only `styles.css`.
- Do not use inline styles or `!important`.
- Keep the existing HTML semantics and content.

## Tasks

1. Add a reset with `box-sizing: border-box`.
2. Establish readable body typography, colors, and spacing.
3. Use cascade layers for reset, base, components, and states.
4. Use reusable classes for repeated visual patterns.
5. Use `:where()` for a low-specificity base link style.
6. Use an attribute selector for external links.
7. Use `:has(img)` on a card containing an image.
8. Use `clamp()` for the artist name.
9. Use `svh` or `dvh` to give the hero meaningful height.
10. Add visible hover and `:focus-visible` states.

## Completion Check

Explain one cascade conflict in DevTools, including the selectors and the rule
that wins. Then test every link with the keyboard and zoom the page to 200%.
