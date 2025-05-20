# Test Execution – UX

**Data wykonania:** 2024-05-20
**Środowisko:** Chrome 135.0.7049.114 (Official Build) (x86_64) - macOS 15.3.2
**Zakres** TC01-TC05

| Test Case | Wynik     | Uwagi                                                       |
|-----------|-----------|-------------------------------------------------------------|
| TC01      | Failed    | 2 rodzaje przycisku “Dodaj do koszyka”                      |
| TC02      | Passed    | Nazwy są zwięzłe, logiczne, nie zawierają błędów językowych |
| TC03      | Passed    | Opis poprawny, bez literówek,                               |
| TC04      | Passed    | Brak martwych linków                                        |
| TC05      | Passed    | Działania przycisków są zgodne z etykietą                   |

**Zgłoszone błędy**

- `BUG-01`: Przycisk „Dodaj do koszyka” występuje w dwóch wariantach wizualnych — wersja beżowa charakteryzuje się bardzo niskim kontrastem i jest łatwa do pomylenia z przyciskiem „Na zamówienie” (TC01)

**Podsumowanie:** 4/5 testów zakończonych sukcesem (80% PASS rate)
