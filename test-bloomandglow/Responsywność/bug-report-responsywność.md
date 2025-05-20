# BUG - 001 - Formularz zmiany hasła: błędne pozycjonowanie ikon podglądu (mobile)

**Środowisko**
- Chrome DevTools (responsive mode)
- macOS 15.3.2
---

## 🔁Kroki do odtworzenia
1. Zaloguj się na konto
2. Przejdź do "Szczegóły konta" w panelu uytkownika
3. Przełącz widok na 360px (np. iPhone 12)
4. Zweryfikuj pozycję ikon podglądu hasła w formularzu

----

## ✅Oczekiwany rezultat:
Ikony „pokaż/ukryj hasło” są prawidłowo wyrównane względem pól tekstowych

## Rzeczywisty rezultat:
Ikony podglądu nachodzą na inne elementy formularza i zlewają się z treścią

----
## 🧷 Załączniki:
- [screenshot z błędu](../../assets/bloom- password.png)

## 🏷 Priorytet: Medium  
## 🔧 Status: Open

----

# BUG-002 – Elementy stopki nachodzące na siebie po obrocie ekranu (mobile)

**Środowisko**
- Chrome DevTools (responsive mode)
- macOS 15.3.2
---

## 🔁Kroki do odtworzenia
1. Wejdź na stronę główną
3. Przełącz widok na 360px (np. iPhone 12)
2. Obróć ekran z portrait na landscape
4. Przewiń do sekcji stopki
----

## ✅Oczekiwany rezultat:
Elementy stopki reorganizują się w poziomie lub kolumnach bez kolizji

## Rzeczywisty rezultat:
Bloki tekstu i linki nachodzą na siebie – nieczytelne UI
----
## 🧷 Załączniki:
- [screenshot z błędu](../../assets/fotter-bloom.png)

## 🏷 Priorytet: Medium  
## 🔧 Status: Open