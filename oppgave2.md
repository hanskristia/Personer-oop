# Nå skal du utvide Person -klassen du har jobbet med i oppgavene 1.
## Lag klassen Elev som arver fra klassen Person .
1. Lag metoden finnTrinn() som bruker elevens fødselsår til å avgjøre hvilket trinn eleven tilhører (Vg1, Vg2 eller Vg3). Her finnes det mange unntak, men bruk det årstallet som gjelder flest elever. Hvis årstallet ikke stemmer med dem som går på Vgs i dag, kan du skrive «ukjent trinn» i stedet.
2. Utvid metoden visInfo() slik at elevens trinn skrives ut sammen med resten av informasjonen (som definert i Person -klassen).
3. Lag tre Elev -objekter og test visInfo() -metoden for hvert av dem.

# Lag klassen Laerer som arver fra klassen Person. 
4. En lærer skal ha en liste med fag som læreren kan undervise i, og en tekstvariabel som inneholder klassen læreren har kontaktlæreransvar for. Som standardverdi skal denne tekstvariabelen få verdien "" (en tom tekst).
5. Lag en metode i klassen Laerer som kan sjekke om en lærer underviser i et bestemt fag. Fagets navn skal gis som parameter, og metoden skal returnere True eller False .
6. Utvid metoden visInfo() slik at lærerens fag og eventuelle kontaktlærerklasse skrives ut på en fin måte. Skriv ut informasjonen over to linjer, der den første linja er den som allerede er definert i Person -klassen.
7. Lag to Laerer -objekter og test visInfo() -metoden for begge. Test også metoden som sjekker om lærerne underviser i et gitt fag.