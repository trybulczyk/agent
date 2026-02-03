# Ekrany - Nurse App

Tracking ekranów aplikacji do zaprojektowania w Figma Make.

## Legenda

- `[ ]` Do zrobienia | `[~]` W trakcie | `[x]` Gotowe | `[!]` Blokada
- Priorytet: `P0` Krytyczne | `P1` Ważne | `P2` Normalne | `P3` Niski

---

## Auth `/(auth)`

| Ekran | Ścieżka | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|---------|-------|-----------|--------|------------|---------|
| Login | `login.tsx` | default, loading, error | P0 | [ ] | | |
| Register | `register.tsx` | default, loading, error | P0 | [ ] | | |
| Forgot Password | | | P2 | [ ] | | |

## Tabs `/(app)/(tabs)`

| Ekran | Ścieżka | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|---------|-------|-----------|--------|------------|---------|
| Tab 1 - Home? | `index.tsx` | empty, loading, loaded | P0 | [ ] | | |
| Tab 2 | | | P1 | [ ] | | Do zidentyfikowania |
| Tab 3 | | | P1 | [ ] | | Do zidentyfikowania |
| Tab 4 | | | P1 | [ ] | | Do zidentyfikowania |

## Visits `/(app)/visits`

| Ekran | Ścieżka | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|---------|-------|-----------|--------|------------|---------|
| Lista wizyt | `index.tsx` | empty, loading, loaded | P0 | [ ] | | |
| Szczegóły wizyty | `[id].tsx` | loading, loaded | P0 | [ ] | | |
| Nowa wizyta | | | P1 | [ ] | | |
| Edycja wizyty | | | P2 | [ ] | | |

## Group Actions `/(app)/group_actions`

| Ekran | Ścieżka | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|---------|-------|-----------|--------|------------|---------|
| Akcje grupowe | | | P1 | [ ] | | Do zbadania |

## Modals & Bottom Sheets

| Ekran | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|-------|-----------|--------|------------|---------|
| Filter Modal | | P2 | [ ] | | |
| Confirmation Dialog | | P2 | [ ] | | |
| Success Toast | | P3 | [ ] | | |
| Error Toast | | P3 | [ ] | | |

---

## Nowe ekrany do dodania

<!-- Wpisuj tutaj nowe ekrany które odkryjesz w aplikacji -->

| Ekran | Moduł | Ścieżka | Priorytet | Notatki |
|-------|-------|---------|-----------|---------|
| | | | | |

---

## Mapa ekranów

```
[Login] → [Register]
    ↓
[Tabs Home] ←→ [Tab 2] ←→ [Tab 3] ←→ [Tab 4]
    ↓
[Visits List] → [Visit Details]
    ↓
[Group Actions]
```

## Do uzupełnienia

Po przejściu przez aplikację uzupełnij:
- [ ] Nazwy wszystkich tabów
- [ ] Dokładne ścieżki plików
- [ ] Wszystkie stany każdego ekranu
- [ ] Screenshoty jako referencje
