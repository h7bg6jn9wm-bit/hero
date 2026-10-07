# SHK Theorie Trainer – V5 Fix

Drei Hauptbereiche:
1. Prüfungsmodus
2. Fragebögen zum Lernen
3. Diagnose

Die Diagnose ist jetzt Bestandteil derselben App-Struktur. Die Diagnose besitzt keinen eigenen Manifest-/Service-Worker mehr und kann dadurch nicht mehr versehentlich als Startseite der installierten App geöffnet werden. Der Zurück-Button führt zuverlässig zum Hauptmenü.

Für iPhone: Root-`index.html` über GitHub Pages öffnen und über Safari „Zum Home-Bildschirm“ hinzufügen.


V6 Fehlerbehebung: Diagnose liegt direkt als diagnose.html im Hauptverzeichnis. Prüfung und Ergebnis besitzen eine Hauptmenü-Taste. Der Diagnose-Simulator registriert keinen eigenen Service Worker.


V7: Hauptmenü auf Mobilgeräten zentriert; Bauteilbeschriftungen im Diagnose-Simulator kontrastreicher und besser lesbar gestaltet.
