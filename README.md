# MCTK GPX bestandsnamen

De bestandsnamen zijn bedoeld om:

- in dezelfde opmaak te zijn
- duidelijk te zijn in verwachtingen en bij selectie
- kort te zijn voor leesbaarheid op verschillende fietscomputers
- snel te kunnen worden geselecteerd voor planningsdoeleinden: x aantal kilometers / hoogtemeters
- uniek te zijn, ook als de route verandert

De huidige opmaak bevat 4 velden, gescheiden met een streepje:

**MCTK-km-hm-label**

- Veld 1: prefix `MCTK`
- Veld 2: aantal kilometers, afgerond naar het dichtstbijzijnde hele getal
- Veld 3: aantal hoogtemeters, afgerond naar het dichtstbijzijnde hele getal
    - dit is een indicatie vanwege verschillen tussen tools/fietscomputers.
    - huidige referentie: gebaseerd op geïmporteerde gpx-bron in Strava-route
- Veld 4: een label om de rit te beschrijven, bestaande uit 1 of meer woorden gescheiden door streepjes. Voor zowel conformiteit als subtiliteit dient de eerste letter van het woord in hoofdletters te worden geschreven en de rest van de letters in kleine letters:
    - Moedermeule
    - Zennegat
    - Herentals-Grobbendonk

De start en finish van de ritten bevinden zich altijd in Keerbergen, tenzij voor speciale evenementen. Om de bestandsnamen kort en leesbaar te houden op fietscomputers, wordt aangeraden de locatie Keerbergen weg te laten uit het label.


Samen maakt dit een unieke combinatie, duidelijk te begrijpen en makkelijk voor planningsdoeleinden.

Bijvoorbeeld: `MCTK-90-115-Herentals-Grobbendonk`
Is een rit van 90 km en +/- 115 hoogtemeters in de richting van Herentals-Grobbendonk.
