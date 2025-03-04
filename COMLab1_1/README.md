# Zadanie 1 - Konfiguracja ścieżki do `serwerInProc.dll`

## Instrukcja

Aby poprawnie uruchomić projekt, należy zmienić ścieżkę do pliku **`serwerInProc.dll`** w odpowiednim pliku rejestru:

- **Dla systemów 64-bit**: edytuj plik `rej64.reg`.
- **Dla systemów 32-bit**: edytuj plik `rej.reg`.

## Kroki do wykonania

1. Otwórz odpowiedni plik (`rej64.reg` lub `rej.reg`).
2. Znajdź linię zawierającą ścieżkę do **`serwerInProc.dll`**.
3. Zmień ścieżkę na prawidłową zgodnie z lokalizacją pliku `serwerInProc.dll`.  
   **Uwaga**: W plikach `.reg` znak `\` musi być zapisany podwójnie jako `\\`.
4. Uruchom plik plik (`rej64.reg` lub `rej.reg`).

## Usunięcie z rejestru

Uruchom plik `unrej64.reg` lub `unrej.reg`.
