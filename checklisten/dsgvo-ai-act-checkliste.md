# Checkliste zur Einführung eines KI-Systems

Diese Checkliste begleitet die Einführung eines neuen KI-gestützten Werkzeugs im Unternehmen, von der ersten Prüfung bis zur Dokumentation. Sie ist für jedes einzelne System separat auszufüllen und im Anschluss als Nachweis aufzubewahren. Ein ausgefülltes Beispiel findet sich in `fallbeispiel/kmu-chatbot-fallbeispiel.md`.

Rechtsstand: Verordnung (EU) 2024/1689 (AI Act) mit Anwendungsbeginn der hier relevanten Vorschriften gemäß Art. 113 AI Act; Datenschutz-Grundverordnung (DSGVO).

## Schritt 1: Systeminventar

- [ ] Name des Systems und Anbieter
- [ ] Zweck der geplanten Nutzung im Unternehmen (konkret, nicht "allgemeine Unterstützung")
- [ ] Betroffene Abteilung(en) und Anzahl der Nutzenden
- [ ] Wird das System als fertiges Produkt genutzt (z. B. ChatGPT-Weboberfläche) oder in eine eigene Anwendung integriert (z. B. über eine API)?
- [ ] Verarbeitet das System dabei personenbezogene Daten von Kunden, Beschäftigten oder Dritten? Falls nein, weiter zu Schritt 2, Abschnitt AI Act; Schritt 3 entfällt dann größtenteils.

## Schritt 2: Einordnung nach dem AI Act

### 2.1 Verbotene Praktiken (Art. 5 AI Act)

- [ ] Das System dient nicht der unterschwelligen Beeinflussung von Personen zu deren Schaden.
- [ ] Das System dient nicht der Ausnutzung von Schutzbedürftigkeit aufgrund von Alter, Behinderung oder sozialer/wirtschaftlicher Lage.
- [ ] Das System wird nicht zur sozialen Bewertung (Social Scoring) von Personen eingesetzt.
- [ ] Das System dient nicht der biometrischen Kategorisierung zur Ableitung sensibler Merkmale (z. B. politische Meinung, sexuelle Orientierung).
- [ ] Das System wird nicht zur Emotionserkennung am Arbeitsplatz eingesetzt (vorbehaltlich der engen Ausnahmen in Art. 5 Abs. 1 lit. f AI Act).

Ist auch nur eine dieser Aussagen falsch, ist die geplante Nutzung nicht zulässig. Das Verfahren endet an dieser Stelle; die Datenschutzbeauftragte ist zu informieren.

### 2.2 Hochrisiko-Einstufung (Art. 6 i. V. m. Anhang III AI Act)

- [ ] Das System wird nicht zur automatisierten Vorauswahl, Bewertung oder Ablehnung von Bewerbungen eingesetzt.
- [ ] Das System wird nicht zur Bewertung, Beförderung oder Kündigung von Beschäftigten eingesetzt.
- [ ] Das System wird nicht zur Bonitätsprüfung oder Kreditwürdigkeitsbewertung von Personen eingesetzt.
- [ ] Das System wird nicht in einem Produkt eingesetzt, das bereits einer produktrechtlichen Sicherheitsprüfung unterliegt (z. B. Medizinprodukte, Maschinen).

Ist eine dieser Aussagen falsch, handelt es sich voraussichtlich um ein Hochrisiko-System im Sinne des AI Act. Für ein solches System reicht diese Checkliste nicht aus; es sind die weitergehenden Pflichten aus Titel III Kapitel 2 AI Act zu prüfen (Risikomanagementsystem, Daten-Governance, technische Dokumentation, menschliche Aufsicht), bevor eine Nutzung erfolgen darf.

### 2.3 Transparenzpflichten (Art. 50 AI Act)

- [ ] Tritt das System gegenüber Kunden oder Dritten direkt in Erscheinung (z. B. Chatbot, Sprachassistent)? Falls ja: Ist sichergestellt, dass die interagierende Person erkennt, dass sie mit einem KI-System kommuniziert, sofern dies nicht ohnehin offensichtlich ist (Art. 50 Abs. 1)?
- [ ] Erzeugt oder verändert das System Bild-, Audio- oder Videoinhalte, die authentisch wirken könnten? Falls ja: Ist eine maschinenlesbare Kennzeichnung als KI-generiert vorgesehen (Art. 50 Abs. 2)?
- [ ] Werden mit dem System sogenannte Deepfakes erzeugt oder verändert? Falls ja: Ist eine Offenlegung gegenüber dem Publikum vorgesehen (Art. 50 Abs. 4)?

### 2.4 KI-Kompetenz (Art. 4 AI Act)

- [ ] Die betroffenen Mitarbeitenden haben die interne KI-Richtlinie zur Kenntnis genommen.
- [ ] Eine Einweisung in die konkreten Grenzen und Fehlerquellen des Systems hat stattgefunden.
- [ ] Die Teilnahme an der Einweisung ist dokumentiert.

## Schritt 3: Datenschutzrechtliche Prüfung (nur bei Verarbeitung personenbezogener Daten)

- [ ] Rechtsgrundlage der Verarbeitung nach Art. 6 DSGVO ist bestimmt (z. B. berechtigtes Interesse, Vertragserfüllung, Einwilligung).
- [ ] Es werden keine besonderen Kategorien personenbezogener Daten nach Art. 9 DSGVO eingegeben, oder eine Ausnahme nach Art. 9 Abs. 2 DSGVO liegt vor.
- [ ] Mit dem Anbieter besteht ein Vertrag zur Auftragsverarbeitung nach Art. 28 DSGVO.
- [ ] Der Verarbeitungsort bzw. eine mögliche Datenübermittlung in ein Drittland ist bekannt. Falls eine Übermittlung in ein Land außerhalb des EWR erfolgt: Angemessenheitsbeschluss oder Standardvertragsklauseln liegen vor.
- [ ] Es ist festgelegt, ob und wie betroffene Personen nach Art. 13/14 DSGVO über die Verarbeitung informiert werden (z. B. Hinweis in der Datenschutzerklärung, sofern Kundendaten betroffen sind).
- [ ] Es ist geprüft, ob die Verarbeitung eine automatisierte Entscheidung mit rechtlicher oder ähnlich bedeutsamer Wirkung im Sinne von Art. 22 DSGVO darstellt. Falls ja, sind die dortigen zusätzlichen Voraussetzungen erfüllt.
- [ ] Es ist geprüft, ob aufgrund der Art, des Umfangs oder des Zwecks der Verarbeitung eine Datenschutz-Folgenabschätzung nach Art. 35 DSGVO erforderlich ist (etwa bei umfangreicher Verarbeitung oder systematischer Überwachung).
- [ ] Löschfristen für die in das System eingegebenen bzw. dort verarbeiteten Daten sind festgelegt.

## Schritt 4: Dokumentation

- [ ] Ein Eintrag im Verzeichnis von Verarbeitungstätigkeiten wurde nach der Vorlage in `vvt/verzeichnis-verarbeitungstaetigkeiten-llm.md` erstellt (sofern personenbezogene Daten verarbeitet werden).
- [ ] Das System wurde in die Liste der freigegebenen KI-Systeme aufgenommen.
- [ ] Diese Checkliste wurde vollständig ausgefüllt, datiert und unterzeichnet abgelegt.

Ausgefüllt am: ______________ von: ______________

Freigabe durch die Datenschutzbeauftragte / den Datenschutzbeauftragten am: ______________
