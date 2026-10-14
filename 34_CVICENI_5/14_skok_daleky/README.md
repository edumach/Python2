
# (14) Skok do dálky

> `(), [], {}, txt`

Mezinárodní světová sportovní organizace vyhlásila celosvětový závod ve skoku do dálky amatérů. Každý soutěžící měl pět pokusů. Vyhrál soutěžící, který skočil nejdál v rámci svých pěti pokusů. Sportovní výsledky všech zúčastněných jsou v textového souboru `pokusy.txt`. Každý řádek souboru má následující formát:

```
Jméno kod_země vykon1 vykon2 vykon3 vykon4 vykon5
```

přičemž jméno je jednoslovné (neobsahuje mezery), kód země sestává ze tří velkých písmen anglické abecedy a výkony jsou celá čísla (jsou od sebe odděleny mezerou):

```
Larson SVE 580 570 574 585 599
Polanski POL 588 583 592 590 601
...
```

Vytvořte program, který:

- vypíše seznam zemí, ze kterých byli sportovci účastníky soutěže,
- vypíše počty soutěžících z jednotlivých zemí,
- vypíše jméno celkového vítěze – kdo skočil nejdál. Pokud jich bylo víc, vypíše všechny.

