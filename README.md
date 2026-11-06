# OEVIA

Statisk landningssida for OEVIA.

## Struktur

- `index.html` - publik landningssida.
- `om.html` - kort informationssida for tjänster, arbetssätt och priser.
- `bokning.html` - noindex-sida med mejlkontakt för äldre bokningslänkar.
- `CNAME` - GitHub Pages-domän för `oevia.se`.
- `robots.txt` och `sitemap.xml` - grundläggande indexeringssignaler för sökmotorer.
- `assets/` - bilder, CSS och JavaScript nar sidan bryts ut i separata filer.
- `admin/` - interna checklistor, lanseringsanteckningar och forvaltningsmaterial.
- `docs/` - teknisk dokumentation och beslut som bor sparas.

## Lokal forhandsvisning

Fran projektroten:

```sh
python3 -m http.server 8080
```

Oppna sedan `http://localhost:8080`.

## Att gora fore publicering

- Kontrollera att kontaktlänkarna går till `hello@oevia.se`.
- Bekrafta adress, e-post och eventuell juridisk sidfot.
- Lagga till favicon, Open Graph-bild och analytics endast om det behovs.
- Flytta inline CSS till `assets/css/` nar sidan vaxer.
