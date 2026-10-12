# Responsive Image Answers

- Resolution switching: The content and crop stay the same while the browser chooses an efficiently sized file.
- Art direction: The author deliberately chooses a different crop or composition at a media condition.
- Why the `img` inside `picture` still matters: It provides the fallback, dimensions, alternative text, and the image element that is rendered.
- Why the CSS background starts with a color and normal URL: The color remains if no image loads, and the normal URL works before the enhanced `image-set()` declaration is understood.
