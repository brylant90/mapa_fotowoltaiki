# mapa_fotowoltaiki

## Konfiguracja formularza (Formspree)

1. Załóż formularz w Formspree dla `kontakt@mapafotowoltaiki.pl`.
2. Skopiuj endpoint w formacie: `https://formspree.io/f/<id>`.
3. W pliku `index.html` uzupełnij wartość:
   - `const FORMSPREE_ENDPOINT = "https://formspree.io/f/<id>";`

Po wdrożeniu na GitHub Pages formularz będzie wysyłał zgłoszenia na Twoją skrzynkę (zgodnie z ustawieniami Formspree).