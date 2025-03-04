# Zadanie 4 

## Kompilacja

Projekt **COMLab1_4** jest projektem biblioteki, co oznacza, że nie można go uruchomić bezpośrednio.  

Aby skompilować projekt, wykonaj następujące kroki:

### Kroki do wykonania

1. W **Eksploratorze rozwiązań** znajdź projekt **COMLab1_4**.
2. Kliknij **prawym przyciskiem myszy** na projekt **COMLab1_4**.
3. Wybierz opcję **Kompiluj**.
4. Po zakończeniu procesu w katalogu `Debug` powinien pojawić się skompilowany plik `COMLab1_4.dll`.

![image](https://github.com/user-attachments/assets/bcb43649-baf0-403c-a243-c0a4340813da)

## Rejestracja biblioteki

Po zakończeniu kompilacji konieczne jest zarejestrowanie biblioteki w systemie:  
Analogicznie jak w **Zadaniu 1**.

1. Otwórz odpowiedni plik rejestru w edytorze:
 - **Dla systemów 32-bit**: `rej_3.reg`
 - **Dla systemów 64-bit**: `rej3_64.reg`
2. Znajdź linię zawierającą ścieżkę do **`COMLab1_4.dll`**.
3. Zmień ścieżkę na rzeczywistą lokalizację skompilowanej biblioteki.  
 **Uwaga**: W plikach `.reg` przy podawaniu ścieżki znak `\` musi być podwójny `\\`.
4. Uruchom plik `.reg`

## Test
Test działania będzie w zadaniu 5.
