# Zadanie: Stworzenie Tabeli HTML z Stylami CSS

## Cel Zadania
Celem zadania jest stworzenie tabeli HTML z wykorzystaniem atrybutów `id` i `class` dla różnych elementów tabeli oraz zastosowanie stylów CSS bezpośrednio w pliku HTML.

## Wymagania

### HTML i CSS
1. Utwórz plik HTML `table.html`.
2. Dodaj podstawową strukturę HTML (doctype, head, body).
3. W `<head>`, umieść tagi `<style>` do zdefiniowania stylów CSS.
4. W `<body>`, utwórz tabelę `<table>` z następującymi cechami:
   - Minimum 4 kolumny (np. ID, Name, Price, Quantity).
   - Minimum 3 wiersze danych.
   - Nadaj tabeli atrybut `id` (np. `id="productTable"`).
   - Nadaj różnym elementom tabeli klasy CSS (np. `class="tableHeader"`, `class="tableData"`).

### Stylizacja CSS
1. Zdefiniuj style dla tabeli w tagach `<style>` w sekcji `<head>`:
   - Stylizuj tabelę (`#productTable`) – ustaw szerokość, marginesy, obramowanie.
   - Stylizuj nagłówki kolumn (`th`) – ustaw tło, kolor czcionki, wyśrodkowanie tekstu.
   - Stylizuj komórki danych (`td`) – ustaw wyśrodkowanie tekstu, padding.

### Dodatkowe Wyzwania
- Dodaj pseudoklasy CSS, takie jak `:hover`, do wierszy danych, aby zmieniały one kolor tła po najechaniu kursorem.
- Zastosuj różne style dla parzystych i nieparzystych wierszy tabeli za pomocą pseudoklas `:nth-child`.

### Testowanie
- Sprawdź, czy tabela jest poprawnie wyświetlana i stylizowana w przeglądarce.
- Testuj efekty interakcji użytkownika z tabelą, takie jak zmiana koloru tła przy najechaniu kursorem.
