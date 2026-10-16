# Moje wykonanie Lab00

- Login GitHub / pseudonim: jerzy-kisielewski
- System i terminal (np. Windows + WSL Ubuntu): Ubuntu
- Edytor / IDE: nano oraz te od jetbrains
- Wersja Git: 2.43.0
- Wersja kompilatora C++: 13.3.0
- Wersje java i javac: 17.0.20.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): ...

## Uruchomienie lokalne
Wynik programu C++:
```Hello C++! Author: Jerzy
...
```
Wynik programu Java:
```Hello Java! Author: Jerzy
...
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: cpp/main.cpp: In function ‘int main()’:
cpp/main.cpp:5:57: error: expected ‘;’ before ‘return’
    5 |     std::cout << "Hello from C++! Author: Jerzy" << '\n'
      |                                                         ^
      |                                                         ;
    6 |     return 0;
      |     ~~~~~~                                               
Error: Process completed with exit code 1.

- Przyczyna oraz sposób naprawy: brak średnika na końcu lini 5, dodanie średnika na końcu linii 5
- Commit z błędem (SHA lub link): https://github.com/jerzy-kisielewski/oop-lab00-jerzy-kisielewski/commit/30d7a128fa406eb6236c5f50f5521cd1b189db6a
- Czy Actions pokazały błąd, a po naprawie sukces? tak

## Krótkie odpowiedzi
1. Co różni commit od push? Commit zatwierdza zmiany, push przesyła je na zdalne repozytorium
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Żeby pobrać aktualną wersję repozytorium
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Potwierdza poprawną kompilację, nie potwierdza poprawnego działania programu

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: ...
