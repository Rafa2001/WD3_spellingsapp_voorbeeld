# spellingapplicatie week 4

## opdracht

Deze week voeg je al het werk van de vorige weken samen en ga je aan de slag met een eerste URL parameter. Kopieer de volgende bestanden naar deze map:

 - index.php (uit week 2)
 - exercise.php (uit week 2)
 - style.css (uit week 2)
 - database.php (uit week 3)

Gebruik nu de functie in database.php om een willekeurige vraag van één categorie te tonen in exercise.php. Geef aan exercise.php een parameter mee, waaraan de categorie van de vraag wordt meegegeven. 

bv.:<br>
als je een vraag uit de categorie `vervoeging` wilt tonen, dan wordt een url parameter `categorie=vervoeging` aan de url meegegeven. Je haalt deze dan op met behulp van de `$_GET` array, zodat je de waarde `vervoeging` kunt meegeven als parameter aan de functie in database.php.

## peer review week 3

Ga naar de issues tab van het project dat jij moet reviewen. Maak een nieuw issue aan genaamd "week 3 peer review". Maak daarin volgende tabel opnieuw na* en vul deze in.

\* je kan zo'n tabel met [html](https://www.w3schools.com/html/html_tables.asp) maken of met [github markdown](https://help.github.com/en/github/writing-on-github/organizing-information-with-tables).

| vraag | commentaar |
| --- | --- |
| De database bevat alle gegevens die er volgens de applicatiebeschrijving in moet zitten (id, vraag, categorie, moeilijkheid, antwoord, regel, foute antwoorden) |  |
| De functie heeft een duidelijke naam |  |
| De functie vraagt een parameter die de categorie aanduidt |  |
| De functie vraagt een parameter die de moeilijkheid aanduidt |  |
| De functie geeft een vraag terug met alle gegevens van die vraag ((id, vraag, categorie, moeilijkheid, antwoord, regel, foute antwoorden)  |  |
| De functie geeft een willekeurige vraag terug |  |
| De functie geeft een vraag terug van de juiste categorie |  |
| De functie geeft een vraag terug van de juiste moeilijkheid |  |

---

## Evaluatie Dagelijks Werk

Deze week maak je een een array aan, waarin je alle data voor je applicatie opslaat. Je maakt ook een functie aan, die data uit die array ophaalt.

De rubric hieronder toont hoe je zult geëvalueerd worden. 

|	doelstelling	|	A	|	B	|	C	|	D	|	E	|														
|	---	|	---	|	---	|	---	|	---	|	---	|														
|	Programmeerattitude: Coding Guidelines	|	Je indentatie, naamgeving en commentaar is correct en duidelijk. Je hebt ook duidelijke commentaar toegevoegd op plaatsen waar je code moeilijker te begrijpen.	|	Je indentatie is correct en de namen die je koos voor de verschillende elementen zijn duidelijk. Je hebt commentaar toegevoegd op de plaatsen waar dit verplicht is volgens de coding guidelines.	|	De commentaar die je schrijft is onvoldoende uitgewerkt. De naamgeving van elementen is duidelijk en je indentatie is correct.	|	De namen die je kiest voor de verschillende elementen zijn niet duidelijk genoeg. Je indentatie is correct en je hebt commentaar toegevoegd op de plaatsen waar dit verplicht is volgens de coding guidelines. 	|	Je indentatie, naamgeving en commentaar zijn onduidelijk en onvoldoende uitgewerkt.	|														
|	Programmeren: Codeblokken (functie)	|	Parameters zijn correct gedefinieerd en worden correct gebruikt in de functie. De return waarde is correct geimplementeerd en wordt juist opgevangen bij de aanroep. Functies hebben één duidelijk doel. Functies werken zoals beschreven in de opdracht, waarbij je een optimale oplossing gebruikt voor het probleem.	|	Parameters zijn correct gedefinieerd en worden correct gebruikt in de functie. De return waarde is correct geimplementeerd en wordt juist opgevangen bij de aanroep. Functies hebben één duidelijk doel. Functies werken zoals beschreven in de opdracht, maar er zijn oplossingen die veel korter of sneller zijn.	|	Parameters zijn correct gedefinieerd en worden correct gebruikt in de functie. De return waarde is correct geimplementeerd, maar wordt niet opgevangen bij het aanroepen van de functie.	|	Parameters zijn correct gedefinieerd, maar worden verkeerd gebruikt in de functie zelf. De return waarde is correct geimplementeerd, maar wordt niet opgevangen bij het aanroepen van de functie.	|	De signature van de functie is niet volledig. Het aanroepen van de functie gebeurt verkeerd. Er is geen return-waarde aanwezig wanneer dit nodig is.	|														
|	Webontwikkeling: dynamische websites	|	GET waardes werden correct doorgegeven en opgevangen op verschillende pagina's. URL parameters worden correct gebruikt. POST en SESSION waardes werden gebruikt waar nodig. Sessions werden correct geinitialiseerd. 	|	GET waardes werden correct doorgegeven en opgevangen op verschillende pagina's. URL parameters worden correct gebruikt. POST waardes werden gebruikt in plaats van GET waardes waar nodig. SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. 	|	GET waardes werden correct doorgegeven en opgevangen op verschillende pagina's. URL parameters worden correct gebruikt. POST en SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. 	|	GET waardes werden correct doorgegeven naar verschillende pagina's. POST en SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. URL parameters worden verkeerd gebruikt.	|	GET, POST en SESSION waardes werden niet of verkeerd doorgegeven tussen pagina's. Sessions werden niet geinitialiseerd. URL parameters worden verkeerd gebruikt.	|														