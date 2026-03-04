# Gra „Zgadnij liczbę” – Python

    Ten projekt to prosta gra konsolowa, w której użytkownik próbuje odgadnąć liczbę wylosowaną przez komputer.  
    Program podpowiada, czy podana liczba jest większa czy mniejsza od wylosowanej, a na końcu informuje, po ilu próbach udało się zgadnąć poprawną odpowiedź.

## Struktura projektu
    guessing_game/
        │── guessing_game.py
        │── README.md

## Funkcjonalności

    - Losowanie liczby z zakresu 1–10.
    - Pobieranie odpowiedzi od użytkownika.
    - Informowanie, czy podana liczba jest:
    - większa od wylosowanej,
    - mniejsza od wylosowanej.
    - Liczenie liczby prób.
    - Komunikat końcowy po odgadnięciu liczby.

## Jak działa gra

    1. Program losuje liczbę z przedziału 1–10.
    2. Użytkownik podaje swoje typy.
    3. Po każdym typie program:
        - zwiększa licznik prób,
        - informuje, czy użytkownik powinien spróbować wyżej lub niżej.
    4. Gdy użytkownik trafi poprawną liczbę, gra kończy się komunikatem z liczbą wykonanych prób.

## Przykładowy przebieg gry

    Zgadnij liczbę z przedziału 1 - 10
    Podaj liczbę: 7
    Niestety wylosowana liczba jest mniejsza od Twojej
    Podaj liczbę: 3
    Niestety wylosowana liczba jest większa od Twojej
    Podaj liczbę: 5
    Brawo!!! Odgadłeś za 3 razem.

## Czego uczy ten projekt

    - pracy z modułem `random`,
    - pętli `while`,
    - instrukcji warunkowych,
    - konwersji danych wejściowych,
    - prostego sterowania logiką gry.

## Uruchamianie

    W terminalu:

        python guessing_game.py

    Plik musi znajdować się w bieżącym katalogu lub należy podać pełną ścieżkę.
