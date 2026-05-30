# Slow Input

Root page for [slowinput.org](https://slowinput.org).

This is just the front door. A tiny static directory for a few projects:

* [Faro](https://faro.slowinput.org)
* [Havannah](https://havannah.slowinput.org)
* [Breakthrough](https://breakthrough.slowinput.org)
* [Randos](https://randos.slowinput.org)
* [Hours in Spanish](https://hoursinspanish.com)

No framework. No build step. No spiritual journey through a JavaScript toolchain. It is HTML, CSS, and the logo.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy

This is meant for Cloudflare Pages.

Use:

```text
Framework preset: None
Build command: leave blank
Build output directory: .
```

The files Cloudflare needs are already in the repo root.
