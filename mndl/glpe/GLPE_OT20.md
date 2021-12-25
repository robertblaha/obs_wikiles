#mndl/zkousky #mndl/glpe
# Metody měření pomocí GNSS, aparatury a jejich využití, vlivy působící na přesnost

**Rozdělení metod**
- podle zpracování
	- kódové
	- fázové
- podle doby
	- v reálném čase
	- následné zpracování
- podle pohybu přijímače
	- statické
	- kinematické
- podle počtu přijímačů
	- autonomní
	- diferenční


**Kódové měření**
- jednoduché, spolehlivé, nižší přesnost
- družice i přijímač vysílají identické řady kódů
- v kódu poloha a čas družice
- porovnání času v kódu a přijetí => vzdálenost

**Fázová měření**
- přesná geodetická měření
- určuje se počet fázových délek mezi přijímačem a družicí a následné změny (velká nejednoznačnost ambiquity)

**Statická metoda**
- dlouhodbé (hodiny, dny) měření více referenčních přijímačů a postprocessing

**Rychlá statická**
- měření v minutách - nutnost dvou referenčních přijímačů, jeden na známých souřadnicích, a post-processing

**Kinematická**
- jeden statický referenční přijímač a druhý pohyblivý (inicialiazece na referenčním bodě - vyřešení ambiquity)
- posprocessing celé trasy

**Stop and go**
- jako kinematická, ale vyhodnocení jen vybraných bodů

**RTK**
- kinematická v reálném čase, inicializace a korekce z referenční stanice

**Rozšiřující pozemní polohové systémy v ČR**
- CZEPOS
- TopNet
- Trimble VRS Now
- odpadá nutnost vlastní referenční stanice
- při vzdálenosti do 10km od referenčního až centimetrová přesnost
- lze vyzužít i pro měření bodů pro katastr nemovitostí

**Přijímače**
- jedno/více frekvenční
- jedno/více kanálové
- kódové/fázové
- kompaktní/víceprvkové
- turistické, navigační, sledování zásilek, GIS aparatury (Trimble, Topcon, Leica), geodetické (fázové měření - přesnost milimetry až centimetry)

## Chyby měření
**Systematické**
- při šíření atmosférou
- troposférická korekce (vliv počasí) - výpočet z modelu nebo výpoče - 2 - 25m
- ionosférická korekce - zakřivené signálu - matematický model  - až 10m
- pouze u kódového měření

**Nahodilé**
- vícenásobné šíření signálu - odrazy (až 1m)
- chyby staničních a družicových hodin (až 3m)
- chyby efemerid (až 3m)
- chybný výpočet ambiquity
- lidský faktor