# Habibi · حبيبي

**Bilingual Type-Design — A study on harmonizing Latin and Arabic typefaces.**
Bachelor project by **Mathias Lauter**.

A single-page, bilingual (DE/EN) website documenting the *Habibi* project: a research
path toward a shared voice for Latin and Arabic letterforms, born out of encounters with
people seeking asylum in German-language courses in Krems, Austria (2015).

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)
Push this folder to a repository, then enable **Settings → Pages → Deploy from branch → `main` / root**.
The site is fully static (HTML/CSS/vanilla JS, fonts from Google Fonts) — no build step.

## Structure
- `index.html` — the whole site (styles and script inline)
- `assets/` — images rendered from the printed catalogue
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Credits
Design, typeface & photography © Mathias Lauter.
