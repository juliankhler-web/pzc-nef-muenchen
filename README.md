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

## Offen / prüfen
- Dringlichkeits-Felder pro Code sind vom Foto der Tafel abgelesen → gegen das Original prüfen
- Krankenhausliste fehlt bewusst (keine verifizierte Quelle)
