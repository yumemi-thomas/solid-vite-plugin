---
'@solidjs/vite-plugin': minor
---

Front ends get `context.resolve(source, importer?)`, which resolves an import as Vite would for the environment (through every plugin's `resolveId`, so aliases and tsconfig paths included), so a front end that reads other modules' imports names them as the bundler will.
