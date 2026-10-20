# Sito Buona Fede

Sito statico: HTML e un solo foglio di stile, in stile testo puro (monospazio di sistema, giallo come unico accento). Nessun JavaScript, nessun cookie, nessuno strumento di analisi, nessuna risorsa caricata da servizi esterni. Ogni pagina ha una Content-Security-Policy in un tag meta che vieta qualunque risorsa che non venga dallo stesso dominio.

## Pagine

- `index.html`: apertura, manifesto (testo di `manifesto/MANIFESTO.md`), invito alla call
- `call.html`: la call (testo di `call/CALL.md`), con la mail precompilata come via di risposta
- `confronto.html`: tabella e quattro schede (da `confronto/`), con i punti "da verificare" visibili
- `chi-siamo.html`: da `GOVERNANCE.md`
- `firmatari.html`: regole e elenco (vuoto) da `firmatari/`

Le pagine non sono generate: se cambi un testo nel repository, cambia anche la pagina corrispondente. Intestazione e piè di pagina sono ripetuti in ogni file. Se i file crescono, conviene passare a un generatore statico, ma per cinque pagine non vale il costo.

## Da sistemare prima della pubblicazione

1. **Marchio.** Fatto. I file stanno in `logo/` (vedi `logo/LEGGIMI.md`); l'intestazione e il piede caricano la versione orizzontale, con il negativo in modalità scura. `favicon.svg` è il quadrato "bf.".
2. **Date.** La call dice "quattro settimane" e "le date saranno indicate in questa pagina": quando fissi l'apertura, inserisci apertura e chiusura in `call.html`.
3. **Link al repository.** Le pagine parlano di issue, pull request e repository, ma non hanno un link, perché l'indirizzo non è ancora noto. Aggiungilo in `call.html` e `firmatari.html`.
4. **Dominio.** Aggiungi il file `CNAME` con `buonafede.org` solo quando il dominio è registrato e puntato. Il redirect di `buonafede.net` si configura a livello DNS o di registrar.
5. **Schede del confronto.** Restano valide solo finché le fonti primarie non vengono lette. I punti da verificare sono marcati in pagina.

## Pubblicazione con GitHub Pages

Il sito sta in una sottocartella, quindi il workflow `.github/workflows/pages.yml` pubblica solo `sito/`:

```yaml
name: Pubblica sito
on:
  push:
    branches: [main]
    paths: ["sito/**"]
  workflow_dispatch:
permissions:
  contents: read
  pages: write
  id-token: write
concurrency:
  group: pages
  cancel-in-progress: true
jobs:
  deploy:
    runs-on: ubuntu-latest
    environment:
      name: github-pages
      url: ${{ steps.deployment.outputs.page_url }}
    steps:
      - uses: actions/checkout@v4
      - uses: actions/configure-pages@v5
      - uses: actions/upload-pages-artifact@v3
        with:
          path: sito
      - id: deployment
        uses: actions/deploy-pages@v4
```

Nelle impostazioni del repository, sezione Pages, scegliere come sorgente "GitHub Actions".

## Prova in locale

```
cd sito && python3 -m http.server 8000
```
