# ingersoll.dev

Source for [ingersoll.dev](https://ingersoll.dev), a small directory of frontend projects and browser-based utilities by Tyler Ingersoll.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No build step, no framework, no dependencies. Deploys directly from the repo.

## Structure

```
index.html   — single-page site
style.css    — all styles, CSS custom properties
.gitignore
```

## Design

Shares the color palette and typography of [tyleringersoll.com](https://tyleringersoll.com) — Roboto Condensed, dark base (`#151a1e`), cyan accent (`#00b7ff`). Intentionally restrained: no gradients, no animations beyond the mobile nav transition.

## Features

- Sticky frosted-glass header (Safari iOS fix: blur on `::before`, not the sticky element)
- Slide-out mobile nav with animated hamburger → X, backdrop blur, focus trap, and Escape/tap-outside close
- `scroll-padding-top` dynamically matched to actual header height on load and resize
- External link `↗` indicator via CSS `::after`, suppressed on buttons and nav
- `prefers-reduced-motion` respected throughout

## Related

- [tyleringersoll.com](https://tyleringersoll.com) — frontend architecture, engineering resume, and music history
- [tyleringersolldrums.com](https://tyleringersolldrums.com) — drumming background, studio details, videos, and session information
- [letterlock.ingersoll.dev](https://letterlock.ingersoll.dev) — word game project
