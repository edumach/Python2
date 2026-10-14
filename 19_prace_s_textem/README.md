
# Lekce 19: Pracujeme s textem <!-- omit in toc -->


---

- [1. Textové řetězce](#1-textové-řetězce)
- [2. ❓Otázky](#2-otázky)
- [3. 💾 Úkoly](#3--úkoly)


---

# 1. Textové řetězce
Doposud jsme pracovali převážně s čísly, která jsme si dokázali uložit do proměnných. Okrajově jsme se už setkali i s textovými informacemi – například když jsme příkazem `canvas.create_text` vykreslili text. Také při volbě náhodné barvy ze seznamu jsme si její název uložili do proměnné. V takovém případě jsme sice pracovali s barvou, ale počítač si ji pamatoval jako text – tedy jako řetězec znaků, kterému se v programování říká také _textový řetězec_ nebo prostě _řetězec_. 

S textovými řetězci jsme se setkali i při použití vstupního textového pole. Měli bychom tedy rozumět následujícímu programu:

```py
# 19_1.py

import tkinter
canvas = tkinter.Canvas()
canvas.pack()

slovo1 = 'velké'
slovo2 = 'tajemství'

canvas.create_text(200, 100, text=slovo1)
canvas.create_text(200, 200, text=slovo2)
```

Program kreslí na obrazovku pod sebou dvě  slova: "velké"  a "tajemství". Může se nám zdát, že si je zatím pamatujeme v proměnných zbytečně. Textové řetězce můžeme také spojit pomocí operace `+`.

```py
# 19_2.py

import tkinter

canvas = tkinter.Canvas()
canvas.pack()

slovo1 = 'velké'
slovo2 = 'tajemství'
spojene  = slovo1 + slovo2
canvas.create_text(200, 100, text=spojene)
```

Už také víme, že nemusíme vše psát a kreslit pouze na plátno, ale můžeme také zapisovat informace příkazem `print()` v okně  shellu  (příkazový řádek).

```py
# 19_3.py

import tkinter

canvas = tkinter.Canvas()
canvas.pack()

slovo1 = 'velké'
slovo2 = 'tajemství'
spojene = slovo1 + slovo2

print(spojene)
```

V tomto příkladu vidíme, že nepotřebujeme používat `canvas` a knihovnu `tkinter`. Bude fungovat i program, jako je tento:

```py
slovo1 = 'velké'
slovo2 = 'tajemství'
spojene = slovo1 + slovo2
print(spojene)
```

# 2. ❓Otázky

1) Co se stane, když místo `spojene = slovo1 + slovo2` v programu napíšeme následující: `spojene = slovo2 + slovo1`?

2) Jak byste změnili přidružený `pravopis = slovo1 + slovo2`, kdybyste chtěli mít mezeru mezi slovy?

3) Co se stane, když nahradíme třetí řádek v předchozím programu dalším záznamem?
a. `spojene = slovo1 * 2`
b. `spojene = slovo1 + ' ' * 2 + slovo2`
c. `spojene = (slovo1 + ' ') * 2 + slovo2`

4) Odhadněte, co udělá tento program:

	```py
	# 19_4.py

	from random import *
	
	jake = choice(['velké','malé','obrovské','drobné','smutné','veselé'])
	co = choice(['tajemství','překvapení','předsevzetí'])
	spojene = jake  + ' ' + co
	print(spojene)
	```

Můžeme také vytvořit funkci z předchozího programu a doplnit program tak, aby nám napsal několik náhodně složených vět.

```py
# 19_5.py

from random import *

def nahodna_veta():
	kdo = choice(['Kamarád','Spolužák','Pavel','Karel'])
	delal = choice(['viděl', 'prozradil', 'řekl', 'napsal', 'zjistil', 'nakreslil'])
	jake = choice(['velké', 'malé', 'obrovské', 'drobné', 'smutné', 'veselé'])
	co = choice(['tajemství', 'překvapení', 'předsevzetí'])
	spojene = kdo+' '+delal+' '+jake+' '+co+'.'
	print(spojene)

for i in range(21):
	nahodna_veta()
```

Když spustíme program, můžeme vidět podobné věty:

```
Karel řekl velké překvapení.
Kamarád řekl smutné překvapení.
Spolužák řekl drobné tajemství.
...
Kamarád řekl veselé překvapení.
Pavel zjistil velké překvapení.
```

# 3. 💾 Úkoly

1) Rozšiřte program pro vytváření náhodných vět. Přidejte do programu další slova, vytvořte víceslovné věty.

---

2) Která slova z vět bychom mohli vynechat, pokud chceme, aby věty byly správné a smysluplné? Upravte program tak, aby věty měly proměnlivý počet slov a program se náhodně rozhodl, zda slovo z věty vynechat.

---

3) Upravte úlohu 1 nebo 2 tak, aby se ve větách vyskytovala i ženská jména, a podle toho, zda je jméno vybráno ze seznamu mužských nebo ženských jmen, je sloveso přizpůsobeno správnému rodu ve větě, např. napsal/napsala, viděl/viděla.

---

4) Vytvořte hru, ve které náhodně vylosované slovo (ze sekvence předem napsaných slov) postupně padá z horní části plátna. Například posloupnost slov se skládá ze správných a nesprávných pravopisných slov. Úkolem hráče je zachytit pouze správně napsaná slova kliknutím myši. Nesprávná slova musí hráč nechat propadnout do spodní části obrazovky. Za chycení správného slova získá hráč +1 bod, za chycení nesprávného slova ztrácí 2 body. Na obrazovce průběžně vidíme počet získaných bodů.

---

5) Vytvořte úkol č. 3 tak, aby nám hra se ziskem bodů o více než 10 bodů napsala, že nám gratuluje a že jsme vyhráli nějakou cenu. Také to může být náhodné z předem napsaného seznamu. Například: nový telefon, lístky do divadla, knížka s názvem, poukaz na doučování pravopisu, kurz uklízení...

---
