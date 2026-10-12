# 05 - Theme Token Pass

## Goal

Create a light and dark token system, then derive related component colors
without maintaining two separate stylesheets.

## Tasks

1. Add `color-scheme: light dark` to `:root` and the matching metadata to HTML.
2. Keep the existing static colors as fallbacks.
3. Use `light-dark()` for surface, text, border, brand, and accent tokens.
4. Use `color-mix(in oklch, ...)` for the card tint and button hover color.
5. Check text contrast in both operating-system color schemes.

Do not use a class or JavaScript theme switcher in this exercise.
