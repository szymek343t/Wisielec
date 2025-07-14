# Wisielec (Hangman)

Gra wisielec z interfejsem terminalowym, napisana w Pythonie. Program losuje słowo z bazy nazw zwierząt, a gracz zgaduje je litera po literze.

## Funkcje

- **Losowanie słowa**: Automatyczne wybieranie hasła z bazy 39 nazw zwierząt
- **Wizualizacja wisielca**: Graficzne przedstawienie postępu gry w terminalu
- **Śledzenie stanu gry**: System zliczania błędnych odpowiedzi i pokazywania użytych liter
- **Komunikaty**: Informacje o wygranej/przegranej i błędnych wpisach

## Technologie

- **Język**: Python 3.x
- **Moduły**: random (do losowania słów)

## Struktura kodu

- **hangman_art**: Słownik z grafiką wisielca w 7 etapach
- **words**: Krotka zawierająca 39 nazw zwierząt
- **display_man()**: Funkcja wyświetlająca aktualny stan wisielca
- **display_hint()**: Funkcja pokazująca aktualny stan zgadywanego słowa
- **main()**: Główna pętla gry zarządzająca logiką aplikacji

## Jak uruchomić grę

1. **Sklonuj repozytorium**:
   ```bash
   git clone https://github.com/steedware/Wisielec.git
   cd Wisielec

2. **Uruchom gre**:
```bash
 python hangman.py
