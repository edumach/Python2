
# (23) Zašifrovaný text 1

> `"", txt, fx()`

Vytvořte program, který bude šifrovat / dešifrovat textový soubor následujícím způsobem:

- Od uživatele program načte šifrovací klíč. Klíčem je slovo složené z malých písmen bez diakritiky.
- Od uživatele načte textový řetězec. Vstupní řetězec zašifruje. Šifruje pouze písmena malé abecedy (bez diakritiky). 
- Každý znak zašifruje posunem v malé abecedě, přičemž velikost posunu je dána klíčem (příslušným písmenem z klíče). Například písmeno `c` v klíči znamená, že vstupní znak posuneme v abecedě o pozici `c`, tedy o 3 znaky. Následující znak zašifruje posunem následujícího znaku v klíči. V případě, že posun je za poslední písmeno abecedy, posune ho na první písmena v abecedě (dle daného posunu).

    ```
    vstup:           programujeme v pythonu
    klíč:            abc
    přiložený klíč:  abcabcabcabcabcabcabca
    posun:           1231231231-3-231231231
    výstup:          qtrhtdnwmfoh x qawiqqv
    ```

- Program čte řádky z textového souboru a každý řádek zašifruje (od uživatele zjistí klíč). V řádku šifruje pouze písmena malé abecedy (bez diaktiriky). Zašifrovaný text zapíše do souboru.
- Program zjistí od uživatele, zda chce textový soubor zašifrovat nebo dešifrovat, zjistí klíč a zadaný textový soubor zašifruje/dešifruje do výstupního souboru.
Vstupní nezašifrovaný text se nachází v souboru `vstupni_text.txt`. Zašifrovaný text s klíčem abc se nachází v souboru `zasifrovany_text_1.txt`.

Otázky:

1.	V čem se liší a co má společné takové šifrování a dešifrování?
2.	Jak se zašifrují znaky s diakritikou?
3.	Proč se může stát, že stejná písmena se zašifrují na různá písmena?
4.	Co se stane, když je klíč delší než vstupní řetězec?
5.	Můžeme při použití stejného klíče dostat různé zašifrované výstupy? Odpověď zdůvodněte.

