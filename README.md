# Kamera-Monitor

Ein Handy filmt mit der Hauptkamera, das zweite zeigt live das Bild und startet oder stoppt die Aufnahme.

**Adresse:** https://jranglack-bot.github.io/kamera-monitor/

1. Auf dem Handy, das filmt, die Adresse öffnen, „Dieses Handy filmt“ wählen, Kamera und Mikrofon erlauben.
2. Mit dem zweiten Handy den QR-Code scannen. Fertig.
3. Aufnahmen bleiben auf dem Kamera-Handy unter „Aufnahmen“ und werden von dort gesichert.

Beide Handys müssen im selben WLAN sein. Das Video läuft direkt von Handy zu Handy und über keinen Server.
Zum Koppeln wird kurz der kostenlose Vermittlungsdienst PeerJS genutzt, er sieht nur Verbindungsdaten, kein Bild.

Zum Ausprobieren am PC ohne Kamera: `?test=1` an die Adresse hängen, dann gibt es ein Testbild.
