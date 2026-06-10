[![Deploy to GitHub Pages](https://github.com/ulfurloyd/phoenyxlab.xyz/actions/workflows/deploy.yaml/badge.svg)](https://github.com/ulfurloyd/phoenyxlab.xyz/actions/workflows/deploy.yaml)

personal website built with **astro**.

contains information about my projects, homelab workflow,
and the tools I use daily.

## overview
[phoenyxlab.xyz](https://phoenyxlab.xyz) is a minimal portfolio website
with a focus on readibility and simplicity.

it serves as a central place for:

- projects
- current work and interests
- software and hardware I use
- contact info

## structure

```
src/
├── pages/
├── content/
│   └── projects/
├── components/
├── layouts/
└── styles/
```

## development

```
npm install
npm run dev
```

## build

```
npm run build
```

generated files are written to `dist/`

## deployment

the site is deployed to GitHub Pages through
GitHub Actions whenever changes are pushed to
the `main` branch.

