# ✅ Test Cases – Responsywność (bloomandglow.pl)

**Środowisko**
- Chrome DevTools (responsive mode)
- macOS 15.3.2

## TC01 – Układ strony głównej na mobile (360px)

**Cel:**  
Zweryfikować poprawność układu strony głównej na ekranie telefonu

**Kroki:**
1. Otwórz stronę główną
2. Przełącz widok na 360px szerokości (np. iPhone 12)
3. Zweryfikuj układ nagłówka, menu, produktów

**Oczekiwany rezultat:**  
Elementy mieszczą się na ekranie, nie nachodzą na siebie

---

## TC02 – Widoczność przycisków i menu na mobile

**Cel:**  
Upewnić się, że przyciski i menu są dostępne na małym ekranie

**Kroki:**
1. Wejdź na stronę w widoku mobile
2. Otwórz menu
3. Sprawdź działanie ikon i dostępność nawigacji

**Oczekiwany rezultat:**  
Menu rozwija się prawidłowo, wszystkie elementy są klikalne

---

## TC03 – Koszyk na małym ekranie

**Cel:**  
Zweryfikować widoczność i obsługę koszyka na mobile

**Kroki:**
1. Dodaj produkt do koszyka
2. Przejdź do koszyka
3. Zweryfikuj widoczność listy produktów i przycisków

**Oczekiwany rezultat:**  
Zawartość koszyka i przyciski są czytelne i nie wychodzą poza ekran

---

## TC04 – Skalowanie formularza zamówienia

**Cel:**  
Sprawdzenie skalowania i układu formularza przy finalizacji zamówienia

**Kroki:**
1. Dodaj produkt i przejdź do checkoutu
2. W widoku 360px zweryfikuj formularz danych

**Oczekiwany rezultat:**  
Pola formularza nie są ucięte, całość jest skalowalna i czytelna

---

## TC05 – Obrót ekranu mobile (portrait ↔ landscape)

**Cel:**  
Sprawdzić zachowanie strony po zmianie orientacji

**Kroki:**
1. Przełącz z widoku pionowego na poziomy i odwrotnie
2. Obserwuj układ strony

**Oczekiwany rezultat:**  
Układ strony dostosowuje się do nowej orientacji bez błędów
