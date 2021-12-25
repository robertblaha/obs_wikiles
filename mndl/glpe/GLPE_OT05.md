#mndl/zkousky #mndl/glpe
# Souřadnicové systémy na území ČR (bývalé i současné)

## Souřadnicový systém stabilního katastru
Katastrální mapování Rakouska-Uherska v 19. století (1817-1864)
Území rozděleno na 3 části s různými počátky souřadnicových soustav (podle poledníků)
- Čechy - hornorakouský kopec Gusterberk
- Morava - věž chrámu sv. Štěpána Vídeň
- Slovensko - kopec Gellerthegy u Budapešti

Cassiny-Soldnerovo příčné zobrazení, základní mapové měřítko **1:2880** (sáhová míra).
Jižníková soustava - kladná část poledníkové osy X k jihu

## Souřadnicový systém reambulovaného katastru
Oprava chyb stabilního katastru - mapová i písemná část (1869-1882)
Zavedeno nové měřítko **1:2500** - pravděpodobně vazba na zavedení metrických měr - [[GLPE_OT03#Jednotky|1871]]

## Souřadnicový systém S-JTSK
Vznik po roce 1918 pro potřeby vzniklé ČSR. Založena Triangulační kancelář, přednostou Ing. Jaroslav Křovák. Zvolil kuželové zobrazení (úspěch díky převodním tabulkám).
Měřičské práce zahájeny 1920, základní síť (268 bodů) dokončena 1927. Další zhušťování až po V. řád ukončeno 1958 (průměrná délka strany 2km)
Nová měřítka map (1927) **1:2000** (1:1000, 1:500)
Pro zobrazení do roviny dvojité[^1]  [[Kartografická zobrazení#Konformní|konformní]] kuželové (stejnoúhlé) zobrazení v obecné poloze, Besselův elipsoid, referenční bod Herrmanskogel, poledník 42°30' od Ferra. Pro území Česka odchylka od severu se pohybuje zhruba mezi 4,5 a 9,5° (stoupá směrem k západu).
Kladná X na jih, kladná Y na západ. Celé území republiky v prvním kvadrantu, kladné souřadnice.
Základní triangulační listy 50x50km, triangulační listy 10x10km, mapové listy v měř. 1:2000
**Pro území ČR Y vždy menší než X.** X (900 000 - 1 300 000), Y (400 000 - 900 000)

[^1]: nejprve konformní zobrazení Besselova elipsoidu na kouli - Gaussovo zobrazení a následně konformní zobrazení koule na kužel

## Souřadnicový systém S-1942
Nevěřejné (vojenské) mapy do 31.12.2005 (poté nahrazen WGS-84).
Severníkový systém (+X sever, +Y východ)
Krasovského elipsoid, referenční bod Pulkovo, Graus-Krügerovo válcové příčné konformní zobrazení.
Číslování začíná na 180°, pásy, dle měřítka, 6° nebo 3°, každý vlastní souřadnicový systém
ČR ve 3. a částečně 4. 6° poledníkovém pásu.

## Souřadnicový systém WGS-84
Geocentrický pravoúhlý pravotočivý systém pevně spojený se Zemí.
Počátek geodetického systému v těžišti Země (střed referenčního elispodu WGS84)
Osa Z prochází pólem
Osa X průsečnice roviny referenčního poledníku a rovníku
Osa Y kolmá na X 90° východně - pravoúhlá pravotočivá soustava
Se Zemí spojen souborem pěti pozemních stanic pozemního kontrolního segmentu GPS.

Určení polohy
- pravoúhlé souřadnice X, Y, Z
- zeměpisné souřadnice φ - šířka, λ - délka a h - elipsoidická výška
- pravoúhlé souřadnice [[UTM|UTM]] nebo [[UPS|UPS]] - E (Easing), N (Northing)


## Souřadnicový systém ETRS-89
Celoevropsky budovaný jednotný souřadnicový systém.
Realizován souřadnicemi stabilizovaných bodů na zemském povrchu.
Založen na elipsoidu GRS-80 (blízký WGS84).
