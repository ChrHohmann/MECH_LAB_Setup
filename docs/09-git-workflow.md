# 9. Git-Arbeitsablauf im Labor

## Ziel

Sie können eigene Änderungen sichern und Aktualisierungen der Modulverantwortlichen übernehmen.

## Die drei Orte

| Name | Ort | Zweck |
|---|---|---|
| upstream | GitHub der Modulverantwortlichen | Offizieller Laborcode |
| origin | Ihr persönlicher Fork | Ihre Änderungen online |
| lokal | Raspberry Pi | Code bearbeiten und testen |

## Vor Beginn

Öffnen Sie das Repository im entfernten VS-Code-Fenster und prüfen Sie:

    git status
    git remote -v

## Eigene Änderung sichern

1. Bearbeiten und testen Sie den Code.
2. Prüfen Sie:

       git status

3. Wählen Sie gezielt Dateien:

       git add <dateiname>

4. Erstellen Sie einen Commit:

       git commit -m "Kurze Beschreibung der Änderung"

5. Laden Sie ihn in Ihren Fork:

       git push origin main

Eine gute Meldung wäre beispielsweise: GPIO für Sensor D18 anpassen.

## Aktualisierungen aus upstream übernehmen

Committen Sie eigene Änderungen zuerst.

    git fetch upstream
    git merge upstream/main
    git push origin main

Testen Sie den Code vor dem Push. Falls das Original einen anderen Standardbranch verwendet, ersetzen Sie main entsprechend.

## Kontrolle

    git status

Im Idealfall erscheint:

    nothing to commit, working tree clean

Öffnen Sie Ihren Fork auf GitHub und prüfen Sie den letzten Commit.

## Bei Problemen

Öffnen Sie [Fehlerbehebung](11-fehlerbehebung.md).

## Weiter

[Abschlusstest →](10-abschlusstest.md)
