# do-dynamic-pricing

Dedicated inference prototype: **Contract** vs **Dynamic** GPU pricing UI (dashboard shell).

## Public site (GitHub Pages)

**https://digitalocean-udhay.github.io/do-dynamic-pricing/**

### Enable Pages (one time)

1. Repository: [DigitalOcean-Udhay/do-dynamic-pricing](https://github.com/DigitalOcean-Udhay/do-dynamic-pricing)
2. **Settings** → **Pages** → **Build and deployment** → **Source**: **GitHub Actions**
3. **Actions** → open **Deploy do-dynamic-pricing to Pages** → confirm the latest run succeeded (green).  
   If needed, use **Run workflow**.

Source files for the live site live in the [`do-dynamic-pricing/`](./do-dynamic-pricing/) folder; the workflow publishes that folder as the site root.

## Local preview

```bash
cd do-dynamic-pricing && python3 -m http.server 8765
```

Open http://127.0.0.1:8765/ → **Inference Hub → Dedicated inference** → **Deploy Dedicated Inference**.
