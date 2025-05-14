# 🐞 Bug Reports – Sortowanie

- [BUG-001 – Niepoprawne sortowanie A-Z](#bug-001)
- [BUG-002 – Błąd systemowy przy Z-A](#bug-002)
- [BUG-003 – Zła kolejność wg ceny rosnąco](#bug-003)
- [BUG-004 – Zła kolejność wg ceny malejąco](#bug-004)


# BUG - 001 - Niepoprawne sortowanie A-Z na liście produktów

**Środowisko**
- Chrome 135.0.7049.114 (Official Build) (x86_64)
- macOS 15.3.2
- Aplikacja: DemoApp (wersja webowa)

---

## 🔁Kroki do odtworzenia
1. Przejdź na stronę sklepu 
2. Sprawdź ustawienie sortowania (powinno być `Name (A to Z)`)
3. Zweryfikuj kolejność wyświetlanych produktów

----

## ✅Oczekiwany rezultat:
Produkty wyświetlają się w kolejności alfabetycznej od A do Z

## Rzeczywisty rezultat:
Produkty wyświetlają się w kolejności niezgodnej z oczekiwanym sortowaniem

----
## 🧷 Załączniki:
- [screenshot z błędu](assets/sort-bug-1.png)

## 🏷 Priorytet: Medium  
## 🔧 Status: New



-------------------

# BUG - 002 - Błąd systemowy przy sortowaniu Z-A (komunikat “Sorting is broken!”)

**Środowisko**
- Chrome 135.0.7049.114 (Official Build) (x86_64)
- macOS 15.3.2
- Aplikacja: DemoApp (wersja webowa)

---

## 🔁Kroki do odtworzenia
1. Przejdź na stronę sklepu 
2. Zmień opcje sortowania na `Name (Z to A)`
3. Zweryfikuj kolejność wyświetlanych produktów

----

## ✅Oczekiwany rezultat:
Produkty wyświetlają się w kolejności alfabetycznej od Z do A

## Rzeczywisty rezultat:
Komunikat “Sorting is broken!” zamiast działania

----
## 🧷 Załączniki:
- [screenshot z błędu](assets/sort-bug-2.png)

## 🏷 Priorytet: Medium  
## 🔧 Status: New



-------------------

# BUG - 003 - Nieprawidłowe sortowanie produktów według ceny rosnąco

**Środowisko**
- Chrome 135.0.7049.114 (Official Build) (x86_64)
- macOS 15.3.2
- Aplikacja: DemoApp (wersja webowa)

---

## 🔁Kroki do odtworzenia
1. Przejdź na stronę sklepu 
2. Zmień opcje sortowania na `Price (low to high)`
3. Zweryfikuj kolejność wyświetlanych produktów

----

## ✅Oczekiwany rezultat:
Produkty wyświetlają się w kolejności od najtańszego do najdroższego

## Rzeczywisty rezultat:
Produkty wyświetlają się w kolejności niezgodnej z oczekiwanym sortowaniem

----
## 🧷 Załączniki:
- [screenshot z błędu](assets/sort-bug-3.png)

## 🏷 Priorytet: Medium  
## 🔧 Status: New



-------------------

# BUG - 004 - Nieprawidłowe sortowanie produktów według ceny malejąco

**Środowisko**
- Chrome 135.0.7049.114 (Official Build) (x86_64)
- macOS 15.3.2
- Aplikacja: DemoApp (wersja webowa)

---

## 🔁Kroki do odtworzenia
1. Przejdź na stronę sklepu 
2. Zmień opcje sortowania na `Price (high to low)`
3. Zweryfikuj kolejność wyświetlanych produktów

----

## ✅Oczekiwany rezultat:
Produkty wyświetlają się w kolejności od najdroższego do najtańszego

## Rzeczywisty rezultat:
Produkty wyświetlają się w kolejności niezgodnej z oczekiwanym sortowaniem

----
## 🧷 Załączniki:
- [screenshot z błędu](assets/sort-bug-4.png)

## 🏷 Priorytet: Medium  
## 🔧 Status: New