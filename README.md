# erickirkresearch.github.io — Starter Portfolio

This repository holds a minimal static portfolio for Erick Kirk. It uses plain HTML/CSS so you can edit files directly.

Contents
- index.html — home
- about.html, projects.html, contact.html — simple pages
- css/styles.css — shared styling

Deploy to GitHub Pages (user site)
1. Create a repository on GitHub named: `erickirkresearch.github.io`
2. Push these files to the repository root on the `main` branch.

Common commands (if starting locally)
```bash
# create repo locally (or clone your repo)
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
# replace URL below with your repo URL
git remote add origin https://github.com/erickirkresearch/erickirkresearch.github.io.git
git push -u origin main
```

After pushing, visit: `https://erickirkresearch.github.io` (wait a minute for Pages to publish). To change the domain, add a `CNAME` file with your domain and update DNS.

Customizations
- Replace text, add images into an `images/` or `assets/` folder.
- Add analytics or contact forms (note: JS forms may need third-party form service).
- If you prefer a static site generator (Jekyll/Hugo/Vite), I can add a workflow to build & deploy.

License
- Copy and modify freely.
