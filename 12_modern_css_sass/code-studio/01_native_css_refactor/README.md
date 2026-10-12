# 01 - Native CSS Refactor

## Goal

Refactor a working but repetitive stylesheet using modern browser-native CSS.

## Tasks

1. Separate reset, theme, component, and utility rules with named cascade layers.
2. Replace repeated colors and spacing with semantic custom properties.
3. Nest the card's child and state rules no more than two levels deep.
4. Replace the fixed heading size and card padding with sensible `clamp()` values.
5. Use component variables so the warning card only overrides tokens.
6. Confirm the final stylesheet does not require Sass or a build step.

Keep the visual result recognizable while improving the architecture.
