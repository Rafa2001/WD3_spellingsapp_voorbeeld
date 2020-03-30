# Spellingsoefeningen Applicatie

## Beschrijving

Je maakt een applicatie waarmee je spellingsoefeningen kunt maken voor het vak Nederlands. De applicatie werkt met oefeningen zoals je die terugvindt op [DuoLingo](https://www.duolingo.com/) of [Memrise](https://www.memrise.com/).

Op basis van een template ontwerp je een user interface die geschikt is voor dit soort programma. De UI bestaat uit twee pagina's: een hoofdpagina en een oefenpagina.

Elke oefening kan gemaakt worden als invul-oefening **EN** als meerkeuze-oefening. Elke oefening bevat daarom een unieke ID, een vraag, een categorie, een moeilijkheidsgraad, een juist antwoord, de regel die toegepast moet worden en een lijst met foute antwoorden. De lijst met foute antwoorden wordt gebruikt wanneer de oefening als meerkeuze wordt weergegeven.

De verschillende categorieën en moeilijkheidsgraden van oefeningen krijgen jullie van de leraar Nederlands.

Oefeningen worden altijd in oefeningenreeksen gemaakt. Een oefeningenreeks bestaat uit 10 willekeurige oefeningen van één categorie en dezelfde moeilijkheidsgraad, waarvan er minstens 5 uniek zijn. Het komt dus zelden voor dat een gebruiker dezelfde oefeningenreeks krijgt voorgeschoteld, omdat elke reeks telkens bestaat uit een willekeurige greep van 5 of meer oefeningen uit de database.

Op de hoofdpagina kan een gebruiker kiezen welke moeilijkheidsgraad en categorie zij of hij graag wenst. Wanneer de categorie is gekozen start er automatisch een oefeningenreeks.

De 10 oefeningen van een oefeningenreeks worden één voor één getoond op de oefenpagina. De oefening wordt willekeurig getoond als meerkeuze- of invul-oefening. Bij het geven van een juist antwoord krijgt de gebruiker een positieve boodschap, waarna zij of hij de volgende oefening kan beginnen. Bij het geven van een fout antwoord krijgt de gebruiker het juiste antwoord te zien en de regel die toegepast moest worden, waarna de volgende oefening gestart kan worden. Aan het einde van een oefeningenreeks word de score van de gebruiker getoond in een pop-up op de oefenpagina. Op elk moment moet een gebruiker de oefeningenreeks kunnen stopzetten en terugkeren naar de hoofdpagina.

## Voorwaarden

 - de applicatie wordt ontwikkeld met behulp van HTML, CSS en PHP.
   - ontwikkel je User Interface steeds met Mobile First in gedachte.
 - styling wordt in één externe stylesheet gebundeld. 
   - stijlen en selectors worden zoveel mogelijk herbruikt en gedeeld tussen de verschillende pagina's.
 - er wordt gebruik gemaakt van een icon library (bv. Google Material Icons of Font Awesome).
 - de vragen-database is één array waarin alle informatie wordt opgeslagen. Dit mag (moet?) een array van arrays (van arrays ...) zijn. 
 - Er worden functies gemaakt om informatie uit de array op te vragen.
   - Uitbreiding: je kan ook aan de slag gaan met klassen en objecten.
 - De applicatie werkt zoals in de beschrijving.

## Woordenlijst
| WOORD | OMSCHRIJVING |
| --- | --- |
| spellingsoefening | Eén oefening die een gebruiker kan maken. De oefening bestaat uit een vraag, een antwoord, een categorie, een moeilijkheidsgraad en een lijst met foute antwoorden. |
| oefeningenreeks | Een gebruiker maakt oefeningen altijd in een reeks van 10 willekeurige oefeningen. Een oefeningenreeks bevat 10 willekeurige vragen van dezelfde moeilijkheidsgraad en dezelfde categorie. Van de oefeningen moeten er minstens 5 telkens uniek zijn. |
| hoofdpagina | de pagina van waaruit een gebruiker een oefeningenreeks kan starten. |
| oefenpagina | de pagina waarop een oefening getoond wordt en, aan het einde van een oefeningenreeks, de score die behaald werd. |

---

# Evaluatie

## Evaluatie Dagelijks Werk

Elke week krijg je een nieuwe opdracht. Onderaan de opdracht kan je telkens terugvinden hoe deze opdracht beoordeeld wordt.

Deze beoordelingen bepalen het grootste deel van je dagelijks werk resultaat.

## Evaluatie Examen

De eindversie van deze opdracht bepaalt het grootste deel van je examenresultaat. Dit project wordt beoordeeld op basis van 3 onderdelen:

 - Kwaliteit: 
   - In welke mate heb je het maken van de applicatie voorbereid? 
   - Hoe leesbaar is de code voor andere programmeurs? 
   - Bevat de applicatie nog fouten en bugs die je niet kan verklaren?
 - Code: 
   - Hoe efficient is de code? 
   - Maak je goed gebruik van codeblokken en arrays? 
 - UI:
   - Hoe is de user interface opgebouwd?
   - Is er rekening gehouden met verschillende apparaten?

Deze 3 onderdelen worden beoordeel aan de hand van de rubrics die je hieronder vindt.


### Kwaliteit

| Doelstelling | A | B | C | D | E |
| --- | --- | --- | --- | --- | --- |
| Programmeer attitude: coding guidelines | Je indentatie, naamgeving en commentaar is correct en duidelijk. Je hebt ook duidelijke commentaar toegevoegd op plaatsen waar je code moeilijker te begrijpen. |	Je indentatie is correct en de namen die je koos voor de verschillende elementen zijn duidelijk. Je hebt commentaar toegevoegd op de plaatsen waar dit verplicht is volgens de coding guidelines. |	De commentaar die je schrijft is onvoldoende uitgewerkt. De naamgeving van elementen is duidelijk en je indentatie is correct. |	De namen die je kiest voor de verschillende elementen zijn niet duidelijk genoeg. Je indentatie is correct en je hebt commentaar toegevoegd op de plaatsen waar dit verplicht is volgens de coding guidelines. | 	Je indentatie, naamgeving en commentaar zijn onduidelijk en onvoldoende uitgewerkt.
| Programmeer attitude: probleem analyse  | De opdracht werd goed uitgewerkt. Je probleem analyse bevat weinig of geen fouten. |	Hoewel de opdracht niet goed werd uitgewerkt, heb je een goede probleem analyse gemaakt met weinig of geen fouten. |	Je hebt de opdracht correct uitgewerkt, maar je probleemanalyse is onvoldoende uitgewerkt. |	Je hebt de opdracht niet goed uitgewerkt, omdat je probleem analyse fouten bevat. |	Je hebt geen probleem analyse gemaakt, waardoor de opdracht niet goed werd uitgewerkt. |
| Foutopsporing: syntax- en runtimefouten | Je hebt de meeste syntax- en runtimefouten gevonden en verklaard, en kan er ook een oplossing voor geven. | Je hebt de meeste runtime-fouten gevonden en verklaard, en kan er ook een oplossing voor geven. Je hebt slechts weinig syntax fouten gevonden. | Je hebt de meeste syntax-fouten gevonden en verklaard, en kan er ook een oplossing voor geven. Je hebt slechts weinig runtime fouten gevonden. | Je hebt weinig fouten gevonden. Je kan de fouten die je vond wel verklaren, maar je biedt weinig oplossingen hiervoor.  | Je hebt weinig fouten gevonden. De fouten die je vond kan je niet verklaren of oplossen. |

### programmeren

| Doelstelling | A | B | C | D | E |
| --- | --- | --- | --- | --- | --- |
|	Programmeren: Instructies	|	Variabelen worden correct geinitialiseerd en je maakt correct gebruik van de verschillende datatypes en operators.	|	Enkele variabelen worden nog niet juist geinitialiseerd. Je maakt wel correct gebruik van de verschillende datatypes en operators.	|	Je gebruik van de verschillende operators is correct. Je gebruikt de verschillende datatypes nog niet correct. Variabelen worden nog niet juist geinitialiseerd.	|	Je gebruik van de verschillende datatypes is correct. Je gebruikt de verschillende operators nog niet correct. Variabelen worden nog niet juist geinitialiseerd.	|	Variabelen worden niet goed geinitialiseerd, je maakt verkeerd gebruik van de verschillende datatypes en operators.	|														
|	Programmeren: Codeblokken (selectie)	|	Je past selectie toe op de juiste plaats met de juiste voorwaarde, waarbij je een optimale oplossing gebruikt voor het probleem.	|	Je past selectie toe op de juiste plaats met de juiste voorwaarde, maar er zijn oplossingen die veel korter of sneller zijn.	|	Je past selectie toe op de juiste plaats met de juiste voorwaarde, maar zet je selectie-blokken in de foute volgorde.	|	Je past selectie toe op de juiste plaats met de juiste voorwaarde, maar gebruikt hiervoor de verkeerde selectie-blokken.	|	Selecties worden niet gebruikt waar nodig. Wanneer je een selectie gebruikt is de voorwaarde niet juist.	|														
|	Programmeren: Codeblokken (iteratie)	|	Je past iteratie toe op de juiste plaats met de juiste voorwaarde en iterator en maakt correct het onderscheid tussen variabelen binnen en buiten de iteratie, waarbij je een optimale oplossing gebruikt voor het probleem.	|	Je past iteratie toe op de juiste plaats met de juiste voorwaarde en iterator en maakt correct het onderscheid tussen variabelen binnen en buiten de iteratie, maar er zijn oplossingen die veel korter of sneller zijn.	|	Je past iteratie toe op de juiste plaats met de juiste voorwaarde en maakt correct het onderscheid tussen variabelen binnen en buiten de iteratie, maar gebruikt de iterator niet wanneer dit nodig is.	|	Je past iteratie toe op de juiste plaats met de juiste voorwaarde, maar gebruikt de iterator niet wanneer dit nodig is en begrijpt niet wat het verschil is tussen een variabele die voor, tijdens en na de iteratie wordt aangemaakt.	|	Iteraties worden niet gebruikt waar nodig. Wanneer je een selectie gebruikt is de voorwaarde niet juist.	|														
|	Programmeren: Codeblokken (functie)	|	Parameters zijn correct gedefinieerd en worden correct gebruikt in de functie. De return waarde is correct geimplementeerd en wordt juist opgevangen bij de aanroep. Functies hebben één duidelijk doel. Functies werken zoals beschreven in de opdracht, waarbij je een optimale oplossing gebruikt voor het probleem.	|	Parameters zijn correct gedefinieerd en worden correct gebruikt in de functie. De return waarde is correct geimplementeerd en wordt juist opgevangen bij de aanroep. Functies hebben één duidelijk doel. Functies werken zoals beschreven in de opdracht, maar er zijn oplossingen die veel korter of sneller zijn.	|	Parameters zijn correct gedefinieerd en worden correct gebruikt in de functie. De return waarde is correct geimplementeerd, maar wordt niet opgevangen bij het aanroepen van de functie.	|	Parameters zijn correct gedefinieerd, maar worden verkeerd gebruikt in de functie zelf. De return waarde is correct geimplementeerd, maar wordt niet opgevangen bij het aanroepen van de functie.	|	De signature van de functie is niet volledig. Het aanroepen van de functie gebeurt verkeerd. Er is geen return-waarde aanwezig wanneer dit nodig is.	|														
|	Programmeren: Arrays	|	Arrays worden correct aangemaakt en het opvragen, invoegen, verwijderen en aanpassen van elementen gebeurt op de juiste wijze. 	|	Arrays worden correct aangemaakt en het opvragen, invoegen en aanpassen van elementen gebeurt op de juiste wijze. Het verwijderen van elementen wordt echter niet op de juiste manier gedaan.	|	Arrays worden correct aangemaakt en het opvragen en aanpassen van elementen gebeurt op de juiste wijze. Het invoegen en verwijderen van elementen wordt echter niet op de juiste manier gedaan.	|	Arrays worden correct aangemaakt en het opvragen van elementen gebeurt op de juiste wijze. Het invoegen, aanpassen en verwijderen van elementen wordt echter niet op de juiste manier gedaan.	|	Arrays worden op de verkeerde manier aangemaakt. Het opvragen, invoegen en verwijderen van elementen gebeurt niet op de correcte wijze.	|														

### UI

| Doelstelling | A | B | C | D | E |
| --- | --- | --- | --- | --- | --- |
|	Webontwikkeling: structuur	|	Elementen worden correct genest. De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig, maar hebben vaak onduidelijke naamgeving. Elementen zijn onderverdeeld in grotere elementen, en er is gekozen voor een optimale oplossing.	|	Elementen worden correct genest. De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig, maar hebben vaak onduidelijke naamgeving. Elementen zijn onderverdeeld in grotere elementen, hoewel er oplossingen bestaan die korter of optimaler zijn. 	|	Elementen worden correct genest. De semantisch juiste elementen werden gebruikt. Elementen zijn niet voldoende onderverdeeld in grotere elementen. De id's en classes van elementen zijn ingevuld waar nodig, maar hebben vaak onduidelijke naamgeving.	|	Elementen worden correct genest. Elementen zijn niet voldoende onderverdeeld in grotere elementen. Er wordt geen rekening gehouden met de semantiek van de elementen. De id's en classes van elementen zijn ingevuld waar nodig, maar hebben vaak onduidelijke naamgeving.	|	Elementen worden niet correct genest. Elementen zijn niet voldoende onderverdeeld in grotere elementen. Er wordt geen rekening gehouden met de semantiek van de elementen. De id's en classes van elementen zijn niet of onduidelijk ingevuld waar nodig.	|														
|	Webontwikkeling: opmaak	|	Selectors zijn correct en voldoende specifiek gedefinieerd. CSS documenten worden gedeeld door verschillende pagina's. Er werd gekozen voor de correcte stijlregels met de juiste waardes en eenheden. Selectors werden samengevoegd waar nodig.	|	Selectors zijn correct en voldoende specifiek gedefinieerd. CSS documenten worden gedeeld door verschillende pagina's. Er werd gekozen voor de correcte stijlregels met de juiste waardes en eenheden. Selectors worden te weinig samengevoegd. 	|	Selectors zijn correct en voldoende specifiek gedefinieerd. CSS documenten worden gedeeld door verschillende pagina's. Selectors worden te weinig samengevoegd. Er werd gekozen voor de correcte stijlregels, maar de waardes en eenheden werden niet correct gebruikt. 	|	Selectors zijn correct gedefinieerd, maar zijn vaak niet specifiek genoeg. CSS documenten worden niet gedeeld door verschillende pagina's. Selectors worden te weinig samengevoegd. Er werd gekozen voor de correcte stijlregels, maar de waardes en eenheden werden niet correct gebruikt. 	|	Selectors zijn verkeerd of niet specifiek genoeg gedefinieerd. Selectors worden te weinig samengevoegd. CSS documenten worden niet gedeeld door verschillende pagina's. Stijlregels, waardes en eenheden werden niet correct gebruikt. 	|														
|	Webontwikkeling: box model	|	Randen werden correct toegepast, net als de ruimte tussen en in elementen. De box-sizing regel werd juist toegepast. De ruimte rond het body-element werd correct aangepast volgens de opdracht. 	|	Randen werden correct toegepast, net als de ruimte tussen en in elementen. De box-sizing regel werd juist toegepast. De ruimte rond het body-element werd niet aangepast volgens de opdracht. 	|	Randen werden correct toegepast, net als de ruimte tussen elementen. De ruimte binnen in elementen werd niet correct aangepast. De ruimte rond het body-element werd niet aangepast volgens de opdracht. De box-sizing regel werd niet juist toegepast.	|	Randen werden correct toegepast, net als de ruimte binnen in elementen. De ruimte tussen elementen werd niet correct aangepast. De ruimte rond het body-element werd niet aangepast volgens de opdracht. De box-sizing regel werd niet juist toegepast.	|	De ruimte tussen en in elementen werd niet correct aangepast. De ruimte rond het body-element werd niet aangepast volgens de opdracht. De box-sizing regel werd niet juist toegepast.	|														
|	Webontwikkeling: responsive websites	|	Media queries werden correct en op de juiste plaats gedefinieerd. Elementen staan correct binnen of buiten de media queries. De pagina werd Mobile First ontwikkeld. Media queries werden samengevoegd waar mogelijk.	|	Media queries werden correct en op de juiste plaats gedefinieerd. Elementen staan correct binnen of buiten de media queries. De pagina werd Mobile First ontwikkeld. Enkele media queries kunnen samengevoegd worden. 	|	Media queries werden correct en op de juiste plaats gedefinieerd. Enkele media queries kunnen samengevoegd worden. Enkele elementen zijn verkeerd binnen of buiten media queries geplaatst. De pagina werd Mobile First ontwikkeld.	|	Media queries werden correct gedefinieerd. Media queries worden overschreven doordat ze op de foute plaats zijn gedefinieerd. Enkele media queries kunnen samengevoegd worden. Enkele elementen zijn verkeerd binnen of buiten media queries geplaatst. De pagina werd niet Mobile First ontwikkeld.	|	Media queries werden niet correct gedefinieerd. Media queries worden overschreven doordat ze op de foute plaats zijn gedefinieerd. Elementen zijn verkeerd binnen of buiten media queries geplaatst. De pagina werd niet Mobile First ontwikkeld.	|														
|	Webontwikkeling: layout	|	Kolommen en rijen schalen mee met de grootte van het venster op de gewenste manier. Het juiste aantal rijen en kolommen werd gebruikt. Elementen staan op de juiste plaats in de layout.	|	Kolommen en rijen schalen mee met de grootte van het venster op de gewenste manier. Elementen staan op de juiste plaats in de layout.  Een aantal kolommen of rijen van de layout zijn overbodig. 	|	Kolommen en rijen schalen mee met de grootte van het venster op de gewenste manier. Een aantal kolommen of rijen van de layout zijn overbodig. Elementen staan op de verkeerde plaats in de layout. 	|	Kolommen en rijen schalen mee met de grootte van het venster op de gewenste manier. Een aantal kolommen of rijen van de layout missen of zijn overbodig. Elementen staan op de verkeerde plaats in de layout. 	|	Een aantal kolommen of rijen van de layout missen of zijn overbodig. kolommen en rijen schalen niet correct mee met de grootte van het venster. Elementen staan op de verkeerde plaats in de layout. 	|														
|	Webontwikkeling: dynamische websites	|	GET waardes werden correct doorgegeven en opgevangen op verschillende pagina's. URL parameters worden correct gebruikt. POST en SESSION waardes werden gebruikt waar nodig. Sessions werden correct geinitialiseerd. 	|	GET waardes werden correct doorgegeven en opgevangen op verschillende pagina's. URL parameters worden correct gebruikt. POST waardes werden gebruikt in plaats van GET waardes waar nodig. SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. 	|	GET waardes werden correct doorgegeven en opgevangen op verschillende pagina's. URL parameters worden correct gebruikt. POST en SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. 	|	GET waardes werden correct doorgegeven naar verschillende pagina's. POST en SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. URL parameters worden verkeerd gebruikt.	|	GET, POST en SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. URL parameters worden verkeerd gebruikt.	|														
