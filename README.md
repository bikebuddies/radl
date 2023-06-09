# BikeBuddies

Miriam Kirschner, Laura Saxer, Simon Damarow

VU Geoinformatik: Web mapping (Sommersemester 2023) – Konzept zum Gruppenprojekt
Projektgruppe: Simon Damarow, Miriam Kirschner, Laura Saxer
09. Juni 2023
BikeBuddies
Das konzipierte Kartenprojekt soll die Planung und Durchführung von Fahrradtouren in der Region Ostösterreich unterstützen.
Um die Karte für Ausflüge und Radurlaube gut nutzen zu können, werden neben Fahrradwegen und GPX-Tracks mit empfohlenen Touren auch zusätzliche Informationen und Angebote angezeigt,
die zu einer angenehmen Radreise beitragen. Die Bundesländer, auf die sich das Projekt vorerst konzentriert, sind Burgenland, Wien und Niederösterreich. Im Rahmen der Projektarbeit werden 
somit vier HTML-Seiten erstellt. Das Projekt soll mit Ende der Projektarbeit jedoch weiterhin ausbaubar bleiben, um auch später zusätzliche Bundesländer und Radregionen mit entsprechenden
Daten hinzufügen zu können, wenn Bedarf und Interesse von Nutzer/innen bestehen.
Auf der Startseite des Projekts werden zunächst die Inhalte, Funktionen und Anwendungsmöglichkeiten der Karte in einem Einleitungstext erklärt. 
Darunter soll eine Übersichtskarte die verschiedenen Radwege der gesamten Region Oberösterreich (z.B. OpenCycleMap, JSON Files von Radwegen der jeweiligen Bundesländer von data.gv.at),
sowie die Radrouten, welche in den Pulldown Seiten des Kartenprojekts näher vorgestellt werden, als Hintergrund- bzw. Themenlayer darstellen. Außerdem soll ein aufklappbares Fenster, 
in dem man Ortsnamen eingeben kann, welche anschließend auf der Karte angezeigt werden, in der Übersichtskarte eingebaut werden. Das Suchfenster soll dabei helfen, die eigene Position zu finden,
wenn man gerade kein GPS hat, bzw. im Vorfeld einen bestimmten Ort zu suchen, um von dort die nächsten Radtouren zu planen.
Mithilfe eines Geolocation Plugins soll die eigene Position auf der Karte angezeigt werden (dazu gibt es noch die Frage zu klären, ob es ein Plugin gibt, welches die Position automatisch aktualisiert,
nicht nur beim Neu-Laden der Seite.). Unter der Karte wird noch ein kurzer Text mit Informationen zum Kontext des Projekts und zu unserer Gruppe eingefügt.
Mittels einem Pulldown Menü auf der Startseite kann der/die Nutzer/in das Bundesland auswählen, wo geradelt werden soll und wird dann auf die entsprechende neue Seite weitergeleitet.
Auf der jeweiligen Seite eines Bundeslands befinden sich dann Informationen über die ausgewählten Radwege als Text in Form von kurzen Beschreibungen der Routen. 
Wir werden ca. fünf Touren pro Bundesland auswählen, die wir am ansprechendsten finden. Neben hilfreicher Hintergrundlayer (z.B. Orthofotos und Topographie mit Beschriftungen)
sollen die GPX Tracks auf der Karte als Themenlayer der ausgewählten Routen in verschiedenen Farben und mit ihren dazugehörigen Höhenprofilen darunter dargestellt werden.
Diverse Points of Interest (z.B. Badegewässer von data.gv.at; Eisdielen, die wir selbst in einem Dokument aus verschiedenen Quellen entlang der Routen sammeln und in das Projekt einbinden) 
werden wir entlang der Routen und entsprechend der Datenverfügbarkeit als zusätzliche Themenlayer anbieten, die optional als Marker mit informativen Popups angezeigt werden können. 
Insgesamt werden folgende Plugins für die Karten zu Verfügung stehen:
- Providers (OSM, Open Cycle Map, Orthofotos, etc. als Hintergrundlayer)
- Minimap
- Fullscreen
- Geolocation
- Hash
- Markercluster
- Wettervorhersage

Weiterführende Links zu weiteren nützlichen Informationen zur Region, wie z.B. ein Verzeichnis zu Unterkünften und Heurigen- bzw. Buschenschankkalender, werden unter der jeweiligen Karte aufgelistet.
VU Geoinformatik: Web mapping (Sommersemester 2023) – Konzept zum Gruppenprojekt
Projektgruppe: Simon Damarow, Miriam Kirschner, Laura Saxer
Mögliche Quellen für GPX Tracks:
• Top Radrouten (burgenland.info): https://www.burgenland.info/erleben/sportlich-aktiv/mit-dem-rad/top-radrouten
• Top-Radrouten in Niederösterreich - Radfahren in Niederösterreich (niederoesterreich.at): https://www.niederoesterreich.at/top-radrouten
• #gofuture be happy - (mobilitaetsagentur.at): https://www.mobilitaetsagentur.at/touren/

Mögliche Quellen für Points of Interest:
• Österreichische Badegewässer: https://www.data.gv.at/katalog/dataset/2646025c-8ab9-4850-b76c-c2f508b34798, https://www.data.gv.at/katalog/dataset/898afe8c-0297-45d6-b4b5-0cb9e632094b
• Eisgeschäfte: Koordinaten von google.maps in eigenes Excel übertragen
Mögliche Quellen für weiterführende Links:
• Heurigen und Buschenschanken: Heurigenkalender (https://www.heurigenkalender.at/de/), Wienerheurige (http://www.wienerheurige.at/de/), Heurigenkalender Niederösterreich (https://heurigenkalender.niederoesterreich.at/), Heurige und Buschenschenken (https://www.burgenland.info/heurige-und-buschenschenken)
• Unterkünfte: für Radfahrer (https://www.burgenland.info/uebernachten/unterkuenfte/unterkuenfte-fuer-radfahrer), Hotels & Unterkünfte in Wien - wien.info (https://www.wien.info/de/reiseinfos/hotels-unterkunft/liste-der-unterkuenfte?type=pension,privatzimmer&bycicle=is_bike_friendly), Radfreundliche Betriebe - Radfahren in Niederösterreich (niederoesterreich.at) (https://www.niederoesterreich.at/radfreundliche-unterkunft)
