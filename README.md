# makenPOC

Proof of Concept

Onze design challenge luidt als volgt: 
“Hoe kunnen we BDD cliënten helpen om hun herstelproces inzichtelijker te maken, zodat ze zich bewust worden van hun gedrag en minder kans hebben op een terugval?” 

Een belangrijk onderdeel binnen de applicatie is privacy. (Ex-)patiënten delen gevoelige gegevens en ze willen niet dat mensen die hier geen baat bij hebben zomaar deze gegevens kunnen bekijken.

Ik heb hier de volgende deelvraag uit gehaald:
“Hoe kan de applicatie zo ingericht worden dat het aan de privacy eisen van de gebruiker voldoet?” 

#Leerdoelen
- Goed technisch onderzoek verrichten;
- Net HTML/CSS prototype maken (of Framer).

#Uitdagingen
- Op welke manier gaat de applicatie ingericht worden, kijkend naar privacy?

#Inleiding
Privacy is een belangrijk gegeven in de medische wereld. Tijdens de interviews gaven de patiënten aan dat zij graag een app als My Health Diary zouden willen gebruiken. Ze willen echter wel zeker weten dat zij ook gegeven ontoegankelijk kunnen maken voor anderen en dat er geen misbruik gemaakt kan worden van de gegevens die geplaatst worden. Wanneer ik denk aan privacy binnen een applicatie, komen de volgende aspecten bij mij op:

- Laten we gebruikers anoniem content plaatsen?
- Maakt de applicatie gebruik van een privé modus?
- Staan we screenshots van de applicatie toe?

#Onderzoek

Laten we gebruikers anoniem content plaatsen?

Gebruikers volledig anoniem content laten plaatsen heeft voordelen en nadelen. Zonder enig voor onderzoek denk ik bij de voordelen aan meer eerlijkheid. Ik heb zelf het idee dat mensen eerlijker zijn over zichzelf en hun prestaties en problemen wanneer ze weten dat niemand weet wie iets heeft geplaatst. Aan de andere kant zie ik een nadeel in volledige anonimiteit omdat ook de therapeuten niet bij zouden kunnen houden hoe het met welke ex-patiënt gaat. Voor hen is het wel fijn om te weten wie er wat geplaatst heeft. 

Bindu Reddy is oprichter van Candid, een volledig anonieme app waar mensen hun ongezouten mening op kunnen plaatsen. Ze kwam erachter dat mensen Facebook en Twitter inruilden voor de anonieme app, omdat zij op Candid wel hun mening over politiek konden plaatsen, zonder meteen een vloedgolf aan commentaar over zich heen te krijgen. Er is dus wel degelijk behoefte aan anonimiteit. 

De keerzijde van deze app was echter ook heel duidelijk: meer dan 40% en soms zelfs 70% van de geplaatste content wordt verwijderd doordat er misbruik wordt gemaakt van de anonimiteit: de posts bevatten pesterijen, spam en andere soorten misbruik. 

Binnen een volledig anonieme applicatie kan je niet voorkomen dat mensen worden lastig gevallen of dat de anonimiteit wordt misbruikt. Daarom denk ik dat het geen goed idee is om gebruikers de mogelijkheid te geven alleen maar volledig anoniem content te plaatsen. 

Bron: http://fortune.com/2016/07/21/candid-anonymous-app/
Bron: http://fortune.com/2016/08/11/candid-app-anonymity/

Maakt de app gebruik van een privé modus?

Uit een onderzoek van elie.net blijkt dat 19,1% van de internet gebruikers regelmatig de privé modus gebruikt. De privé modus wordt vooral gebruikt om mensen op te zoeken, informatie te vinden, te winkelen of om volwassen websites te bezoeken. 22,6% van deze gebruikers is man. Dit onderzoek laat zien dat er wel degelijk behoefte is aan een privé modus, omdat niet iedereen handelingen uitvoert wanneer deze zichtbaar zijn voor iedereen. (Bron: https://www.elie.net/blog/privacy/19-of-users-use-their-browser-private-mode)

Daarom wil ik de gebruikers van My Health Diary de mogelijkheid geven om in privé modus een post te plaatsen. Facebook heeft een vergelijkbare optie als je kijkt naar posten, namelijk de ‘Alleen ik’ modus. Op deze manier kan jij een foto plaatsen of een bericht schrijven zonder dat iemand anders hier toegang tot heeft. Deze zelfde functie wil ik gaan verwerken in My Health Diary. 

Staan we screenshots in de applicatie toe?

Om misbruik te voorkomen kunnen er geen screenshots worden gemaakt van de applicatie en de posts van (andere) gebruikers. Er zijn al verschillende apps die maatregelen hebben genomen tegen screenshots: Snapchat stuurt jou een melding wanneer de gebruiker naar wie jij een Snap hebt verstuurd een screenshot maakt en Instagram doet dit tegenwoordig ook, wanneer gebruiker een screenshot maken van een tijdelijke direct message. Op deze manier worden gebruikers geattendeerd op het feit dat er informatie is opgeslagen. 

Android staat bij sommige applicaties screenshots helemaal niet toe en geeft dan de volgende melding. Er kunnen bijvoorbeeld geen screenshots worden gemaakt van de ABM Amro applicatie, omdat deze applicatie gevoelige informatie bevat. 

Wanneer laatst genoemde functie ook in My Health Diary wordt toegepast, weten de gebruikers zeker dat er geen misbruik gemaakt kan worden door anderen door middel van screenshots. Op deze manier voelt de applicatie veiliger en zijn er minder factoren die de gebruiker tegenhouden om compleet eerlijk te zijn in de applicatie. 

Bron: http://www.theandroidsoul.com/psst-beta-releases-play-store-lets-send-receives-messages-auto-deletes-read/

Conclusie

Het is erg belangrijk dat de privacy van de gebruikers wordt gewaarborgd. Een volledig anonieme app zal niet helemaal gaan werken binnen dit concept, maar delen anoniem maken wel. Door een privé modus toe te voegen kunnen gebruikers hun hart luchten zonder dat anderen mee lezen en dat kan soms erg fijn zijn. Door screenshots uit te sluiten kan er geen misbruik gemaakt worden van de informatie die de gebruikers delen in de applicatie. 



