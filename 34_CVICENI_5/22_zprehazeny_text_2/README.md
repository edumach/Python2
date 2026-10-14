
# (22) Zpřeházený text 2

> `"", [], txt`

Výzkumy ukázaly jednu zajímavou věc. Člověk dokáže přečíst slova i bez toho, aby jednotlivá písmena dávala smysl. Je to způsobeno tím, že mozek čte slova jako celek, ne po jednotlivých písmenech. Stačí, aby bylo první a poslední písmeno na stejném místě, tak jako v klasickém slově. Anglicky se to nazývá *Scrambled text*.

V textovém souboru `zprehazeny_text.txt` je připraven vstupní soubor.

Vytvořte program, který:

- přečte a vypíše textový soubor,
- v textu identifikuje jednotlivá slova, přičemž nebude brát jiné znaky než součást slova – například interpunkční znaménka, číslice apod. Tyto znaky se nacházejí pouze na začátku nebo konci slova a nejsou umístěny v textu samostatně, 
- ve slově náhodně zpřehazuje písmena, kromě prvního a posledního písmena, 
- na zpřeházení využijte připravenou funkci `zamichej`, 
- takto transformovaný text vypíše na obrazovku, součástí transformovaného textu budou i původní znaky (např. interpunkční znaménka), 
- takto transformovaný text uloží do textového souboru `zprehazeny_text_vystup.txt`.
import random

```py
def zamichej(retezec):
    pismena = list(retezec)
    random.shuffle(pismena)
    return ''.join(pismena)
```

Ukázka vstupního textového souboru:

```
Výzkumy prozradily jednu zajímavou věc
Člověk dokáže přečíst slova i bez toho
aby jednotlivá písmena dávala smysl
```

Ukázka výstupního textového soboru:

```
Vumzýky pirozldray jednu zmíoaajvu věc
Čoěvlk doákže pčíesřt solva ii bez thoo
aby jovnitedlá penímsa davála ssyml
```

Otázka:
- Která slova se nebudou jevit jako zpřeházená ve výstupním textu?

