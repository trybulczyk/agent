# Design Tracking System

System do śledzenia zmian designowych dla aplikacji mobilnej iOS.

## Struktura

```
/design-tracking
├── APP_STRUCTURE.md      # Mapowanie struktury aplikacji
├── COMPONENTS.md         # Śledzenie komponentów UI
├── SCREENS.md            # Śledzenie ekranów
├── FLOWS.md              # Śledzenie flows użytkownika
└── /changelog            # Dziennik zmian
    └── YYYY-MM-DD.md     # Codzienne wpisy
```

## Jak korzystać

### Codzienne aktualizacje
1. Stwórz nowy plik w `/changelog` z datą (np. `2026-02-03.md`)
2. Użyj szablonu z `TEMPLATE_DAILY.md`
3. Zaktualizuj odpowiednie pliki (`COMPONENTS.md`, `SCREENS.md`, `FLOWS.md`)

### Statusy zadań
- `[ ]` - Do zrobienia
- `[~]` - W trakcie
- `[x]` - Gotowe w Figma Make
- `[!]` - Wymaga uwagi / blokada

### Priorytety
- `P0` - Krytyczne (dzisiaj)
- `P1` - Ważne (ten tydzień)
- `P2` - Normalne (ten sprint)
- `P3` - Niski priorytet

## Workflow

1. **Analiza** - Sprawdź strukturę w Xcode
2. **Dokumentacja** - Zaktualizuj pliki tracking
3. **Design** - Stwórz/zaktualizuj w Figma Make
4. **Sync** - Oznacz jako gotowe, dodaj linki

## Linki

- Figma Make: [dodaj link]
- Repozytorium aplikacji: [dodaj link]
