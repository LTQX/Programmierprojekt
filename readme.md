Projekt-Dokumentation

✍️ Ihr Nachname; bei Gruppenarbeiten Ihr Gruppenname und Ihre Nachnamen

| Datum | Version | Zusammenfassung |
| --- | --- | --- |
|     | 0.0.1 | Projektdokumentation: Hypothekenrechner in C#<br/><br/>Projektübersicht:<br/>Das Ziel dieses Projekts war die Entwicklung eines Hypothekenrechners als Konsolenanwendung in C#. Das Team bestand aus Ylli, Amar und Alan.<br/><br/>Teammitglieder:<br/><br/>Amar (Implementierung):<br/>Erklärte die Funktionalität des Hypothekenrechners.<br/>Implementierte die Hypothekenberechnungslogik (Darlehensbetrag, Laufzeit, Zinssatz) in C#.<br/>Alan (Planung und Koordination):<br/>Koordinierte den Ablauf des Projekts.<br/>Entscheid über die Aufgabenverteilung und wer welchen Teil des Codes umsetzt.<br/>Ylli (Kommunikation und Dokumentation):<br/>Stellte Fragen an die Lehrer für Klärungen und Unterstützung.<br/>Sandte die erstellten Dokumentationen als Markdown-Text an Herrn Fähndrich.<br/>Projektphasen:<br/><br/>Anforderungsanalyse:<br/>Amar erklärte Funktionalitäten des Hypothekenrechners.<br/>Identifizierte notwendige Eingabeparameter.<br/>Design:<br/>Amar entwarf Struktur der Hypothekenberechnungslogik.<br/>Alan plante Schnittstellen und Aufgabenverteilung im Code.<br/>Implementierung:<br/>Amar setzte Hypothekenberechnungslogik um.<br/>Alan integrierte implementierte Teile.<br/>Integration und Test:<br/>Gemeinsame Tests, um korrekte Funktionalität sicherzustellen.<br/>Dokumentation:<br/>Ylli stellte sicher, dass Fragen für Klärungen gestellt wurden.<br/>Ylli sandte Dokumentation als Markdown-Text an Herrn Fähndrich.<br/>Herausforderungen:<br/><br/>Ylli nutzte einen Mac, führte zu Problemen bei Codeöffnung und GUI.<br/>GUI-Funktionalität nicht reibungslos auf Yllis System ausführbar.<br/>Live-Sharing nicht vollständig nutzbar, Ylli konnte daher weniger zum Projekt beitragen.<br/>Lessons Learned:<br/><br/>Klare Kommunikation und Aufgabenverteilung sind entscheidend.<br/>Technische Hindernisse sollten frühzeitig angesprochen und gelöst werden.<br/>Ausblick:<br/>Der Hypothekenrechner in C# ist erfolgreich implementiert. Zukünftige Entwicklungen könnten Feedback der Lehrer berücksichtigen und mögliche Erweiterungen umfassen.<br/><br/>Abschließende Bemerkungen:<br/>Das Team hat erfolgreich zusammengearbeitet, trotz technischer Herausforderungen. Die Dokumentation bietet einen umfassenden Überblick und wurde an Herrn Fähndrich gesendet. |
|     | ... |     |
|     | 1.0.0 |     |

## 1 Informieren

### 1.1 Ihr Projekt

✍️ Beschreiben Sie Ihr Projekt in einem griffigen Satz.

Bei unserem Projekt machen wir ein Konsolenprogramm, das Hypotheken berechnet. Der Benutzer wird aufgefordert, den Immobilienwert, jährliches Haushaltseinkommen, Zinssatz und eigene Mittel einzugeben. Das Programm gibt dann aus, ob der Benutzer die Hypothek tragen kann und gibt dabei auch die Nebenkosten für die Immobilie an.

### 1.2 Anforderungen

| №   | Verbindlichkeit | Typ | Beschreibung |
| --- | --- | --- | --- |
| 1   | Nutzereingabe | Funktionalität | Nutzer kann die Werte eingeben. |
| 2   | Korrekte Berechnung der Hypothek | Funktionalität | Das Programm berechnet die nötigen Daten aus den Werten, die das Programm von der Nutzereingabe erhalten hat. |
| 3   | Programm funktioniert auch bei Ausnahmen | Funktionalität | Das Programm stürzt nicht ab, wenn der Nutzer anstatt Zahlen Buchstaben oder Sonderzeichen verwendet |
| 4   | Design & Layout | Qualität | Das Programm sieht gut und benutzerfreundlich aus. |
| 5   | Programm funktioniert schnell und unkompliziert | Qualität | Das Programm ist effizient geschrieben und die einzelnen Schritte brauchen nicht lange. |

### 1.3 Testfälle

| TC-№ | Vorbereitung (*given*) | Eingabe (*when*) | Erwartete Ausgabe (*then*) |
| --- | --- | --- | --- |
| 1.1 | Programm fragt nach Einkommen | Einkommen zu niedrig | Einkommen ist zu niedrig und kann die Hypothek nicht tragen. |
| 1.2 | Programm fragt nach Einkommen, Immobilienwert oder eigene Mittel | Buchstaben anstatt Zahlen | Bitte geben Sie Zahlen ein |
| 1.3 |     |     |     |
| 1.4 |     |     |     |

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung |
| --- | --- | --- | --- |
| 1.A | 30.10.2023 | Ylli | Fragen an Frau Klink stellen und ein Termin vereinbaren. |
| 1.B | 30.10.2023 | Amar | Programmablaufsplan |
| 1.C | 02.11.2023 | Amar,Alan,Ylli | Programm zu Hypotheken erstellen. Code sollte einfach sein und die Grundlagen zur Berechnung beherschen. |
| 2.A | 6.11.2023 | Alan (Amar ist krank) | Exceptions im Code schreiben, damit dass Programm bei eingegebenen Buchstaben nicht abstürzt. |
| 2.B | 6/10.11.2023 | Ylli | Code optimieren, refactoring wo, nötig ist. |
| 3.A | 13.11.2023 | Amar | Optimierung vom Code |
| 3.B | 13.11.2023 | Alan | Exceptions im Code abschliessen und der Gruppe vorstellen |
| 3.C | 13.11.2023 | Alan/Amar/Ylli | Code im GUI übertragen |
| 3.D | 13.11.2023 | Ylli | Windows Form auf MacOS zum laufen bringen (Youtbe Tutorial) |
| 4.A | 20.11.2023 | Amar, Alan | Code zu GUI übertragen und anpassen |
| 4.B | 20.11.2023 | Ylli | Unterstützung beim Codieren und über Prallels interessieren |
| 5.A | 27.11.2023 | Amar, Alan, Ylli | Überlegen wie man die Amortisation berechnet und im Code umsetzten kann |
| 5.B | 27.11.2023 | Amar, Alan, Ylli | Amortisation im Code abschliessen |

✍️ Total: bspw. 26 Arbeitspakete

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | tatsächliche Zeit |
| --- | --- | --- |
| 1.A |     |     |
| ... |     |     |

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| --- | --- | --- | --- |
| 1.1 |     |     |     |
| ... |     |     |     |
