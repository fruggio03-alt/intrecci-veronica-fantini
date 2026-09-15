# Intrecci — Veronica Fantini · sito vetrina

Sito statico: un solo file (`index.html`) più la cartella `assets/`.
Niente database, niente carrello. Si pubblica così com'è su GitHub Pages.

```
index.html                 il sito
anteprima-con-video.html   copia con il video dentro, solo per guardarlo
assets/hero.mp4            il video della hero
assets/hero-poster.jpg     fermo immagine prima che parta il video
assets/borse/              (per ora vuota, vedi sotto)
```

## Il catalogo

Nomi, descrizioni e prezzi delle dodici borse arrivano dal modulo ordini
JotForm. Si modificano tutti in fondo a `index.html`, nel blocco che
inizia con `const BORSE = [`.

Le foto **non sono ancora nel sito**: vengono lette dai server di JotForm.
Funziona, ma dipende da loro. Quando puoi, scarica le immagini, mettile in
`assets/borse/` e sostituisci l'indirizzo lungo con `assets/borse/01.jpg`.
Tieni ogni foto sotto i 300 KB.

## Cosa manca ancora

1. **Il logo** → `assets/logo.png`, meglio se PNG con sfondo trasparente,
   largo circa 1200 px. Finché non c'è, il sito disegna una versione
   scritta del marchio: somiglia, ma non è il logo vero.
2. **Le foto della collezione Industrial-Pop**, quando è pronta.

## Pubblicare su GitHub Pages

Trascina l'intera cartella nella finestra di upload del repo
`fruggio03-alt/intrecci-veronica-fantini`: `index.html` e `assets/`
devono restare allo stesso livello, altrimenti il video non si vede.
