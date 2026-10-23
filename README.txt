# Familien-Ernährungsmanager – Web-App Starter

## Was ist enthalten?
- `index.html`: responsive App-Oberfläche mit Speiseplan, Einkaufsliste, Budget und Assistent-Demo
- `manifest.webmanifest`: Metadaten für die Installation als Web-App
- `service-worker.js`: Offline-Grundfunktion für Hosting über HTTPS

## Wichtig
- Diese Version benötigt noch kein Konto und keine kostenpflichtigen Dienste.
- Daten werden nur lokal im jeweiligen Browser gespeichert (`localStorage`).
- Es gibt noch keine Synchronisierung zwischen iPhone und Computer.
- Der Assistent ist noch keine echte KI-Anbindung.
- Keine echten medizinischen Entscheidungen aus der App ableiten; besonders keine Änderungen an Insulin oder Medikamenten.
- Die App ist noch nicht online veröffentlicht.

## Kostenlos veröffentlichen (späterer Schritt)
Die Dateien müssen in das Stammverzeichnis eines kostenlosen statischen Hostings hochgeladen werden. Zum Beispiel kann GitHub Pages für ein öffentliches Repository kostenlos sein. Dabei gilt: Wer ein öffentliches Repository verwendet, sollte keine persönlichen Gesundheitsdaten oder Zugangsdaten in den Quellcode schreiben.

Nach der Veröffentlichung über HTTPS kann die Seite in Safari geöffnet werden. Unter iOS kann sie über **Teilen → Zum Home-Bildschirm** auf dem Home-Bildschirm abgelegt werden.

## Testen
Öffne `index.html` lokal in einem Browser. Manche Vorschauen (auch Datei-Vorschauen in Apps) führen JavaScript nicht vollständig aus. Für die PWA-/Offline-Funktion ist ein HTTPS-Hosting nötig.
