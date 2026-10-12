# Performance Notes - Example

- Hero priority decision: It is the likely largest-contentful image in the first viewport, so it receives the single high-priority hint.
- Why the hero is not lazy-loaded: Delaying discovery can delay meaningful rendering and Largest Contentful Paint.
- Why dimensions matter: They give the browser an aspect ratio before the file arrives, reducing layout shift.
- Why gallery images may be lazy-loaded: They begin below the first viewport and do not help the initial render.
- What async decoding changes: The browser may decode the non-critical image without blocking other main-thread presentation work.
