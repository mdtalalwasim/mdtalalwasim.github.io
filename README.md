# Md. Talal Wasim — Portfolio

Modern personal portfolio for [mdtalalwasim.github.io](https://mdtalalwasim.github.io/).

Built with plain **HTML + CSS + JavaScript** — no build step, no frameworks.

## Features

- Modern dark theme with gradient accents + light mode toggle (persisted)
- Animated hero with typing effect, floating tech badges, and glowing orbs
- Scroll-reveal animations and animated stat counters
- Fully responsive (mobile hamburger menu, fluid grids)
- Sections: Home · About · Skills · Services · Projects · Achievements · GitHub Activity · Contact
- Live GitHub stats cards
- Respects `prefers-reduced-motion`

## Structure

```
index.html        — all content
css/style.css     — theme, layout, animations
js/script.js      — typing effect, theme toggle, scroll spy, counters
images/           — profile photo + resume (copy from old repo, see below)
```

## Before deploying

Copy these two files from the old repository into an `images/` folder here
(the site links to them):

- `images/Md_Talal_Wasim.jpeg` — profile photo (falls back to your GitHub avatar if missing)
- `images/Md_Talal_Wasim.pdf` — resume ("Download CV" button)

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Redesign portfolio with modern look"
git branch -M main
git remote add origin https://github.com/mdtalalwasim/mdtalalwasim.github.io.git
git push -f origin main   # -f replaces the old site
```

The site goes live at https://mdtalalwasim.github.io/ within a minute or two.

> Tip: before force-pushing, keep a backup of the old site with
> `git clone https://github.com/mdtalalwasim/mdtalalwasim.github.io old-site-backup`

## Preview locally

Just open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

and visit http://localhost:8000
