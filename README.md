# Kraftlog

Installierbare, statische HTTPS-Web-App für Krafttraining. Öffne die Site auf Android in Chrome und wähle im Browser-Menü „Zum Startbildschirm hinzufügen“ oder „App installieren“.

## Veröffentlichung über GitHub Pages

1. Lade alle Dateien in diesem Ordner in ein GitHub-Repository hoch.
2. Öffne im Repository **Settings → Pages**.
3. Wähle **Deploy from a branch**, Branch `main`, Ordner `/ (root)`, und speichere.
4. GitHub Pages stellt nach dem Build eine HTTPS-Adresse bereit. Öffne diese Adresse in Chrome auf dem Smartphone und füge sie zum Startbildschirm hinzu.

## Datenspeicherung

Trainingseinträge werden in `localStorage` des jeweiligen Browsers gespeichert. Sie werden nicht an GitHub Pages gesendet und nicht automatisch zwischen Geräten synchronisiert. Nutze in der App **Daten → Daten exportieren/importieren**, um eine Sicherung manuell zu übertragen. Lösche die Browserdaten für die Website nicht ohne vorherigen Export.

## Spracheingabe

Die Spracherkennung benötigt einen unterstützenden Browser, Mikrofonzugriff und Internet. Der Browser kann die Spracherkennung über einen Online-Dienst verarbeiten. Die Spracheingabe zeigt vor dem Speichern den erkannten Satz und die Zuordnung zu Übung, Gewicht, Wiederholungen je Satz und Satzanzahl. Unterschiedliche Wiederholungen lassen sich als Liste sprechen oder eintragen, zum Beispiel „vier Sätze: zehn, acht, acht und sechs Wiederholungen“.


