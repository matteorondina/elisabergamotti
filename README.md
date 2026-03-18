# elisa — ecosystem proposal

Proposta strategica per il riposizionamento di **Elisa S.r.l. Società Benefit** come ecosistema di verticali di consulenza.

## Struttura

Single-page application HTML statica con navigazione interna. Nessuna dipendenza, nessun build step.

```
index.html    ← tutto il sito (HTML + CSS + JS inline)
```

## Pagine

| Pagina | Contenuto |
|--------|-----------|
| **Home** | Hero animato con slash rotante /ai /marketing /impact |
| **Chi siamo** | Profili founder (Stefano Storoni, Matteo Rondina) |
| **/ai** | Verticale AI — augmented intelligence |
| **/marketing** | Verticale Marketing — marketing partner |
| **/impact** | Verticale Impact — social impact by design |
| **Orizzonti** | Verticali future in esplorazione |

## Deploy su GitHub Pages

1. Crea un repository su GitHub (es. `elisa-ecosystem`, consiglio **privato**)
2. Carica `index.html`, `README.md` e `robots.txt`
3. Dal repo su GitHub, clicca **Add file → Create new file** e crea questi due file:
   - Nome: `.nojekyll` — contenuto: lascia vuoto → Commit
   - Nome: `.gitignore` — contenuto: lascia vuoto → Commit
4. Vai in **Settings → Pages → Source → Deploy from a branch → main → / (root) → Save**
5. Il sito sarà live su `https://tuousername.github.io/elisa-ecosystem/`

## Password

Il sito è protetto da una password leggera (client-side): `elisa2026`

Per cambiarla, modifica la variabile `PASS` nel tag `<script>` di `index.html`.

## Tecnologie

- HTML5 / CSS3 / Vanilla JS
- Google Fonts (DM Sans + DM Serif Display)
- Zero dipendenze, zero build

## Note

- Documento riservato — non indicizzare pubblicamente
- Per evitare indicizzazione, il repo GitHub dovrebbe essere **privato** (GitHub Pages funziona anche con repo privati su piani Pro/Team)

---

Elisa S.r.l. Società Benefit — Fano (PU) — Marzo 2026
