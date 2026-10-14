
# (11) Běžecký závod

> `(), [], txt`

Závodu se zúčastnilo mnoho sportovců. Organizátor zakoupil zařízení, které dokáže automaticky rozpoznat sportovce, který doběhne do cíle a zaznamenat jeho čas v sekundách. Takto zaznamenané výsledky ukládá do řádků textového souboru `vysledky.txt`. V každém řádku je uvedeno příjmení sportovce (jednoslovné) a jeho naměřený čas v sekundách.

Ukázka textového souboru:

```
Peterson 272
Koloman 233
Amundsen 272
...
```

Vytvořte program, který:

- vypíše počet sportovců ve tvaru:
Počet zúčastněných sportovců: 32
- přehledně vypíše seznam sportovců a jejich výkonů ve tvaru:

```
Soutěžící Majerský doběhl do cíle za 272 sekund
Soutěžící Moravec doběhl do cíle za 234 sekund
...
```

- vypíše jméno nejlepšího soutěžícího, (můžete předpokládat, že bude pouze jeden),
- ke jménu vítěze dopíše jeho čas ve tvaru: `3 min a 53 sec`.
