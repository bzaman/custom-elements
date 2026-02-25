# custom-elements

A personal collection of vanilla web components I build whenever I get the time. No frameworks, no dependencies — just the platform.

Built on three native web technologies:
- **Custom Elements** — define and register new HTML tags
- **Shadow DOM** — encapsulated styles and markup
- **HTML Templates** — reusable `<template>` + `<slot>` patterns

---

## Packages

| Package | Tag | Description |
|---------|-----|-------------|
| [hero-img](./packages/hero-img) | `<hero-img>` | Hero image component |

---

## Dev

```bash
# install everything
npm install

# run all packages in dev mode
npm run dev

# build all packages
npm run build
```

To work on a single package:

```bash
cd packages/hero-img
npm run dev
```

---

## Structure

```
custom-elements/
└── packages/
    └── hero-img/   ← each component is its own package
```

Each package is standalone — its own `package.json`, built with Vite, publishable independently.

---

## Stack

- Vanilla JS (no frameworks)
- Vite (build + dev server)
- npm workspaces (monorepo)

---

## Contributing

Free to use. If you have something that fits — open a PR, I'm happy to take a look.

---

*By [Badiuzzaman](https://github.com/badiuzzaman)*
