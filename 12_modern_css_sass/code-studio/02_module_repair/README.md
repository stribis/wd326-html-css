# 02 - Repair a Sass Module System

## Goal

Migrate a small button system from deprecated global `@import` rules to the Sass
module system.

## Run

```bash
npm install
npm run sass:build
```

## Tasks

1. Create a `settings/_index.scss` entry point that forwards `_tokens.scss`.
2. Make the button module load settings with `@use` and a namespace.
3. Create a `components/_index.scss` entry point that forwards the button.
4. Replace both `@import` rules in `main.scss` with `@use`.
5. Make every variable reference explicit, such as `settings.$brand`.
6. Compile with no deprecation warnings and inspect `css/styles.css`.
