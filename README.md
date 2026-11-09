# SCHUFI · Underwater Imaging — University of Rostock

Companion website for the poster **"Non-invasive Fish Monitoring in Baltic Sea Marine Protected Areas: Underwater Imaging and Automated Fish Detection"** (Tippani & Fischbach, GFI conference, November 2026).

**Live site:** https://dheeraj9932.github.io/schufi_uni_rostock_imaging/

## What is on the site

- Project motivation: non-invasive fish monitoring in German Baltic Sea MPAs (Adlergrund, Pommersche Bucht–Rönnebank)
- Four research cruises to Adlergrund (RV Alkor · Nov 2025; RV Prince Madog · Apr 2026; RV Fortuna · Jul 2026; RV Prince Madog · Sep 2026) and the ~10,000 images collected
- The camera systems: ROV (Chasing M2), tow camera (Schleppkamera), BRUV300 stereo, static stereo & drop/360° rigs
- The imaging-to-AI pipeline (7 steps) and the challenges (marine snow, turbidity, camouflage, no Baltic benchmark datasets)
- Insights from the literature review, current work, theses and 2027 plans

## How this site is served

Plain static HTML/CSS — no build step. GitHub Pages serves it directly from this repository.

### First-time deployment checklist (do once on GitHub)

1. Push this repo to GitHub: `https://github.com/dheeraj9932/schufi_uni_rostock_imaging`
2. Open **Settings → Pages → Build and deployment → Source: Deploy from a branch**
3. Choose branch **main**, folder **/ (root)** → Save
4. After ~1 minute the site is live at the URL above.

## QR code

Print-ready QR code (points to the live site):
- `images/qr_site.png` (also shown on the page itself)
- `/Conferences/2026_11_GFI/qr_schufi_website_dheeraj9932.github.io.png` (standalone copy for the poster)

## Structure

```
index.html        # single landing page (all sections)
assets/style.css
images/           # compressed photos, maps and the QR code
```
