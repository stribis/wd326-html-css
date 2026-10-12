# 01 - Feature Support Plan

## Goal

Position a help popover near its trigger in supporting browsers while keeping a
readable fixed-position fallback everywhere else.

## Tasks

1. Keep the fallback rules outside any feature query.
2. Test support with `@supports (position-area: top)`.
3. Inside the query, connect the popover to `--help-trigger` and place it above
   the button.
4. Complete `support-plan.md` before checking the reference build.

## Completion Check

The help content can open, close, receive focus, and remain readable with the
entire `@supports` block disabled.
