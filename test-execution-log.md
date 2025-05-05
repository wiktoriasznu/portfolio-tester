# Test Execution – Logowanie

**Data:** 2024-05-06  
**Zakres:** TC01–TC03

| Test Case | Wynik     | Uwagi                          |
|-----------|-----------|--------------------------------|
| TC01      | Passed    | Logowanie działa poprawnie     |
| TC02      | Failed    | Brak komunikatu o pustym haśle |
| TC03      | Passed    | Komunikat o złym haśle działa  |

**Zgłoszone błędy:**  
- `BUG-001`: brak walidacji pustego hasła (TC02)