# Auxilia — website

Marketingsite voor **Auxilia**: AI-automatisering, AI-implementatie en AI-opleiding voor Vlaamse kmo's.

## Bestanden

| Bestand | Wat het is |
|---|---|
| `index.html` | De volledige website (one-pager). Statisch, geen build-stap nodig. |
| `promo.html` | De 40-seconden promofilm. Speelt inline in de hero (`?embed=1`, zonder afspeelbalk) én in de lightbox. |
| `animations.jsx` | Animatie-engine voor de promofilm (geladen door `promo.html`). |
| `logo.html` | Logo-referentie (beeldmerk, lockup, icoonformaten). |
| `og-image.png` | Social-share-afbeelding (1200×630), gerefereerd in de meta-tags. |

## Lokaal bekijken

Open `index.html` niet via `file://` — het inline filmvenster gebruikt een iframe en heeft een webserver nodig. Start een mini-server:

```bash
npx serve .
# of
python3 -m http.server 8000
```

en surf naar `http://localhost:8000`.

## Publiceren via GitHub Pages

1. Maak een nieuwe repository en push deze map:
   ```bash
   git init
   git add .
   git commit -m "Auxilia website"
   git remote add origin git@github.com:<jouw-account>/auxilia-site.git
   git push -u origin main
   ```
2. Ga naar **Settings → Pages**, kies **Deploy from a branch**, branch `main`, map `/ (root)`.
3. De site staat daarna op `https://<jouw-account>.github.io/auxilia-site/`.

## Checklist vóór lancering

- [ ] Eigen domein koppelen en de placeholder-URL's bijwerken in `index.html`: `<link rel="canonical">`, `og:url`, `og:image`, `twitter:image` en de twee `@id`-velden in de JSON-LD (zoek op `www.auxilia.be`).
- [ ] Ondernemingsnummer en btw-nummer invullen in de footer (nu `0xxx.xxx.xxx`).
- [ ] Privacybeleid-pagina toevoegen en linken in de footer (GDPR).
- [ ] `robots.txt` en `sitemap.xml` toevoegen zodra het domein vastligt.
- [ ] LinkedIn-link in de footer naar de echte bedrijfspagina laten wijzen.
- [ ] Overweeg de promofilm als echte `.mp4` te exporteren voor productie — laadt lichter dan de live-animatie (React + Babel in een iframe).

## Technisch

- Pure HTML/CSS met een vleugje vanilla JS — geen frameworks of build-stap voor de site zelf.
- De promofilm gebruikt React (via CDN) + een eigen timeline-engine; alleen geladen binnen `promo.html`.
- Alle animaties respecteren `prefers-reduced-motion`.
- Structured data: `ProfessionalService` + `FAQPage` (JSON-LD in de `<head>`).
