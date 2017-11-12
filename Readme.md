Testovací skript na POP3 server v ISA
=====================================

Několik málo testů na POP3 server

Použití
-------

1. Před prvním testovacího skriptu spusťe `./make-dirs.sh`, který vytvoří
    potřebné podadresáře v adresáři Maildir *(git nepodporuje nahrávání
    prázdných adresářů)*.
2. Pokud není váš `popser` přeložený, přeložte ho.
3. Umístěte složku s testovacím skriptem do složky s projektem tak, aby
    se binární soubor `popser` nacházel v nadřazeném adresáři od adresáře
    s testovacím skriptem, nebo upravte cestu k binárce v souboru `test.py`.
4. Server není třeba spouštět, testovací skript si ho pustí sám.
5. Spusťte testovací skript:
        
        ./test.py
