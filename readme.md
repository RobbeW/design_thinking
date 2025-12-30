# Design Thinking — Kaarten Shuffler

Kleine webtool voor een Design Thinking-opdracht: leerlingen trekken willekeurig **3 kaarten** (PERSONA, LOCATIE, MODIFIER). De trekking wordt opgeslagen in **localStorage** zodat herrollen niet kan zonder vrijgave.

## Structuur
- `index.html`
- `SVG/`
  - `PERSONA 1.svg`, `PERSONA 2.svg`, …
  - `LOCATIE 1.svg`, `LOCATIE 2.svg`, …
  - `MODIFIER 1.svg`, `MODIFIER 2.svg`, …

## Gebruik (lokaal testen)
PNG-export werkt niet via `file://`. Gebruik een lokale webserver.



Werking
Leerling vult naam (en evt. buddy’s met +) in.

Tool toont shuffle-animatie en kiest 3 kaarten.

Resultaat wordt vastgezet via localStorage.

Herrol kan enkel na wachtwoordprompt (Accenture).

Resultaat kan worden gedownload als PNG (3 losse of 1 gecombineerd).

