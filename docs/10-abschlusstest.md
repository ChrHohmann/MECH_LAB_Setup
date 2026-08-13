# 10. Abschlusstest mit welcome.py

## Ziel

Sie prüfen, dass VS Code, SSH, Git, Python und der Laboraufbau gemeinsam funktionieren.

## Voraussetzungen

- VS Code ist mit GitHub verknüpft.
- Die SSH-Verbindung ist aktiv.
- MECH_LAB ist auf den Raspberry Pi geklont.
- Die benötigte Hardware ist verfügbar.

## Hardware vorbereiten

1. Schalten Sie den Aufbau vor dem Umstecken aus.
2. Schliessen Sie die LED-Bar am Port **D18** des Grove BaseHat an.
3. Prüfen Sie die Verbindung.
4. Schalten Sie den Aufbau ein.
5. Warten Sie, bis der Raspberry Pi gestartet ist.

## Skript ausführen

1. Prüfen Sie unten links die SSH-Verbindung.
2. Öffnen Sie links **Explorer**.
3. Öffnen Sie welcome.py.
4. Klicken Sie oben rechts auf **Run Python File**.
5. Beobachten Sie Terminal und LED-Bar.
6. Warten Sie auf die Erfolgsmeldung.

Die LED-Bar wird einige Sekunden angesteuert. Im Terminal erscheint ein Fortschrittsbalken.

## Kontrolle

- Die LED-Bar reagiert.
- Es erscheint keine unbehandelte Fehlermeldung.
- Der Fortschrittsbalken wird beendet.
- Die Erfolgsmeldung erscheint.

## Falls der Run-Button fehlt

1. Prüfen Sie die Python-Erweiterung.
2. Öffnen Sie welcome.py.
3. Prüfen Sie die SSH-Verbindung.
4. Führen Sie alternativ im Raspberry-Pi-Terminal aus:

       python3 welcome.py

## Bei Problemen

Öffnen Sie [Fehlerbehebung](11-fehlerbehebung.md). Veröffentlichen Sie keine Passwörter.

## Abschluss

Wenn alle Kontrollen erfolgreich sind, ist Ihre Entwicklungsumgebung eingerichtet.

[Zur Vorbereitung zurück](01-vorbereitung.md)
