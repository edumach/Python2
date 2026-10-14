

#  (63) Dopravní průzkum 

> `(), [], txt`

Městský dopravní podnik dělal jeden měsíc, po změnách v trasách tramvajových linek, průzkum vytíženosti jednotlivých linek. V souboru `pruzkum.txt` je uveden seznam zastávek s průměrnými počty nastupujících a vystupujících během sledovaného období. V souboru jsou na každém řádku uvedeny tři údaje – průměrný počet nastupujících, průměrný počet vystupujících na zastávce a název zastávky. Údaje jsou odděleny středníkem. Počty jsou celá čísla, název zastávky může být i víceslovný.
Podnik chce takto získané údaje využít ke zlepšení služeb – umístění automatů na jízdenky, výběr správného typu vozidla na linku a zavedení málo využívaných zastávek jako zastávky na znamení.
Ukázka textového souboru:

```
10;0;Na stráni
5;0;Městský park
50;1;Jiráskova
2;0;Nemocnice
10;3;U lípy
...
```

Vytvořte program, který bude mít tyto vlastnosti:

- Vypíše seznam zastávek s počty cestujících v autobusu po odjezdu z dané zastávky.
- Zobrazí doporučení, který vhodný typ autobusu se vyplatí nasadit na danou linku. Vhodný typ se zvolí podle největšího počtu cestujících ve vozidle během jízdy. Typy autobusů jsou: dlouhý, standardní, krátký. Hranice, při jakém počtu cestujících se vyplatí daný typ autobusu, si zvolte sami.
- Na zastávkách, kde nastupuje alespoň 10 cestujících, je vhodné umístit automat na prodej jízdenek. Vypište seznam vhodných zastávek pro umístění automatu.
- Zastávky, kde nastupují méně než tři lidé, resp. vystupují méně než tři, budou změněny na zastávky na znamení. Autobus tedy na nich nebude zastavovat, pokud cestující nedá znamení
řidiči. Vypište seznam takových zastávek.


Příklad možného výsledku:

```
Zastávka - Počet cestujícich
Na stráni - 10
Městský park - 15
Jiráskova - 64
Nemocnice - 66
U lípy - 73
Městský úřad - 73
Městský úřad - 78
Poděbradská - 77
Nové dvory - 98
U školy - 91
Autobusové nádraží - 0

Doporučený typ autobusu: standardní

Zastávky vhodné na instalaci automatu: 
Na stráni
Jiráskova
U lípy
Městský úřad
Nové dvory

Vhodné zastávky na znamení: 
Nemocnice
Městský úřad
Poděbradská
```