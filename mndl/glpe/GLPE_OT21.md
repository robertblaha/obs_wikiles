#mndl/zkousky #mndl/glpe
# Laserové skenování – princip, rozdělení, výhody, nevýhody, přesnost a využití

**LIDAR** - LIght Detection And Ranging

**Prinicp** - výpočet rychlosti odraženého laserového pulsu. Poloha bodů určována prostorovými polárními souřadnicemi.

Rychle se rozvíjející metoda. Během krátké doby velké množství přesných polochových 3D dat.

Primární výstupem je mračno bodů - soubor 3D souřadnic. Následně digitální zpracování - výpočet poloh, kubatur.

**Využití**
- dokumentace aktuálního stavu
- digitální modely skutečnosti (terénu, staveb, ...)

**Výhody**
- rychlost
- možnost měření vícenásobných odrazů
- vysoká přesnost a hustota
- úspora nákladů

## Letecké laserové skenování - LLS
Soustava
- laserový skener
- přesná GPS
- inerciální GPS
- řídící jednotka
- digitální fotokamera
- digitální fotogemmetrická kamera

- tvorba digitálních modelů terénu
- dokumentace liniových staveb, el. vedení, překážek

## Pozemní laserové skenování - PLS
- bezkontantní určení polohových souřadnic
- neodmyslitelná součást soudobé geodézie
- rozmítání paprsku rotujícím hranolem nebo zrcadlem
- možnost řízeného pořadu měření
- určení polárních souřadnic na základě úhlu a šikmé vzdálenosti

**Dělení pozemních skenerů**
- podle účelu
	- víceúčelové - nejběžnější
	- triangulační
	- totální stanice
	- speciální - např. skenování dutin
	- kinematické (skener neustále v pohybu)
- podle způsobu měření
	- Phase-Shift - měření fázového posunu neustále vysílaného a přijímaného laserového paprsku - vysoká rychlost zaznamenání
	- Time od Flight - polovina času mezi vyslaným a přijatým paprskem - větší dosah
- podle dosahu
	- krátký (do 100m)
	- střední (150 - 350m)
	- dlouhý (až 6 km)
- podle pohybu při měření
	- statické
	- dynamické
- podle prostoru pokrytí
	- kamerové - jako fotoaparát - dva kolmé směry rozmítání - vzdílené objetky
	- panoramatické - servopohon a otáčení kolem celé osy - např. skenování interiérů
	- hybridní - jedna osa omezena v pohybu

## Mobilní laserové skenováná - MLS
- soustava obdobná jako u LLS
- velký význam inerciální jednotky - auto/člověk větší počet náhlých změn směru a rychlosti
- problémy se zakrytými prostory - více průjezdů, více skenerů s různými úhly pohledu
- dokumentace lůiniových staveb (stavy vozovek), reambulace digitálních map, ...


## Porovnání fotogrammetrie a laserového skenování
**Fotogrammetrie**
**výhody** - na menší vzdálenost vyšší přesnost, lepší určení hran, lepší vlícování do referenčního systému
**nevýhody** - pomalé vyhodnocování, méně bodů, se vzdáleností klesá přesnost

**Laserové skenování**
**výhody** - rychlý sběr, vysoký počet bodů, konstatní přesnost, automatizovaný provoz
**nevýhody** - špatná identifikace hran, drahé přístroje a speciální, a rychle zastarávající, SW


