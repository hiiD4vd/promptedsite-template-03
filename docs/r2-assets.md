# R2 media release

- Bucket: `media`
- Project prefix: `templates/seed-lifecycle/releases/630f0ebbe7097b45`
- Public base URL: `https://cdn.promptedsite.com/templates/seed-lifecycle/releases/630f0ebbe7097b45`
- Manifest: `src/config/assets.json`
- Files: 18
- Total bytes: 6,768,136

Structure:

```text
branding/
decoders/basis/
fonts/
textures/ash/
textures/soil/1k/
textures/soil/2k/
textures/trees/
```

Every object was checked by CDN download, SHA-256, Content-Type, and CORS. Runtime URLs are patched reproducibly with `npm run assets:patch`. Upload credentials are read only from an explicit external environment file by `scripts/assets-r2.mjs`; they never enter the browser bundle or Git history.

The organized local administration copy is outside the repository at `/Users/mahezadaud/projects/.promptedsite-assets/template-03`.
