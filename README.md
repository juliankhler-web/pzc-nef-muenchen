# PZC NEF München

Eingabehilfe für NEF-Fahrer: PZC-Code finden (Geschlecht · Code / Alter / Dringlichkeit), SK-1-Anmeldung Schritt für Schritt, Notizen und Archiv mit Datum/Uhrzeit.

- Reine HTML-App, keine Server, keine Abhängigkeiten
- Dunkelmodus (Auto/Dunkel/Hell), Wischen für Zurück/Vor, Start-Button
- Offline-fähig (PWA), Archiv liegt nur lokal im Browser des Geräts
- Keine Patientennamen speichern

## Veröffentlichen mit GitHub Pages
1. Neues Repository auf GitHub anlegen, alle Dateien dieses Ordners hochladen
2. Settings → Pages → Branch `main`, Ordner `/ (root)` → Save
3. Adresse: `https://<benutzername>.github.io/<repo>/`
4. Am Handy öffnen → Teilen → „Zum Home-Bildschirm"

## Nach Änderungen
In `sw.js` die Versionsnummer (`pzc-v1`) erhöhen, damit Geräte die neue Version laden.

## Datenquelle
Codeliste und mögliche Behandlungsdringlichkeiten (BD1/BD2/BD3) stammen aus der offiziellen IVENA-Bayern-PZC-Liste
(https://bayern.ivena-web.de/pzc.php), abgerufen am 03.10.2026 (190 Codes). Bei Abweichungen gilt die IVENA-App.
Die Such-Begriffe (Alltagswörter, Körperteile, Fachrichtungen) sind eine eigene Zuordnung und bitte im Alltag prüfen.

## Offen / prüfen
- Krankenhausliste fehlt bewusst (keine verifizierte Quelle)
- Foto-Auslesen (Karte/Ausweis) ist mit echten Karten noch zu testen
