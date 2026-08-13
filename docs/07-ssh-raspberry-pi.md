# 7. SSH-Verbindung zum Raspberry Pi herstellen

## Ziel

Nach dieser Seite steuern Sie den Labor-Raspberry-Pi über ein entferntes VS-Code-Fenster.

## Voraussetzungen

- **Remote - SSH** ist installiert und aktiv.
- Computer und Raspberry Pi sind im vorgesehenen HSLU-WLAN.
- Es ist kein fremdes VPN aktiv.
- Sie kennen die Gerätenummer.
- Sie haben die aktuellen Zugangsdaten über den geschützten Kurskanal.

## Raspberry Pi vorbereiten

1. Schliessen Sie den Raspberry Pi an die Stromversorgung an.
2. Verbinden Sie Ihren Computer mit dem vorgesehenen HSLU-WLAN.
3. Deaktivieren Sie eine aktive VPN-Verbindung.
4. Warten Sie mindestens zwei Minuten.

Ein zu früher Verbindungsversuch kann die Hostnamensauflösung vorübergehend stören.

## Hostnamen bestimmen

Die Geräte verwenden gemäss bisheriger Anleitung:

    eee-w006-<0xx>.simple.eee.intern

Ersetzen Sie <0xx> durch die dreistellige Gerätenummer. Für Gerät 18:

    eee-w006-018.simple.eee.intern

Der bisherige Benutzername lautet stud. Prüfen Sie im geschützten Kurskanal, ob diese Angaben noch aktuell sind.

## Verbindung herstellen

1. Öffnen Sie VS Code.
2. Klicken Sie unten links auf **Remote Window**.
3. Wählen Sie **Connect to Host…**.
4. Wählen Sie **Add New SSH Host…**, wenn das Gerät noch fehlt.
5. Geben Sie ein:

       <Benutzername>@<Hostname>

   Beispiel:

       stud@eee-w006-018.simple.eee.intern

6. Bestätigen Sie und wählen Sie die vorgeschlagene SSH-Konfigurationsdatei.
7. Öffnen Sie erneut **Connect to Host…** und wählen Sie den Host.
8. Prüfen und bestätigen Sie bei der ersten Verbindung den Host-Schlüssel.
9. Geben Sie das aktuelle Passwort aus dem geschützten Kurskanal ein.
10. Warten Sie bis zu einer Minute.

## Kontrolle

Unten links wird der Hostname angezeigt. Öffnen Sie **Terminal → New Terminal**; das Terminal muss auf dem Raspberry Pi laufen.

## Bei Problemen

Öffnen Sie [Fehlerbehebung](11-fehlerbehebung.md).

## Weiter

[Repository klonen →](08-repository-klonen.md)
