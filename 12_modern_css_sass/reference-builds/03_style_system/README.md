# Style System Lab: Reference Build

This solution replaces legacy `@import` rules with a small module graph. Sass
handles source organization, arithmetic, mixins, and status generation. CSS
custom properties carry theme values that must still change in the browser.

## Run the project

```bash
npm install
npm run sass:build
```

Open `index.html` with a local development server. The Sass compiler writes to `css/styles.css`.

## Module graph

```text
main.scss
|-- @use settings as s
|-- @use tools as t
`-- @use components
    |-- buttons
    `-- status
```

Edit files in `scss/`, then rebuild `css/styles.css`. The compiled file is an
artifact and should not be edited directly.
