# Banking_System

* ### Jak uruchomic program:

    - Aby uruchomic program, nalezy wykonac:   make run
    - Aby skompilowac program, nalezy wykonac:  make all
    - Aby wyczyscic zawartosc ktalogu (usunac zbedne pliki), 
        nalezy wykonac:   make clean

* W projekcie zostaly uzyte elementy z C++20 dlatego do kompilacji 
  nalezy uzyc g++ w wersji 10.

----------------------------------------------------------------------------------

* ### O projekcie:
    Projekt stanowi implementacje systemu bankowego. 
    Mozliwe sa dwa widoki: klienta oraz pracownika. 
    Do poziomu pracownika mozna sie dostac przez zalogowanie sie na odpowiednie 
    konto pracownicze. Tych kont nie mozna tworzyc z poziomu programu. 
    Widok pracownika pozwala na wyszukiwanie rekordu po loginie i wyswietlanie 
    danych o wybranym kliencie. 
    Do poziomu klienta mozna przejsc na 2 sposoby: logujac sie do istniejacego 
    juz konta lub tworzac nowe podczas rejestracji. Klient ma mozliwosc 
    wyswietlenia danych o swoim koncie, zaciagniecia pozyczki, wyplaty pieniedzy 
    ze swojego konta lub wykonania przelewu na podany nrumer konta bankowego.

----------------------------------------------------------------------------------
