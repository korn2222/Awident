# Awident — Strona Gabinetu Stomatologicznego

Premium strona internetowa dla gabinetu stomatologicznego Awident w Lubartowie.

## Pliki
- `index.html` — kompletna strona HTML
- `styles.css` — arkusz stylów CSS
- `script.js` — skrypt JavaScript (menu, scroll, FAQ, animacje)

## Co podmienić przed wdrożeniem

1. **Logo** — wyszukaj `<!-- TUTAJ WKLEJ LOGO -->` i podmień SVG na własne logo
2. **Zdjęcia** — wyszukaj `<!-- TUTAJ WKLEJ` i podmień placeholdery na zdjęcia kliniki/lekarzy (.webp)
3. **Google Maps** — w sekcji Kontakt podmień `iframe src` na poprawny embed z Google Maps
4. **Bookero** — upewnij się, że linki `https://bookero.pl` prowadzą do Twojego kalendarza
5. **Cennik** — zaktualizuj ceny usług w sekcji Cennik
6. **Zespół** — uzupełnij imiona i zdjęcia lekarzy
7. **Formularz** — podłącz backend do formularza kontaktowego (np. Formspree, Netlify Forms)

## Uruchomienie lokalne
```bash
# Otwórz plik bezpośrednio w przeglądarce:
open index.html

# Lub użyj prostego serwera:
npx serve .
```

## Technologie
- HTML5 semantyczny
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (zero zależności)
- Google Fonts (Inter)
- SVG ikony inline
