#mndl/zkousky #mndl/glpe
# Kartografie, matematická kartografie, kartografická zobrazení a jejich dělení

![[Kartografie]]

Vazby: heografie, geodézie, mapování, DPZ, GNSS

Dělení:
- nauka o mapách
- matematická kartografie
- kartografická tvorba
- kartografická polygrafie a reprografie
- kartometrie a morfometrie
- kartografické metody výzkumu
- praktická kartografie (tvorba map)
- teroretická kartografie (generalizace, jazyk map, algoritmy)

## Matematická kartografie
Řeší způsoby zobrazení referenčních ploch (koule, elipsoid) do roviny mapy, vysvětluje jejich vlastnosti a podává návod k jejich používání při tvorbě map.

Ideální zobrazené referenční plochy (elispoid, koule) - glóbus. Ale velká generalizace/zmenšení.

Povrch referenčních těles nelze rozvinout do roviny bez zkreslení v důsledku rozdílů v křivosti originálu a obrazu.

Základem kartografického zobrazení je zeměpisná síť poledníků a rovnoběžek a její přenos na rovinnou plochu.

### Kartografické zobrazení
Způsob přiřazení právě jednoho obrazu bodu referenční plochy na zobrazovací ploše. Realozováno prostřednictvím spojitých funkcí představovaných kartografickými rovnicemi - rovinné souřadnice jsou funkcí [[GLPE_OT04#Souřadnice na referenčních plochách|zeměpisných souřadnic]] na referenční ploše.

### Zobrazovací plochy
![[Pasted image 20210531230144.png]]

Azimutální
- poledníky - paprsky ze středu, rovnoběžky - soustřené kružnice
- zkreslení roste se vdáleností od středu
- nejvhodnější na pólech

Kuželové
- poledníky - paprsky z vrcholu kužele, rovnoběžky soustředné kružnice se středem ve vecholu kužele
- poloha se volí tak, aby dotyková kružnice půlila zobrazované území
- zkreslení roste se vzdáleností od dotykové kružnice

Válcové
- poledníky a rovnoběžky - vzájemně kolmé přímky
- vhodné pro oblasti rozložené kolem některé hlavní kružnice
- nevhodné pro přehledné mapy

### Polohy zobrazovacích ploch
![[Pasted image 20210531230156.png]]

### Způsoby promítání

Gnómické - ze středu
Stereografické - z protilehlého pólu
Externí - z bodu vně tělesa
Ortografické - rovnoběžné paprsky

![[Pasted image 20210602195843.png]]

### Zkreslení

**konformní** (rovnoúhlá)
- zachovává úhly/tvary
- značné zkreslení ploch

**ekvivalentní** (rovnoplošná)
- zachovává plochy
- značně zkresluje úhly/tvary

**ekvidistantní** (délkojevná)
- zachovává délky v některém směru (např. poledníku)
- délkové zkreslení není možné odstranit úplně

**kompenzační** (vyrovnávací)
- mezi konformním a ekvivalentním

