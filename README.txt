# MC-Core Product — Maciej Cieślak (final)

Ta paczka zawiera zmodyfikowany `index.html` (bez dużego zdjęcia, z GA `G-EHX2MGCECB`) oraz pliki: `manifest.webmanifest`, `robots.txt`, `sitemap.xml`, `favicon.svg`.

## Jak wdrożyć
- Wgraj wszystkie pliki do katalogu głównego hostingu (np. GitHub Pages, Netlify, Vercel, serwer www).
- Zaktualizuj domenę w `robots.txt` i `sitemap.xml` (pole `Sitemap:` i `<loc>`).
- Jeśli korzystasz z favicon w PNG, utrzymaj istniejący `favicon.png`; dodatkowo dostarczamy `favicon.svg`.
- Grafiki klientów i logo definiowane są w skrypcie `window.__MC_LOGO_URL` i `window.__CLIENT_LOGOS` w `index.html`.
