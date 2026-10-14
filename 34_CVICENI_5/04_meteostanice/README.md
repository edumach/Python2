
# (4) Záznamy z meteorologických stanic

> `"", (), [], txt`

V textovém souboru `meteo_stanice.txt` jsou uložena denní měření z meteorologických stanic z celé ČR. Informace z každé stanice je v jednom řádku. Řádek obsahuje: `kód_stanice` (3 znaky), datum ve tvaru `rrrr.mm.dd`, čas ve tvaru `hh:mm`, znaménko teploty, teplotu, typ oblačnosti (`JJ` – jasno, `SZ` – skoro zataženo, `PJ` – polojasno, `OO` – oblačno).

Ukázka vstupního souboru:

```
M01 2017.05.10 06:00 +10,3 SZ
M07 2017.05.10 06:00 +08,2 JJ
M04 2017.05.10 06:00 –01,5 OO
...
```

Vytvořte program, který:

- zjistí počet měření,
- vypíše pouze naměřené teploty,
- zjistí a vypíše nejvyšší naměřenou teplotu,
- zjistí a vypíše kód stanice, kde byla naměřena nejvyšší teplota,
- zjistí a vypíše průměrnou teplotu všech stanic.

Otázky:

- Některé ze vstupních údajů jsou v méně vhodném tvaru pro zpracování v Pythonu. Které údaje to jsou a jak změníme jejich tvar bez editování vstupního souboru?

