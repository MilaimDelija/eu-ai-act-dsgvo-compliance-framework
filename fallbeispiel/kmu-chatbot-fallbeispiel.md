# Fallbeispiel: Einführung eines Kundenservice-Chatbots bei einem mittelständischen Unternehmen

Das folgende Beispiel ist fiktiv und dient dazu, die drei Dokumente dieses Repositoriums (interne KI-Richtlinie, Checkliste, Verzeichnis von Verarbeitungstätigkeiten) an einem zusammenhängenden Fall zu zeigen. Die Mustermann GmbH beschäftigt vierzig Mitarbeitende und vertreibt technische Ersatzteile über einen Onlineshop. Der Kundenservice erhält täglich eine größere Zahl wiederkehrender Anfragen zu Bestellstatus, Versandzeiten und Rückgaben und möchte diese über einen auf einem Sprachmodell basierenden Chatbot auf der eigenen Website vorqualifizieren, bevor sie gegebenenfalls an einen Mitarbeitenden weitergeleitet werden.

## Ausgangslage

Die Geschäftsführung hat von einem Anbieter erfahren, der eine Chatbot-Lösung auf Basis eines großen Sprachmodells anbietet, und möchte diese kurzfristig einführen. Bevor eine Entscheidung getroffen wird, zieht sie die interne Datenschutzbeauftragte hinzu, die das Vorhaben anhand der Checkliste aus diesem Repositorium prüft.

## Schritt 1: Systeminventar

Das System wird nicht als isoliertes Produkt genutzt, sondern über eine Programmierschnittstelle in die bestehende Website eingebunden. Es beantwortet Anfragen von Website-Besuchern, die dabei ihren Namen, ihre Bestellnummer und ihr Anliegen im Freitext eingeben. Personenbezogene Daten sind damit unstreitig betroffen, sodass sowohl die Prüfung nach dem AI Act als auch die datenschutzrechtliche Prüfung vollständig durchlaufen werden.

## Schritt 2: Einordnung nach dem AI Act

Bei der Prüfung der verbotenen Praktiken nach Art. 5 AI Act ergeben sich keine Auffälligkeiten: Der Chatbot beeinflusst niemanden unterschwellig, bewertet keine Person sozial und nimmt keine biometrische Kategorisierung vor. Auch die Prüfung der Hochrisiko-Tatbestände nach Anhang III fällt negativ aus, da der Chatbot weder über Beschäftigungsverhältnisse noch über Kreditwürdigkeit entscheidet, sondern ausschließlich Bestellinformationen kommuniziert.

Anders verhält es sich mit den Transparenzpflichten aus Art. 50 AI Act. Da der Chatbot unmittelbar mit Website-Besuchern interagiert, muss für diese erkennbar sein, dass sie nicht mit einem Menschen kommunizieren. Die Datenschutzbeauftragte legt fest, dass der Chatbot sich zu Beginn jedes Gesprächs eindeutig als automatisiertes System zu erkennen gibt und dass diese Kennzeichnung nicht in den erweiterten Einstellungen deaktiviert werden darf. Da der Chatbot keine Bilder, Audio- oder Videoinhalte erzeugt, sind Art. 50 Abs. 2 und Abs. 4 AI Act hier nicht einschlägig.

Für die mit dem System arbeitenden Kundenservice-Mitarbeitenden wird eine kurze Einweisung angesetzt, die insbesondere auf die Möglichkeit falscher oder unpräziser Antworten des Systems eingeht. Diese Einweisung erfüllt zugleich die Pflicht zur KI-Kompetenz nach Art. 4 AI Act.

## Schritt 3: Datenschutzrechtliche Prüfung

Als Rechtsgrundlage kommt Art. 6 Abs. 1 lit. b DSGVO in Betracht, soweit sich die Anfrage auf eine bestehende Bestellung bezieht, da die Bearbeitung dieser Anfragen Teil der Vertragserfüllung gegenüber dem Kunden ist. Besondere Kategorien personenbezogener Daten nach Art. 9 DSGVO sind bei Bestellanfragen nicht zu erwarten; die Datenschutzbeauftragte weist die Kundenservice-Leitung dennoch an, den Chatbot regelmäßig stichprobenartig zu prüfen, da Kunden im Freitextfeld grundsätzlich auch ungefragt sensible Angaben machen könnten.

Mit dem Anbieter des Sprachmodells wird ein Vertrag zur Auftragsverarbeitung nach Art. 28 DSGVO geschlossen. Da die Verarbeitung in Rechenzentren außerhalb des Europäischen Wirtschaftsraums erfolgt, prüft die Datenschutzbeauftragte, auf welcher Grundlage diese Übermittlung zulässig ist, und stellt fest, dass der Anbieter Standardvertragsklauseln anbietet und zusätzliche technische Maßnahmen zur Absicherung der Übermittlung beschreibt. Diese werden im Verzeichnis von Verarbeitungstätigkeiten dokumentiert.

Eine automatisierte Entscheidung mit rechtlicher oder ähnlich bedeutsamer Wirkung im Sinne von Art. 22 DSGVO liegt nicht vor, da der Chatbot keine verbindlichen Entscheidungen trifft, sondern lediglich informiert und bei Bedarf an einen Mitarbeitenden weiterleitet. Angesichts des begrenzten Umfangs der Verarbeitung und des Fehlens einer systematischen Überwachung kommt die Datenschutzbeauftragte zu dem Ergebnis, dass eine Datenschutz-Folgenabschätzung nach Art. 35 DSGVO nicht erforderlich ist, hält diese Einschätzung jedoch schriftlich fest, um sie im Fall einer späteren Ausweitung des Systems erneut prüfen zu können.

## Schritt 4: Dokumentation

Auf Grundlage dieser Prüfung wird ein Eintrag im Verzeichnis von Verarbeitungstätigkeiten angelegt, wie er als ausgefülltes Beispiel in `vvt/verzeichnis-verarbeitungstaetigkeiten-llm.md` hinterlegt ist. Der Chatbot wird in die unternehmensinterne Liste freigegebener KI-Systeme aufgenommen, und die ausgefüllte Checkliste wird zusammen mit dem Auftragsverarbeitungsvertrag als Nachweis abgelegt.

## Ergebnis

Die Einführung des Chatbots wird freigegeben, verbunden mit drei Auflagen: der sichtbaren Kennzeichnung als KI-System zu Gesprächsbeginn, der Einweisung der Kundenservice-Mitarbeitenden vor Inbetriebnahme, und einer erneuten Prüfung durch die Datenschutzbeauftragte, falls der Chatbot künftig auch auf Bestandsdaten wie Zahlungsinformationen oder Vertragshistorie zugreifen oder eigenständig über Rückerstattungen entscheiden soll. Im letzteren Fall wäre die Einordnung nach Anhang III AI Act sowie nach Art. 22 DSGVO neu zu bewerten.

Dieses Beispiel zeigt, dass die eigentliche Arbeit selten in der Einordnung des Systems selbst liegt, sondern in den Anschlussfragen: welchem Anbieter man vertraut, wie eine Drittlandübermittlung abgesichert wird, und welche Auflagen eine an sich unproblematische Anwendung dennoch begleiten müssen.
