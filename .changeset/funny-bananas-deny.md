---
'@lit-labs/ssr': patch
---

`LitElementRenderer` now uses `renderValue` from `render-lit-html.js`, removing a circular dependency.
