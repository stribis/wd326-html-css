# 01 - Semantic Rewrite

## Goal

Turn generic containers into a document whose structure communicates meaning to
browsers, search engines, and assistive technology.

## Tasks

1. Replace weak `div` containers with suitable page landmarks and content
   elements.
2. Turn the visual headline into the correct heading element.
3. Build a logical heading hierarchy without skipping levels.
4. Replace vague link text with text that makes sense out of context.
5. Add useful alternative text to the informative image.
6. Keep the original content and reading order.

## Completion Check

- The page has one `header`, one `main`, and one `footer` landmark.
- The group of navigation links is identified as navigation.
- The album review can stand on its own as a reusable piece of content.
- The image and its caption are structurally connected.
- The document passes the W3C HTML validator without errors.

## Stretch

Add an accessible name to the navigation and use a `time` element for the
publication date.
