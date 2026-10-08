# Discovery Labs Innsbruck

Veröffentlicht mit GitHub Pages unter https://discoverylabs-uibk.github.io/

## Texte ändern

Alle Texte stehen als einfache Markdown-Dateien im Ordner **`website/`**.

1. Auf github.com die Datei öffnen, zum Beispiel `website/index.md`.
2. Oben rechts auf das **Stift-Symbol** (Edit) klicken.
3. Text ändern, unten **Commit changes** wählen.

Nach ein bis zwei Minuten ist die Änderung auf der Seite sichtbar. (Den Fortschritt sieht man im Reiter *Actions*.)
Auf der veröffentlichten Seite führt der Stift oben rechts neben dem Seitentitel direkt zur richtigen Datei.

## Aussehen ändern

Farben stehen in `website/stylesheets/extra.css`, Seitenname und Einstellungen in `mkdocs.yml`.
Diese Dateien muss man für Textänderungen nicht anfassen.

## Ein neues Lernlabor hinzufügen

1. In der Organisation ein neues **öffentliches** Repository anlegen (Kleinbuchstaben, zum Beispiel `labname`) und dort ebenfalls GitHub Pages einrichten (siehe das Repository `quantumcrypto` als Vorlage).
2. Hier in `website/index.md` einen weiteren Eintrag unter `<div class="grid cards">` ergänzen, mit dem Link `https://discoverylabs-uibk.github.io/labname/`.

## Wichtige Einstellung

Unter **Settings → Pages** muss die Quelle auf **GitHub Actions** stehen (nicht „Deploy from a branch").

## Lokal ansehen (optional)

```
pip install -r requirements.txt
mkdocs serve
```

Nur Inhalte ablegen, die öffentlich sein dürfen (keine Lösungen für Lehrkräfte, keine urheberrechtlich geschützten Dokumente).
