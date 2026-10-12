# 03 - Responsible Iframe Pass

## Goal

Embed a supplied local page without sacrificing naming, layout stability, or
unnecessary permissions.

## Tasks

1. Give the iframe a useful `title` describing its content.
2. Add `loading="lazy"` because the embed is below the introduction.
3. Add the strictest sandbox that still supports this static embed.
4. Style `.embed-frame` with a stable `aspect-ratio`.
5. Make the iframe fill the wrapper without fixed pixel positioning.
6. Keep the fallback link to the standalone content.

## Completion Check

Inspect the accessibility tree for the iframe name and verify that the page does
not jump as the embed loads.
