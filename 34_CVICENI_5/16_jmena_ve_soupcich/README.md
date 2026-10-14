
# (16) Jména ve sloupcích

> `"", [], txt`

Vytvořte program, který zpracuje export jmen zaměstnanců z informačního systému společnosti. Ze vstupního souboru chceme vytvořit přehlednější dvousloupcovou tabulku. V něm budou jména pod sebou a u jmen budou příjmení zarovnána mezerami ve sloupci pod sebou (viz příklad). Seznam zaměstnanců v textovém souboru jmena_zamestnancu.txt obsahuje nejprve pouze jména (v každém řádku jedno jméno – může být víceslovné) a na dalších řádcích jsou pouze odpovídající příjmení (pořadí jmen a příjmení je zachováno).

Příklad textového souboru:

```
Mária Lujza
Andrej
Jean Michel
Phillippe
Poláková
Velký
Portree
de Ryannitto
```

Vytvořte program, který:

- vypíše počet jmen v souboru, 
- vypíše délku nejdelšího křestního jména (více křestních jmen považujeme za jedno delší křestní jméno) a nejdelšího příjmení, 
- vytvoří výsledný soubor vystup.txt podle zadání.

Správný výstupní soubor:

```
Mária Lujza Poláková
Andrej      Velký
Jean Michel Portree
Phillippe   de Ryannitto
```

Otázka:

- Jak je třeba změnit program, chceme-li v délce křestního jména zjistit i délku jednotlivých křestních jmen jednoho zaměstnance?
