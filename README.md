# Live Editor Pro Redirect

A lightweight full-screen redirect page that embeds the **Live Editor Pro** app
([dhiraj9619.github.io/LiveEditorPro](https://dhiraj9619.github.io/LiveEditorPro/))
in a borderless iframe, so the editor can be opened under this repository's own
GitHub Pages URL.

## Features

- Full-viewport iframe with no scrollbars, borders, or white flash (black background)
- `allowfullscreen` enabled so the embedded editor can use fullscreen mode
- Responsive viewport meta tag — works on desktop and mobile browsers
- Zero dependencies, zero build step — a single `index.html` file

## Tech Stack

- Plain HTML + CSS (inline styles)
- Hosted via GitHub Pages (no backend)

## Quick Start

Open the live page:

**https://girishlade111.github.io/Live-Editor-Pro-Redirect/**

Or serve it locally — any static file server works:

```bash
npx serve .
```

## Project Structure

```
.
├── index.html    # Full-screen iframe redirect page
├── LICENSE      # MIT License
└── README.md
```

## Deploy Notes

This is a static single-page redirect with no build step. It is served via
GitHub Pages from the `main` branch root (`/`). The iframe points at
`https://dhiraj9619.github.io/LiveEditorPro/` — if that upstream app ever moves
or is taken down, update the `src` attribute in `index.html` and push.

## License

MIT

---

Built by Girish Lade — https://ladestack.in
