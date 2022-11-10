# **Herangehensweise:**

Das Thema der Webseite ist nach Vorgabe „Games“ und als persönlicher Favourit dieser wurde Elden Ring zum erweiterten Themenbereich gewählt. Inhaltlich bietet sich ein Wiki an, wonach der geplante Seiteninhalt dem des bereits existenten Elden Ring Wikis nachempfunden ist: https://eldenring.wiki.fextralife.com/Elden+Ring+Wiki

Nach einer entsprechenden Recherche und Sammeln von Material wurde ein Konzept entworfen, das sowohl den Anforderungen, wie beispielsweise einem statischen Layout, als auch einem ähnlichen Aufbau nach Vorbild entspricht.Somit weicht das Layout an manchen Stellen vom Original ab. Für jede der drei geplanten Seiten wurde eine separate Skizze erstellt. Die Farben sind dunkel und grau gehalten, um sowohl die Stimmung des Spiels darzustellen, als auch schonend für die Augen zu wirken.

Die Art der unterschiedlichen Kästen, Felder und ihre Aufteilung ließen sich dabei bereits festlegen. Ebenso half dieser Vorgang dabei zu entscheiden, welche Art von Navigation und Footer genutzt werden sollte und wo eine Tabelle sinnvoll ist.
Die Navigation ist klassisch und simpel gehalten, da es kaum Menüpunkte gibt. Die Menüleiste ist am oberen Rand fixiert um auf beom Scrollen noch zugänglich zu sein.

Für die Implementierung wurden zu Beginn als Startseite[start](./../index.html) eine simple Grundseite mittels HTML und eine dazugehörige CSS geschrieben [main.css](./../assets/css/main.css). Hier wurde die grundlegende Struktur der Seite festgelegt, die sich durch alle Unterseiten zieht. Somit sind auch die hier festgelegten css-Klassen ider main.css definiert und in allen HTML- Unterseiten wieder verwendet.

Die Grundstruktur ist erstmal umschlossen von einem Wrapper mit der fixen Höhe von 920px und einer Breite von 1900px um ein statisches Layout zu gewährleiten. Er bekam als Hintergrund für die gesamte Seite das Titelbild des Spiels Elden Ring.
Im Inneren wird der _main_container_ aufgespannt, der mit einer fixen Breite von 1805px die Seite auf 95% der Seitenbreite begrenzt und für ein angenehmeres Leseerlebnis des Anwenders sorgt.

Die Grundstruktur ist nun in navbar, _content_container_ und footer eingeteilt und wiederholt sich auf allen Unterseiten. Das HTML der Navigation und des Footers sind in eigene HTML-Dateien ausgelagert und werden dynamisch via Jquery eingebunden unm Code Duplizierung zu vermeiden.

Anschließend ließ sich die Seite mit Inhalten wie ersten div-Boxen, Fließtextund Bildern füllen. Bei diesem Vorgang halfen die Dev-Tools sowie die Webseite von W3School um Code auszuprobieren und zu erweitern.
Letztlich sind kaum Kommentare im HTML-Quelltext, da die Klassen semantisch aufschlussreich benannt wurden.
