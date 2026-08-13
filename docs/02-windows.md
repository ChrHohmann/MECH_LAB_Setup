# 2. Entwicklungsumgebung unter Windows installieren

## Ziel

Nach dieser Seite sind VS Code, Python und Git installiert. Git kennt Ihren Namen und Ihre HSLU-E-Mail-Adresse.

## Voraussetzungen

- Windows 10 oder Windows 11,
- ein 64-Bit-System,
- Administratorrechte und
- eine Internetverbindung.

## 1. Visual Studio Code installieren

1. Öffnen Sie die [offizielle VS-Code-Downloadseite](https://code.visualstudio.com/download).
2. Laden Sie unter **Windows** den passenden **User Installer** herunter. Meist ist dies **x64**.
3. Öffnen Sie die Installationsdatei.
4. Akzeptieren Sie die Lizenzvereinbarung.
5. Übernehmen Sie die Standardoptionen.
6. Klicken Sie auf **Installieren**.
7. Starten Sie VS Code.

## 2. Python installieren

Python wird zur lokalen Prüfung von VS Code benötigt. Der Laborcode läuft später auf dem Raspberry Pi.

1. Öffnen Sie die [offizielle Python-Downloadseite](https://www.python.org/downloads/windows/).
2. Laden Sie die aktuelle stabile 64-Bit-Version herunter.
3. Öffnen Sie die Installationsdatei.
4. Aktivieren Sie **Use admin privileges when installing py.exe**.
5. Aktivieren Sie unbedingt **Add python.exe to PATH**.
6. Klicken Sie auf **Install Now**.
7. Bestätigen Sie die Administratorabfrage.
8. Warten Sie auf den Abschluss und klicken Sie auf **Close**.

## 3. Git installieren

1. Öffnen Sie die [offizielle Git-Downloadseite](https://git-scm.com/download/win).
2. Laden Sie **64-bit Git for Windows Setup** herunter.
3. Öffnen Sie die Installationsdatei.
4. Übernehmen Sie die vorgeschlagenen Standardoptionen.
5. Wählen Sie als Standardeditor **Use Visual Studio Code as Git's default editor**.
6. Klicken Sie auf **Install**.

## 4. Git konfigurieren

1. Drücken Sie Windows + S.
2. Suchen und öffnen Sie **Git Bash**.
3. Ersetzen Sie die Beispielwerte und führen Sie aus:

       git config --global user.name "Vorname Nachname"
       git config --global user.email "vorname.nachname@stud.hslu.ch"
       git config --global --list

## Kontrolle

Schliessen und öffnen Sie Git Bash. Führen Sie aus:

    git --version
    python --version

Git und Python müssen jeweils eine Versionsnummer anzeigen. VS Code muss über das Startmenü öffnen. Die Git-Konfiguration muss Ihren Namen und Ihre HSLU-E-Mail-Adresse enthalten.

## Bei Problemen

Öffnen Sie [Fehlerbehebung](11-fehlerbehebung.md).

## Weiter

[GitHub-Konto erstellen →](04-github-konto.md)
