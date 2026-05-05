# Resona Labs Website

Static company website for Resona Labs LLC.

## Local preview

Open `index.html` directly in a browser, or run a tiny static server:

```bash
python3 -m http.server 8787
```

Then visit:

```text
http://127.0.0.1:8787
```

## Cloudflare Pages

Recommended settings:

- Framework preset: None
- Build command: leave empty
- Build output directory: `/`
- Root directory: repository root

The logo is expected at `assets/Resona_Icon.png`. The site still renders cleanly if that file is missing.
