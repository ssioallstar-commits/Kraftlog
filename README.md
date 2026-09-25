# Kraftlog

Installierbare, statische HTTPS-Web-App für Krafttraining. Öffne die Site auf Android in Chrome und wähle im Browser-Menü „Zum Startbildschirm hinzufügen“ oder „App installieren“.

## Veröffentlichung über GitHub Pages

1. Lade die App-Dateien in den Stammordner des GitHub-Repositorys hoch.
2. Öffne **Settings → Pages** und wähle als Quelle **GitHub Actions**.
3. Der Workflow veröffentlicht Änderungen automatisch nach jedem Push. Öffne die HTTPS-Adresse in Chrome auf dem Smartphone und füge sie zum Startbildschirm hinzu.

## Datenspeicherung

Trainingseinträge werden in `localStorage` des jeweiligen Browsers gespeichert. Sie werden nicht an GitHub Pages gesendet und nicht automatisch zwischen Geräten synchronisiert. Nutze in der App **Daten → Daten exportieren/importieren**, um eine Sicherung manuell zu übertragen. Lösche die Browserdaten für die Website nicht ohne vorherigen Export.

## Spracheingabe

Die Spracherkennung benötigt einen unterstützenden Browser, Mikrofonzugriff und Internet. Der Browser kann die Spracherkennung über einen Online-Dienst verarbeiten. Die Spracheingabe zeigt vor dem Speichern den erkannten Satz und die Zuordnung zu Übung, Gewicht, Wiederholungen je Satz und Satzanzahl. Unterschiedliche Wiederholungen lassen sich als Liste sprechen oder eintragen, zum Beispiel „vier Sätze: zehn, acht, acht und sechs Wiederholungen“.

