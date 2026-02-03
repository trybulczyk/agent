# Struktura Aplikacji

Mapowanie struktury projektu iOS z Xcode.

> Uzupełnij tę sekcję na podstawie struktury folderów w Xcode

## Drzewo projektu

```
/NazwaAplikacji
├── /App
│   ├── AppDelegate.swift
│   └── SceneDelegate.swift
├── /Views                    # <- Uzupełnij
│   ├── /Components
│   └── /Screens
├── /Models
├── /ViewModels
├── /Services
├── /Resources
│   ├── Assets.xcassets
│   └── /Fonts
└── /Supporting Files
```

## Moduły / Features

| Moduł | Ścieżka w Xcode | Opis | Status |
|-------|-----------------|------|--------|
| Auth | `/Views/Auth/` | Logowanie, rejestracja | [ ] |
| Home | `/Views/Home/` | Ekran główny | [ ] |
| Profile | `/Views/Profile/` | Profil użytkownika | [ ] |
| Settings | `/Views/Settings/` | Ustawienia | [ ] |

## Technologie UI

- [ ] UIKit
- [ ] SwiftUI
- [ ] Mix (UIKit + SwiftUI)

## Design System w kodzie

| Element | Lokalizacja | Notatki |
|---------|-------------|---------|
| Kolory | `Assets.xcassets/Colors` | |
| Typografia | `/Resources/Fonts/` | |
| Ikony | `Assets.xcassets/Icons` | |
| Spacing/Layout | | |

## Notatki

<!-- Dodaj tutaj własne obserwacje o strukturze -->
