# Struktura Aplikacji - Nurse App

Aplikacja mobilna dla pielęgniarek zbudowana w **React Native + Expo Router**.

## Stack technologiczny

- **Framework:** React Native z Expo
- **Nawigacja:** Expo Router (file-based routing)
- **Platform:** iOS + Android (cross-platform)

## Drzewo projektu

```
/nurse-app
├── /app                          # Główny folder routingu (Expo Router)
│   ├── /(auth)                   # Moduł autoryzacji
│   │   ├── login.tsx             # Ekran logowania
│   │   ├── register.tsx          # Ekran rejestracji
│   │   └── ...
│   │
│   └── /(app)                    # Główna aplikacja (po zalogowaniu)
│       ├── /(tabs)               # Nawigacja tabowa (dolny pasek)
│       │   ├── index.tsx         # Tab 1 - Home?
│       │   ├── _layout.tsx       # Konfiguracja tabów
│       │   └── ...
│       │
│       ├── /visits               # Moduł wizyt
│       │   ├── index.tsx         # Lista wizyt
│       │   ├── [id].tsx          # Szczegóły wizyty
│       │   └── ...
│       │
│       └── /group_actions        # Akcje grupowe
│           └── ...
│
├── /components                   # Reużywalne komponenty (do sprawdzenia)
├── /assets                       # Obrazy, fonty, ikony
├── /constants                    # Stałe, kolory, config
├── /hooks                        # Custom hooks
├── /services                     # API, storage
└── /types                        # TypeScript types
```

## Moduły / Features

| Moduł | Ścieżka | Opis | Status designu |
|-------|---------|------|----------------|
| Auth | `app/(auth)/` | Logowanie, rejestracja | [ ] Do zmapowania |
| Tabs | `app/(app)/(tabs)/` | Główna nawigacja | [ ] Do zmapowania |
| Visits | `app/(app)/visits/` | Zarządzanie wizytami | [ ] Do zmapowania |
| Group Actions | `app/(app)/group_actions/` | Akcje grupowe | [ ] Do zmapowania |

## Ekrany do zidentyfikowania

> Uruchom aplikację i przejdź przez każdy ekran, zapisując:

| Ekran | Ścieżka pliku | Screenshot | Notatki |
|-------|---------------|------------|---------|
| Login | `(auth)/login.tsx` | | |
| Register | `(auth)/register.tsx` | | |
| Home (Tab 1) | `(tabs)/index.tsx` | | |
| Tab 2 | | | |
| Tab 3 | | | |
| Lista wizyt | `visits/index.tsx` | | |
| Szczegóły wizyty | `visits/[id].tsx` | | |

## Design System w kodzie

| Element | Lokalizacja | Notatki |
|---------|-------------|---------|
| Kolory | `/constants/Colors.ts` ? | Do sprawdzenia |
| Typografia | | |
| Spacing | | |
| Komponenty | `/components/` ? | |

## Pytania do zbadania

- [ ] Jakie taby są w dolnej nawigacji?
- [ ] Czy jest dark mode?
- [ ] Jakie komponenty są współdzielone?
- [ ] Jak wygląda flow wizyty od początku do końca?

## Notatki

<!-- Dodaj tutaj własne obserwacje -->

