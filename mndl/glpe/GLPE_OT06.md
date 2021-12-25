#mndl/zkousky #mndl/glpe
# Úhlová měření – jaké rozlišujeme úhly, přístroje a úhlové jednotky

Úhly jsou v geodézii jednou ze zákkladních veličin (minimální ovlivnění zakřivením Země).

- vodorovný (horizontální) ω
	- určen svislými rovinami proloženými stanoviskem přístroje a signály (cílovými značkami)
	- dán rozdílem úhlových hodnot měřených směrů
	- měříme vždy ve směru hod. ručiček
- svislý (vertikální) ε, z
	- odchylka od vodorovné roviny
		- výškový úhel ε<sub>1</sub>
		- hloubkový úhel ε<sub>2</sub>
		- od svislice (zenitová vzdálenost) z

## Vodorovný úhel
- na jednom stanovisku lze měřit více úhlů - osnova měřených směrů
- pokud je osnova orientována k jednomu základnímu - orientovaná osnova směrů
- základní **nulový** směr (0<sup>g</sup>)
	- jižník - kladný směr osy X k jihu
	- severník - kladný směr osy X k severu
	- astronomický azimut - absolutní směr k severu - zeměpisný poledník
	- magnetický azimut - směr k magnetickému pólu - magnetický poledník
		- posun
		- deklinace
	- **vrcholový úhel ω** - vodorovný úhel, který svírají dva paprsky ze stanoviska na cílové body
	- **směrový úhel α** - vodorovný úhel, který svírá paprsek ze stanoviska na cílový bod s nulovým paprskem P<sub>0</sub>
	

## Přístroje pro měření

### Teodolit
- od 1720, 1. pol. 20. stol. Čechy Josef a Jan Frič Praha (Meopta)
- svět Wild, Kren, Leica, Zeiss, Spectra Precission, Nikon, Pentax...
- určení libovolného vodorovného nebo svislého úhlu
- tři základní části
	- trojnožka
	- **limbus** - pevná spodní část
	- **alhidáda** - horní otočná část s dalekohledem
- dělení dle konstrukce
	- mechanické - čtení hodnot na kruhu
	- optické - čtení hodnot v objektivu - mikroskop/mřížka, optický mikrometr
	- repetiční - dvojosé -- možnost otáčení limbu (chyba z jeho pohybu)
	- elektronické
- dělení dle přesnosti 
	- nižší - chyba do 80<sup>cc</sup>
	- střední - chyba do 20<sup>cc</sup>
	- přesné -  chyba do 06<sup>cc</sup>
	- velmi přesné (triangulačn) - chyba 01<sup>cc</sup> - 02<sup>cc</sup>
- dalekohled
	- pevná nebo proměnlivá délka
	- malé zorné pole 1° - 3° => hledáček/kolimátor
	- záměrný kříž
- libely pro urovnání
	- krabicová
	- trubicová
- ustanovky - pomůcky pro spojení pohyblivé části s pevnou
	- hrubé/jemné
	- horizontální/vertikální
	- obvodové/osové
- optický centrovač - pro dostředění nad záměrný bod - dalekohled s optickou osou zalomenou do pravého úhlu
- **urovnání přístroje**
	- horizontace
	- centrace
- metody měření (optimalizace poměru přesnoti a času měření)
	- jednoduché měření (největší chyba)
	- měř. v obou polohách dalekohledu
	- měř. násobením - repeticí
	- měř. v řadách a skupinách (nejčastější)
- chyby měření
	- hrubé
	- nevyhnutelné
	- náhodné
	- systematické

## Magnetické přístroje
Měří úhel/azimut vůči magnetickému severu
- magnetický meridián S<sub>M</sub> - průsečnice roviny proložené deklinační magnetkou a zemským povrchem
- magnetický azimut A<sup>M</sup> - orientovaný úhel (ve směru hod. ručiček) mezi směrem a S<sub>M</sub>
- astronomický meridián S<sub>A</sub> - průsečnice roviny směřující k astronomickému severu a zemským povrchem - **místní poledník**
- astronomický azimut A<sup>A</sup> - orientovaný úhel (ve směru hod. ručiček) mezi směrem a S<sub>A</sub>
- meridiánová konvergence γ - úhel mezi osou X a S<sub>M</sub>
	- závisí na zem. šířce a délce a zbrazení
	- V ČR a S-JTSK až 10°
- magnetická deklinace δ - úhel mezi  S<sub>M</sub> a S<sub>A</sub> - mění se v čase a místě
- přístroje (vodorovný kruh pevně spojen se záměrným zařízením)
	- **kompas** - zasklené pouzdro s děleným kruhem a deklinační magnetkou
	- **buzola** - kompas doplněný záměrným zařízením
	- **buzolní teodolit** - teodolit doplněný celokruhovou buzolou nebo buzolním trubicovým zaměřovačem

## Gyroteodolit
Základem je setrvačníkový kompas upravený tak, že se může osa pohybovat pouze ve vodorovné rovině. V důsledku zemské rotace se stáčí do roviny místního poledníku. Z krajních poloh kývající se osy odečet místního poledníku.
Využití při usměrnění (orientaci) trigonometrické sítě a v důlním zeměměřičství.

## Totální stanice
Registrační elektronický teodolit  kombinovaný s elektrooptickým dálkoměrem.
Ukládání velkého množství měření, SW, tvorba map, automatizovaný provoz (vyhledání cíle), kombinace s GPS, ...
