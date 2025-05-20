# Test Execution – ecommerce(koszyk)

**Data wykonania:** 2024-05-20
**Środowisko:** Chrome 135.0.7049.114 (Official Build) (x86_64) - macOS 15.3.2
**Zakres** TC01-TC05

| Test Case | Wynik     | Uwagi                                                       |
|-----------|-----------|-------------------------------------------------------------|
| TC01      | Failed    | Przycisk “Dodaj do koszyka” nie działa poprawnie            |
| TC02      | Passed    | Usuwanie produktu z koszyka działa zgodnie z oczekiwaniem   |
| TC03      | Passed    | Ceny aktualizują się po zmianie ilości w koszyku            |
| TC04      | Passed    | Przycisk „Zobacz koszyk” działa i przekierowuje poprawnie   |
| TC05      | Passed    | Użytkownik jest przekierowywany do formularza zamówienia    |

**Zgłoszone błędy**
- `BUG-001`: Przycisk “Dodaj do koszyka” po wcisnieciu odcina się w połowie (TC01)

**Podsumowanie:** 4/5 testów zakończonych sukcesem (80% PASS rate)