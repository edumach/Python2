
# (29) Komprese obrázku

> `"", txt, fx()`

V souboru `obrazek_1.txt` je zapsán černobílý obrázek (k dispozici jsou i soubory `obrazek_2.txt` a `obrazek_3.txt`). V prvním řádku souboru jsou rozměry obrázku - první číslo představuje šířku obrázku (počet pixelů v řádku) a druhé číslo představuje jeho výšku (počet pixelů ve sloupci). Každý řádek obrázku je zapsán v samostatném řádku textového souboru. Tyto řádky následují postupně za prvním řádkem s jeho rozměry. Řádek obrázku je zapsán čísly `0` a `1`, přičemž `0` představuje černou barvu a `1` bílou. Čísla nejsou ničím oddělena.

Vytvořte program, který komprimuje zápis nul a jednotek. Program bude mít tyto vlastnosti:

- Přečte a vypíše ze souboru šířku a výšku obrázku a počet všech bodů.
- Přečte první řádek obrázku a pošle jej ke zpracování funkci `zpracuj_radek()`.
- Obsahuje funkci `zpracuj_radek()`, která z posloupnosti nul a jedniček vytvoří výstupní textový řetězec. Ve výstupu budou za sebou jdoucí nuly nahrazeny jejich počtem a rovněž za sebou jdoucí
jedničky budou nahrazeny jejich počtem. Na začátku výstupního řetězce bude počet nul na začátku vstupního řetězce. V případě, že vstupní řetězec začíná jedničkami, na začátku výstupního řetězce
bude 0, vyjadřující nula nul na začátku vstupu.
- Přečte všechny řádky souboru, transformuje je pomocí funkce `zpracuj_radek()` a vytvoří nový textový soubor s názvem `komprese_obrazku_vystup.txt`. I ve výstupním souboru bude v
prvním řádku uložena velikost obrázku.

Ukázka vstupního textového souboru:

```
20 5
11100110000000011111
00111010001111111100
11111111111111111111
00000000000000000000
00000001111100000111
```

Ukázka výstupního textového souboru:

```
20 5
0 3 2 2 8 5
2 3 1 1 3 8 2
0 20
20
7 5 5 3
```

Otázky:

1. Pro jaký řádek bude ve výstupním souboru jen jedno číslo?
2. Jaké řádky budou mít více čísel ve výstupním souboru?
3. Jak bude vypadat nejdelší možný výstupní řádek?
4. Jaký obrázek (při stejné velikosti celkového počtu bodů) bude mít nejkratší výstupní soubor?

