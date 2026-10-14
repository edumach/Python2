
# (45) Učení slovíček

> `"", [], txt`

V textovém souboru `slovicka.txt` jsou ve dvou po sobě jdoucích řádcích uloženy dvojice slov - české slovo a anglické slovo.

Ukázka textového souboru:

```
obdélník
rectangle
čtverec
square
trojúhelník
triangle
čára
line
```

Vytvořte program pro učení se slovíček v textovém režimu s vlastnostmi:

- Program přečte všechna slovíčka do paměti. Hráč si vybere, zda má program zadávat české nebo anglické slovo.
- Program postupně zadá všechna slovíčka dle výběru zadaného jazyka a přečte odpověď.
- Když slovo zadáme nesprávně, program nás z něj po vyzkoušení všech slov znovu vyzkouší (pokud jich je více, pak ze nesprávných).
- Program nás zkouší slovíčka, dokud nezadáme správně všechna slovíčka v souboru, v závěru nám vypíše počet nesprávných odpovědí.

Otázky:

1. Jak bychom zamíchali pořadí zkoušených slov?
2. Jakými různými způsoby můžeme číst soubor? Který způsob bude vhodnější a proč?