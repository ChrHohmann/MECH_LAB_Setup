# 3. Entwicklungsumgebung unter macOS installieren

## Ziel

Nach dieser Seite sind Homebrew, VS Code, Python und Git installiert. Git kennt Ihren Namen und Ihre HSLU-E-Mail-Adresse.

## Voraussetzungen

- ein unterstütztes macOS,
- Administratorrechte und
- eine Internetverbindung.

Prüfen Sie unter **Apple-Menü → Über diesen Mac**, ob Ihr Gerät einen Apple-Chip oder einen Intel-Prozessor besitzt.

## 1. Visual Studio Code installieren

1. Öffnen Sie die [offizielle VS-Code-Downloadseite](https://code.visualstudio.com/download).
2. Wählen Sie unter **Mac** Apple silicon, Intel chip oder Universal passend zu Ihrem Gerät.
3. Öffnen Sie die geladene DMG-Datei.
4. Ziehen Sie Visual Studio Code in **Programme**.
5. Öffnen Sie VS Code und bestätigen Sie den ersten Start.

## 2. Homebrew installieren

1. Öffnen Sie **Programme → Dienstprogramme → Terminal**.
2. Prüfen Sie:

       brew --version

3. Erscheint eine Versionsnummer, fahren Sie mit Abschnitt 3 fort.
4. Erscheint command not found, öffnen Sie die [offizielle Homebrew-Seite](https://brew.sh/).
5. Verwenden Sie den dort angezeigten aktuellen Installationsbefehl.
6. Folgen Sie den Terminal-Anweisungen. Die Passworteingabe bleibt unsichtbar.
7. Führen Sie nach der Installation die von Homebrew angezeigten **Next steps** aus.
8. Schliessen und öffnen Sie das Terminal.
9. Prüfen Sie erneut:

       brew --version

## 3. Python und Git installieren

    brew update
    brew install python
    brew install git

Prüfen Sie:

    python3 --version
    git --version

## 4. Git konfigurieren

Ersetzen Sie die Beispielwerte:

    git config --global user.name "Vorname Nachname"
    git config --global user.email "vorname.nachname@stud.hslu.ch"
    git config --global --list

## Kontrolle

Homebrew, Python und Git zeigen Versionsnummern. VS Code startet aus **Programme**. Die Git-Konfiguration enthält Ihren Namen und Ihre HSLU-E-Mail-Adresse.

## Bei Problemen

Öffnen Sie [Fehlerbehebung](11-fehlerbehebung.md).

## Weiter

[GitHub-Konto erstellen →](04-github-konto.md)
