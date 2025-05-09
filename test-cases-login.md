# Test Cases - DemoApp - Login

## TC01 - Logowanie z poprawnymi danymi 
**Cel:** sprawdzenie, czy uytkownik moe się zalogować 

**Kroki:**
1. Wejdź na strone logowania 
2. Wpisz poprawny e-mail i hasło 
3. Kliknij "Zaloguj"
**Oczekiwany rezultat:** Uzytkownik zostaje przeniesiny na stronę główną

---

## TC02 - Logowanie z pustym hasłem 
**Cel:** sprawdzenie, czy system poprawnie waliduje brak hasła przy logowaniu

**Kroki**
1. Wejdź na strone logowania 
2. Wpisz poprawny e-mail, pole hasło pozostaw puste
3. Kliknij "Zaloguj"

**Oczekiwany rezultat:** Uzytkownik otrzymuje komunikat "Wprowadz hasło"


---

## TC03 - Logowanie z niepoprawnym hasłem
**Cel:** sprawdzenie, czy system blokuje logowanie przy błędnym haśle

**Kroki**
1. Wejdź na strone logowania 
2. Wpisz poprawny e-mail
3. Wpisz niepoprawne hasło: `zlehaslo123`
4. Kliknij "Zaloguj"

**Oczekiwany rezultat:**  
System wyświetla komunikat: “Nieprawidłowy login lub hasło”. Użytkownik nie zostaje zalogowany.