*********
Inleiding
*********

.. admonition:: Concepten en leerdoelen

  * Internet of Things - als volgende stap in de ontwikkeling van het internet
  * IoT-toepassingen: van sensordata naar beslissingen, met gebruik van Data Science en Artificial Intelligence
  * persoonlijke en maatschappelijke gevolgen van IoT-toepassingen

.. rubric:: Van Internet van computers tot Internet of Things

.. figure:: inleiding/Internet-of-computers.png
   :width: 400px
   :align: center

   Internet of computers

De eerste gebruikers van het internet waren universiteiten en onderzoeksinstellingen.
Belangrijke toepassingen uit die periode zijn e-mail, file-transfer (ftp),
remote login (telnet, nu ssh), en chat (IRC, internet relay chat).
Deze periode zou je het "internet van computers" kunnen noemen:
het internet werd vooral gebruikt om computers aan elkaar te verbinden,
en bijvoorbeeld om op afstand toegang te hebben tot supercomputers.

.. figure:: inleiding/Internet-of-people.png
   :width: 400px
   :align: center

   Internet of people

Rond 1989/1990 vonden twee belangrijke ontwikkelingen plaats:
het internet werd voor iedereen toegankelijk;
en Tim Berners-Lee bedacht het web, met als eerste browser "WorldWideWeb".
Later werden de browsers Netscape Navigator (de voorloper van Firefox) en Internet Explorer.
Door het gemak van het web is het gebruik van het internet in de periode 1990-2000 razendsnel gegroeid.

  Het web is een toepassing van het internet.
  HTTP, het web-protocol, is gebaseerd op de basisprotocollen van het internet: TCP met daaronder IP.
  Alleen dit laatste protocol vind je in het eigenlijke internet terug.
  Voor een nieuwe toepassing hoef je alleen de eindpunten (eindapparaten) aan te passen,
  niet het netwerk zelf (*end-to-end* principe).
  Dit maakt het erg eenvoudig om nieuwe toepassingen in te voeren.

Een volgende stap was de introductie van de smartphone:
vooral de iPhone (2007) heeft de aanzet gegeven tot de smartphone als *persoonlijk internet apparaat*.
Dit leidt tot de opkomst van "sociale toepassingen" zoals Facebook en Twitter.
Deze periode zou je het *internet van mensen* kunnen noemen:
het internet verbindt niet alleen computers, maar ook mensen.

Voor het aansluiten van een smartphone op het internet heb je *mobiel internet* nodig:
via een radioverbinding (bijvoorbeeld 3G, 4G, enz.) maakt je telefoon verbinding met het netwerk van je internet-provider.
Deze netwerkprovider heeft daarvoor overal antenne's geplaatst, bij voorkeur hoog op een gebouw of in een mast.
Via het netwerk van je provider maak je dan verbinding met de rest van het internet.
De rest van het internet hoeft voor het gebruik van smartphones en de bijbehorende toepassingen niet aangepast te worden.

Overigens

.. figure:: inleiding/Internet-of-things.png
   :width: 400px
   :align: center

   Internet of things

Een volgende stap is het "internet of things":
door de ontwikkeling van de micro-elektronica is het mogelijk om zeer goedkope,
kleine en draadloze internetverbindingen te maken.
Hiermee kunnen allerlei "dingen" in het internet verbonden worden,
ook als deze niet over een eigen stroomvoorziening beschikken.
Het begrip "ding" is erg ruim: het kan ook gaan om levende wezens, zoals dieren of planten.
Het is nu mogelijk om computers, mensen en dingen via het internet aan elkaar te verbinden.
Het aantal internetverbindingen neemt hierdoor explosief toe.

Meestal sluit je een "ding" aan op het internet via een radioverbinding:
daarmee voorkom je lastige bedrading, en kun je werken met mobiele dingen.
Net als bij de smartphones heb je voor het internet of things alleen aanpassingen aan de rand van het netwerk nodig:
de rest van het netwerk hoeft niet aangepast te worden.

.. rubric:: Andere ontwikkelingen in de ICT: Data Science, Artificial Intelligence

Het internet of things maakt het mogelijk om beslissingen te nemen op basis van de actuele situatie - in plaats van op basis van een historisch gemiddelde.
De vele sensordata van het IoT moeten dan wel verder geanalyseerd en bewerkt worden.
De ontwikkelingen op het gebied van Data Science (big data) en Artificial Intelligence sluiten hier goed op aan:
hiermee kun je ruwe data omvormen tot zinvolle informatie.
Vaak worden de sensordata hierbij gecombineerd met data en kennis over de context.
Het combineren van de sensordata met diensten en data uit andere bronnen kom je bij veel IoT-toepassingen tegen.

In sommige gevallen worden de beslissingen op grond van de sensordata automatisch genomen, zonder tussenkomst van mensen.
Dit kan bijvoorbeeld nodig zijn om snel genoeg te reageren in risicovolle situaties.
Een dergelijke automatische verwerking stelt extra hoge eisen aan de sensordata en aan de verwerking hiervan.

  Een voorbeeld van een dergelijke volautomatisch systeem is de `Maeslantkering <https://nl.wikipedia.org/wiki/Maeslantkering>`_ in de Nieuwe waterweg.

.. rubric:: Over dit hoofdstuk

In dit hoofdstuk geven we een paar uitgebreide voorbeelden van IoT-toepassingen.
Vervolgens gaan we in op de eisen die deze toepassingen stellen aan de communicatie.
Deze eisen hebben gevolgen voor de technologie-keuzes voor deze toepassingen.
IoT-toepassingen hebben ook persoonlijke en maatschappelijke gevolgen,
bijvoorbeeld op het gebied van privacy en veiligheid.
Tenslotte geven we een lijst van mogelijke IoT-toepassingen op allerlei gebied.

.. admonition:: Samenvattend

  * het internet of things (IoT) is de meest recente uitbreiding van het internet:
    na computers en mensen verbindt het internet nu ook dingen (en dieren en planten);
  * dit betekent dat dingen met dingen kunnen communiceren (machine to machine, M2M),
    maar ook mensen met dingen of dingen met computers (diensten).
  * de ontwikkeling van het internet of things is nog maar net begonnen:
    er zullen nog veel nieuwe toepassingen bedacht worden;
  * veel IoT-toepassingen zijn bedoeld om beter/sneller/automatisch te kunnen beslissen en besturen,
    bijvoorbeeld om de efficiëntie (verbruik van energie en materialen) en de veiligheid te verbeteren.
  * het internet of things heeft gevolgen in je persoonlijke omgeving en op maatschappelijk niveau;
    naast positieve effecten zijn er ook risico's aan verbonden;
  * de ontwikkeling van het internet of things staat niet op zichzelf:
    de ontwikkelingen op het gebied van Data Science en Kunstmatige Intelligentie maken de verwerking van de "dingen"-data en het nemen van beslissingen op grond van deze data mogelijk.

.. toctree::
  :maxdepth: 2
  :hidden:

  inleiding/voorbeelden.rst
  inleiding/iot-eisen.rst
  inleiding/overzicht.rst
  inleiding/meer-voorbeelden.rst
  inleiding/gevolgen.rst
  inleiding/opdrachten.rst
  inleiding/toetsvragen.rst
