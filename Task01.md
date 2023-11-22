# Zadanie: Stylizowany Formularz Rejestracyjny

## Cel Zadania
Stworzyć formularz rejestracyjny z wykorzystaniem HTML i CSS, gdzie każda para etykieta (`label`) i pole (`input`) będzie opakowana w `div`, a style będą stosowane zarówno do etykiet, jak i pól.

## Wymagania

### HTML
1. Utwórz plik HTML `formularz.html`.
2. Dodaj podstawową strukturę HTML.
3. W `<body>`, utwórz formularz `<form>` zawierający:
   - **Imię**: Pole tekstowe
   - **Nazwisko**: Pole tekstowe
   - **Email**: Pole typu email
   - **Hasło**: Pole typu password
   - **Przycisk**: "Zarejestruj się" (`type="submit"`)

   Każdą parę `label` i `input` umieść w osobnym `<div>`.

### CSS
1. Utwórz plik CSS `style.css`.
2. Dołącz plik CSS do pliku HTML.
3. Stylizuj wszystkie elementy `input` i `label`:
   - **Czcionka**: Ustaw wielkość na 16px, kolor na ciemnoniebieski.
   - **Tło**: Ustaw tło pól na jasnoszary.
   - **Ramka**: Ustaw cienką, solidną ramkę o kolorze szarym.

4. Dodaj marginesy i paddingi, aby poprawić wygląd formularza.

### Dodatkowe Wyzwania
- Zastosuj pseudoklasy CSS, np. `:hover`, `:focus`, dla lepszego UX.
- Dodaj walidację formularza z wykorzystaniem atrybutów HTML - np. atrybut `required`.

### Testowanie
- Upewnij się, że formularz wygląda estetycznie i jest funkcjonalny.
