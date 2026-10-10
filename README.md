# Portfolio · Giulia Mangraviti

Sito statico (HTML, CSS e JavaScript), nessun passaggio di build: si apre `index.html` e funziona.
Pubblicato con GitHub Pages dal repository `ki-rin-cmd/Portfolio`.

## Struttura

| File / cartella | Cosa contiene |
|---|---|
| `index.html` | Home: hero video, ruota di card "Cosa vuoi esplorare?", contatti |
| `daizyshely.html` | Capitolo 01 · Daizyshely |
| `nikitena.html` | Capitolo 02 · Nikitena |
| `bgen.html` | Capitolo 03 · Bgen |
| `motion.html` | Capitolo 04 · Motion e video |
| `viking.html` | Capitolo 05 · Viking Medieval |
| `ief.html` | Capitolo 06 · Italian Export Forum |
| `video/` | Registrazioni dei siti (seguono lo scroll) e video di Bgen |
| `motion/`, `viking/`, `ief/` | Video e immagini dei capitoli 04–06 |

Librerie da CDN: GSAP 3.13.0 + ScrollTrigger + Observer, Lenis 1.1.14, Three.js r128.

## Come funziona
- Cliccando una card nella home si apre la copertina del progetto (simbolo di particelle, numero, nome, tag) e poi la pagina del capitolo, che parte con la stessa composizione.
- "← Tutti i progetti" riporta alla ruota con la card del progetto davanti (`index.html#id-progetto`).
- Le registrazioni dei siti seguono lo scroll; vengono scaricate intere (fetch → blob) perché lo scrubbing sia fluido.
- Sul telefono, durante le registrazioni dei siti, si vede solo il video (testi e particelle nascosti).

## Caricare su GitHub dall'interfaccia web
1. Apri `github.com/ki-rin-cmd/Portfolio`.
2. **Add file → Upload files**, trascina **tutto il contenuto** di questa cartella (file e cartelle), sostituendo il vecchio `index.html`.
3. Scrivi un messaggio (es. "Nuovo portfolio") e premi **Commit changes**.
4. Dopo 1–2 minuti il sito è aggiornato su `https://ki-rin-cmd.github.io/Portfolio/`.

La cartella `en/` (vecchia versione inglese) non viene toccata.

## Da completare
- Testi reali al posto dei "Segnaposto" (brief, didascalie, tag da confermare).
- Capitolo Manuale di gioco (tolto per ora dalla ruota).
