# 03 - Scoped Component: Reference

Scoping proximity lets the nested light component win without long selectors or
`!important`. The dark scope stops before `.unscoped-note`, so that subtree
retains the neutral fallback.
