
# (32) Konverze souboru

> `"", txt, fx()`

V souboru `obrazek_1.txt` je zapsán černobílý obrázek (k dispozici jsou i soubory `obrazek_2.txt` a `obrazek_3.txt`). V prvním řádku souboru jsou rozměry obrázku - první číslo představuje šířku obrázku (počet pixelů v řádku) a druhé číslo představuje jeho výšku (počet pixelů ve sloupci). Každý řádek obrázku je zapsán v samostatném řádku textového souboru. Tyto řádky následují postupně za prvním řádkem s jeho rozměry. V řádku obrázku jsou uloženy barvy pixelů (odstín šedé barvy). Barva jednoho pixelu je zapsána dvouciferným číslem v šestnáctkové soustavě, tedy čísla od `00` do `ff`. Barva vyjadřuje odstín šedé barvy (*pouze si připomeňme, že všechny odstíny šedé barvy mají stejnou hodnotu červené, zelené a modré barvy v modelu RGB*). Čísla reprezentující pixely nejsou v řádku ničím oddělena (následují těsně za sebou).

Ukázka formátu textového souboru:

```
20 5
ffa315070300aa0000000000000000ffffffffff
00000000000000000000afbfcfdfef0000000000
0000000000ffffffffff0000000000ffffffffff
ffffffffff0000000000ffffffffff000000ffff
00102030405060708090a0b0c0d0e0f0001f2f3f
```

Vytvořte program, který:

- přečte a vypíše ze souboru šířku a výšku obrázku a počet všech bodů,
- přečte první řádek obrázku a pošle jej ke zpracování funkci `zpracuj_radek()`,
- obsahuje funkci `zpracuj_radek()`, která z textového řetězce - posloupnosti barev odstínů šedé
vyrobí výstup - textový řetězec z `0` a `1`. Na výstupu budou `0` a `1` odděleny mezerou. Čísla šestnáctkové soustavy, která jsou v první polovině (tmavší barvy), se transformují na nulu, a čísla, která jsou v horní polovině (světlejší odstíny), se transformují na číslo 1.
- přečte všechny řádky souboru, transformuje je pomocí funkce `zpracuj_radek()` a vytvoří nový textový soubor s názvem `konverze_souboru_1_vystup.txt`. I ve výstupním souboru bude v prvním řádku uložena velikost obrázku.

Ukázka formátu výstupního textového souboru:

```
20 5
1 1 0 0 0 0 1 0 0 0 0 0 0 0 0 1 1 1 1 1
0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 0 0 0 0 0
0 0 0 0 0 1 1 1 1 1 0 0 0 0 0 1 1 1 1 1
1 1 1 1 1 0 0 0 0 0 1 1 1 1 1 0 0 0 1 1
0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 0 0 0 0
```

Otázky:

1. Jak výrazně by se změnila velikost vstupního souboru, pokud by byly jednotlivé barvy pixelů odděleny například mezerou?
2. Zhodnoťte, zda je vhodnější v takových textových souborech používat čísla v šestnáctkové nebo desítkové soustavě.
3. Jak bychom zjistili číslo nejtmavší použité barvy?
4. V jakém vztahu je velikost vstupního a výstupního souboru?

