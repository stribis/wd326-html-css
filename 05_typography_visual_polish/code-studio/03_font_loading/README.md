# 03 - Font Loading Decision

## Goal

Implement the same Inter typeface through an online service and a local font
file, then make a reasoned delivery choice.

## Tasks

1. Complete `online.html` with Google Fonts preconnect and stylesheet links.
2. Complete `online.css` with an Inter-first fallback stack.
3. Complete the `@font-face` rule in `self-hosted.css` using the supplied WOFF2.
4. Set `font-display: swap` and the supported variable weight range.
5. Compare requests in the DevTools Network panel.
6. Complete `decision.md` for a real client scenario.

## Comparison Prompts

- Which version sends requests to a third party?
- Who is responsible for licensing and font-file updates?
- Which version gives the project more deployment control?
- What happens when the custom font fails to load?
