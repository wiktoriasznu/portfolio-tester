# Test Case - DemoApp - Sorting

## TC01 - Sortowanie produktów A-Z 
**Cel** Weryfikacja domyślnego sortowania produktów alfabetycznie (rosnąco)

**Kroki:**
1. Wejdź na stronę sklepu
2. Sprawdź ustawienie sortowania (powinno być `Name (A to Z)`)
3. Zweryfikuj kolejność wyświetlanych produktów

**Oczekiwany rezultat:** Produkty wyświetlają się w kolejności alfabetycznej od A do Z

---

## TC02 - Sortowanie produktów od Z-A
**Cel** Weryfikacja domyślnego sortowania produktów alfabetycznie (malejąco)

**Kroki:**
1. Wejdź na stronę sklepu
2. Zmień opcje sortowania na `Name (Z to A)`
3. Zweryfikuj kolejność wyświetlanych produktów

**Oczekiwany rezultat:** Produkty wyświetlają się w kolejności alfabetycznej od Z do A

---

## TC03 - Sortowanie według ceny rosnąco
**Cel** Weryfikacja sortowania produktów według ceny – od najniższej do najwyższej

**Kroki:**
1. Wejdź na stronę sklepu
2. Zmień opcje sortowania na `Price (low to high)`
3. Zweryfikuj kolejność cenową produktów

**Oczekiwany rezultat:** Produkty wyświetlają się w kolejności od najtańszego do najdroższego

---

## TC04 - Filtrwanie według ceny malejąco
**Cel** Weryfikacja sortowania produktów według ceny – od najwyższej do najniższej

**Kroki:**
1. Wejdź na stronę sklepu
2. Zmień opcje sortowania na `Price (high to low)`
3. Zweryfikuj kolejność cenową produktów

**Oczekiwany rezultat:** Produkty wyświetlają się w kolejności od najdroższego do najtańszego