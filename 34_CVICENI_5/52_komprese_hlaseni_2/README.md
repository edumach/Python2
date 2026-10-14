

# (52) Komprese hlášení 2

> `"", []`

Hlášení pro cestující, které se zobrazují na informačních obrazovkách ve stanicích příměstských vlaků, se z počítače do samotných obrazovek přenášejí co nejúsporněji. Jedná se totiž o starší zařízení s delší životností. Proto také systém podporuje pouze znaky anglické abecedy. Obslužný program proto nejprve text zadaný dispečerem "stlačí", odešle zařízení, a to jej zobrazí v původním tvaru, překonvertován plně na velká písmena. 

Stlačení textu probíhá tak, že program vynechá mezery z oznámení. Aby však tato oznámení zůstala čitelná, bude každé slovo oznámení začínat velkým písmenem a pokračovat pouze malými písmeny.

Například větu:

```
Pres vikend je planovana odstavka severni casti linky
```

lze zapsat ve tvaru:

```
PresVikendJePlanovanaOdstavkaSeverniCastiLinky
```

- vypíše, z kolika slov sestává oznámení,
- upraví (stiskne) daný text podle zadání a vypíše jej na obrazovku,
- simuluje příjem stlačeného textu a jeho zobrazení na informační tabuli – tedy ze stlačeného formátu zpětně vytvoří řetězec s původním oznámením (slovy oddělenými mezerou) zapsaným pouze velkými písmeny.

Příklad:

```
Zadejte informaci pro cestující: Pres vikend je planovana odstavka severni casti linky
Počet slov: 8
Stlačená zpráva: PresVikendJePlanovanaOdstavkaSeverniCastiLinky
Na obrazovce: PRES VIKEND JE PLANOVANA ODSTAVKA SEVERNI CASTI LINKY
```
