# 03 - Artist Profile Polish

## Goal

Polish the flexbox version of the Nova Vale profile with predictable sizing and
carefully scoped positioning.

## Tasks

1. Add the global `border-box` reset.
2. Give sections and cards consistent padding, borders, and maximum widths.
3. Make `.release-card` the containing block for `.release-badge`.
4. Pin the badge to the card's top-right corner with logical inset properties.
5. Make each `.section-title` sticky with a visible background.
6. Keep the fixed back-to-top control clear of content and keyboard accessible.
7. Use small, documented `z-index` values.

## Completion Check

Inspect one card in the DevTools Box Model panel. Then disable the release
card's positioning context and explain why the badge moves.
