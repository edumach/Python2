
# (50) Obrys obrázku

> `txt, Cnv`

V souboru `obrys_obrazku_1.txt` je zapsán černobílý obrázek (k dispozici jsou i soubory:
`obrys_obrazku_2.txt` a `obrys_obrazku_3.txt`). V prvním řádku souboru jsou rozměry obrázku - první číslo představuje šířku obrázku (počet pixelů v řádku) a druhé číslo představuje jeho výšku (počet pixelů ve sloupci). Každý řádek obrázku je zapsán v samostatném řádku textového souboru. Tyto řádky následují postupně za prvním řádkem s jeho rozměry. První číslo v řádku vyjadřuje počet černých bodů vedle sebe v řádku obrázku. Další číslo vyjadřuje počet bílých bodů vedle sebe v řádku obrázku. Takto se střídají čísla vyjadřující počet bílých a černých bodů v jednom řádku obrázku. Čísla jsou oddělena jednou mezerou.

Vytvořte program, který vykreslí takto zapsaný obrázek. Program bude mít tyto vlastnosti:

- Přečte ze souboru velikost obrázku a podle ní nastaví velikost grafické plochy.
- Přečte první řádek obrázku a vykreslí jej do grafické plochy, vždy nakreslí obdélník velikosti 1x1 pixel jen pro první černý bod, i když jich je v popisu za sebou více.
- Podle údajů v souboru vykreslí do grafické plochy celý obrázek, přičemž program nezatěžuje paměť a všechna data čte a vykresluje přímo ze souboru.
- Po stisku tlačítka **Jinak** vykreslí pouze první bod z počtu bílých bodů jako jeden černý obdélník o velikosti 1&times;1 px, přičemž nesmaže obrázek nakreslený hned po spuštění programu.


Ukážka vstupního textového souboru:

```
20 5
0 3 2 2 8 5
2 3 1 1 3 8 2
0 20
20
7 5 5 3
```

Ukázka zabarvení bodů (B - bílý, Č - černý) po rozkódování vstupního souboru (vykreslujeme pouze první černý a první bílý bod - černou barvou):

```
BBBČČBBČČČČČČČČBBBBB
ČČBBBČBČČČBBBBBBBBČČ
BBBBBBBBBBBBBBBBBBBB
ČČČČČČČČČČČČČČČČČČČČ
ČČČČČČČBBBBBČČČČČBBB
```

Ukázka vykreslení obrázků podle jednotlivých textových souborů. Vlevo jsou po spuštění programu, vpravo po kliknutí na tlačítko Jinak:


<img src="../img/50a.png" height="200">
<img src="../img/50a2.png" height="200">

---

<img src="../img/50b.png" height="200">
<img src="../img/50b2.png" height="200">

---

<img src="../img/50c.png" height="200">
<img src="../img/50c2.png" height="200">

---


Otázky:

1. Pro jaký řádek bude ve vstupním souboru jen jedno číslo?
2. Které řádky budou mít více čísel ve vstupním souboru?
3. Jak bude vypadat nejdelší možný vstupní řádek?
4. Jaký obrázek (při stejné velikosti celkového počtu bodů) bude mít nejkratší vstupní soubor?
5. V jakém vztahu bude velikost vstupního a výstupního souboru?

