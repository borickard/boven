# boven.se

Personlig startsida som samlar mina projekt. Retro-skrivbord: flyttbara fönster (ett per projekt), Om mig, en liten Paint och ett aktivitetsfält med Start-meny.

- `index.html` – hela sidan, en fil, ingen build, inga beroenden.
- `fonts/vt323-latin.woff2` – typsnittet VT323 (SIL Open Font License), självhostat så att inga anrop går till Google.
  Nytt fönster = ny `<section class="win">` (se kommentaren i filen) + en ikon i `<nav class="icons">`.
  Nytt projekt = nytt projektfönster + en ikon i projektmappen (`#w-projects`).

## Projekt (subdomäner)

Varje projekt får en egen subdomän som pekar på sin egen hosting (egen DNS-post,
t.ex. CNAME). Den här sidan länkar bara till dem – byt projektets
`<button class="btn" data-soon>` mot `<a class="btn" href="…">` i `index.html` när det går live.

| Projekt            | Adress                          |
| ------------------ | ------------------------------- |
| Sociala raketer    | https://www.socialaraketer.se/  |
| Sanktan            | https://sanktan.vercel.app/     |
| Ursäkten           | https://ursakter.vercel.app/    |
| Fråga svenskarna   | pågår                           |
| Under/overrated    | https://overunderrated.vercel.app/ |
