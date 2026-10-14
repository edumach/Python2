
# (12) Vytíženost linky MHD

> `"", [], txt`

Městský dopravní podnik se rozhodl provést průzkum vytíženosti svých linek. Pomocí automatických sčítacích zařízení vznikl soubor `vytizenost.txt`, který má následující tvar:

- v 1. řádku je číslo udávající kapacitu autobusu (max. počet lidí),
- v každém dalším řádku je zapsán počet nastupujících, počet vystupujících na zastávce a název samotné zastávky. Tyto údaje jsou odděleny mezerou.

Ukázka textového souboru:

```
50
20 0 Na stráni
35 0 Městský park
10 20 Jiráskova
40 20 Nemocnice
10 40 U lípy
5 10 Městský úřad
35 10 Poděbradská
0 55 Nové dvory
```

Vytvořte program, který:

- vypíše počet zastávek na trase autobusu,
- vypíše názvy zastávek – název zastávky je jedno- nebo dvouslovný, zastávky budou vypsány v jednom řádku a budou odděleny čárkou,
- vypíše názvy zastávek, kde po nastoupení lidí byl autobus přeplněn (nad povolenou kapacitu),
- vypíše nejvyšší počet lidí nad rámec kapacity, pokud byla v nějakých částech trasy překročena kapacita autobusu.

Otázky:

1. Jaké možné chyby v souboru lze odhalit programem (za předpokladu, že je dodržen formát vstupního souboru)?
2. Co by se změnilo v programu, kdyby byl souboru nejprve název zastávky a až za ním čísla o počtu přistupujících a vystupujících?
