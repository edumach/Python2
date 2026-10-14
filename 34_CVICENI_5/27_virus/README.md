
# (27) Virus

> `"", [], txt, fx()`

Petra má zavirovaný počítač. Virus mění obsah textových souborů. Někdy změní pořadí řádků v souboru, někdy změní pořadí slov v řádku a někdy i otočí celá slova (zapíše je odzadu). Pro zjednodušení řešení považujme za slovo vše, co je zapsáno mezi dvěma mezerami (resp. text na začátku a na konci řádku).

Vytvořte program, který:

- přečte a vypíše textový soubor `virus.txt`,
- se náhodně rozhodne, zda bude měnit pořadí řádků. Změní pořadí řádků, pokud se tak rozhodl.
- pro každý řádek se náhodně rozhodne, zda změní pořadí slov v řádku a pořadí případně změní,
- pro každé slovo se náhodně rozhodne, zda jej otočí. Pokud se tak rozhodl, slovo otočí.
- takto transformovaný text uloží do textového souboru `virus_vystup.txt`.

Ukázka vstupního textového souboru:

```
Detekce a oprava chyb nebo zjišťování a oprava chyb 
(anglicky Error detection and correction, EDAC), 
v širším rámci řízení zabezpečení (anglicky Error control) 
v teorii informace a teorii kódování s aplikacemi
```

Ukázka výstupního textového souboru:

```
Detekce a avarpo byhc nebo zjišťování a avarpo chyb
and ,)CADE detection correction, (anglicky Error
v míšriš rámci ínezíř zabezpečení ykcilgna( rorrE )lortnoc
s kódování v a informace aplikacemi teorii iiroet
```

Otázky:

1. Co udělá program s prázdným řádkem?
2. Je třeba načíst celý textový soubor do paměti? Jaké to má výhody a nevýhody?

