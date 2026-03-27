# do-dynamic-pricing (site root)

This directory is what GitHub Pages publishes as the **website root**.

## Live URL

**https://digitalocean-udhay.github.io/do-dynamic-pricing/**

If you see **404**: in repo **Settings → Pages**, use **Deploy from a branch** → `main` + **/ (root)** (repo root has `index.html`), or run the **Deploy site to gh-pages** workflow and set branch **`gh-pages`** + **/ (root)**.

## Local preview

```bash
cd do-dynamic-pricing && python3 -m http.server 8765
```

Open http://127.0.0.1:8765/ — then **Inference Hub → Dedicated inference** → **Deploy Dedicated Inference**.
