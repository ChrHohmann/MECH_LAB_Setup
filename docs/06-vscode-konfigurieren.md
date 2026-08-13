# 6. Visual Studio Code konfigurieren

## Ziel

Nach dieser Seite sind die benötigten Erweiterungen installiert und VS Code ist mit Ihrem GitHub-Konto verknüpft.

## Voraussetzungen

- VS Code ist installiert.
- Ihr GitHub-Konto und Ihr Fork MECH_LAB bestehen.

## 1. Erweiterungen installieren

1. Öffnen Sie VS Code.
2. Klicken Sie links auf **Extensions**.
3. Suchen und installieren Sie nacheinander:
   - **Python** von Microsoft,
   - **Remote - SSH** von Microsoft,
   - **GitHub Pull Requests** von GitHub.

Die Kennungen lauten:

    ms-python.python
    ms-vscode-remote.remote-ssh
    github.vscode-pull-request-github

Pylint, Git Graph oder Todo Tree sind optional.

## 2. Erweiterungen prüfen

1. Leeren Sie das Suchfeld.
2. Öffnen Sie **Installed**.
3. Prüfen Sie alle drei Erweiterungen.
4. Öffnen Sie jede Erweiterung.
5. Wenn **Disable** angeboten wird, ist sie aktiv.
6. Klicken Sie andernfalls auf **Enable**.

Zusätzliche Erweiterungen wie Pylance können automatisch als Abhängigkeit installiert werden.

## 3. Mit GitHub anmelden

1. Öffnen Sie links **GitHub Pull Requests**.
2. Klicken Sie auf **Sign in**.
3. Klicken Sie im Dialog auf **Allow**.
4. Melden Sie sich im geöffneten Browser bei GitHub an.
5. Bestätigen Sie die Autorisierung von VS Code.
6. Wählen Sie bei mehreren Konten Ihr Kurskonto.
7. Klicken Sie auf **Continue**.
8. Wechseln Sie zurück zu VS Code.

## Kontrolle

1. Klicken Sie unten links auf **Accounts**.
2. Prüfen Sie, ob Ihr GitHub-Benutzername angezeigt wird.
3. Prüfen Sie unter **Extensions → Installed** alle drei Erweiterungen.

## Bei Problemen

Öffnen Sie [Fehlerbehebung](11-fehlerbehebung.md).

## Weiter

[SSH-Verbindung herstellen →](07-ssh-raspberry-pi.md)
