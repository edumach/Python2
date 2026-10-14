
# (17) Tajná tabulka

> `"", []`

Dva kamarádi se dohodli, že si budou posílat zašifrovaný text. Text budou kódovat po znacích tak, že každé písmeno nahradí číslem políčka ve své tajné tabulce. Tabulka má 10 políček očíslovaných `0` až `9`. V každém políčku tajné tabulky jsou tři za sebou jdoucí velké znaky anglické abecedy (v posledním políčku pouze poslední dvě písmena abecedy). Mezera má samostatné políčko s číslem `0` – viz ukázka tabulky. Jelikož každé políčko kromě nultého obsahuje více znaků, tak číslo políčka se zobrazí dvojmo, pokud jde o druhé písmeno z políčka, resp. trojmo, jde-li o třetí písmeno (viz ukázka vstupu a výstupu).

| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| mezera | ABC | DEF | GHI | JKL | MNO | PQR | STU | VWX | YZ |

Vytvořte program, který:

- načte větu ze vstupu (předpokládejme, že uživatel zadá pouze velká písmena a mezery), zašifruje ji na čísla políček podle zadání a vypíše zašifrovanou větu na obrazovku,
- vypíše na obrazovku informaci o tom, které číslo políčka se v šifru vyskytlo nejčastěji, pokud je takových políček více, vypíše čísla všech políček.

Ukázka vstupu:

```
JAK SE MAS
```

Příklad zašifrované věty:

```
4 1 44 0 7 22 0 5 1 7 
Nejčastěji zvolená políčka: 4
```

Otázky:
1.	Co můžeme udělat se zadanou větou, pokud obsahuje i jiné znaky než velká písmena a mezery?
2.	Porovnáme-li délku vstupu a délku výstupu, v jakém budou vztahu?
3.	Je třeba, aby ve výstupu byla čísla oddělena mezerami?

