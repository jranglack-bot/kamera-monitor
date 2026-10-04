# Kamera-Monitor

Ein Handy filmt mit der Hauptkamera, das zweite zeigt live das Bild und startet oder stoppt die Aufnahme.

**Adresse:** https://jranglack-bot.github.io/kamera-monitor/ (am besten in Chrome öffnen)

1. Auf dem Handy, das filmt, die Adresse öffnen, „Dieses Handy filmt“ wählen, Kamera und Mikrofon erlauben.
2. Mit dem zweiten Handy den QR-Code scannen. Fertig.
3. Nach jeder Aufnahme landet die Datei automatisch im Download-Ordner des Kamera-Handys
   (Samsung-Galerie: Alben, „Download“). Beim zweiten Mal fragt Chrome einmal, ob die Seite
   mehrere Dateien laden darf: „Zulassen“ tippen.

Unter „Einstellungen“ (auf beiden Handys):
- Format: Video als MP4 oder nur Ton als MP3
- Qualität: 1080p mit 30 oder 60 Bildern/s, 4K für die beste Bildqualität
- Farben: Looks wie Lebendig, Warm, Kühl, Kino, Schwarzweiß und Regler für Helligkeit, Kontrast, Farbe, Wärme, Schärfe
- Kamera: Belichtung („Bewegung scharf“ gegen verwischte Bewegung), ISO, Weißabgleich, Fokus, Zoom, Licht,
  soweit das Handy sie im Browser freigibt

Die App zeigt an, wie viele Bilder pro Sekunde die Kamera wirklich schafft. Fällt die Zahl, ist es meist zu dunkel.

Beide Handys müssen im selben WLAN sein. Das Video läuft direkt von Handy zu Handy und über keinen Server.
Zum Koppeln wird kurz der kostenlose Vermittlungsdienst PeerJS genutzt, er sieht nur Verbindungsdaten, kein Bild.

Zum Ausprobieren am PC ohne Kamera: `?test=1` an die Adresse hängen, dann gibt es ein Testbild.
