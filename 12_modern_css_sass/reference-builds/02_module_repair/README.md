# 02 - Sass Module Repair: Reference

`settings` and `components` are small public entry points. The button states its
dependency with `@use`, and every token reference carries the `settings.`
namespace so its origin remains obvious.
