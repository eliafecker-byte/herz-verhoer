# Herz-Verhör

Partyspiel für Freunde: Ein Video aus euren TikTok-Likes taucht auf, und alle raten, wer es geliked hat.

## Spielen

1. Seite öffnen, Namen eingeben, «Neues Spiel erstellen».
2. Freunde öffnen dieselbe Seite und geben den 4-stelligen PIN ein. Ein Konto braucht niemand.
3. Jeder lädt seine TikTok-Datei hoch oder fügt Links ein.
4. Der Gastgeber startet. Die Seite des Gastgebers muss bis zum Schluss offen bleiben.

## TikTok-Likes holen

TikTok → Profil → Menü → Einstellungen und Datenschutz → Konto → Deine Daten herunterladen.
Nur «Likes und Favoriten» anhaken, Format JSON wählen, «Daten anfordern».
Nach 1–4 Tagen die ZIP-Datei herunterladen (der Link gilt 4 Tage).

Die Datei bleibt auf dem eigenen Gerät. Ins Spiel gehen nur 20 zufällig gewählte Videos.

## Technik

Eine einzige Datei, `index.html`. Die Handys verbinden sich direkt über PeerJS (kostenloser öffentlicher Server).
