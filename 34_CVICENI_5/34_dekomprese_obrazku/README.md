
# (34) Dekomprese obrázku

> `"", [], txt, fx()`

V souboru `obrazek_1.txt` je zapsán černobílý obrázek (k dispozici jsou i soubory `obrazek_2.txt` a `obrazek_3.txt`). V prvním řádku souboru jsou rozměry obrázku - první číslo představuje šířku obrázku (počet pixelů v řádku) a druhé číslo představuje jeho výšku (počet pixelů ve sloupci). Každý řádek obrázku je zapsán v samostatném řádku textového souboru. Tyto řádky následují postupně za prvním řádkem s jeho rozměry. První číslo v řádku vyjadřuje počet černých bodů vedle sebe v řádku obrázku. Další číslo vyjadřuje počet bílých bodů vedle sebe v řádku obrázku. Takto se střídají čísla vyjadřující počet bílých a černých bodů v jednom řádku obrázku. Čísla jsou oddělena jednou mezerou.

Vytvořte program, který dekomprimuje takto zapsaný obrázek a vytvoří z něj posloupnost nul a jedniček (nula je černý bod a jednotka bílý bod). Program bude mít tyto vlastnosti:

- přečte a vypíše ze souboru šířku a výšku obrázku a počet všech bodů,
- přečte první řádek obrázku a pošle jej ke zpracování funkci `zpracuj_radek()`,
- obsahuje funkci `zpracuj_radek()`, která z posloupnosti čísel vyrobí výstupní textový řetězec. Ve výstupním řetězci budou jen nuly nebo jednotky.
- přečte všechny řádky souboru, transformuje je pomocí funkce `zpracuj_radek()` a vytvoří nový textový soubor s názvem obrazek_vystup.txt. I ve výstupním souboru bude v prvním řádku uložena velikost obrázku.

Ukázka vstupního textového souboru:

```
20 5
0 3 2 2 8 5
2 3 1 1 3 8 2
0 20
20
7 5 5 3
```

Ukázka výstupního textového souboru:


```
20 5
11100110000000011111
00111010001111111100
11111111111111111111
00000000000000000000
00000001111100000111
```

Otázky:

1. Pro jaký řádek bude ve vstupním souboru jen jedno číslo?
2. Jaké řádky budou mít více čísel ve vstupním souboru?
3. Jak bude vypadat nejdelší možný vstupní řádek?
4. Jaký obrázek (při stejné velikosti celkového počtu bodů) bude mít nejkratší vstupní soubor?
5. V jakém vztahu bude velikost vstupního a výstupního souboru?
