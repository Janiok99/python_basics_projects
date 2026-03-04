# Kalkulator czterech działań – Python

   Prosty kalkulator konsolowy umożliwiający wykonanie podstawowych działań matematycznych: dodawania, odejmowania, mnożenia oraz dzielenia.
   Program pobiera od użytkownika dwie liczby oraz wybór operacji, a następnie wyświetla wynik.

## Struktura projektu

      calculator/
         │── calculator.py
         │── README.md

## Funkcjonalności

   - Dodawanie dwóch liczb.
   - Odejmowanie dwóch liczb.
   - Mnożenie dwóch liczb.
   - Dzielenie dwóch liczb.
   - Proste menu wyboru operacji.
   - Obsługa danych wejściowych od użytkownika.

## Jak działa program

   1. Program wyświetla listę dostępnych operacji.
   2. Użytkownik wybiera jedną z nich (1–4).
   3. Program pobiera dwie liczby typu `float`.
   4. W zależności od wyboru:
      - wywoływana jest odpowiednia funkcja (`dodaj`, `odejmij`, `pomnóż`, `podziel`),
      - wynik jest wyświetlany w czytelnej formie.
   5. Jeśli użytkownik poda niepoprawny numer operacji, program wyświetla komunikat o błędzie.

## Przykładowy przebieg programu

   Wybierz operację liczbową:
   1.Dodawanie
   2.Odejmowanie
   3.Mnożenie
   4.Dzielenie
   Którą operację chcesz wykonać? Wybierz (1/2/3/4): 3
   Podaj pierwszą wartość: 4
   Podaj drugą wartość: 7
   4.0 * 7.0 = 28.0

## Czego uczy ten projekt

   - definiowania funkcji w Pythonie,
   - pracy z instrukcjami warunkowymi,
   - pobierania danych od użytkownika,
   - konwersji typów (`input` → `float`),
   - podstawowej struktury programu konsolowego.

## Uruchamianie

   W terminalu:

      python calculator.py

   Plik musi znajdować się w bieżącym katalogu lub należy podać pełną ścieżkę.
