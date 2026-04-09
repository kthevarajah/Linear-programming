# Wichtigste Git-Commands

## Status prüfen
```bash
git status
git branch


## Änderungen speichern

git add .
git commit -m "Kurze Beschreibung"
git push

## Neuen Branch erstellen
git checkout -b stock-milp-prototype
git push -u origin stock-milp-prototype

## Zwischen Branches wechseln
git checkout main
git checkout stock-milp-prototype

#neuste Änderungen holen
git pull
