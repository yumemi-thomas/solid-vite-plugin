---
'@solidjs/vite-plugin': minor
---

Front ends get a `buildStart(context)` hook, called when a build of an environment starts (each `vite build`, each rebuild of `vite build --watch`, a dev server's start), so a front end that does work once per build starts it again.
