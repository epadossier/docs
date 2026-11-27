# EPAdossier API-documentatie

De documentatie van de EPAdossier API voor klanten en samenwerkingspartners, gebouwd met [Mintlify](https://mintlify.com). Hij staat op https://epadossier.nl/docs.

- `docs.json`: navigatie, kleuren en logo.
- `*.mdx`: de handleiding.
- `openapi.yaml`: de API-referentie. Mintlify maakt hier de pagina's onder het tabblad API-referentie van.

Een push naar `main` zet de site online.

## Lokaal bekijken

```bash
npx mint@latest dev
```

Controleer voor een push:

```bash
npx mint@latest validate
npx mint@latest broken-links
```
