# Arbeitsauftrag

Ein örtlicher Verein wendet sich mit dem Auftrag an euer Team, eine neue Website zu erstellen.

Die bestehende Website des Vereins ist veraltet: Das Design ist nicht mehr modern, auf mobilen Geräten ist die Website kaum zu bedienen und die Ladezeit beträgt mehrere Sekunden.

## Konzeptvorlage

Verwende für die Planung Deines Projekts [diese Konzeptvorlage](https://github.com/IctBerufsbildungZentralschweiz/modul-101-projekt/raw/master/src/Projektarbeit_M101_Konzept_VORLAGE.docx).

## Ziel

Das Ziel dieser Projektarbeit ist es, bis nach dem Mittag von Tag 5 ein in HTML und CSS umgesetztes Layout zu haben, welches bereit für die Übernahme in ein CMS ist.

## Vorgaben

Folgenden Vorgaben gelten für das Projekt und werden mindestens erwartet.

### Umfang

* [ ] Die Website enthält eine sinnvolle Planung.
* [ ] Die Website besteht aus mindestens `4 Seiten`.
* [ ] Im Layout der Website gibt es mindestens einen `Header`, einen `Footer`, eine `Sidebar`, eine `Navigation`, einen `Content-Bereich` und einen Platz für die `Kontaktinformationen` des Vereins, die auf jeder Seite gut sichtbar sind.
* [ ] Die Startseite soll den Besucher mit einem separaten Layout mit Bildern und grossen Slogans emotional abholen. Die Folgeseiten sollen primär informieren und daher ein strafferes Layout haben.
* [ ] Da weitere Seiten zu einem späteren Zeitpunkt noch ergänzt werden, soll die Navigation erweiterbar mit 
CSS-Flexbox gestaltet werden.
* [ ] Der Kunde besteht darauf, dass eine Schriftart auf der Website verwendet wird, die nicht jeder Besucher bereits von seinem Computer kennt.
* [ ] Die Website enthält Beispiel-Inhalte.
* [ ] Es muss kein JavaScript verwendet werden.

### Formular

* [ ] Die Website beinhaltet mindestens `1 Formular` mit mindestens `4 Feldern`.
* [ ] Im Formular gibt es mindestens ein `select` und ein `radio/checkbox` Feld.
* [ ] Das Formular wird clientseitig validiert.
* [ ] Die Daten des Formulars werden an [https://formlog.offline.ch/log](https://formlog.offline.ch/log) gesendet. Anschauen kannst du die gesendeten Daten auf [https://formlog.offline.ch/](https://formlog.offline.ch/).

### Qualität 

* [ ] Die Website ist responsive.
* [ ] Die Website ist performant.
* [ ] Der Code der Website wurde `zu 100% selber umgesetzt`.
* [ ] Der Code der Website ist übersichtlich formatiert.
* [ ] Der Code der Website ist valide.
* [ ] HTML und CSS sind korrekt separiert. Es gibt kein redundanter CSS-Code (eine zentrale CSS-Datei für alle Seiten).
* [ ] Die verwendeten Bilder sind für die Nutzung im Web zugelassen.

## Arbeitsweise

* Ihr arbeitet in max. `2er-Teams`.
* Bis Tag 5 können die Pausen frei eingeteilt werden. Haltet euch dabei an die Mindestdauer. Mittagspause sowie Start- und Ende des Arbeitstages sind fix und für alle gleich.
* Mit der VS Code Extension "Live Share" kann die Zusammenarbeit via gemeinsamem Code vereinfacht werden.
* Die Extension "Live Server" erlaubt gemeinsames Testing: Rechtsklick auf eine HTML-Datei und "Open with Live Server". Die URL zum Testen wird automatisch mit dem Kollaborateur geteilt. Er kann ie URL dann im Webbrowser öffnen. 
**Hinweis**: Wenn's zickt, VS Code neu starten! 

### Empfohlenes Vorgehen & Zusammenarbeit zu zweit

1. Erstellt zuerst zusammen ein HTML-Grundgerüst (html, head, body) mit allen Containern (Header, Navigation, Content, Sidebar, Footer etc.) und speichert sie z.B. als `vorlage.html`.

2. Erstellt dazu ein CSS mit einem Grid und bindet es ein. 

3. Für alle Webseiten könnt ihr dann eine Kopie vom Grundgerüst erstellen. Achtung: Änderungen am Grundgerüst müssen von Hand in die Kopien übertragen werden.

4. Für die Zusammenarbeit könnt ihr nun entweder 
   * Die Extention `Live Share` installieren und am gleichen Code zusammenarbeiten. Nachteil: Nur eine Person hat den Code und kann die Vorschau ansehen. Sie kann den Code ab & zu auf den Webserver laden (FTP), dann können es beide sehen. Oder: 
   * Ein 2. temporäres CSS (dein-name-temp.css) erstellen und im HTML-Grundgerüst verlinken (dann habt ihr 2. CSS eingebunden). Im zweiten CSS kann die 2. Person frei neuen Code rein schreiben. Dann ab & zu zusammenkopieren. 
   - Vorschau: Auf FTP-Server hochladen und im Browser aktualisieren.

## Etappen

### Konzept (bis Ende Tag 3)

Bis am Abend von Tag 3 muss von jedem Team ein Konzept für die umzusetzende Website erstellt werden. Das Konzept beinhaltet folgende Punkte:

* Projektbeschrieb (max. 500 Zeichen)
* Wettbewerbsanalyse (max. 500 Zeichen)
* Zielsetzung (circa 2 bis 3 Ziele)
* Zielgruppe (min. 1 Persona)
* Projektplanung
* Wireframes (mindestens je ein Wireframe für die Startseite und die Folgeseiten)
* Styleguide (geplante Farben, Schriften und Bildarten)
* Sitemap
* Checkliste für das Testing am Ende des Projekts (min. 6 Testfälle)

Das Konzept ist digital im Moodle abzugeben.

### Umsetzung (bis Nachmittag Tag 5)

Ihr arbeitet im Team an der Umsetzung des Projekts.

## Testing und Projektabschluss (Nachmittag Tag 5)

Das fertige Projekt wird gemäss eurer Planung getestet und die Ergebnisse in eurem Testprotokoll eingetragen. Das 
laufend aktualisierte Konzept wird im Moodle abgegeben.

Das Projekt muss **auf dem Webserver der ICT-BZ** veröffentlicht werden.

Der Datenbestand, der bis zum Abgabetermin auf dem Server ist, wird für die Bewertung verwendet.

Der genaue Abgabetermin wird vom Kursleiter bestimmt.
