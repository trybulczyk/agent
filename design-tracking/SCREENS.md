# Ekrany

Tracking ekranów aplikacji do zaprojektowania w Figma Make.

## Legenda

- `[ ]` Do zrobienia | `[~]` W trakcie | `[x]` Gotowe | `[!]` Blokada
- Priorytet: `P0` Krytyczne | `P1` Ważne | `P2` Normalne | `P3` Niski

---

## Onboarding

| Ekran | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|-------|-----------|--------|------------|---------|
| Splash Screen | | P0 | [ ] | | |
| Welcome | | P1 | [ ] | | |
| Onboarding Step 1 | | P2 | [ ] | | |
| Onboarding Step 2 | | P2 | [ ] | | |
| Onboarding Step 3 | | P2 | [ ] | | |

## Auth

| Ekran | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|-------|-----------|--------|------------|---------|
| Login | default, loading, error | P0 | [ ] | | |
| Register | default, loading, error | P0 | [ ] | | |
| Forgot Password | | P1 | [ ] | | |
| Reset Password | | P1 | [ ] | | |
| Verification Code | | P1 | [ ] | | |

## Main App

| Ekran | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|-------|-----------|--------|------------|---------|
| Home | empty, loading, loaded, error | P0 | [ ] | | |
| Search | empty, results, no results | P1 | [ ] | | |
| Details | loading, loaded | P1 | [ ] | | |
| Profile | own, other user | P1 | [ ] | | |
| Settings | | P2 | [ ] | | |
| Notifications | empty, with items | P2 | [ ] | | |

## Modals & Overlays

| Ekran | Stany | Priorytet | Status | Figma Link | Notatki |
|-------|-------|-----------|--------|------------|---------|
| Filter Modal | | P2 | [ ] | | |
| Share Sheet | | P3 | [ ] | | |
| Confirmation Dialog | | P2 | [ ] | | |

---

## Nowe ekrany do dodania

<!-- Wpisuj tutaj nowe ekrany które odkryjesz w aplikacji -->

| Ekran | Moduł | Priorytet | Notatki |
|-------|-------|-----------|---------|
| | | | |

---

## Mapa ekranów

```
[Splash] → [Onboarding] → [Login/Register]
                              ↓
                          [Home] ←→ [Search]
                            ↓
                        [Details]
                            ↓
                    [Action/Modal]
```
