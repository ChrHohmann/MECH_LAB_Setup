# 8. Persönliches Repository auf den Raspberry Pi klonen

## Ziel

Nach dieser Seite befindet sich eine lokale Kopie Ihres persönlichen Forks auf dem Raspberry Pi.

## Voraussetzungen

- VS Code ist mit GitHub verknüpft.
- Die SSH-Verbindung zum Raspberry Pi ist aktiv.
- Ihr Fork MECH_LAB besteht.

## Repository klonen

1. Prüfen Sie unten links den Hostnamen des Raspberry Pi.
2. Öffnen Sie links **Source Control**.
3. Klicken Sie auf **Clone Repository**.
4. Wählen Sie **Clone from GitHub**.
5. Melden Sie sich bei Bedarf erneut an.
6. Wählen Sie:

       IhrGitHubBenutzername/MECH_LAB

7. Wählen Sie auf dem Raspberry Pi:

       /home/stud/

8. Bestätigen Sie mit **OK**.
9. Warten Sie auf den Download.
10. Klicken Sie auf **Open**.
11. Geben Sie bei Bedarf das aktuelle Laborpasswort ein.
12. Vertrauen Sie dem Inhalt nur, wenn es eindeutig Ihr Fork ist.

## Kontrolle

1. Öffnen Sie **Explorer** und prüfen Sie den Ordner MECH_LAB.
2. Öffnen Sie **Terminal → New Terminal**.
3. Führen Sie aus:

       git remote -v

Bei origin muss Ihr persönlicher Fork stehen.

## Upstream ergänzen

Falls upstream fehlt, verwenden Sie die von den Modulverantwortlichen angegebene URL:

    git remote add upstream <URL-DES-ORIGINAL-REPOSITORIES>
    git remote -v

Origin muss auf Ihren Fork, upstream auf das Original zeigen.

## Bei Problemen

Öffnen Sie [Fehlerbehebung](11-fehlerbehebung.md).

## Weiter

[Git-Arbeitsablauf →](09-git-workflow.md)
