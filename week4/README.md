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