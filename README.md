# halvlek.se

Personlig sajt som visar mina projekt som staplade kort: varje projekt är ett stort
kort som glider upp över det förra när man scrollar. På mobil scrollar korten som vanligt.

- `index.html` – hela sidan, en fil, ingen build, inga beroenden.
- `img/` – skärmdumpar av projekten (WebP, ca 1200 px breda).
- `fonts/` – Inter Tight och IBM Plex Mono (SIL Open Font License), självhostade så att inga anrop går till Google.
- Vercel Web Analytics är inkopplat (cookiefritt).
- Kontaktformuläret skickar till Formspree (formulär `xrpeddpb`). Inställningar, mottagaradress och spamfilter hanteras på formspree.io.
- Föreläsningsbild: `img/forelasning-dentsu.webp` (Dentsu Creative, maj 2026).
- Porträtt: `img/rickard.webp` (360 × 360, kvadratiskt beskuren). Byt filen för att uppdatera bilden.

## Lägga till eller ändra ett projekt

1. Kopiera ett `<article class="card">` i `index.html` och öka `--i` (0, 1, 2 …).
2. Lägg till en rad i listan `.index` i introt.
3. Ändras antalet kort: justera `5 * var(--tab)` i `.card` så att alla flikar får plats.

## Projekt

| Projekt          | Status | Adress                             | Repo                       |
| ---------------- | ------ | ---------------------------------- | -------------------------- |
| Sociala raketer  | Live   | https://www.socialaraketer.se/     | `borickard/guldraketen`    |
| Over/Under       | Live   | https://rated.halvlek.se/          | `borickard/overunderrated` |
| Speltid          | Live   | https://speltid.halvlek.se/        | `borickard/Sanktan`        |
| Klotterväggen    | Pågår  | https://klotter.halvlek.se/        | `borickard/klottervaggen`  |

Vilande, inte på sajten just nu: Fråga svenskarna, Ursäkten (https://ursakter.vercel.app/).
