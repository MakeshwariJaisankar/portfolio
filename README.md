# My Portfolio

A responsive portfolio built with HTML, CSS and Bootstrap 5.

## Customize

1. Open `index.html` and replace "Your Name", the about text, skills, and project cards.
2. Put your photo and project screenshots in an `images/` folder and update the `src` paths.
3. Update the GitHub / LinkedIn / email links in the Contact section.
4. For the contact form: sign up free at https://formspree.io, create a form, and replace `YOUR_FORM_ID` in `index.html`.

Preview locally by double-clicking `index.html` (or use the VS Code "Live Server" extension).

## Push to GitHub

1. Create a new empty repository on https://github.com/new (e.g. `portfolio`). Do not add a README there.
2. In your project folder, run:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

## Deploy on Vercel

1. Go to https://vercel.com and sign up with your GitHub account.
2. Click **Add New → Project** and import your `portfolio` repository.
3. Settings: Framework Preset = **Other**; leave Build Command and Output Directory empty (it's a static site).
4. Click **Deploy**. You get a live URL like `https://portfolio-xxxx.vercel.app`.

Every time you `git push` to `main`, Vercel redeploys automatically.

## Update later

```bash
git add .
git commit -m "Update projects"
git push
```
