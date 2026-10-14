
# (28) SMS hlasování 1

> `"", (), [], txt`

V textovém souboru `hlasovani_1.txt` (k dispozici je také soubor `hlasovani_2.txt`) je uložen průběh SMS hlasování diváků v reality show. V každém řádku je uloženo právě jedno telefonní číslo, na které přišla SMSka. Diváci mohli hlasovat na čísla `5220` až `5229`. V textovém souboru `hlasovani_vypadli.txt` je seznam již vypadlých hráčů (jejich hlasovací čísla, každé je na samostatném řádku).

Ukázka části vstupního textového souboru `hlasovani_1.txt`:

```
5225
5227
5225
5224
5225
5227
...
```

Ukázka textového souboru `hlasovani_vypadli.txt`:

```
5227
5224
```

Vytvořte program, který zjistí a vypíše:

- celkový počet zaslaných SMS,
- kolik hlasů dostal každý ze soutěžících,
- který soutěžící obdržel nejméně hlasů, a tudíž nepostupuje do dalšího kola, 
- který soutěžící obdržel nejméně hlasů, a tudíž nepostupuje do dalšího kola, přičemž nebere v úvahu hlasy zaslané vypadlým soutěžícím.

Otázka:
- Co se stane, pokud soubor `hlasovani_vypadli.txt` bude prázdný?