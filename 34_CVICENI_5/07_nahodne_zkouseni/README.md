
# (7) Náhodné zkoušení

> `"", []`

Vytvořte program, který bude sloužit jako pomůcka pro učitele při ústním zkoušení. Předpokládejme, že ve třídě je **30 studentů** a každý student odpovídá z předem připravených **50 otázek**. Pro zjednodušení má každý student přiděleno číslo (podle abecedy, začíná číslem 1 a končí číslem 30). Otázky jsou číslovány čísly 1 až 50.

Program má následující vlastnosti:

- vypíše náhodné pořadí, ve kterém půjdou studenti odpovědět,
- ke každému studentovi vypíše i náhodné číslo otázky na kterou bude odpovidat,
- otázky, ze kterých studenti odpovídají, se nesmí opakovat,
- programu můžeme zadat počet studentů ve třídě a také počet otázek. Program zjistí, zda není počet otázek menší než počet studentů, a na takovou chybu nás upozorní.
- z důvodu překrývání se témat otázek, v náhodném pořadí zadaných otázek nemohou jít za sebou dvě sudá a dvě lichá čísla otázek (pravidelně se střídají sudá a lichá čísla otázek). Tuto vlastnost doplňte do hotového programu tak, abychom ji mohli pouhým zakomentováním (pouze té doplněné části) v programu nepoužít.

Ukázka vstupu a výstupu kompletně vyřešeného programu:

```
Zadej počet studentů: 8
Zadej počet otázek: 20
Pořadí odpovídajících a jejich číslo otázky:
1. student: 1, otázka: 12
2. student: 6, otázka: 1
3. student: 3, otázka: 14
4. student: 4, otázka: 13
5. student: 2, otázka: 16
6. student: 5, otázka: 5
7. student: 8, otázka: 2
8. student: 7, otázka: 7
```


