# biraz-dev.github.io

The front door of **biraz.dev**: a plain page linking to Sojourn, Jig and The Arena.

This repository owns the `biraz.dev` domain (`CNAME`). Every other repository with GitHub Pages on appears beneath it at its own name, for example `biraz.dev/Sojourn/` and `biraz.dev/Jig/`. Those repositories must not set a custom domain or carry a `CNAME` file of their own.

`the-arena/index.html` preserves the original lowercase Arena link by redirecting
to `/The-Arena/`. Both paths use the same origin and browser saves. The redirect
preserves query strings and fragments when JavaScript is enabled; a static link
and a no-script refresh provide a fallback.
