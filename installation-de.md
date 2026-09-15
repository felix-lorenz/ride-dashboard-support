# Installation und Einrichtung — Deutsch

[English](installation-en.md) | [Deutsch](installation-de.md) | [Startseite](README-de.md)

## Installieren

1. Ride Dashboard im Garmin Connect IQ Store kaufen.
2. Die App auf dem Edge 1040 oder Edge 1040 Solar installieren und das Gerät synchronisieren.
3. Am Edge das Aktivitätsprofil öffnen, in dem das Datenfeld erscheinen soll.
4. Die Datenseiten bearbeiten und ein breites oder halbbreites Feld auswählen.
5. Die Connect-IQ-Datenfelder öffnen und `Ride Dashboard` auswählen.

Die Bezeichnungen der Garmin-Menüs können sich je nach Firmware und
Gerätesprache leicht unterscheiden.

## Konfigurieren

Am Edge die Connect-IQ-Einstellungen von Ride Dashboard öffnen. Die Übersicht
zeigt Beispielwerte und keine Live-Daten. Eine Beispielkachel antippen, um den
Wert zu ändern, die maximale Kachelzahl festlegen, die Vorlage Allgemein,
Leistung oder Klettern laden oder die Anzeigeeinstellungen öffnen.

Werte und Einheiten werden innerhalb jeder Kachel gemeinsam vertikal
zentriert; die Einheit `kcal` erscheint als `kc` über `al`. Die Wertgröße passt
sich immer automatisch an. Zonen für aktuelle Herzfrequenz und Leistung werden
bei aktivierter Zonenfarbe ausschließlich durch die Hintergrundfarbe
dargestellt.

Die optionale Zusatzleiste kann den Routenfortschritt, die aktuelle
Herzfrequenz- oder Leistungszone oder die Verteilung der HF-Zonenzeit in der
aktuellen Runde anzeigen. Ihre Position lässt sich auf Oben oder Unten setzen.
Fehlen die benötigten Daten, wird die gewählte Zusatzleiste ausgeblendet und
der Platz steht wieder den Kacheln zur Verfügung.

Ride Dashboard ist eine App mit einer gemeinsamen Konfiguration. Eine zweite
Platzierung erzeugt keine unabhängigen Einstellungen. Alle Platzierungen nutzen
dieselbe Kachelreihenfolge, maximale Kachelzahl und Anzeige. Kleine Datenfelder
können die letzten Kacheln ausblenden, damit die sichtbaren Werte lesbar bleiben.

## Benötigte Daten

- Für Ziel-, Abbiege-, Kursabweichungs- und Ankunftswerte eine Route starten.
- Für W/kg, FTP-Prozent und Herzfrequenzzonen das Fahrerprofil einrichten.
- Für Herzfrequenz, Trittfrequenz und Leistung kompatible Sensoren koppeln.
- Für Gangwerte eine kompatible elektronische Schaltung koppeln.
- Für Solarintensität einen Edge 1040 Solar verwenden.

`-` bedeutet, dass der ausgewählte Wert aktuell nicht verfügbar ist. Die im
Untertitel genannte Route, das Profil, die Sensor- oder Schaltungsverbindung
beziehungsweise das Gerätemodell prüfen.

Betroffene Herzfrequenz-, Kadenz-, Leistungs- und Schaltungskacheln können bei
fehlender überwachter Quelle abwechselnd rot und normal erscheinen. Hat die
Quelle in der aktuellen Sitzung noch keine Daten geliefert, beginnt die
Warnung sofort; nach dem ersten Empfang beginnt sie nach fünf Sekunden ohne
Daten. Ein gültiger Wert beendet die Warnung sofort. Liefert Garmin einen alten
unveränderten Wert weiter, kann Ride Dashboard ihn nicht von einem aktuellen,
gleichbleibenden Wert unterscheiden.

Ride Dashboard übernimmt die Gerätesprache, wenn sie zu den 14 unterstützten
Sprachen gehört. Andernfalls verwendet die App Englisch.
