# 04 - Design a Tiny Component API

## Goal

Turn three repeated callout variants into one component recipe controlled by a
small custom-property API.

## Tasks

1. Expose custom properties for the accent, background, foreground, and radius.
2. Give every property a fallback in `var()`.
3. Make `.warning` and `.danger` change variables only.
4. Add a new `.success` variant without copying the component recipe.
5. In a CSS comment, name one internal value that should not be public API.

The HTML is complete. Work only in `styles.css`.
