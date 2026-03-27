# do-dynamic-pricing

Dedicated inference prototype: **Contract** vs **Dynamic** GPU pricing UI (dashboard shell).

## Public site (GitHub Pages)

**https://digitalocean-udhay.github.io/do-dynamic-pricing/**

### Fix a 404 (pick one)

#### Option A — Fastest (no workflow): publish from `main`

Your repo already has `index.html` and `styles.css` at the **repository root**.

1. Open [repo Settings → Pages](https://github.com/Digitalocean-Udhay/do-dynamic-pricing/settings/pages).
2. **Build and deployment** → **Source**: **Deploy from a branch** (not “GitHub Actions”).
3. **Branch**: `main`, **Folder**: `/ (root)` → **Save**.
4. Wait 1–2 minutes, then refresh the site URL above.

#### Option B — Publish from `do-dynamic-pricing/` via automation

1. Ensure **Actions** are allowed: **Settings → Actions → General** (read/write for workflows).
2. Push to `main` (or **Actions → Deploy site to gh-pages → Run workflow**).
3. When the workflow is green, **Settings → Pages** → **Source**: **Deploy from a branch** → **Branch**: `gh-pages`, **Folder**: `/ (root)` → **Save**.

The workflow copies [`do-dynamic-pricing/`](./do-dynamic-pricing/) onto the `gh-pages` branch.

## Local preview

```bash
cd do-dynamic-pricing && python3 -m http.server 8765
```

Open http://127.0.0.1:8765/ → **Inference Hub → Dedicated inference** → **Deploy Dedicated Inference**.
