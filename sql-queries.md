## SQL - zapytania
```sql

Zapytanie 1 - Klienci z Niemiec

SELECT FirstName, LastName, Country
From customers
WHERE Country = 'Germany'

Opis
- Zapytanie filtruje klientów po kraju 

https://file+.vscode-resource.vscode-cdn.net/var/folders/m_/dzxxk8v54l32llz9d5bcy4kr0000gp/T/TemporaryItems/NSIRD_screencaptureui_jrvlNf/Screenshot%202025-05-06%20at%2012.52.04.png?version%3D1746528726628

---

Zapytanie 2 - Utwowy dłuższe niż 5 minut

SELECT Name, Milliseconds
FROM tracks
WHERE Miliseconds > 300000;add

Opis
- Weryfikacja, czy system przechowuje czas trwania utworu poprawnie i pozwala go używać jako kryterium filtrowania (edge case: długi utwór).

https://file+.vscode-resource.vscode-cdn.net/var/folders/m_/dzxxk8v54l32llz9d5bcy4kr0000gp/T/TemporaryItems/NSIRD_screencaptureui_Nwydy2/Screenshot%202025-05-06%20at%2012.53.20.png?version%3D1746528817175