# decentralizedlearning.github.io

Source of the website for [dEngine](https://github.com/DecentralizedLearning/dEngine), a decentralized learning framework.

Live at **https://decentralizedlearning.github.io/**

Plain static HTML/CSS — no build step. GitHub Pages serves the `main` branch root.

```
├── index.html            # homepage
├── 404.html              # not-found page
├── assets/css/style.css  # styles
├── assets/img/og-image.png  # social preview (1200×630)
├── logo.png              # logo + favicon (add your own)
├── robots.txt, sitemap.xml, site.webmanifest
└── .nojekyll             # skip Jekyll processing
```

Preview locally: `python3 -m http.server` then open http://localhost:8000.
