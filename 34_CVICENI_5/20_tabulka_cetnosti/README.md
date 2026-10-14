
# (20) Tabulka četností

> `"", [], txt`

Při dešifrování některých šifer nám může pomoci frekvenční analýza zašifrovaného textu. To znamená, že si nejprve zjistíme, jak často se znaky abecedy vyskytují v šifrovaném textu, a to nám může pomoci určit šifru. Vytvořte program, který nám analyzuje vstupní text ze souboru s názvem `tabulka_cetnosti.txt` a provede frekvenční analýzu znaků následovně:

- zobrazí text z textového souboru v terminálu,
- vypíše jednotlivé počty znaků anglické abecedy ve tvaru znak – počet_výskytů; malá a velká písmena nerozlišuje, ostatní znaky ignoruje,
- vypíše seznam znaků, které se v textu vůbec nevyskytly.

Ukázka souboru:

```
THE COMMISSION

Article 1
The Commission shall act collectively in
accordance with these Rules
and in compliance with the political
guidelines laid down by
the President.

Article 2
In compliance with the political guidelines
laid down by the President,
the Commission shall establish its
priorities and each year adopt its
work programme.
```

Ukázka časti výstupu:

```
Počty jednotlivých znaků v textu:
A - 208
B - 63
C - 130
D - 107
E - 434
...
```
