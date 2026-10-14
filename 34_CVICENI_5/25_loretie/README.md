
# (25) Loterie

> `"", [], txt, fx()`

Vytvořte program pro simulaci číselné loterie. V loterii se losuje 6 čísel z čísel od 1 do 49. Vytvořte program, který:

- na vstupu přečte tipy na šest čísel od uživatele. Uživatel zadává čísla v jednom vstupním řádku a oddělí je mezerami,
- simuluje losování a vypíše 6 vylosovaných čísel,
- porovná tipy uživatele s losováním a zobrazí uhodnutá čísla a počet uhodnutých čísel,
- porovná vylosovaná čísla se všemi tipy účastníků loterie. Tipy účastníků loterie jsou uvedeny v textovém souboru `loterie_2.txt` (tipy menšího počtu účastníků se nacházejí v souboru `loterie_1.txt`). Na každém řádku je 6 čísel. Čísla jsou oddělena mezerou. Jeden řádek reprezentuje jedno tipování jednoho účastníka,
- vypíše počet účastníků, kteří správně tipovali právě jedno číslo, právě dvě čísla, právě tři čísla, právě pět čísel, a právě šest čísel.

Ukázka vstupního textového souboru `loterie_1.txt`:

```
32 49 38 11 13 15
40 48 36 27 43 26
8 31 2 40 48 42
19 25 4 12 3 46
20 30 42 43 35 48
21 41 25 32 6 4
40 13 33 29 1 46
...
```

Otázky:

1.	Můžeme tipy a losování porovnat i bez seřazení čísel?
2.	Jak zajistíme, aby se v losování čísla neopakovala?

