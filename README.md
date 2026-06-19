# Andre Walker — Personal Brand Site

A personal brand website for Andre Walker — Enterprise IT leader, founder of The Good Barber (acquired), founder of Walkers Software Development, Car Rentals of Atlanta, and Stocks for the Culture.

🌐 **Live:** [your-username.github.io/andre-walker-brand](https://your-username.github.io/andre-walker-brand) *(update after deploying)*

---

## About

Single-file HTML site (`index.html`) — fully self-contained, no external dependencies except Google Fonts. All images are base64-embedded for portability. Built with vanilla HTML, CSS, and JavaScript.

**Sections:**
- Hero — statement opener (Tesla X + McLaren 570S)
- Dossier — personal portrait & bio
- Metrics Band — $4M+ savings · 40%+ error reduction · 2 exits · team of 7
- Career — full Fortune 500 timeline (Stryten · UPS · Home Depot · Georgia Pacific)
- Tech Stack
- The Work — Walkers Software Dev · Stocks for the Culture · Car Rentals of Atlanta
- Collection — 5 cars & 5 watches
- Experiences — AMAVI, Sevruga, Delaire Graff, Louis Vuitton
- Atlas — 8 verified travel destinations + Hotels.com stats
- Community — 16K Instagram · 117+ Discord · Stocktwits since 2016
- Inquiry — contact

---

## Design System

- **Fonts:** Fraunces (serif/italic accents), Inter (body), JetBrains Mono (data/labels)
- **Palette:** Black bg (`#08070a`) · cream ink (`#d4d0c8`) · gold accent (`#d4af5a`)
- **Aesthetic:** Editorial / magazine — minimal frames, photo-driven, cinematic photo breaks

---

## Deploy to GitHub Pages

The site is a single file — `index.html` — so deployment is trivial.

### One-time setup

```bash
# In an empty folder
git init
git add .
git commit -m "Initial commit"
git branch -M main

# Replace YOUR-USERNAME with your GitHub username
git remote add origin https://github.com/YOUR-USERNAME/andre-walker-brand.git
git push -u origin main
```

### Enable GitHub Pages

1. Go to your repo on GitHub
2. **Settings** → **Pages**
3. Under "Source," select **Deploy from a branch**
4. Choose `main` branch, `/ (root)` folder
5. Click **Save**
6. Your site goes live at `https://YOUR-USERNAME.github.io/andre-walker-brand/` within ~1 minute

### Custom domain (optional)

If you own a domain (e.g. `andrewalker.com`):
1. In repo Settings → Pages, add the custom domain
2. In your DNS provider, add an `ALIAS` or `CNAME` record pointing to `YOUR-USERNAME.github.io`
3. GitHub will issue a free HTTPS cert automatically

---

## Updating Content

Open `index.html` in any editor. All content, styling, and image data lives in this one file. Search for the section you want to edit:

- `<section id="dossier">` — about/bio
- `<section id="career">` — career timeline
- `<section id="collection">` — cars and watches
- `<section id="experiences">` — restaurants and events
- `<section id="atlas">` — travel destinations
- `<section id="inquiry">` — contact section

---

## Tech Notes

- **File size:** ~920KB (mostly base64-encoded images)
- **Browser support:** Modern evergreen browsers (Chrome, Safari, Firefox, Edge)
- **Mobile responsive:** Yes — breakpoints at 1100px, 900px, 500px
- **External requests:** Google Fonts CSS only

---

## Credits

Built by [Walkers Software Development](http://walkerssoftware.com).

© 2026 Andre Walker · Mableton, Georgia
