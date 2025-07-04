# bundesarchiv
In diesem Projekt soll das Bundesarchiv des Deutschen Pfadfinderbundes (DPB) neu entwickelt werden.

Hierbei soll als erstes definiert werden welche Funktionen das alte Archiv hat und anschließend festgestellt werden welche Technologie dafür am besten geeignet sind.

- [ ] Umfang Ermitteln
- [ ] Techstack festlegen

## Features

1. Einen Blog in welchem Posts von bestimmten Mitgliedern 
erstellt werden können.
2. Ein Online Katalog in welchem alle geuploadeten Inhalte des Archives durchsucht werden können
   
   1. **Suche:** Eine Volltextsuche, welche es ermöglicht Einträge über
   2. **Erweiterte Suche** für *Volltextsuche*, *Titel*, *Autor*, *Schlagwort*, *Medienart* und *Dokumenttyp*, wobei *Medienart* und *Dokumenttyp* verschiedene Auspräungen haben und nicht frei eingegeben können.
3. Eine Feedback Funktion, welches es Benutzer ermöglicht zu einem Gegenstand Feedback in Form von Kommentaren zu schreiben.

**Inhalte des Online Kataloges:**
|Feld|Inhalt|
   |----|------|
   | Titel | Titel des Gegenstandes|
   | Author | Verfasser oder Schaffer des Gegenstandes|
   | Medienart| Beschreibt das Medium des Gegenstandes. Beispiele hierfür können sein: [Fahne, Wimpel, Schrifttum]|
   | Dokumenttyp | Beschreibt um welche Art von Gegenstand es sich handelt. Beispiele hierfür können sein: [Chronik, Dokumentation, Zeitschrift]|
   | Hat Datei? | Boolean ob es eine beigefügte Datei gibt |
   | Jahr | Beschreibt aus welchem Jahr der Gegenstand stammt |
   | Signatur | Kürzel des Gegenstandes. Beispiele hierfür können sein: [BA 912, BA XXX] |

Wir brauchen ein Frontend für unsere Besucher und eines für unsere Archivare um Einträge zu erstellen/zu bearbeiten.

   **Was noch cool wäre:**

   Die Oberfläche für die Archivare sollte wenn es geht auch die Möglichkeit haben mehrere Einträge manuell zu bearbeiten, wenn z.B. das physische Archiv umgeräumt werden muss.

Als Techstack eventuell Sqlite, NextJs und Chakra für die Component Library. 
Am besten sollte die Anwendung aber Front und Backend in einem Beeinhalten, damit wir uns nicht um z.B. Netzwerk kümmern müssen. NextJs scheint Back- und Frontend aber mischbar zu machen.

**Strapi**

Strapri könnte als CMS verwendet werden. Ist nicht aufwendig in der Entwicklung, könnte aber unflexibel sein.
