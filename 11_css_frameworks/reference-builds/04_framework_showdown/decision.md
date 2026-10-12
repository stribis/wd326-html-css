# Framework Decision

- Project choice: A short-lived event prototype built by a mixed-experience team.
- Framework choice: Bootstrap.
- What became faster? Grid, equal-height cards, form sizing, and familiar buttons.
- What became awkward? The desired visual identity required custom variables and utility combinations.
- How did customization work? A small custom stylesheet changed Bootstrap component variables and project colors.
- What accessibility work remained yours? Semantics, labels, alternative text, focus order, content, contrast, and testing.
- What production setup would replace the classroom CDN? Install a locked npm version and import only required CSS and JavaScript.
- Largest maintenance risk: Accumulating one-off overrides instead of defining a deliberate theme.
- Final recommendation in one sentence: Use Bootstrap for this prototype because delivery speed and team familiarity outweigh the limited custom design needs.
