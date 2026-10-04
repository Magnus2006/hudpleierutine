# Hudpleierutine v4

Statisk PWA publisert på GitHub Pages: https://magnus2006.github.io/hudpleierutine/

## Rutine fra 4. oktober 2026
- Morgen: CeraVe Hydrating Cleanser → La Roche-Posay Toleriane Sensitive Cream → Eucerin Sun Oil Control Gel-Cream SPF 50+ til ansikt.
- Kveld: CeraVe Blemish Control Cleanser → samme fuktighetskrem. Velg grønn rens for skånsomme kvelder.
- Tidligere BHA-væske og azelainsyre er satt på pause. Begge nye rensene skylles av.

Kalender, historikk, streaks, tema og påminnelser beholdes lokalt i nettleseren. Historiske kveldsrutiner før oppdateringsdatoen bevares. Morgen/kveld kan krysses av separat. Produktvalget på en kveld lagres per dato.

Ingen byggetrinn. For lokal sjekk: `python3 -m http.server 8000` fra prosjektmappen.
Service worker v4 henter HTML fra nett når tilgjengelig, med offline-reserve. Varsler krever støtte/tillatelse og at appen er aktiv; dette er ikke en serverbasert varslingstjeneste.
