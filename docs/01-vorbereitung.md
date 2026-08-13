# 1. Vorbereitung

## Ziel

Nach dieser Seite kennen Sie den Laboraufbau, den Ablauf der Einrichtung und die benötigten Hilfsmittel.

## Das benötigen Sie

- einen Computer mit Windows oder macOS,
- Administratorrechte,
- eine stabile Internetverbindung,
- Ihre HSLU-E-Mail-Adresse,
- etwa 45 bis 60 Minuten Zeit und
- später Zugang zum HSLU-WLAN und zu einem Labor-Raspberry-Pi.

## So funktioniert die Laborumgebung

Der Laboraufbau besteht aus Ihrem Computer und einem physischen Versuchsaufbau. Dieser enthält je nach Labor mechanische Komponenten, Sensoren oder Aktoren, einen Raspberry Pi und eine Stromversorgung.

Auf Ihrem Computer verwenden Sie Visual Studio Code (VS Code). Über eine verschlüsselte SSH-Verbindung bedienen Sie den Raspberry Pi. Der Python-Code wird auf dem Raspberry Pi ausgeführt; Ausgaben erscheinen in VS Code.

Der Laborcode wird mit Git verwaltet:

- **upstream:** Repository der Modulverantwortlichen,
- **origin:** Ihr persönlicher Fork auf GitHub,
- **lokales Repository:** Arbeitskopie auf dem Raspberry Pi.

Mit einem Fork erhalten Sie eine eigene Kopie des Labor-Repositories. Sie können Ihre Änderungen hochladen, ohne das Original zu verändern.

## Ablauf

1. Installieren Sie VS Code, Python und Git.
2. Erstellen Sie ein GitHub-Konto.
3. Erstellen Sie einen Fork des Labor-Repositories.
4. Konfigurieren Sie VS Code.
5. Verbinden Sie VS Code über SSH mit dem Raspberry Pi.
6. Klonen Sie Ihren Fork auf den Raspberry Pi.
7. Lernen Sie den Git-Arbeitsablauf kennen.
8. Führen Sie welcome.py als Abschlusstest aus.

Python auf Ihrem Computer wird hauptsächlich zur Prüfung von VS Code benötigt. Der Laborcode läuft auf dem bereits eingerichteten Raspberry Pi.

## Sicherheits- und Netzwerkhinweise

- Veröffentlichen Sie niemals Passwörter, Tokens oder private SSH-Schlüssel.
- Beziehen Sie Laborzugangsdaten nur über den geschützten Kurskanal.
- Computer und Raspberry Pi müssen sich später im vorgesehenen HSLU-WLAN befinden.
- Deaktivieren Sie vor der SSH-Verbindung eine aktive VPN-Verbindung.

## Kontrolle

- Sie haben Administratorrechte.
- Sie kennen Ihre HSLU-E-Mail-Adresse.
- Sie wissen, ob Sie Windows oder macOS verwenden.
- Sie können alle Schritte ohne Unterbrechung ausführen.

## Weiter

- [Windows einrichten →](02-windows.md)
- [macOS einrichten →](03-macos.md)

Bei Problemen: [Fehlerbehebung](11-fehlerbehebung.md)
