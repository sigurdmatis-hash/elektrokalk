# Elektro-kalkulator (NEK-inspirert) – GitHub Pages

Dette repoet inneholder en enkel, moderne kalkulator i **index.html**. Alt kjører i nettleseren (HTML/JS), ingen byggsteg.

## Rask start

1. **Last opp filene** til repoet (rot-mappen):  
   - `index.html` (selve kalkulatoren)  
   - `.nojekyll` (tom fil som sørger for at GitHub Pages ikke Jekyll-bygger)

2. **Skru på GitHub Pages**  
   - Åpne **Settings → Pages** i GitHub-repoet
   - *Build and deployment* → **Source: “Deploy from a branch”**
   - Velg branch (ofte `main`) og **Folder: “/ (root)”**
   - Trykk **Save**. Etter noen sekunder får du en URL i toppen, typisk:  
     `https://<brukernavn>.github.io/<repo-navn>/`

3. **Test** siden ved å åpne URL-en.

## Lokal testing

Dobbeltklikk `index.html` for å åpne i nettleseren din. Ingen server nødvendig.

## Notater

- Innebygde I_z-tabeller er veiledende/illustrative for testing. Sjekk alltid mot NEK 400:2022 og fabrikantdata før prosjektering.
- Forlegningsmetode **E** er midlertidig satt lik **C** inntil riktige verdier legges inn.
- Ønsker du PWA (ikon + offline)? Legg inn `manifest.json` og `sw.js` (service worker) – jeg kan bidra med en mal.