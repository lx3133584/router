---
'@tanstack/start-plugin-core': patch
---

Preserve binary content when prerendering non-text server routes (such as generated images, icons, and documents) instead of decoding response bytes as UTF-8.
