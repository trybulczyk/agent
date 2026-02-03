# User Flows

Tracking przepływów użytkownika do zaprojektowania w Figma Make.

## Legenda

- `[ ]` Do zrobienia | `[~]` W trakcie | `[x]` Gotowe | `[!]` Blokada
- Priorytet: `P0` Krytyczne | `P1` Ważne | `P2` Normalne | `P3` Niski

---

## Flow: Onboarding

**Status:** `[ ]` | **Priorytet:** `P0`
**Figma Link:** [dodaj]

### Kroki:
1. `[ ]` Splash Screen (2s)
2. `[ ]` Welcome Screen
3. `[ ]` Onboarding Slide 1
4. `[ ]` Onboarding Slide 2
5. `[ ]` Onboarding Slide 3
6. `[ ]` Login / Register choice

### Notatki:
<!-- Dodaj obserwacje z aplikacji -->

---

## Flow: Rejestracja

**Status:** `[ ]` | **Priorytet:** `P0`
**Figma Link:** [dodaj]

### Kroki:
1. `[ ]` Register Screen → wprowadź dane
2. `[ ]` Walidacja formularza
3. `[ ]` Loading state
4. `[ ]` Verification Code Screen
5. `[ ]` Success → Home

### Edge cases:
- [ ] Email już istnieje
- [ ] Błąd połączenia
- [ ] Nieprawidłowy kod weryfikacyjny

### Notatki:
<!-- Dodaj obserwacje z aplikacji -->

---

## Flow: Logowanie

**Status:** `[ ]` | **Priorytet:** `P0`
**Figma Link:** [dodaj]

### Kroki:
1. `[ ]` Login Screen → wprowadź credentials
2. `[ ]` Loading state
3. `[ ]` Success → Home

### Edge cases:
- [ ] Nieprawidłowe hasło
- [ ] Konto nie istnieje
- [ ] Konto zablokowane
- [ ] Błąd połączenia

### Notatki:
<!-- Dodaj obserwacje z aplikacji -->

---

## Flow: Główna nawigacja

**Status:** `[ ]` | **Priorytet:** `P1`
**Figma Link:** [dodaj]

### Struktura Tab Bar:
1. `[ ]` Home
2. `[ ]` Search
3. `[ ]` [Nazwa]
4. `[ ]` [Nazwa]
5. `[ ]` Profile

### Notatki:
<!-- Dodaj obserwacje z aplikacji -->

---

## Flow: [Nazwa głównej akcji]

**Status:** `[ ]` | **Priorytet:** `P1`
**Figma Link:** [dodaj]

### Kroki:
1. `[ ]`
2. `[ ]`
3. `[ ]`

### Edge cases:
- [ ]

### Notatki:
<!-- Dodaj obserwacje z aplikacji -->

---

## Nowe flows do dodania

<!-- Wpisuj tutaj nowe flows które odkryjesz w aplikacji -->

| Flow | Priorytet | Notatki |
|------|-----------|---------|
| | | |

---

## Diagram przepływów

```
                    ┌─────────────┐
                    │   Splash    │
                    └──────┬──────┘
                           ▼
                    ┌─────────────┐
              ┌─────│  Onboarding │─────┐
              │     └─────────────┘     │
              ▼                         ▼
       ┌──────────┐              ┌──────────┐
       │  Login   │              │ Register │
       └────┬─────┘              └────┬─────┘
            │                         │
            └────────────┬────────────┘
                         ▼
                  ┌─────────────┐
                  │    Home     │
                  └──────┬──────┘
                         │
         ┌───────────────┼───────────────┐
         ▼               ▼               ▼
   ┌──────────┐   ┌──────────┐   ┌──────────┐
   │  Search  │   │ [Feature]│   │ Profile  │
   └──────────┘   └──────────┘   └──────────┘
```
