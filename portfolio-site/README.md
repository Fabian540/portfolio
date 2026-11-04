# Lit Creatives – Photography Portfolio

A static site: `index.html` plus the `photos/` folder. No build step.

## Put it on GitHub
1. Create a new repository on github.com (for example `photography-portfolio`).
2. Upload everything in this folder (`index.html`, `photos/`, `README.md`), or run:
   git init && git add . && git commit -m "Photography portfolio" && git branch -M main
   git remote add origin https://github.com/Fabian540/photography-portfolio.git && git push -u origin main

## Launch on Vercel
1. Go to vercel.com, sign in with GitHub and click **Add New → Project**.
2. Import the repository.
3. Leave Framework Preset as **Other**, leave Build Command and Output Directory empty, then click **Deploy**.

## Editing later
- Add photos: put the file in `photos/` and add a line to the `PHOTOS` list in `index.html` with its `src`, `cat` and `title`.
- New category: add its name to the `CATS` list.
- Contact details: search `index.html` for `fabinyams@gmail.com` and `0751`.
