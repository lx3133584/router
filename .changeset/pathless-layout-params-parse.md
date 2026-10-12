---
'@tanstack/router-core': patch
---

Do not overwrite parent segment node's `params.parse` and priority when pathless layout child routes have no `params.parse`, preserving parent route skip checks during matching.
