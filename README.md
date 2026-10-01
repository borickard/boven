# boven.se

Personlig sajt som visar mina projekt som staplade kort: varje projekt är ett stort
kort som glider upp över det förra när man scrollar. På mobil scrollar korten som vanligt.

- `index.html` – hela sidan, en fil, ingen build, inga beroenden.
- `fonts/` – Inter Tight och IBM Plex Mono (SIL Open Font License), självhostade så att inga anrop går till Google.
- Vercel Web Analytics är inkopplat (cookiefritt).

## Lägga till eller ändra ett projekt

1. Kopiera ett `<article class="card">` i `index.html` och öka `--i` (0, 1, 2 …).
2. Lägg till en rad i listan `.index` i introt.
3. Ändras antalet kort: justera `5 * var(--tab)` i `.card` så att alla flikar får plats.

## Projekt

| Projekt          | Status | Adress                             |
| ---------------- | ------ | ---------------------------------- |
| Sociala raketer  | Live   | https://www.socialaraketer.se/     |
| Over/underrated  | Live   | https://overunderrated.vercel.app/ |
| Speltid          | Live   | https://sanktan.vercel.app/ (speltid.nu på gång) |
| Klotterväggen    | Pågår  | –                                  |

Vilande, inte på sajten just nu: Fråga svenskarna, Ursäkten (https://ursakter.vercel.app/).
