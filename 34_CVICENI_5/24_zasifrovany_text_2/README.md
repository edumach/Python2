
# (24) Zašifrovaný text 2

> `"", txt, fx()`

Vytvořte program, který bude šifrovat / dešifrovat textový soubor následujícím způsobem:

- Program šifruje jen znaky malé abecedy bez diakritiky.
- Každé písmeno posune v abecedě o stejnou, předem danou hodnotu (poslední znaky abecedy posouvá na znaky znovu od začátku abecedy).
- Program zadaným posunem (načte jej ze vstupu) zašifruje jeden řádek (načte jej ze vstupu).
- Program čte řádky z textového souboru a každý řádek zašifruje náhodným posunem z intervalu 1 až 25 (celý řádek zašifruje stejným posunem).
- Zašifrované řádky vstupního textového souboru zapíše do výstupního textového souboru, přičemž použitý posun zašifruje na písmeno malé abecedy a přidá jej na začátek zapsaného řádku.
- Program zjistí od uživatele, zda chce textový soubor zašifrovat nebo dešifrovat, a zadaný textový soubor zašifruje/dešifruje do výstupního souboru.

Vstupní nezašifrovaný text se nachází v souboru `vstupni_text.txt`. Zašifrovaný text se nachází v souboru `zasifrovany_text_2.txt`.

Ukázka vstupního textového souboru:

```
CIA dokázala sledovat polohu osoby. Díky Wi-Fi sítím
Jednoduchá, a přitom nenápadná technika umožnila 
pracovníkům CIA sledování cílových osob.
```

Ukázka výstupního textového souboru:

```
oCIA sdzáopap hatsdkpi edadwj dhdqn. Dízn Wx-Fx híiíb
oJtscdsjrwá p eřxidb ctcáepscá itrwcxzp jbdžcxap 
siktvhogídůf CIA lexwhoágí víehoýva hlhu.
```

Otázky:

1.	V čem se liší a co má společné takové šifrování a dešifrování?
2.	Jak se zašifrují znaky s diakritikou?
3.	Může se stát, že stejná písmena se zašifrují na různá písmena?
4.	Jaká bude velikost výstupního souboru v porovnání s velikostí vstupního souboru?
5.	Můžeme při vícenásobném spuštění programu získat různé výstupní soubory? Odpověď zdůvodněte.

