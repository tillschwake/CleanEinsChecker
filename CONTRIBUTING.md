# Contributing to CleanEinsChecker

## Workflow

1. Fork oder branch von `main`
2. Entwickle in deinem Branch
3. Erstelle einen Pull Request
4. Nach Review: Squash-Merge auf `main`

## Branching

```
main           ← stabiler Code
  └── feature/*    Feature-Branches
  └── fix/*        Bugfix-Branches
  └── docs/*       Dokumentation
```

## Commits

Format: `type(scope): Beschreibung`

Types:
- `feat` – neue Funktion
- `fix` – Fehlerbehebung
- `docs` – nur Dokumentation
- `style` – Formatierung
- `refactor` – Code-Umstrukturierung
- `test` – nur Tests
- `chore` – Maintenance, Dependencies

Beispiele:
```
feat(auth): Magic-Link Login implementiert
fix(api): Token-Refresh Timeout behoben
docs(readme): Setup-Anleitung ergänzt
```

## Pull Requests

- Beschreibe **was** und **warum**
- Checkliste:
  - [ ] Tests vorhanden
  - [ ] Build grün
  - [ ] Keine Console-Errors
- Alle Reviews approving before merge
- Keine offenen Conversations beim Merge

## Keine Secrets in Git

`.env` Dateien, API-Keys, Passwörter → NIEMALS einchecken.
Nutze `.env.example` als Template.