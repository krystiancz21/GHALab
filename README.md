# Laboratorium 10 - Zadanie

GitHub Actions - przeglad podstawowych rozwiazan

Przebieg zadania:
1. Uzupełnienie pliku: gha_example.yml

2. Dodanie zmian do repo i uruchomienie workflow (screen: L10ss1):
![image](https://github.com/krystiancz21/GHALab/blob/486d0e95f46b3fcb8e891d37a490a67ff6187a8d/L10ss1.png)
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
![image](https://github.com/krystiancz21/GHALab/blob/486d0e95f46b3fcb8e891d37a490a67ff6187a8d/L10ss2.png)

4. Obrazy z lab na DockerHub:
   * https://hub.docker.com/r/s95382/ghlab10example/tags
   * https://hub.docker.com/r/s95382/lab/tags
