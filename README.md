[LEESMIJ.txt](https://github.com/user-attachments/files/33303859/LEESMIJ.txt)
BLINKTRANSLATE
==============

Vertaalt de chat in Dota 2 naar het Engels, en vertaalt een zelf
getypte zin naar de taal van de andere spelers. De vertalingen komen in
een eigen blok boven de chat van het spel. Engels en Nederlands blijven
staan zoals ze gezegd zijn.


STARTEN
-------

1. Dubbelklik op BlinkTranslate.exe.

   Windows kan een blauw scherm tonen ("Windows heeft uw pc beveiligd"),
   omdat dit programma niet van een grote uitgever komt. Dat is hier
   normaal. Klik op "Meer info" en daarna op "Toch uitvoeren".

2. De eerste keer opent een instelvenster dat je door alles heen helpt:

   - Een gratis sleutel voor het vertalen. Het venster heeft een knop
     die de juiste Google-pagina opent. Maak of kopieer daar een sleutel
     en plak die in het venster. Met "Test de sleutel" zie je meteen of
     hij werkt.

   - Dota laten meeluisteren. Het venster zet met een knop een klein
     bestandje in je Dota-map. Daarna moet je Dota een keer opnieuw
     opstarten.

   - De beeldmodus. Zet Dota op "Borderless Window" of "Windowed":
     Instellingen -> Video -> Weergavemodus. In "Exclusive Fullscreen"
     kan geen enkel programma iets over je game tekenen.

   - Je talen, en een controle of alles klaarstaat.

3. Klik op "Start BlinkTranslate". De volgende keer start het meteen
   door; het instelvenster hoef je alleen opnieuw te openen als je iets
   wilt veranderen (knop "Instellingen").


GEBRUIKEN
---------

Start BlinkTranslate en daarna Dota. Het programmavenster mag open
blijven staan; daar zie je de verbinding en de laatste vertalingen.

De vertalingen verschijnen vanzelf boven de chat. Druk je in het spel op
Enter om de chat te openen, dan blijft het blok staan en kun je met het
muiswiel terugscrollen.

Zelf iets zeggen:

    Ctrl+Enter          een bericht naar je team
    Ctrl+Shift+Enter    een bericht naar alle spelers

Er opent een invoerregel. Typ in het Nederlands of Engels en druk op
Enter; de vertaling gaat de chat in. In die regel wisselt Tab tussen
team en iedereen, en Shift+Tab van taal. Je kunt ook een taal voorop
zetten, bijvoorbeeld "spa: hola".


ALS ER IETS NIET WERKT
----------------------

Het blok blijft leeg
    Er komen geen spelgegevens binnen. Open het instelvenster (knop
    "Instellingen"), zet het cfg-bestand opnieuw neer en herstart Dota.

Het blok is onzichtbaar tijdens het spelen
    Dota staat op Exclusive Fullscreen. Zet het op Borderless Window.

Ctrl+Enter doet niets
    Een ander programma heeft die toetscombinatie al.

Een bericht komt in het verkeerde chatkanaal
    Open het instelvenster; onder de taalstap kun je dit niet wijzigen,
    maar in instellingen.json staat "chat_openen" dat je kunt omdraaien.

Zet in het programmavenster "Logboek: aan" als iets niet werkt; dan
schrijft het programma gsi-log.txt en programma-log.txt naast de .exe.


PRIVACY
-------

De chatregels gaan naar het taalmodel van Google om vertaald te worden.
Op de gratis toegang mag Google die gegevens gebruiken om zijn modellen
te verbeteren, en kunnen medewerkers ze inzien. Alleen chatregels gaan
die kant op, geen spelersnamen en geen andere spelgegevens.

Je sleutel is persoonlijk. Deel hem niet. Elke speler gebruikt zijn
eigen gratis sleutel.

Het programma leest de chat uit de spelgegevens die Dota zelf aanbiedt,
over een verbinding die niet verder komt dan je eigen pc. Er wordt geen
proces geopend en niets uit het geheugen van het spel gelezen. Voor een
eigen bericht worden toetsaanslagen naar Windows gestuurd, zoals een
macrotoets doet.
