# Komponenty UI

Tracking komponentów do zaprojektowania/zaktualizowania w Figma Make.

## Legenda

- `[ ]` Do zrobienia | `[~]` W trakcie | `[x]` Gotowe | `[!]` Blokada
- Priorytet: `P0` Krytyczne | `P1` Ważne | `P2` Normalne | `P3` Niski

---

## Buttons

| Komponent | Warianty | Priorytet | Status | Figma Link | Notatki |
|-----------|----------|-----------|--------|------------|---------|
| PrimaryButton | default, disabled, loading | P1 | [ ] | | |
| SecondaryButton | default, disabled | P2 | [ ] | | |
| IconButton | sizes: sm, md, lg | P2 | [ ] | | |
| TextButton | default, destructive | P2 | [ ] | | |

## Inputs

| Komponent | Warianty | Priorytet | Status | Figma Link | Notatki |
|-----------|----------|-----------|--------|------------|---------|
| TextField | default, error, disabled, focused | P1 | [ ] | | |
| SearchBar | empty, filled, loading | P1 | [ ] | | |
| Checkbox | checked, unchecked, disabled | P2 | [ ] | | |
| Toggle | on, off, disabled | P2 | [ ] | | |
| Dropdown | closed, open, selected | P2 | [ ] | | |

## Cards

| Komponent | Warianty | Priorytet | Status | Figma Link | Notatki |
|-----------|----------|-----------|--------|------------|---------|
| ContentCard | | P2 | [ ] | | |
| ListItem | default, selected, swipeable | P1 | [ ] | | |

## Navigation

| Komponent | Warianty | Priorytet | Status | Figma Link | Notatki |
|-----------|----------|-----------|--------|------------|---------|
| TabBar | | P0 | [ ] | | Phosphor Icons - patrz sekcja poniżej |
| NavBar | default, large title, search | P0 | [ ] | | |
| BackButton | | P1 | [ ] | | Phosphor: `CaretLeft` lub `ArrowLeft` |

### TabBar - Ikony nawigacji (Phosphor Icons)

Biblioteka: `phosphor-react-native` ([npm](https://www.npmjs.com/package/phosphor-react-native))

| Tab | Ikona (primary) | Alternatywy | Import |
|-----|-----------------|-------------|--------|
| **Wizyty** | `Stethoscope` | `FirstAid`, `Clipboard`, `MapPin` | `import { Stethoscope } from 'phosphor-react-native'` |
| **Historia** | `ClockCounterClockwise` | `Clock`, `Archive` | `import { ClockCounterClockwise } from 'phosphor-react-native'` |
| **Grafik** | `CalendarBlank` | `Calendar`, `CalendarCheck` | `import { CalendarBlank } from 'phosphor-react-native'` |
| **Grupowe** | `UsersThree` | `Users`, `UsersFour` | `import { UsersThree } from 'phosphor-react-native'` |
| **Menu** | `List` | `DotsThreeVertical`, `User`, `Gear` | `import { List } from 'phosphor-react-native'` |

**Instalacja:**
```bash
npm install phosphor-react-native
# lub
yarn add phosphor-react-native
```

**Przykład użycia:**
```tsx
import { Stethoscope, ClockCounterClockwise, CalendarBlank, UsersThree, List } from 'phosphor-react-native';

// W TabBar
<Stethoscope size={24} color={focused ? '#007AFF' : '#8E8E93'} weight={focused ? 'fill' : 'regular'} />
```

**Dostępne weights:** `thin`, `light`, `regular`, `bold`, `fill`, `duotone`

## Feedback

| Komponent | Warianty | Priorytet | Status | Figma Link | Notatki |
|-----------|----------|-----------|--------|------------|---------|
| Toast | success, error, warning, info | P1 | [ ] | | |
| Alert | | P1 | [ ] | | |
| LoadingSpinner | | P1 | [ ] | | |
| EmptyState | | P2 | [ ] | | |
| ErrorState | | P2 | [ ] | | |

## Modals

| Komponent | Warianty | Priorytet | Status | Figma Link | Notatki |
|-----------|----------|-----------|--------|------------|---------|
| BottomSheet | | P1 | [ ] | | |
| FullScreenModal | | P2 | [ ] | | |
| ActionSheet | | P2 | [ ] | | |

---

## Nowe komponenty do dodania

<!-- Wpisuj tutaj nowe komponenty które odkryjesz w aplikacji -->

| Komponent | Gdzie znaleziony | Priorytet | Notatki |
|-----------|------------------|-----------|---------|
| | | | |
