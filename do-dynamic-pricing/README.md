# do-dynamic-pricing

Prototype UI for **Dedicated inference** with **Contract** vs **Dynamic** GPU pricing (DigitalOcean-style dashboard shell).

## Live site (GitHub Pages)

After the workflow runs, the public URL is:

**`https://cwuxiaoto.github.io/IA-Nav-Cursor---existing-user/`**

(Replace with your GitHub username/repo if you fork or rename the repository.)

### One-time setup in GitHub

1. Open the repository on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment** → **Source**, choose **GitHub Actions** (not “Deploy from a branch”).
3. Push to `main` (or merge a PR); the **Deploy do-dynamic-pricing to Pages** workflow publishes the contents of this folder.

## Local preview

From the repository root:

```bash
cd do-dynamic-pricing && python3 -m http.server 8765
```

Open http://127.0.0.1:8765/ — then use **Inference Hub → Dedicated inference** → **Deploy Dedicated Inference**.
