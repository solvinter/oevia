# Oevia

Statisk landningssida for Oevia.

## Struktur

- `index.html` - publik landningssida.
- `oevia.se.html` - originalfilen som projektet startade med.
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

- Byt BokaDirekt-lanken i `index.html` till Oevias publika bokningssida.
- Bekrafta adress, e-post och eventuell juridisk sidfot.
- Lagga till favicon, Open Graph-bild och analytics endast om det behovs.
- Flytta inline CSS till `assets/css/` nar sidan vaxer.
