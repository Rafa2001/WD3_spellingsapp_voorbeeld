# Spellingsoefeningen Applicatie

## Beschrijving

Je maakt een applicatie waarmee je spellingsoefeningen kunt maken voor het vak Nederlands. De applicatie werkt gelijkaardig aan apps zoals DuoLingo of Memrise.

Op basis van een template ontwerp je een user interface die geschikt is voor dit soort programma. De UI bestaat uit twee pagina's: een hoofdpagina en een oefenpagina.

Elke oefening kan gemaakt worden als invul-oefening **EN** als meerkeuze-oefening. Elke oefening bevat daarom een unieke ID, een vraag, een categorie, een moeilijkheidsgraad, een juist antwoord, de regel die toegepast moet worden en een lijst met foute antwoorden. De lijst met foute antwoorden wordt gebruikt wanneer de oefening als meerkeuze wordt weergegeven.

De verschillende categorieën en moeilijkheidsgraden van oefeningen krijgen jullie van de leraar Nederlands.

Oefeningen worden altijd in oefeningenreeksen gemaakt. Een oefeningenreeks bestaat uit 10 willekeurige oefeningen van één categorie en dezelfde moeilijkheidsgraad, waarvan er minstens 5 uniek zijn. Het komt dus zelden voor dat een gebruiker dezelfde oefeningenreeks krijgt voorgeschoteld, omdat elke reeks telkens bestaat uit een willekeurige greep van 5 of meer oefeningen uit de database.

Op de hoofdpagina kan een gebruiker kiezen welke moeilijkheidsgraad en categorie zij of hij graag wenst. Wanneer de categorie is gekozen start er automatisch een oefeningenreeks.

De 10 oefeningen van een oefeningenreeks worden één voor één getoond op de oefenpagina. De oefening wordt willekeurig getoond als meerkeuze- of invul-oefening. Bij het geven van een juist antwoord krijgt de gebruiker een positieve boodschap, waarna zij of hij de volgende oefening kan beginnen. Bij het geven van een fout antwoord krijgt de gebruiker het juiste antwoord te zien en de regel die toegepast moest worden, waarna de volgende oefening gestart kan worden. Aan het einde van een oefeningenreeks word de score van de gebruiker getoond in een pop-up op de oefenpagina. Op elk moment moet een gebruiker de oefeningenreeks kunnen stopzetten en terugkeren naar de hoofdpagina.

## Voorwaarden

 - de applicatie wordt ontwikkeld met behulp van HTML, CSS en PHP.
   - ontwikkel je applicatie steeds met Mobile First in gedachte.
 - styling wordt in één externe stylesheet gebundeld. 
   - stijlen en selectors worden zoveel mogelijk herbruikt en gedeeld tussen de twee pagina's.
 - er wordt gebruik gemaakt van een icon library (bv. Google Material Icons of Font Awesome).
 - de vragen-database is één array waarin alle informatie wordt opgeslagen. Dit mag (moet?) een array van arrays (van arrays, ...) zijn. 
 - Er worden functies gemaakt om informatie uit de array op te vragen.
 - De applicatie werkt zoals in de beschrijving.

## Woordenlijst
| WOORD | OMSCHRIJVING |
| --- | --- |
| spellingsoefening | Eén oefening die een gebruiker kan maken. De oefening bestaat uit een vraag, een antwoord, een categorie, een moeilijkheidsgraad en een lijst met foute antwoorden. |
| oefeningenreeks | Een gebruiker maakt oefeningen altijd in een reeks van 10 willekeurige oefeningen. Een oefeningenreeks bevat 10 willekeurige vragen van dezelfde moeilijkheidsgraad en dezelfde categorie. Van de oefeningen moeten er minstens 5 telkens uniek zijn. |
| hoofdpagina | de pagina van waaruit een gebruiker een oefeningenreeks kan starten. |
| oefenpagina | de pagina waarop een oefening getoond wordt en, aan het einde van een oefeningenreeks, de score die behaald werd. |