# Folderstructuur

Het MCTK gpx versiebeheersysteem is ontworpen om een overzichtelijke en gestructureerde manier te bieden om ritten te beheren en te plannen. Het bestaat uit twee hoofdfolders:

- `_kalender`: bevat de planning van de ritten 
- `gpx_winkeltje`: bevat alle MCTK-gpx bestanden


# Gpx naamgeving
## Doel
De bestandsnamen van routes binnen onze wielerclub hebben als doel om:

- Duidelijkheid te bieden over de kenmerken van de route.
- Gemakkelijk te herkennen te zijn.
- Kort, uniek en leesbaar te zijn op verschillende fietscomputers.
- Snel de juiste route te laten selecteren bij het plannen of rijden van een route.
- Niet specifiek verbonden te zijn aan een bepaalde categorie van leden.
- Alle bestandsnamen dienen dezelfde opmaak te hebben om uniformiteit te garanderen. 


## Formaat
Het formaat van de bestandsnamen bestaat uit 4 velden gescheiden door een streepje: 

`MCTK-km-hm-label`

Elk veld heeft een specifieke betekenis:
1. `MCTK` is een vaste prefix van club Maximus Cycling Team Keerbergen
2. `km` is het aantal **kilometers** van de route
    - afgerond naar het dichtstbijzijnde hele getal.
3. `hm` het aantal **hoogtemeters** van de route
    - afgerond naar het dichtstbijzijnde hele getal.
    - het is een indicatie vanwege verschillen tussen tools/fietscomputers.
    - huidige referentie is gebaseerd op het geïmporteerde gpx-bronbestand in een Strava-route
4. `label` is een herkenbare beschrijving van de route
    - Bestaande uit één of meerdere woorden:
        - gescheiden door streepjes, bijvoorbeeld: 
            - Moedermeule
            - Herentals-Grobbendonk 
        - elk woord begint met een hoofdletter en de rest van de letters zijn kleine letters.
    - De start en finish van elke route bevinden zich standaard in Keerbergen, tenzij er speciale evenementen zijn. We raden aan om Keerbergen niet op te nemen in het label om de bestandsnamen kort te houden ifv de beperkte tekens op fietscomputers.

## Voorbeeld
`MCTK-90-115-Herentals-Grobbendonk`
is een rit van 90 km en +/- 115 hoogtemeters in de richting van Herentals-Grobbendonk.

Dit geeft een duidelijk omschrijving van de te verwachten rit.
Niet alle fietscomputers zullen de volledige breedte kunnen tonen, maar met het meest unieke deel in het begin van de naamgeving zou dit moeten volstaan voor selectie ervan.

