# Homework

Website: https://homework.minimum.se

Quiz: https://homework.minimum.se/planetjakten/

Each quiz lives in its own folder. Add future quizzes in separate folders with
an `index.html`, and link to them from the homepage.

This repository contains a static website. Edit `index.html` or add HTML, CSS,
JavaScript, and other assets in the repository root.

## GitHub Pages setup

In repository **Settings → Pages**, configure:

- Source: **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Custom domain: **homework.minimum.se**
- Enable **Enforce HTTPS** once GitHub provisions the certificate.

DNS must contain a CNAME record from `homework.minimum.se` to
`vera256.github.io`. The `CNAME` file preserves the site's custom domain.

Once Pages is enabled, pushes to `main` automatically publish the website.

## Geografiresan

Quiz: https://homework.minimum.se/geografiresan/

60 egenformulerade frågor i fem uppdrag, med faktakort, förklaringar, slumpad
svarsordning, blandade rundor och repetition av felsvar. Framsteg sparas lokalt
i webbläsaren. Bygger på de uppladdade geografiuppslagen (s. 194–207,
214–221 och 112–115) och lärarens provlista. Kartövningar och grundbegrepp om
vattnets kretslopp kompletterar de fotograferade sidorna enligt provlistan.

Statisk HTML/CSS/JavaScript utan byggsteg eller externa beroenden. Starta
lokalt från repots rot med `python3 -m http.server 5173`.
