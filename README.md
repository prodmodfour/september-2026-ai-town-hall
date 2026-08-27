# AI Town Hall — Slidev

[View the public slideshow](https://prodmodfour.github.io/september-2026-ai-town-hall/)

An eight-slide AI town hall presentation built with [Slidev](https://sli.dev/).

## Run locally

```bash
npm install
npm run dev
```

Slidev normally opens <http://localhost:3030>.

## Presentation controls

- Next or previous: arrow keys or `Space`
- Overview: `O`
- Go to slide: `G`
- Full screen: `F`
- Presenter view: <http://localhost:3030/presenter>

## Build and export

```bash
npm run build
npm run export -- --output ai-town-hall.pdf
```

The presentation source is `slides.md`, and the global styling is in `style.css`.

## Deployment

Pushing to `main` automatically builds and deploys the slideshow to GitHub Pages using `.github/workflows/deploy.yml`.
