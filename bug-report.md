# BUG - 001 - brak walidacji pustego hasła

**Środowisko**
- Chrome 135.0.7049.114 (Official Build) (x86_64)
- macOS 15.3.2
- Aplikacja: DemoApp (wersja webowa)

---

## 🔁Kroki do odtworzenia
1. Przejdź na starone logowania 
2. Wpisz poprawny e-mail (np. test@demo.pl)
3. Pozostaw pole hsało puste 
4. Kliknij w przcisk "Zaloguj"

----

## ✅Oczekiwany rezultat:
Wyświetla się komunikat: **"Hasło jest wymagane"**. Logowanie jest zablokowane.

## ❌Rezcywisty rezultat:
Nic się nie dzieje - brak komunikatu, bark akcji

----
## 🧷 Załączniki:
- [screenshot z błędu](assets/bug-empty-password.png)

## 🏷 Priorytet: Medium  
## 🔧 Status: Open