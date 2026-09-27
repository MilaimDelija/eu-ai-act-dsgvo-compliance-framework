# Verzeichnis von Verarbeitungstätigkeiten für KI-gestützte Sprachmodelle (LLM)

Diese Vorlage ergänzt das allgemeine Verzeichnis von Verarbeitungstätigkeiten nach Art. 30 DSGVO um die Angaben, die bei der Nutzung eines KI-Sprachmodells als Auftragsverarbeiter zusätzlich relevant sind. Sie ersetzt nicht das übrige Verzeichnis des Unternehmens, sondern wird dort als eigener Eintrag pro genutztem System eingefügt.

Ein KI-Sprachmodell unterscheidet sich von anderen Auftragsverarbeitern vor allem in drei Punkten, die ein gewöhnliches VVT-Formular selten abbildet: der Frage, ob Eingaben zu Trainingszwecken verwendet werden, dem Serverstandort außerhalb des EWR bei den meisten großen Anbietern, und der Schwierigkeit, im Nachhinein festzustellen, welche konkreten Daten in welcher Anfrage eingegeben wurden. Die folgenden Felder tragen dem Rechnung.

## Felder

| Feld | Erläuterung |
|---|---|
| Bezeichnung der Verarbeitungstätigkeit | Kurzer, eindeutiger Name (z. B. "Kundenservice-Chatbot auf Basis von [Anbieter]") |
| Verantwortlicher | Unternehmen, Anschrift, Kontakt der Datenschutzbeauftragten |
| Zweck der Verarbeitung | Konkreter Geschäftszweck, nicht "KI-Nutzung" allgemein |
| Kategorien betroffener Personen | z. B. Kunden, Website-Besucher, Beschäftigte |
| Kategorien personenbezogener Daten | Welche Datenarten können in Eingaben oder hochgeladenen Dateien enthalten sein |
| Rechtsgrundlage (Art. 6 DSGVO) | z. B. berechtigtes Interesse, Vertragserfüllung |
| Empfänger | Name des KI-Anbieters, Rolle als Auftragsverarbeiter (Art. 28 DSGVO), Vertragsdatum |
| Drittlandübermittlung | Land der Verarbeitung, Übermittlungsgrundlage (Angemessenheitsbeschluss, Standardvertragsklauseln) |
| Nutzung für Modelltraining | Ist vertraglich ausgeschlossen, per Opt-out deaktiviert oder nicht ausgeschlossen, mit Fundstelle in den Anbieterbedingungen |
| Speicherdauer beim Anbieter | Aufbewahrungsfrist laut Anbieter, Möglichkeit zur Löschung auf Anfrage |
| Löschfrist beim Verantwortlichen | Wie lange werden Ein- und Ausgaben unternehmensintern aufbewahrt (z. B. in Chatverläufen, Protokollen) |
| Technische und organisatorische Maßnahmen | Zugriffsbeschränkung, Protokollierung, Verschlüsselung bei Übertragung |
| Verknüpfte Dokumente | Verweis auf AVV, Checkliste (Schritt 1–4), interne KI-Richtlinie |

## Beispiel eines ausgefüllten Eintrags

| Feld | Angabe |
|---|---|
| Bezeichnung der Verarbeitungstätigkeit | Kundenservice-Chatbot auf Basis eines Sprachmodells |
| Verantwortlicher | Mustermann GmbH, Musterstraße 1, 12345 Musterstadt; Datenschutzbeauftragte: siehe Impressum |
| Zweck der Verarbeitung | Automatisierte Beantwortung einfacher Kundenanfragen zu Bestellstatus, Versand und Rückgabe auf der Unternehmenswebsite |
| Kategorien betroffener Personen | Website-Besucher, Kunden |
| Kategorien personenbezogener Daten | Vorname, Bestellnummer, im Freitext eingegebene Anliegen (potenziell weitere Angaben, sofern vom Kunden freiwillig mitgeteilt) |
| Rechtsgrundlage (Art. 6 DSGVO) | Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung/vorvertragliche Maßnahme) für bestellbezogene Anfragen |
| Empfänger | [Anbieter des Sprachmodells], Auftragsverarbeitungsvertrag vom [Datum] |
| Drittlandübermittlung | Verarbeitung in Rechenzentren außerhalb des EWR; Übermittlung auf Grundlage von Standardvertragsklauseln gemäß Durchführungsbeschluss (EU) 2021/914, ergänzt um die im AVV des Anbieters vorgesehenen technischen Zusatzmaßnahmen |
| Nutzung für Modelltraining | Vertraglich ausgeschlossen im Rahmen des gebuchten Geschäftskundentarifs; Fundstelle: Nutzungsbedingungen des Anbieters, Abschnitt zur Datennutzung im Geschäftskundenbereich |
| Speicherdauer beim Anbieter | 30 Tage zur Missbrauchserkennung, danach Löschung laut Anbieterangabe |
| Löschfrist beim Verantwortlichen | Chatverläufe werden 90 Tage im Ticketsystem vorgehalten und anschließend automatisiert gelöscht |
| Technische und organisatorische Maßnahmen | Zugriff auf das Admin-Interface beschränkt auf den Kundenservice-Teamleiter; Übertragung ausschließlich über TLS; keine Speicherung von Zahlungsdaten im Chat |
| Verknüpfte Dokumente | AVV vom [Datum]; ausgefüllte Checkliste vom [Datum]; interne KI-Richtlinie Version [Nummer] |

Die vollständige Herleitung dieses Beispiels, einschließlich der Überlegungen zur Risikoeinstufung nach dem AI Act, findet sich in `fallbeispiel/kmu-chatbot-fallbeispiel.md`.
