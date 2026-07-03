# IKER Schilderwerken

Website voor IKER Schilderwerken (Adrian Palermo), professioneel schilderbedrijf gevestigd in Erembodegem (Aalst), actief in heel België.

Statische site, gebouwd met HTML, CSS en vanilla JS - geen build-stap nodig. Beschikbaar in drie talen:

- `index.html` - Nederlands (standaard)
- `fr.html` - Frans
- `en.html` - Engels

## Structuur

```
index.html / fr.html / en.html   pagina's per taal
assets/css/style.css             stijl
assets/js/main.js                mobiel menu
assets/img/favicon.svg           favicon
```

## Publiceren via GitHub Pages

1. Ga naar **Settings > Pages** in deze repository.
2. Kies **Deploy from a branch**, branch `main`, map `/ (root)`.
3. Sla op - de site is na enkele minuten live op de gegenereerde `github.io`-URL (of een eigen domein via `CNAME`).

## Contactgegevens aanpassen

Telefoon, e-mail en steden in het werkgebied staan rechtstreeks in de HTML-bestanden (`tel:`, `mailto:` links en de `.city-chip` elementen) - pas ze in alle drie de taalversies aan.
