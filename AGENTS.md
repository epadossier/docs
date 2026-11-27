# AGENTS.md

Regels voor iedereen die deze documentatie wijzigt, mensen en AI-agents.

## Wat dit is

De Mintlify-site van de EPAdossier API (`/api/v1`), op https://epadossier.nl/docs. De code van de API staat in de repo `epadossier/epadossier`, onder `apps/web/src/app/api/v1` en `apps/web/src/server/partner-api`.

- Verandert een route, een veld of een foutcode in `/api/v1`, werk dan `openapi.yaml` en de handleiding hier in dezelfde week bij.
- Beschrijf alleen wat de code echt doet. Lees bij twijfel de route na in plaats van te gokken.
- Draai `npx mint@latest validate` en `npx mint@latest broken-links` voor je pusht.

## Taal en stijl

- Nederlands, met "je". Zinnen in zinsvorm, ook koppen: geen Title Case.
- Nooit een em dash (het lange streepje). Gebruik een dubbele punt, komma of een nieuwe zin.
- Veldnamen, codes en paden in `code`. Knoppen en menu's in EPAdossier **vet**.
- Voorbeelden gebruiken verzonnen maar realistische gegevens (Damrak 1, 1012AB), nooit echte klanten.
- De basis-URL is voorlopig `https://test.epadossier.nl/api/v1`. Komt live erbij, voeg die dan toe aan `servers` in `openapi.yaml` en aan `omgevingen.mdx`.
