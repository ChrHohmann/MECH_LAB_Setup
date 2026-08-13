# 11. Fehlerbehebung

Suchen Sie nach der Meldung oder dem Symptom und führen Sie die Schritte der Reihe nach aus.

## Programm wird nicht gefunden

### Git

1. Schliessen Sie alle Terminals.
2. Öffnen Sie das Terminal erneut.
3. Prüfen Sie git --version.
4. Installieren Sie Git erneut, wenn der Fehler bleibt.

### Python

**Windows:** Starten Sie den Installer erneut, aktivieren Sie **Add python.exe to PATH** und prüfen Sie nach einem Terminal-Neustart python --version.

**macOS:** Prüfen Sie brew --version, führen Sie brew install python aus und prüfen Sie python3 --version.

### Homebrew

1. Öffnen Sie [brew.sh](https://brew.sh/).
2. Installieren Sie Homebrew nach der offiziellen Anleitung.
3. Führen Sie die angezeigten **Next steps** aus.
4. Öffnen Sie das Terminal neu.
5. Prüfen Sie brew --version.

## Author identity unknown

    git config --global user.name "Vorname Nachname"
    git config --global user.email "vorname.nachname@stud.hslu.ch"
    git config --global --list

## GitHub-Konto

### Bestätigungsmail fehlt

Prüfen Sie Spam-Ordner und Adresse. Öffnen Sie **Settings → Emails** und fordern Sie die Bestätigung erneut an.

### Benutzername vergeben

Ergänzen Sie eine kurze eindeutige Angabe. Verwenden Sie keine Matrikelnummer als öffentlichen Benutzernamen.

### Fork fehlt

Prüfen Sie Anmeldung, Original-Repository und ob bereits ein Fork in Ihrem Profil besteht.

## VS Code

### Erweiterung fehlt

Suchen Sie nach:

    ms-python.python
    ms-vscode-remote.remote-ssh
    github.vscode-pull-request-github

Prüfen Sie die Herausgeber Microsoft beziehungsweise GitHub.

### GitHub-Anmeldung kehrt nicht zurück

Lassen Sie VS Code geöffnet, wiederholen Sie **Sign in** und erlauben Sie dem Browser, VS Code zu öffnen. Prüfen Sie danach **Accounts**.

## SSH

### Hostname nicht gefunden oder Zeitüberschreitung

1. Prüfen Sie Gerätenummer und Hostname.
2. Verbinden Sie beide Geräte mit dem vorgesehenen HSLU-WLAN.
3. Deaktivieren Sie VPN.
4. Starten Sie den Raspberry Pi neu.
5. Warten Sie mindestens zwei Minuten.

### Passwort abgelehnt

Prüfen Sie Benutzername und aktuelles Passwort im geschützten Kurskanal. Beim Tippen werden möglicherweise keine Zeichen angezeigt.

### Host-Schlüssel hat sich geändert

Bestätigen Sie die Warnung nicht ungeprüft. Vergleichen Sie Gerätenummer und Hostname und wenden Sie sich an die Laborbetreuung.

## Klonen und Remotes

### Fork erscheint nicht

Prüfen Sie den Fork im Browser und das unter **Accounts** angemeldete VS-Code-Konto.

### Ordner MECH_LAB existiert bereits

Überschreiben oder löschen Sie nichts ungeprüft. Prüfen Sie, ob das Repository bereits vollständig vorhanden ist.

### Origin ist falsch

    git remote -v
    git remote set-url origin https://github.com/IHR-BENUTZERNAME/MECH_LAB.git

### Upstream fehlt

    git remote add upstream <URL-DES-ORIGINAL-REPOSITORIES>
    git remote -v

## Push oder Merge

### Push wird abgelehnt

Prüfen Sie origin, GitHub-Anmeldung und neue Remote-Änderungen. Integrieren Sie Änderungen und lösen Sie Konflikte vor einem erneuten Push.

### Merge-Konflikt

1. Öffnen Sie die markierten Dateien in VS Code.
2. Entscheiden Sie, welche Änderung erhalten bleibt.
3. Entfernen Sie alle Konfliktmarkierungen.
4. Testen Sie die Datei.
5. Führen Sie git add für die Datei aus.
6. Erstellen Sie einen Commit.

Holen Sie Unterstützung, wenn Sie die fachlich richtige Variante nicht sicher beurteilen können.

## welcome.py

### Run-Button fehlt

Prüfen Sie Python-Erweiterung, geöffnete Datei und SSH-Verbindung. Verwenden Sie alternativ:

    python3 welcome.py

### LED-Bar reagiert nicht

Schalten Sie sicher aus, prüfen Sie Port D18, Kabel und Stromversorgung und starten Sie erneut.

## Noch nicht gelöst?

Erstellen Sie ein Issue im Setup-Repository und nennen Sie Betriebssystem, Seite, Schritt, Fehlermeldung und bereits versuchte Lösungen.

Entfernen Sie Namen, E-Mail-Adressen, Passwörter, Tokens, Host-Schlüssel und andere vertrauliche Daten.

[Zur Vorbereitung zurück](01-vorbereitung.md)
