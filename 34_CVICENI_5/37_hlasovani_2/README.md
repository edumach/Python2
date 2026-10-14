
# (37) Hlasování 2

> `"", [], txt`

V textovém souboru `hlasovani_1.txt` (k dispozici je také soubor `hlasovani_2.txt`) je uložen průběh SMS hlasování diváků v reality show. V každém řádku je uloženo právě jedno telefonní číslo, na které přišla SMSka. Diváci mohli hlasovat na čísla `5220` až `5229`. Organizátor soutěže chce jednotlivým soutěžícím poskytnout informaci, v jakém časovém sledu (pořadí) obdrželi oni SMS. Z těchto informací může soutěžící zjistit, zda mu posílali SMS dříve v úvodu soutěže nebo např. v závěru.

Ukázka části vstupního textového souboru `hlasovani_1.txt`:

```
5225
5227
5225
5224
5225
5227
```

Vytvořte program, který:

- zjistí a vypíše celkový počet zaslaných SMS,
- vytvoří textový soubor `5220.txt`, kde na samostatných řádcích budou pořadová čísla zaslaných SMS z celého hlasování, ale jen ta, která obdržel soutěžící `5220`,
- vytvoří textové soubory `5221.txt` až `5229.txt` s pořadovými čísly zaslaných SMS z celého hlasování, které obdržel daný soutěžící.

Ukázka části výstupního textového souboru `5225.txt` k části vstupního souboru z předchozí ukázky:

```
1
3
5
```

Otázka:

- Co se stane, když některý ze soutěžících nedostal žádný hlas?
