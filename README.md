# tools

Raccolta di strumenti web statici, pubblicati con GitHub Pages.

## Strumenti

- **[Taglia la prova in brani](taglia-prova/)** — carica una registrazione MP3 e il file dei parziali (`.md`) e taglia l'audio in brani. L'elaborazione avviene interamente nel browser, sul dispositivo: nessun file viene caricato su server.

## Note tecniche

Lo strumento "Taglia la prova" nasce come artefatto Claude. La versione qui pubblicata include una piccola correzione (`index.html`, script in fondo al `<body>`) che ripristina le URL blob native del browser: l'artefatto originale usava uno schema `blob-request://` valido solo dentro claude.ai, che impediva riproduzione audio e download ZIP su hosting statico.
