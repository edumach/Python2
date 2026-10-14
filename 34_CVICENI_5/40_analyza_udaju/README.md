

#  (40) Analýza údajů

> `"", [], txt`

Lokální potraviny se rozhodly, že zjistí spokojenost s poskytnutými službami u svých zákazníků. Při východu z prodejny nainstalovali box, ve kterém zákazník vyjádří svou spokojenost/nespokojenost pomocí dotykové obrazovky. Všechna vyjádření se zapíší do textového souboru. Vyjádření jsou v textovém souboru `spokojenost_1.txt` (k dispozici jsou i soubory `spokojenost_2.txt` a `spokojenost_3.txt`). Na každém řádku je jedno vyjádření zákazníka. Vyjádření obsahuje čas zaznamenání ve tvaru `HH:MM`, poté následuje jedna mezera a text `ano` nebo `ne` podle toho, zda byl zákazník spokojen nebo nespokojen. V souboru jsou vyjádření z více dnů.

Ukázka části vstupního textového souboru `spokojenost_1.txt`:

```
08:39 ano
06:47 ano
10:52 ano
14:55 ne
15:30 ne
10:53 ano
```

Ukázka výstupu:

```
1. den - počet reakcí: 2
2. den - počet reakcí: 1
3. den - počet reakcí: 1
4. den - počet reakcí: 2
Počet všech vyjádření: 6
Hodina: 7 Reakcí zákazníků: 1
Hodina: 8 Reakcí zákazníků: 1
Hodina: 14 Reakcí zákazníků: 1
Hodina: 15 Reakcí zákazníků: 3
Počet dní: 4
```

Vytvořte program, který zjistí a vypíše:

- celkový počet vyjádření,
- počet všech vyjádření v jednotlivých hodinách dne, ale pouze v těch hodinách, kdy byla nějaká vyjádření,
- počet dní, během kterých se sbírala vyjádření (předpkládejme, že každý den bylo zaznamenáno alespoň jedno vyjádření a že vstupní data jsou zapsána v takovém pořadí, jak byla zrealizována),
- počet vyjádření v jednotlivých dnech.




