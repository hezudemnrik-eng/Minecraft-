# Blueprint – Bauprojekt-Planer für deinen Minecraft-Server

Blueprint ist eine Todo-App für Bauprojekte. Sie besteht aus **einer einzigen Datei** (`blueprint.html`), läuft komplett **offline** und braucht weder Server noch Konto oder Installation.

## Starten

1. `blueprint.html` an einen festen Ort legen, z. B. `Dokumente\Blueprint\blueprint.html`.
2. Doppelklick auf die Datei. Sie öffnet sich in deinem Browser (Opera / Opera GX).
3. Tipp: Ein Lesezeichen anlegen, dann ist die App immer einen Klick entfernt.

> **Wichtig:** Lass die Datei immer am selben Ort und öffne sie immer im selben Browser. Die Daten gehören zu diesem Browser auf diesem PC.

### Oder online über GitHub Pages

Blueprint ist auch unter **https://hezudemnrik-eng.github.io/Minecraft-/** erreichbar, auf dem PC und am Handy.

- Auch online bleiben deine Daten **nur im jeweiligen Browser auf dem jeweiligen Gerät**. Niemand sonst sieht sie, auch nicht über die Adresse.
- Die Online-Version und die heruntergeladene Datei haben **getrennte Daten**. Zum Umziehen: in der einen Version unter Einstellungen „Als Datei herunterladen“ wählen, in der anderen „Backup-Datei wählen…“.
- Am Handy gibt es keinen Backup-Ordner. Dort lädt Blueprint das Backup als Datei herunter.

## Erstes Backup einrichten (einmalig, ca. 1 Minute)

1. In Blueprint unten links auf **Einstellungen** klicken.
2. **Backup-Ordner wählen** und einen Ordner aussuchen, z. B. `Dokumente\Blueprint-Backups`.
3. Dem Browser erlauben, dass Blueprint dort speichern darf.

Danach sichert Blueprint **beim ersten Öffnen jedes Tages automatisch** eine Datei `blueprint-backup-JJJJ-MM-TT.json` in diesen Ordner. Die letzten **7** Backups bleiben erhalten, ältere werden gelöscht. Andere Dateien im Ordner werden nicht angefasst.

Manchmal fragt der Browser beim Start erneut nach der Erlaubnis. Dann erscheint oben ein Hinweis, und ein Klick auf **Backup speichern** reicht.

Unten links in der Seitenleiste steht, wann das letzte Backup war.

## Rezepte & Grundmaterialien

Unter **„Rezepte“** trägst du ein, woraus etwas hergestellt wird, zum Beispiel:

| Ergebnis | Menge | Zutaten | Station |
|---|---|---|---|
| Steinziegeltreppe | 4 | 6× Steinziegel | Werkbank |
| Steinziegel | 4 | 4× Stein | Werkbank |
| Stein | 1 | 1× Bruchstein | Ofen |

Steht dann in einer Materialliste „10 Steinziegeltreppe“, rechnet Blueprint über alle Stufen bis zum Rohstoff: **20 Bruchstein**. Dazu kommt ein Bauplan mit allen Zwischenschritten.

- Zu sehen in der **aufgeklappten Aufgabe**, im **Projekt-Gesamtbedarf** und in der **Übersicht** (Umschalter „Grundmaterialien“), außerdem im **Rechner** im Rezeptbuch.
- **Gesamt** rechnet mit „Benötigt“, **Fehlt noch** mit „Benötigt − Gesammelt“.
- Gerechnet wird in ganzen Herstellungen (10 Treppen → 3× herstellen = 12, 2 übrig). Gleiche Zwischenprodukte werden vorher zusammengezählt.
- Alles ohne Rezept zählt als Grundmaterial. Pro Ergebnis gibt es ein Rezept.

## Stück oder Stacks

Unten in der Seitenleiste (und bei den Materialien) schaltest du **„Mengen: Stück | Stacks“** um. Die Einstellung gilt überall und bleibt gespeichert.

- Im Stack-Modus steht z. B. **„20 Stacks + 20“** statt 1.300, „1 Stack“ statt 64. Unter einem Stack bleibt die Zahl, z. B. „20“. Beim Darüberfahren siehst du die Stückzahl.
- Eingegeben wird dann mit zwei Feldern: **Stacks + Rest**. Gespeichert wird immer die Stückzahl, du kannst also jederzeit umschalten.
- Die **Stapelgröße** erkennt Blueprint am Namen: normal 64, **16** z. B. für Eimer, Schilder, Banner, Eier, Schneebälle, Enderperlen, Rüstungsständer („2 Stacks à 16 + 8“), **1** für Werkzeuge, Rüstung, Betten, Boote, Loren, Tränke, gefüllte Eimer, Shulker-Kisten usw.
- Die Kennzahl in der Übersicht zeigt dann „N Stacks fehlen“, also wie viele Inventarplätze noch fehlen.

## Daten übertragen (z. B. Handy → Laptop)

Ohne Dateien, per Code zum Kopieren und Einfügen:

1. **Auf dem Handy:** In Blueprint auf **„Daten übertragen“** tippen → **„Teilen…“** und den Code an dich selbst schicken (E-Mail, WhatsApp, AirDrop) – oder **„Kopieren“** und in eine Notiz einfügen.
2. **Auf dem Laptop:** Blueprint öffnen → **„Daten übertragen“** → den Code ins Feld **„Importieren“** einfügen.
   Hast du stattdessen die **Backup-Datei (.json)**, z. B. über „Als Datei herunterladen“: dort auf **„Datei wählen…“** klicken oder die Datei am PC einfach in den Import-Bereich ziehen.
3. **„Importieren“** klicken. Ist der Laptop noch leer, werden die Daten nach einer Bestätigung übernommen. Hat er schon Daten, wählst du:
   - **Zusammenführen:** Neues kommt dazu, bei gleichen Einträgen gewinnt die zuletzt geänderte Version.
   - **Alles ersetzen:** Der Laptop übernimmt exakt den Stand vom Handy.

Gut zu wissen: Beim Zusammenführen tauchen Einträge wieder auf, die du nur auf dem Zielgerät endgültig gelöscht hast (Papierkorb geleert). Mit „Alles ersetzen“ passiert das nicht.

## Backup wiederherstellen

1. **Einstellungen** → **Backup-Datei wählen…**
2. Die gewünschte `blueprint-backup-….json` aus dem Backup-Ordner auswählen.
3. Bestätigen. Hat das Gerät schon Daten, wählst du „Zusammenführen“ oder „Alles ersetzen“.

So ziehst du auch auf einen neuen PC oder einen anderen Browser um: Datei kopieren, Backup laden, fertig.

## Was die App kann

- **Projekte** mit Pixel-Icon, Farbe, Status (Planung / Im Bau / Pausiert / Fertig), Koordinaten und Beschreibung (Markdown)
- **Kanban-Board** pro Projekt: Offen → In Arbeit → Fertig, Karten per Drag & Drop verschieben und sortieren
- **Aufgaben** mit Priorität (Niedrig / Mittel / Hoch / Dringend), Zuständigem, Koordinaten, Checkliste, Materialliste, Tags und Bild-Links
- **Koordinaten** als Punkt oder Bereich (Ecke A/B) in Overworld, Nether oder End. Ein Klick kopiert die Zahlen, die Umrechnung zwischen Overworld und Nether wird automatisch angezeigt.
- **Material** pro Aufgabe und pro Projekt. Die Projekt-Summe fasst gleiche Namen zusammen, Fortschrittsbalken zeigen, was noch fehlt.
- **Übersicht** für den PC: Kennzahlen, alle Projekte als Tabelle mit Aufgaben-Stand und ihren **Materialien (gesammelt / benötigt)**, dazu „In Arbeit“ und fehlendes Material über alle Projekte
- **Filter** nach Priorität, Dimension und Zuständigem
- **Projektansicht** mit immer sichtbarem Material-Bereich (Projekt-Material + Gesamtbedarf), Beschreibung einklappbar
- **Mengen in Stück oder Stacks** per Umschalter, auch bei der Eingabe
- **Rezepte** mit Rechner: Materiallisten werden über alle Stufen in Grundmaterialien umgerechnet
- **Daten übertragen** zwischen Geräten per Code (Kopieren/Teilen → Einfügen), wahlweise zusammenführen oder ersetzen
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
