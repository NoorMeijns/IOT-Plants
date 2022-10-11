# IOT-plants

## Stap 1: <br>
Als eerste stap moesten we de arduino IDE, USB driver en NodeMCU installeren en de board-settings instellen.
Ik heb dit volgens het stappenplan gedaan alleen kwam ik er al snel achter dat de LED-strip niet werkte. Het blauwe lichtje op het board knippert wel dus het board doet het wel, maar zodra ik RGB LEDstrip Fastled probeer te installeren dan doet de LED-strip niks. 

Het zwarte draadje (waar GND bij staat) heb ik op het board bij een pin GND gedaan. Het rode draadje (+5v) bij 3v3 pin en de gele draad (Din) bij D5 op het board. In de code heb ik de pin verandert van 6 naar 5, aangezien ik het draadje geconnect heb bij D5 en de led-count naar de hoeveel LED's op de strip. Helaas werkte dit niet. <br>

Vandaar dat ik alles verwijdert had en opnieuw gedownload heb. Vervolgens weer alle stappen doorlopen die beschreven waren en toen was het wel gelukt. Bij het intstalleren van de blink sketch was het de vorige keer niet gelukt. Dit keer klikte ik eerst op "Verify" en vervolgens op "Upload" waarna het dit keer wel knipperde. 

<img src="Images/verify-knop.png">

Vervolgens lukte het mij ook niet om de LED strip te laten branden. Ik had aan Gloria gevraagd of ik even met haar LED-strip het mocht proberen om te kijken of mijn LED-strip stuk was of dat het aan mijn skills lag. Al snel kwam ik erachter dat het wel aan mijn skills lag en niet aan de LED-strip. Ik had een kleine, maar belangrijke fout gemaakt. Ik was vergeten om een D voor de 5 neer te zetten bij DATA_PIN. Waardoor hij niet weet met welke pin de LED-strip verbonden is. Na het aangepast te hebben, deed de LED-strip het wel. 

<Video LED-strip> / <Foto 5 ipv D5>




##Bronnen: <br>
Foto plant:
https://www.ecopots.eu/?utm_source=social+media+&utm_medium=pinterest&utm_campaign=UGC+Pinterest+Board+October
