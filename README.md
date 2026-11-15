# Web-trilingua

Landing page for [Trilingua](https://github.com/aladewealth/Trilingual-), a 70M-parameter English / Spanish / French language model trained from scratch on free Kaggle GPUs. Weights: [huggingface.co/aladewealth/trilingua](https://huggingface.co/aladewealth/trilingua).

A static site: plain HTML and CSS, no build step, no dependencies.

```
index.html               the page
hark.css, hark-hero.css  styles
hark.js                  small UI script
trilingua_compare.png    model comparison chart
favicon.svg              logo mark
```

## Run locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy

**Vercel:** New Project → import this repo → Framework preset "Other", no build command, output directory `./` → Deploy.

**Netlify:** Add new site → import from GitHub → leave build command empty, publish directory `.` → Deploy.

**GitHub Pages:** Settings → Pages → Source "Deploy from a branch" → `main` / root → Save. Live at `https://aladewealth.github.io/Web-trilingua/`.

---

built by [@aladewealth_](https://x.com/AladeWealth_)
