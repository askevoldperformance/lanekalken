# Lånekalken

Gratis lånekalkulator for det norske markedet. Bygget med ren HTML/CSS/JS – ingen rammeverk, ingen byggsteg.

**Live:** [lånekalken.no](https://lånekalken.no)  
**Hosting:** Vercel (auto-deploy fra main-branch)

---

## Sider

| Fil | URL | Type |
|---|---|---|
| `index.html` | `/` | Generell lånekalkulator |
| `boliglan.html` | `/boliglan.html` | Boliglånskalkulator |
| `billan.html` | `/billan.html` | Billånskalkulator |
| `forbrukslan.html` | `/forbrukslan.html` | Forbrukslånskalkulator |
| `kredittkort.html` | `/kredittkort.html` | Kredittkortkalkulator |
| `sparing.html` | `/sparing.html` | Sparekalkulator |
| `guider.html` | `/guider.html` | Samleside for artikler |
| `refinansiering.html` | `/refinansiering.html` | Guide: Refinansiering |
| `omstartslan.html` | `/omstartslan.html` | Guide: Omstartslån |
| `inkasso.html` | `/inkasso.html` | Guide: Inkasso |
| `kredittsjekk.html` | `/kredittsjekk.html` | Guide: Kredittsjekk |

---

## Monetisering

- **AdSense:** Bytt ut `.ad-box`-elementene med ekte AdSense-kode når domenet er godkjent
- **Affiliate:** Lenker i `.affiliate-btn` oppdateres med affiliate-tracking-URL fra Adtraction / Tradedoubler

---

## Oppdatere innhold

Rediger direkte i HTML-filen. Push til main → Vercel deployer automatisk innen ~30 sekunder.

---

## Stack

- Ren HTML/CSS/JS
- [Chart.js 4.4](https://www.chartjs.org/) – grafer
- [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) – font
- Vercel – hosting
- Domeneshop – domene
