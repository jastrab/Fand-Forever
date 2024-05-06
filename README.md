# Fand-Forever
F^2 = Fand-Forever alebo PC Fand Viewer

- prehliadač pc fand súborov
- podpora farebnej syntaxe
- knižnica pre spracovanie fand súboru - **000** - zobrazenie / uloženie
- knižnica pre spracovanie db súboru - **dbf** - zobrazenie / uloženie
  (vlastné spracovanie so súborom dbf)
- knižnica pre spracovanie formátu - **csv** - zobrazenie / uloženie
- konverzia medzi formátmi **000** <==> **dbf** <==> **csv**

- naprogramované ešte v roku 2018 v python 2
- update 2024 migrácia python 2 na 3
  
- obe verzie majú rovnaký základ
- 1 verzia je naprogromovaná v TKinter
- 2 verzia je webový formát html

! Momentálne len ukážky programu !

Tento program bol naprogramovaný okolo r.2017, kedy reverzným inžinierstvom sa mi podarilo rozlúsknuť fandovský súborový formát s dátami 000 ako aj súbor RDB. Preto bolo možné vytvoriť jednoduchý program, pre zobrazenie zdrojových kódov fandu a dorobiť vylepšenia, ktoré pôvodnej verzii chýbali.
Pôvodne bolo zobrazenie naprogramované v tkintery neskôr bolo spravené aj pre web verziu. Tento program bol naprogramovaný ako hobby projekt.

_fand db formát 000:_
- štrukúra je dosť podobná dbf štruktúre
- fand používa svoje typy formátu
- súbor neobsahuje hlavičku

# Ukážky

1. GUI - TKinter

- menu

![Snímka obrazovky_2024-05-06_15-34-56](https://github.com/jastrab/Fand-Forever/assets/6190406/889cc10c-a758-404b-b1de-785112f7ff40)

- dátový súbor - 000 hlavička

![Snímka obrazovky_2024-05-06_15-35-32](https://github.com/jastrab/Fand-Forever/assets/6190406/acef148e-0bb7-45e5-ad90-e8ad4476373e)

- zdrojový súbor - procedúra

![Snímka obrazovky_2024-05-06_15-36-09](https://github.com/jastrab/Fand-Forever/assets/6190406/a079a964-cb39-411d-8c2d-2268b048bacc)

---
2. GUI - Webová verzia

- menu

![Snímka obrazovky_2024-05-06_15-30-07](https://github.com/jastrab/Fand-Forever/assets/6190406/1f44dc6e-8e64-4e14-b2bd-e62598e1ac6d)

- dátový súbor - 000 hlavička
  
![Snímka obrazovky_2024-05-06_15-30-52](https://github.com/jastrab/Fand-Forever/assets/6190406/b9c7c17b-1863-43ff-95d5-b99afe521981)

- zdrojový súbor - procedúra

![Snímka obrazovky_2024-05-06_15-30-30](https://github.com/jastrab/Fand-Forever/assets/6190406/46e91ea2-016b-4322-bae2-35505c3032d8)

---
3. Originál PC FAND

- menu

![snimka3](https://github.com/jastrab/Fand-Forever/assets/6190406/1a3576bf-b3c7-4a6c-9de1-d2fe0ad3c0ab)


- dátový súbor - 000 hlavička
  
![snimka1](https://github.com/jastrab/Fand-Forever/assets/6190406/102df6d8-64e1-43e1-bf2b-5b18642493a1)

- zdrojový súbor - procedúra

![snimka2](https://github.com/jastrab/Fand-Forever/assets/6190406/5cbda4e2-450a-42da-9e63-ab718a3ccc6b)

---

Niečo k pôvodnému programu:

PC FAND

- DOS vývojový program, pre jednoduché programovanie s možnosťou DB
- od českých autorov
- svojho času neprekonateľný program v našich končinách - CZ, SK
- https://www.alis.cz/cs/pc-fand


Zdrojové kody PC FAND boli zverejnené v roku 2019 ako open source:

- https://github.com/alisoss/pcfand

