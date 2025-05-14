# Test Execution – Sortowanie

**Data wykonania:** 2024-05-14
**Środowisko:** Chrome 135.0.7049.114 (Official Build) (x86_64) - macOS 15.3.2
**Zakres** TC01-TC04

| Test Case | Wynik     | Uwagi                                                         |
|-----------|-----------|---------------------------------------------------------------|
| TC01      | Failed    | Niepoprawne sortowanie - kolejność niezgodna z alfabetem (A-Z)|
| TC02      | Failed    | Komunikat “Sorting is broken!” zamiast działania              |
| TC03      | Failed    | Niepoprawne sortowanie - kolejność niezgodna z ceną (rosnąco) |
| TC04      | Failed    | Niepoprawne sortowanie - kolejność niezgodna z ceną (malejąco)|


**Zgłoszone błędy**
- `BUG-001`: produkty wyświetlają się w losowej kolejności (TC01)
- `BUG-002`: funkcjonalność sortowania nie działa(TC02)
- `BUG-003`: funkcjonalność sortowania działa poprawnie - kolejność niezgodna z ceną, rosnąco (TC03)
- `BUG-004`: funkcjonalność sortowania działa poprawnie - kolejność niezgodna z ceną, malejąco (TC04)

**Podsumowanie:** 0/4 testów zakończonych sukcesem (0% PASS rate)