# Test Cases - DemoApp - Products

## TC01 - Dodanie produktu do koszyka
**Cel:** Sprawdzanie, czy produkt trafia do koszyka

**Kroki:**
1. Otwórz stronę produktu
2. Kliknij "Dodaj do koszyka"
3. Otwórz koszyk
**Oczekiwany rezultat:** w koszyku widoczny jest wybrany produkt z poprawną nazwą i ceną

---

## TC02 - Filtrowanie produktów po kategorii
**Cel:** Sprawdzanie działania filtra katergorii

**Kroki:**
1. Otwórz listę produktów
2. Z menu filtrów wybierz kategorię “Elektronika”

**Oczekiwany rezultat:** wyświetlają się tylko produkty z kategorii “Elektronika”

---

## TC03 - Złożenie zamówienia z pustym koszykiem
**Cel:** sprawdzenie zabezpieczenia przed checkoutem bez produktów

**Kroki:**
1. Wejdź do koszyka (bez dodawania produktów)
2. Kliknij “Przejdź do płatności”

**Oczekiwany rezultat:** pojawia się komunikat “Koszyk jest pusty” i brak przejścia dalej

---