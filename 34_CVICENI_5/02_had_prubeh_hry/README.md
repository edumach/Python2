
# (2) Had – průběh hry

> `"", txt, fx()`

V textovém souboru `had.txt` máme zapsaný průběh her "Had". V každém řádku je zapsán průběh jedné hry. (Jedna hra je posloupnost jednobodových kroků, kterými se pohybovala hlava hada na obrazovce ve čtyřech základních směrech a za sebou zanechávala čáru. Had se neustále pohyboval, klávesami jsme měnili jeho směr a cílem hry bylo co nejdéle nenarazit do nakreslené čáry). Takto nějak by mohly hry vypadat:

![](../img/01.png)

V řádku jsou znaky, které reprezentují směr pohybu hada (`U` – nahoru, `D` – dolů, `L` – vlevo, `R` – vpravo). Jeden znak symbolizuje jeden krok v daném směru. Například: `UUUUDDDDDDLLLLLLLDU`.

Ukázka textového souboru:

```
UUUUDDDDDDLLLLLLLDU
UUUUUUUUUUUUUUUUUUUUUULLLLLLLLLLLLLLLLLDDDDDDDDDDDDDDDRRRRRRRRRR
UUUUUUUUULLLLLLLLLLLLLLLLLDDDDDDDDDDDDDDDRRRRRRRRRR
```

Vytvořte program, který:

- zjistí počet zapsaných her v souboru,
- zjistí, kolik kroků měla nejdelší hra,
- vytvoří kopii textového souboru, kopii vytvoří v komprimovaném tvaru použitím metody opakujících se znaků. Například místo posloupnosti `UUUUDDDDDDLLLLLLLDUU` zapíše do souboru posloupnost `U 4 D 6 L 7 D 1 U 2`.

Otázka:

- Které řešení nám pomůže minimalizovat množství použité paměti?

