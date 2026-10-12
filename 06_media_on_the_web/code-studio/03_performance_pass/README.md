# 03 - Image Performance Pass

## Goal

Add browser hints that improve loading without delaying the page's critical
image or destabilizing layout.

## Tasks

1. Add intrinsic `width` and `height` to all four images.
2. Give only the hero image `fetchpriority="high"`.
3. Do not lazy-load the hero image.
4. Add `loading="lazy"` to the three gallery images below the first viewport.
5. Add `decoding="async"` to non-critical gallery images.
6. Explain each decision in `notes.md`.

## Completion Check

Reload with the Network panel open. Confirm that reserved aspect-ratio space is
visible before images finish and that the hero is requested without waiting for
scroll proximity.
