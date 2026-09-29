# boven.se

Personlig startsida som samlar mina projekt. Retro-skrivbord: flyttbara fönster (ett per projekt), Om mig, en liten Paint och ett aktivitetsfält med Start-meny.

- `index.html` – hela sidan, en fil, ingen build, inga beroenden.
  Nytt fönster = ny `<section class="win">` (se kommentaren i filen) + en ikon i `<nav class="icons">`.

## Projekt (subdomäner)

Varje projekt får en egen subdomän som pekar på sin egen hosting (egen DNS-post,
t.ex. CNAME). Den här sidan länkar bara till dem – byt projektets
`<button class="btn" data-soon>` mot `<a class="btn" href="…">` i `index.html` när det går live.

| Projekt            | Subdomän (förslag)  |
| ------------------ | ------------------- |
| Under/overrated    | `rated.boven.se`    |
| Fråga svenskarna   | `fraga.boven.se`    |
