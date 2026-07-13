# Tägliche Mobility-Routine

Eine kleine Web-App, die dich durch 5 tägliche Mobility-Übungen führt – mit Timer, Animationen und deutscher Sprachausgabe. Alles steckt in einer einzigen `index.html`, ohne Abhängigkeiten, und läuft offline im Browser oder als App vom iPhone-Home-Bildschirm.

## Übungen

1. **Ischias Nerv stretch** – Oberschenkelrückseite / Ischias (pro Bein)
2. **Tiefe Kniebeuge** – Hüfte / Sprunggelenke (mehrere Durchgänge)
3. **Couch Stretch** – Hüftbeuger / unterer Rücken (pro Seite)
4. **Schulterkreisen mit Stab** – Nacken / Schultern / Brust
5. **Kosaken-Squat** – innere Oberschenkel / Adduktoren (Wiederholungen)

## Features

- Geführter Ablauf: „Übung x von 5", schematische Animation und kurze Anleitung je Übung
- Vorbereitungs-Countdown „3 – 2 – 1 – Los!" als Vollbild-Animation mit Ton und Stimme
- Kreis-Fortschrittsring als Timer mit Countdown der empfohlenen Dauer
- Automatischer Seitenwechsel bzw. mehrere Durchgänge, plus automatisches Weiterspringen zur nächsten Übung
- Deutsche Sprachausgabe (Übungsname, beim ersten Mal die Anleitung, Start-/Ende-Ansagen) – abschaltbar über 🔊
- Hält das Display wach, solange die App geöffnet ist (Screen Wake Lock, ab iOS 16.4)

## Auf dem iPhone einrichten

1. Diese `index.html` in ein **öffentliches** GitHub-Repository hochladen.
2. Im Repo unter **Settings → Pages** die Quelle auf **Deploy from a branch**, Branch `main`, Ordner `/(root)` stellen und speichern.
3. Nach ~1 Minute steht deine Adresse bereit: `https://DEIN-BENUTZERNAME.github.io/DEIN-REPO/`
4. Diese URL in **Safari** öffnen (kurz warten bzw. neu laden, falls anfangs 404).
5. Auf das **Teilen-Symbol** tippen → **„Zum Home-Bildschirm"**. Fertig – die App startet nun mit eigenem Icon im Vollbild.

Hinweise: Ton, Sprachausgabe und der Wake Lock funktionieren nur in echtem Safari (bzw. der vom Home-Bildschirm gestarteten App), nicht in der Datei-Vorschau. Achte darauf, dass der Lautlos-Schalter des iPhones aus ist.

## Lokal ausprobieren

Einfach die `index.html` in einem Browser öffnen. Für die vollständige Funktion (Wake Lock) sollte die Seite über `https` bzw. `localhost` ausgeliefert werden.

## Credits

Übungen und Anleitungen basieren auf dem Video [„5 Mobility-Übungen, die 95 % deiner Probleme lösen"](https://youtu.be/mDvdnl7UyZs) von **Medeasway**. 🙏

## Haftungsausschluss

Diese App dient nur zu Informations- und Fitnesszwecken und ersetzt keine medizinische Beratung. Höre auf deinen Körper und brich bei Schmerzen ab.

## Lizenz

Veröffentlicht unter der [MIT-Lizenz](LICENSE).
