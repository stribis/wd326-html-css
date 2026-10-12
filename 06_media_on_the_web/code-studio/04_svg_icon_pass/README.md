# 04 - SVG Icon Pass

## Goal

Finish inline SVG controls so their graphics scale, inherit color, and expose
the correct accessible names.

## Tasks

1. Add `viewBox="0 0 24 24"` to every icon SVG.
2. Hide decorative icons with `aria-hidden="true"`.
3. Make paths and circles use `currentColor` through CSS.
4. Keep visible text on the download button.
5. Give the icon-only save button an `aria-label`.
6. Name the standalone meaningful SVG with `role="img"` and `aria-labelledby`.
7. Add visible hover and keyboard-focus states.

## Completion Check

Inspect the accessible name of both buttons and the standalone graphic. Change
the controls' text color in DevTools and confirm that their icons follow it.
