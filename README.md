# The 2026 Swedish Open

A Masters Tournament-inspired tribute site for the XIIIᵗʰ edition of the Swedish Open Golf — Glenn, Espen, Geir & Svein Anders. Trollhättan, April 30 – May 2, 2026.

## Filer

```
swedish-open-2026/
├── index.html         # Hovedsiden
├── images/
│   ├── golfbag.jpg
│   ├── drivingrange.jpg
│   ├── practicegreen.jpg
│   ├── espen.jpg
│   └── garmin.png
└── README.md
```

## Slik publiserer du via GitHub Pages

### Alternativ A — via nettleseren (enkleste vei)

1. Gå til https://github.com/new og lag et nytt repository, f.eks. `swedish-open-2026`. Sett det som **Public**.
2. På den nye repo-siden: trykk **"uploading an existing file"**.
3. Dra alle filene fra `swedish-open-2026/`-mappen inn (både `index.html`, `images/`-mappen og `README.md`). Trykk **Commit changes**.
4. Gå til **Settings → Pages** (i venstre meny).
5. Under "Source": velg **Deploy from a branch**, velg `main` og `/ (root)`. Trykk **Save**.
6. Vent 1–2 minutter. Linken vises øverst på Pages-siden, formen er:
   ```
   https://<brukernavn>.github.io/swedish-open-2026/
   ```

### Alternativ B — via terminal

```bash
cd swedish-open-2026
git init
git add .
git commit -m "Initial commit — The 2026 Swedish Open"
git branch -M main
git remote add origin https://github.com/<brukernavn>/swedish-open-2026.git
git push -u origin main
```

Aktiver deretter GitHub Pages som beskrevet i steg 4–6 over.

## Tips

- Linken kan deles direkte med Espen, Geir og Svein Anders.
- For å oppdatere etter Round 2 og Round 3: rediger `index.html` direkte på GitHub (blyant-ikonet) eller push en ny commit. Endringene er live på 1–2 minutter.
- Egendomene (f.eks. `swedishopen.no`) kan kobles til via Pages-innstillingene.
