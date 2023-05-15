# Laboratorium 10 - Zadanie

GitHub Actions - przeglad podstawowych rozwiazan

Przebieg zadania:
1. Uzupełnienie pliku: gha_example.yml

2. Dodanie zmian do repo i uruchomienie workflow (screen: L10ss1):
    * Wykonanie commita:
        ```
        git add . && git commit -m "GA test run 2 - example"
        ```

    * Załadowanie zmian do repo git:
        ```
        git push
        ```

    *  Wyświetlenie listy workflow:
        ```
        gh workflow list
        ```

    *  Ręczne uruchomienie workflow:
        ```
        gh workflow run 57306681
        ```

        ```
        gh run watch
        ```

3. Efekt wykonania workflow (L10ss2)