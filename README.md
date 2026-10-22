# Blueprint – Bauprojekt-Planer für deinen Minecraft-Server

Blueprint ist eine Todo-App für Bauprojekte. Sie besteht aus **einer einzigen Datei** (`blueprint.html`), läuft komplett **offline** und braucht weder Server noch Konto oder Installation.

## Starten

1. `blueprint.html` an einen festen Ort legen, z. B. `Dokumente\Blueprint\blueprint.html`.
2. Doppelklick auf die Datei. Sie öffnet sich in deinem Browser (Opera / Opera GX).
3. Tipp: Ein Lesezeichen anlegen, dann ist die App immer einen Klick entfernt.

> **Wichtig:** Lass die Datei immer am selben Ort und öffne sie immer im selben Browser. Die Daten gehören zu diesem Browser auf diesem PC.

## Erstes Backup einrichten (einmalig, ca. 1 Minute)

1. In Blueprint unten links auf **Einstellungen** klicken.
2. **Backup-Ordner wählen** und einen Ordner aussuchen, z. B. `Dokumente\Blueprint-Backups`.
3. Dem Browser erlauben, dass Blueprint dort speichern darf.

Danach sichert Blueprint **beim ersten Öffnen jedes Tages automatisch** eine Datei `blueprint-backup-JJJJ-MM-TT.json` in diesen Ordner. Die letzten **7** Backups bleiben erhalten, ältere werden gelöscht. Andere Dateien im Ordner werden nicht angefasst.

Manchmal fragt der Browser beim Start erneut nach der Erlaubnis. Dann erscheint oben ein Hinweis, und ein Klick auf **Backup speichern** reicht.

Unten links in der Seitenleiste steht, wann das letzte Backup war.

## Backup wiederherstellen

1. **Einstellungen** → **Backup-Datei wählen…**
2. Die gewünschte `blueprint-backup-….json` aus dem Backup-Ordner auswählen.
3. Bestätigen. Alle aktuellen Daten werden durch das Backup ersetzt.

So ziehst du auch auf einen neuen PC oder einen anderen Browser um: Datei kopieren, Backup laden, fertig.

## Was die App kann

- **Projekte** mit Pixel-Icon, Farbe, Status (Planung / Im Bau / Pausiert / Fertig), Deadline, Koordinaten und Beschreibung (Markdown)
- **Kanban-Board** pro Projekt: Offen → In Arbeit → Fertig, Karten per Drag & Drop verschieben und sortieren
- **Aufgaben** mit Priorität (Niedrig / Mittel / Hoch / Dringend), Deadline, Zuständigem, Koordinaten, Checkliste, Materialliste, Tags und Bild-Links
- **Koordinaten** als Punkt oder Bereich (Ecke A/B) in Overworld, Nether oder End. Ein Klick kopiert die Zahlen, die Umrechnung zwischen Overworld und Nether wird automatisch angezeigt.
- **Material** pro Aufgabe und pro Projekt. Die Projekt-Summe fasst gleiche Namen zusammen, Fortschrittsbalken zeigen, was noch fehlt.
- **Dashboard** mit „Bald fällig & überfällig“, fehlendem Material über alle Projekte und dem Fortschritt jedes Projekts
- **Filter** nach Priorität, Dimension, Zuständigem und „nur überfällig“
- **Archiv** für fertige Projekte und erledigte Aufgaben, **Papierkorb** mit Wiederherstellen (leert sich nach 7 Tagen)
- **Akzentfarbe** wählbar: Gras-Grün, Diamant-Türkis, Redstone-Rot, Gold
- **Hilfe** direkt in der App über den Knopf „Hilfe“

## Gut zu wissen

- **Browserdaten löschen = Daten weg.** Wer in Opera „Browserdaten löschen“ mit „Cookies und andere Websitedaten“ ausführt, löscht auch Blueprint. Dann hilft nur noch das Backup.
- Die App lädt nichts aus dem Internet. Nur Vorschaubilder von Bild-Links, die du selbst einträgst, werden aus dem Netz geholt.
- Mehrere Tabs gleichzeitig sind möglich: Änderungen werden zwischen den Tabs übernommen.

## Lizenzen

- Überschriften-Schrift: **Silkscreen** von Jason Kottke, SIL Open Font License 1.1
- Pixel-Icons: selbst gezeichnet für Blueprint
