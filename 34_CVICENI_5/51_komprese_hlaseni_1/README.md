

# (51) Komprese hlášení 1

> `"", []`

Hlášení pro cestující, které se zobrazují na informačních obrazovkách ve stanicích příměstských vlaků, se z počítače do samotných obrazovek přenášejí co nejúsporněji. Jedná se totiž o starší zařízení s delší životností. Proto také systém podporuje pouze znaky anglické abecedy. Obslužný program proto nejprve text zadaný dispečerem "stlačí", odešle zařízení, a to jej zobrazí v původním tvaru, překonvertovaný pouze na velká písmena. "Stlačení" textu probíhá tak, že program vynechá mezery v textu hlášení. Aby však tato hlášení zůstala čitelná, budou slova hlášení zapsána střídavě velkými a malými písmeny.

Například větu:

```
Pres vikend je planovana odstavka severni casti linky
```

lze zapsat ve tvaru:

```
PRESvikendJEplanovanaODSTAVKAseverniCASTIlinky
```

Váš program načte od uživatele jeden řádek s informací pro cestující. Informace může obsahovat pouze malá a velká písmena a mezery. Vytvořte program, který:

- vypíše, z kolika slov sestává oznámení,
- upraví (stlačí) daný text podle zadání a vypíše jej na obrazovku,
- simuluje příjem stlačeného textu a jeho zobrazení na informační tabuli – tedy ze stlačeného formátu zpětně vytvoří řetězec s původním oznámením (slovy oddělenými mezerou) zapsaný pouze
velkými písmeny.

Příklad:

```
Zadejte informaci pro cestující: Pres vikend je planovana odstavka severni casti linky
Počet slov: 8
Stlačená zpráva: PRESvikendJEplanovanaODSTAVKAseverniCASTIlinky
Na obrazovce: PRES VIKEND JE PLANOVANA ODSTAVKA SEVERNI CASTI LINKY
```

