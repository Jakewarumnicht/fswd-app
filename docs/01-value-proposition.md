[← Documentation Home](README.md)

# Value Proposition

### Demand Side: Unternehmen

- Unternehmen und Arbeitgeber auf der Suche nach passenden Studierenden für Werkstudentenstellen.

- **Problem:**
- **Schwierige Ansprache der Zielgruppe:** Unternehmen müssen Studierende erreichen, die gezielt nach einer Werkstudententätigkeit in ihrem Fachgebiet suchen. Ohne Filter nach Fachgebiet erreichen sie viele Studierende, die fachlich nicht passen.
 
- **Begrenzte Reichweite der eigenen Website:** Studierende suchen häufig auf Jobbörsen und kommen nicht von sich aus auf die Karriere-Seite eines Unternehmens. Passende Studierende erfahren so nicht, dass es dort eine Werkstudentenstelle gibt.
  
- **Hoher Recruiting-Aufwand:** Die Organisation und Koordination von Bewerbungsprozessen kostet Zeit. Jeder zusätzliche Weg, Studierende zu erreichen, bedeutet zusätzlichen Aufwand für die Personalabteilung.
    
### Supply Side: Studierende

- Studierende auf der Suche nach einem Werkstudentenjob, der zum Studium passt. Sie möchten 
Praxiserfahrung im eigenen Fachbereich sammeln und bringen theoretische Grundlagen sowie Skills mit.

- **Problem:**
- **Mangel an spezialisierten Plattformen:** Es gibt kaum Jobportale, die ausschließlich auf Werkstudentenstellen ausgerichtet sind.
Angebote gehen meist auf allgemeinen Plattformen unter. 

- **Geringe Sichtbarkeit potenzieller Arbeitgeber:** Unternehmen veröffentlichen Stellen oft auf der eigenen Website, und nicht jede davon erscheint auf den großen Jobportalen oder Suchmaschinen. Studierende, die dort suchen, sehen deshalb nicht alle Werkstudentenstellen, auch nicht die von kleineren und mittleren Unternehmen, welche sie vielleicht noch nicht kennen.

- **Fehlende Erfassung akademischer Leistungen:** Aktuelle Portale bieten keine Möglichkeit, absolvierte Hochschulkurse, Noten, Universitätsprojekte oder Zertifikate strukturiert im Profil zu hinterlegen.

## Our Plattform Solution

Unsere Plattform verbindet Studierende und Unternehmen über ein schlagwortbasiertes Matching-System. Es gibt eine feste Liste von Schlagwörtern (z. B. Java, Python, SQL, Marketing), die zu den Studiengängen passen. Studierende wählen im Profil die Schlagwörter aus, die zu ihren Themen, Skills, Kursen und Projekten passen. Über eine API holt die Plattform automatisch die Informationen zum Unternehmen und zu seinen Werkstudentenstellen von der Unternehmenswebsite und zeigt sie bei uns an. Aus diesen Infos ermittelt die Plattform automatisch, welche Schlagwörter aus der Liste zum Unternehmen passen. Der Match-Score ist der Anteil der Schlagwörter des Unternehmens, die auch der/die Studierende gewählt hat. Studierenden werden passende Unternehmen und deren aktuelle Werkstudentenstellen vorgeschlagen. Eine direkte Verlinkung führt zur Stelle auf der Website des Unternehmens, sodass der Bewerbungsprozess unkompliziert gestartet werden kann. Gibt es bei einem Unternehmen gerade keine Werkstudentenstelle, zeigt das Profil nur die Informationen zum Unternehmen und was es macht. 

### Solution for the Demand Side (Unternehmen)

- **Kein zusätzlicher Aufwand:** Das Unternehmen legt kein Konto an und pflegt nichts. Seine Informationen und Werkstudentenstellen werden automatisch von der eigenen Website übernommen und für Studierende sichtbar gemacht. Die Bewerbung läuft weiter über den bestehenden Kanal des Unternehmens.
  
- **Sichtbarkeit bei passenden Studierenden:** Unternehmen erscheinen bei Studierenden, die gezielt nach einer Werkstudentenstelle in ihrem Fachbereich suchen. Auch Stellen, die nur auf der eigenen Website stehen, werden so angezeigt, und die Studierenden gelangen mit einem Klick direkt zur Stelle.

- **Bessere Passung der Interessenten:** Studierende wählen ihre Schlagwörter aus und sehen anhand des Match-Scores, wie gut sie zum Unternehmen passen. So melden sich eher Studierende, die fachlich zu den Stellen passen.


### Solution for the Supply Side (Studierende)

- **Gezielte Erfassung akademischer Leistungen & Skills:** Über eine standardisierte Liste fachbezogener Schlagwörter hinterlegen Studierende ihre absolvierten Hochschulkurse, Noten, Universitätsprojekte und Zertifikate strukturiert im Profil, ohne dass theoretische Vorkenntnisse im Lebenslauf untergehen.

- **Transparenter Match-Score zu (unbekannten) Unternehmen:** Ein sichtbarer prozentualer Match-Score zeigt sofort, wie gut das eigene Skill-Profil zu einem Unternehmen und dessen Tech-Stack passt. Dadurch entdecken Studierende auch kleinere und mittlere Betriebe, die ihnen bei der normalen Recherche verborgen geblieben wären.

- **Direktzugriff auf passende Werkstudentenstellen:** Hat ein passendes Unternehmen aktuelle Werkstudentenstellen ausgeschrieben, werden diese direkt angezeigt. Ein Klick führt ohne Umwege zur Original-Ausschreibung auf der Unternehmenswebsite, wodurch das zeitraubende manuelle Durchsuchen einzelner Karriereseiten entfällt.

## Happy Paths

Die Interaktion zwischen Studierenden und Unternehmen erfolgt auf folgenden Wegen:

- **Von Studierenden zu Unternehmen:** Studierende entdecken auf Basis ihres Match-Scores passende (auch bisher unbekannte) Unternehmen und werden mit einem Klick direkt zur Original-Ausschreibung auf der Karriereseite des Unternehmens weitergeleitet, um sich dort zu bewerben.

- **Von Unternehmen zu Studierenden:** Unternehmen sehen passende Studierende für ihre hinterlegten Werkstudentenstellen, sortiert nach Match-Prozent, und können geeignete Kandidatinnen und Kandidaten direkt über die Plattform zum Vorstellungsgespräch einladen.

### Demand-Side Happy Path (Unternehmen)

- **Unternehmensprofil aufrufen:** Das Unternehmen meldet sich mit seiner Firmen-E-Mail-Adresse an und erhält Zugriff auf sein Unternehmensprofil und die zugeordneten Werkstudentenstellen.

- **Automatisch erfasste Stellen & Schlagwörter einsehen**: Nach dem Login sieht das Unternehmen seine automatisch importierten Werkstudentenstellen inklusive der daraus erkannten Skill-Schlagwörter (z. B. Java, Python, SQL, 15 Std./Woche).   

- **Sortierte Kandidatenliste sichten**: Die Plattform gleicht die Stellen-Schlagwörter automatisch mit den Studierendenprofilen ab und zeigt eine nach Match-Prozent absteigend sortierte Kandidatenliste an; die besten Treffer stehen ganz oben. Bei Bedarf verfeinert das Unternehmen die Liste über Filter (Studiengang, Semester, Skills, Stunden/Woche, Verfügbarkeit).   

- **Qualifikationen & Projekte prüfen**: Das Unternehmen öffnet die Detailansicht vielversprechender Kandidaten und prüft deren hinterlegte Skills, absolvierte Hochschulkurse, Noten sowie praktische Studienprojekte.   

- **Direkte Kontaktaufnahme**: Das Unternehmen wählt im Einladungs-Formular die betreffende Stelle aus, fügt eine kurze Nachricht sowie einen Terminvorschlag hinzu und sendet die Gesprächseinladung direkt an das Dashboard des Studierenden.   


### Supply-Side Happy Path (Studierenden)

- **Registrierung & Profil anlegen:** Der/die Studierende registriert sich mit der Hochschul-E-Mail-Adresse, wählt Studiengang sowie aktuelles Fachsemester aus und hinterlegt im Profil fachliche Interessen, konkrete Skills (z. B. Java, Python, Fullstack), abgeschlossene Uni-Kurse und eigene Projekte.   

- **Empfohlene Unternehmen & Stellen entdecken:** Direkt nach dem Login zeigt das Dashboard automatisch empfohlene Werkstudentenstellen von passenden – teils noch unentdeckten – Unternehmen inklusive des jeweiligen Match-Prozentwerts (z. B. Match 92 %) sowie eingegangene Mitteilungen und Gesprächseinladungen von Arbeitgebern an.   

- **Gezielte Suche & Anforderungsabgleich:**  Über die Such- und Filterfunktion (nach Stelle/Skill, Studiengang, Semester, Stunden/Woche, Standort oder über die Checkbox „Nur Stellen, die zu meinem Profil passen“) grenzt der/die Studierende die aggregierten Ausschreibungen ein und sieht sofort anhand der Schlagwort-Tags und des Match-Scores, wie gut das eigene Profil zur Stelle passt.   

- **Weiterleitung zur Bewerbung oder Einladung annehmen:** Klickt der/die Studierende auf eine passende Stelle, erfolgt die direkte Weiterleitung zur Original-Ausschreibung auf der Karriereseite des Unternehmens, um die Bewerbung dort einzureichen. Alternativ öffnet der/die Studierende im Bereich Einladungen bzw. Mitteilungen eine erhaltene Gesprächseinladung eines Unternehmens und nimmt den vorgeschlagenen Interviewtermin direkt an.
---

## Initial Target Scope (as per Assignment)

[UI Design](assets/pdf/Uni2Work_UI.pdf)
