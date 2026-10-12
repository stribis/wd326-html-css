# Framework Decisions

| Scenario | Choice | Strongest reason | Cost or risk |
| --- | --- | --- | --- |
| Internal admin dashboard needed in three days | Bootstrap | Ready-made layout, forms, and common components | Generic result and override debt |
| Art-direction-heavy portfolio with a unique visual identity | Vanilla CSS | Full control with little framework surface | Team must define its own conventions |
| Large product with an existing design-token system | Tailwind | Theme tokens and constrained utilities can expose the system | Long class lists and upgrade governance |
| One-page event invitation maintained by one designer | Vanilla CSS | The scope is too small to justify a dependency | Reuse is limited if the site grows |
| Team wants accessible modal behavior and data fetching | Not a CSS framework problem | Behavior and data architecture require HTML and JavaScript decisions | Assuming CSS solves application architecture |
| Prototype that may be thrown away after user testing | Bootstrap | Fast assembly with recognizable patterns | Prototype styling may accidentally ship |
| Legacy Bootstrap site receiving one new section | Bootstrap | Consistency and existing dependency beat novelty | Existing version may constrain new patterns |
| Component library shared across several applications | Tailwind | Utilities and tokens can support a governed design API | Consumers need shared build configuration |

## Final Question

Team experience, browser support, existing dependencies, and the expected life
of the project could change several choices.
