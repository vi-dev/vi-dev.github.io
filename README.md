# vi-dev.org

Source for [vi-dev.org](https://vi-dev.org) — the landing page for **vi-dev**,
open-source software cooked by the Vietnamese community.

Built with [Hugo](https://gohugo.io) and the
[Hextra](https://imfing.github.io/hextra/) theme, deployed to GitHub Pages.

## Develop

```sh
hugo mod get -u
hugo server
```

The site is published automatically on every push to `main` by
[`.github/workflows/pages.yml`](.github/workflows/pages.yml).
