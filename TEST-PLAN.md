#  Test Plan – Portfolio Tester Manualny

##  Cel testów

Celem jest sprawdzenie poprawności działania kluczowych funkcjonalności webowych oraz API w aplikacjach typu e-commerce i demo. Testy mają charakter eksploracyjny oraz oparte na przypadkach testowych. Dokumentacja służy potwierdzeniu umiejętności manualnego testowania.

---

## Zakres testów

- Rejestracja i logowanie
- Koszyk, ceny i formularz zamówienia
- Responsywność UI (mobile vs desktop)
- Podstawowe testy UX i kontrastów
- Obsługa sortowania (A-Z, cena)
- Testowanie REST API (GET, POST, PUT, DELETE)
- Zgłaszanie błędów i analiza wyników

---

## Narzędzia

| Narzędzie        | Zastosowanie                            |
|------------------|-----------------------------------------|
| Postman          | testowanie REST API, testy automatyczne |
| Chrome DevTools  | analiza responsywności                  |
| DB Browser SQLite| testowanie zapytań SQL                  |
| Jira (demo)      | zarządzanie błędami/testami             |
| Markdown + Git   | dokumentacja testów i wersjonowanie     |

---

## Struktura dokumentacji

- `test-case-*` – przypadki testowe
- `test-execution-*` – wykonanie testów
- `bug-report-*` – raporty błędów ze screenami
- `api-tests.md` – testy API z przykładowymi zapytaniami
- `sql-queries.md` – zapytania SQL na przykładowej bazie
- `assets/` – zrzuty ekranu dołączone do raportów

---

## Harmonogram

Testy wykonywane etapowo w ramach portfolio – każda funkcjonalność testowana osobno i dokumentowana od razu.

---

## Kryteria zakończenia

- Sprawdzone wszystkie przypadki testowe
- Zgłoszone i udokumentowane błędy
- Ukończone testy API i dokumentacja testów
- Repozytorium kompletne i publiczne

---

**Autorka: Wiktoria Sznurowska**  
**Repozytorium:** [github.com/wiktoriasznu/portfolio-tester](https://github.com/wiktoriasznu/portfolio-tester)
