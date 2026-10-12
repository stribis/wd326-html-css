# 01 - Relative Paths

## Goal

Repair links and image paths by treating each HTML file's own folder as the
starting point.

## Project Tree

```text
01_relative_paths/
|-- index.html
|-- css/
|   `-- styles.css
|-- images/
|   `-- cat.jpg
`-- pages/
    `-- about.html
```

## Tasks

1. Link `index.html` to `pages/about.html`.
2. Load `images/cat.jpg` on `index.html`.
3. Load the same image from `pages/about.html`.
4. Link `pages/about.html` back to the homepage.
5. Load `css/styles.css` from both HTML pages.

Do not move or duplicate any files. Use only relative paths.
