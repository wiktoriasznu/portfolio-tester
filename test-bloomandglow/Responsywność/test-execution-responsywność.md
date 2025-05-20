# Test Execution – responsywność

**Data wykonania:** 2024-05-20
**Środowisko**
- Chrome DevTools (responsive mode)
- macOS 15.3.2
**Zakres** TC01-TC05

| Test Case | Wynik     | Uwagi                                                            |
|-----------|-----------|------------------------------------------------------------------|
| TC01      | Failed    | Formularz zmiany hasła - elemty podglądu hasła                   |
| TC02      | Passed    | Przycisk menue działa zgodnie z oczekiwaniem                     |
| TC03      | Passed    | Koszyk działa zgodnie z oczekiwaniem                             |
| TC04      | Passed    | Formularza finazlizujący zamównie działa zgodnie z oczekiwaniami |
| TC05      | Failed    | Elementy stópki nachodzą na siebie                               |

**Zgłoszone błędy**
- `BUG-001`: W oknie formularzu zmiany hasła elemty podglądu hsała nachodzą na pola (TC01)
- `BUG-002`: Obrót ekranu mobile (portrait ↔ landscape) - elementy stópki nachodzą na siebie (TC02) 

**Podsumowanie:** 3/5 testów zakończonych sukcesem (60% PASS rate)