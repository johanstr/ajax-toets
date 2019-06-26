# AJAX-TOETS
  
## Inleiding
In deze repository vind je de startbestanden voor de toets. 
  
  
## Voorbereiding
1. Ga via de GitBash terminal naar de root van je lokale webserver. Dit is waarschijnlijk de map c:\xampp\htdocs.  
  
2. Haal de startbestanden binnen via de terminal opdracht:  
  
```bash  
$ git clone https://github.com/johanstr/ajax-toets  
```  
  
3. Open deze map in je editor (bijvoorbeeld Visual Studio Code)  
  

## Wat moet je doen?
Je gaat via een AJAX call (een http request) data van een andere server binnenhalen. De data betreft een verzameling gegevens van games. Volg sowieso de volgende stappen:  
1. Open het bestand js/index.js  
Hierin ga je programmeren. Vergeet **NIET** in index.js in het commentaarblok bovenin de code je naam en je klas te vermelden.  
  
2. Om de data binnen te halen vanaf de server doe je een AJAX call naar de onderstaande API:  
  https://games-api.ao-alfacollege.nl/api/games  
Dit levert data op in JSON-formaat (zie afbeelding hieronder)  

![json-data](https://webapps.ao-alfacollege.nl/games_api/jsonoutput.png)
  
3. In de pagina plaats je per game die je ontvangt een rij in de tabel, waarbij id, title, description, price en image getoond worden.  
  
4. Het resultaat moet er als volgt uitzien:  
  
  ![resultaat](https://webapps.ao-alfacollege.nl/games_api/resulttable.png)  

5. Lever het bestand a.s. vrijdag in tijdens de les Databases. NIET MAILEN!!!!!