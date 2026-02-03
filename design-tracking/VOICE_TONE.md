# Voice & Tone - Komunikacja ze Specjalistami uPacjenta

Wytyczne dotyczące języka i tonu komunikacji w aplikacji Nurse App dla specjalistów uPacjenta.pl.

---

## Profil odbiorcy

| Aspekt | Charakterystyka |
|--------|-----------------|
| **Kim są** | Pielęgniarki, położne, ratownicy medyczni, analitycy medyczni |
| **Wiek** | 25-50 lat (głównie 28-40) |
| **Wykształcenie** | Wyższe kierunkowe, prawo wykonywania zawodu |
| **Kontekst pracy** | Mobilni, praca w terenie, pod presją czasu |
| **Relacja z firmą** | B2B/zlecenie - partnerska, nie podwładna |
| **Wartości** | Profesjonalizm, autonomia, empatia, jakość |

---

## Zasada główna

> **Zwracaj się jak do kompetentnego partnera, nie jak do pracownika.**

Specjaliści uPacjenta to wykwalifikowani profesjonaliści medyczni, którzy cenią swoją autonomię i niezależność. Aplikacja jest ich narzędziem pracy - ma pomagać, nie pouczać.

---

## Formy zwracania się

### Rekomendowane: **"Ty" (2 os. l.poj.)**

| Kontekst | Przykład |
|----------|----------|
| Przyciski akcji | "Rozpocznij wizytę", "Zapisz", "Dodaj" |
| Komunikaty | "Twoja wizyta została zapisana" |
| Instrukcje | "Wybierz typ blokady" |
| Błędy | "Sprawdź połączenie internetowe" |
| Puste stany | "Nie masz nadchodzących wizyt" |

### Unikaj

| Forma | Dlaczego unikać |
|-------|-----------------|
| "Pan/Pani" | Zbyt formalne, dystans |
| "Państwo" | Bezosobowe, korporacyjne |
| "Użytkownik" | Techniczne, zimne |
| Formy bezosobowe | "Należy wypełnić..." - zbyt urzędowe |

### Wyjątki - formy bezosobowe dopuszczalne

- Komunikaty systemowe: "Sesja wygasła"
- Nazwy sekcji: "Szczegóły wizyty"
- Etykiety pól: "Adres e-mail"

---

## Ton komunikacji

### Skala tonu

```
Formalny ←――――●―――――→ Swobodny
              ↑
         Tu jesteśmy
    (profesjonalnie przyjazny)
```

### Cechy tonu

| Cecha | Opis | Przykład ✓ | Przykład ✗ |
|-------|------|------------|------------|
| **Bezpośredni** | Bez owijania w bawełnę | "Rozpocznij wizytę" | "Czy chciałbyś teraz rozpocząć wizytę?" |
| **Rzeczowy** | Konkret, bez zbędnych słów | "Wizyta zakończona" | "Gratulacje! Wizyta została pomyślnie zakończona!" |
| **Pomocny** | Wskazuje rozwiązanie | "Sprawdź PESEL i spróbuj ponownie" | "Błąd walidacji PESEL" |
| **Szanujący czas** | Krótko i na temat | "Brak wizyt" | "Aktualnie nie posiadasz żadnych wizyt w systemie" |
| **Partnerski** | Bez pouczania | "Pamiętaj o rejestracji" | "Musisz zarejestrować badania!" |

---

## Słownictwo

### Preferowane terminy

| Używaj | Zamiast | Powód |
|--------|---------|-------|
| Specjalista | Pielęgniarka/pracownik | Neutralne, szacunek |
| Wizyta | Zlecenie/zamówienie | Medyczny kontekst |
| Pacjent | Klient | Medyczna relacja |
| Grafik | Harmonogram | Potoczne, krótsze |
| Dostępność | Slot czasowy | Polski termin |
| Badania | Produkty | Medyczny kontekst |
| Pakiet | Zestaw | Spójność z ofertą |
| Pobranie | Wizyta pobraniowa | Krótsze |

### Terminy branżowe - zachowaj

Specjaliści znają i oczekują terminologii medycznej:

- PESEL, numer PWZ
- Probówka, materiał
- Rejestracja laboratoryjna
- Kod zlecenia
- Akcja zdrowia (termin uPacjenta)

### Unikaj żargonu technicznego

| Unikaj | Użyj |
|--------|------|
| Token wygasł | Zaloguj się ponownie |
| Błąd synchronizacji | Nie udało się zapisać. Sprawdź internet |
| Timeout | Zbyt długi czas oczekiwania |
| Cache | Odśwież dane |

---

## Wzorce komunikatów

### Przyciski i akcje

```
Format: [Czasownik] + [opcjonalnie: co]

✓ "Rozpocznij wizytę"
✓ "Zakończ"
✓ "Dodaj pacjenta"
✓ "Zapisz"
✓ "Anuluj"

✗ "Kliknij tutaj aby rozpocząć"
✗ "Naciśnij przycisk zapisu"
```

### Komunikaty sukcesu

```
Format: [Co] + [zostało zrobione]

✓ "Wizyta zakończona"
✓ "Grafik zapisany"
✓ "Pacjent dodany do wizyty"
✓ "Dane zaktualizowane"

✗ "Operacja zakończona sukcesem!"
✗ "Świetnie! Udało się!"
```

### Komunikaty błędów

```
Format: [Co się stało] + [Co zrobić]

✓ "Nie udało się zapisać. Sprawdź połączenie i spróbuj ponownie"
✓ "Nieprawidłowy PESEL. Sprawdź i popraw dane"
✓ "Sesja wygasła. Zaloguj się ponownie"

✗ "Błąd 500"
✗ "Coś poszło nie tak"
✗ "Wystąpił nieoczekiwany błąd"
```

### Puste stany

```
Format: [Stan] + [opcjonalnie: co można zrobić]

✓ "Brak nadchodzących wizyt"
✓ "Nie masz jeszcze ocen"
✓ "Historia jest pusta"

✗ "Ups! Nic tu nie ma!"
✗ "Wygląda na to, że nie masz żadnych wizyt w tym momencie"
```

### Potwierdzenia i pytania

```
Format: [Pytanie]? + [Opcje]

✓ "Zakończyć wizytę?"
   [Anuluj] [Zakończ]

✓ "Usunąć blokadę?"
   [Nie] [Tak, usuń]

✗ "Czy na pewno chcesz zakończyć tę wizytę? Ta operacja jest nieodwracalna."
```

---

## Kontekstowe dostosowanie tonu

### Sytuacje stresowe (błędy, problemy)

**Ton:** Spokojny, pomocny, bez dramatyzowania

```
✓ "Nie udało się połączyć z laboratorium. Spróbuj za chwilę"
✓ "Brak zasięgu. Dane zapiszą się gdy wrócisz online"

✗ "UWAGA! Krytyczny błąd połączenia!"
✗ "Niestety wystąpił problem i nie możemy kontynuować"
```

### Sytuacje czasochłonne (ładowanie, oczekiwanie)

**Ton:** Neutralny, informacyjny

```
✓ "Zapisywanie..."
✓ "Ładowanie wizyt"
✓ "Synchronizacja danych"

✗ "Proszę czekać, trwa przetwarzanie Twojego żądania..."
✗ "Jeszcze chwilka!"
```

### Potwierdzenia ważnych akcji

**Ton:** Jasny, bez zbędnych emocji

```
✓ "Wizyta zostanie oznaczona jako nieudana. Kontynuować?"
✓ "Blokada zostanie usunięta z grafiku"

✗ "Uwaga! Ta akcja jest nieodwracalna! Czy na pewno chcesz kontynuować?"
```

---

## Benchmarki z branży

### uPacjenta - ton rekrutacyjny

Na podstawie komunikacji uPacjenta w rekrutacji:

| Element | Obserwacja |
|---------|------------|
| Forma | "Ty" - "Dołącz do nas", "Twoja praca" |
| Ton | Przyjazny, partnerski |
| Wartości | Komfort, elastyczność, wsparcie zespołu |
| Język | Polski bez anglicyzmów, prosty |

**Cytaty z materiałów uPacjenta:**
> "Praca dla uPacjenta wygląda zupełnie inaczej niż w szpitalu"
> "Komfort czasowy - 1 wizyta na godzinę"
> "Elastyczne godziny pracy ustalane samodzielnie"

### Healthcare UX Writing - dobre praktyki

| Zasada | Zastosowanie |
|--------|--------------|
| **Precyzja** | Każda informacja musi być jednoznaczna |
| **Bezpieczeństwo** | Komunikuj jak chronisz dane |
| **Empatia** | Rozpoznawaj presję i stres użytkownika |
| **Dostępność** | Teksty zrozumiałe dla różnych poziomów |

### Polskie aplikacje medyczne - wzorce

| Aplikacja | Ton | Uwagi |
|-----------|-----|-------|
| Terminarz NURSEUM | Rzeczowy, funkcjonalny | Skupienie na zadaniach |
| MEDchart | Profesjonalny | Terminologia medyczna |
| Gabinet drWidget | Przyjazny | Balans formalność/prostota |

---

## Przykłady ekranowe

### Ekran: Lista wizyt

```
Nagłówek: "Nadchodzące wizyty"

Stan pusty: "Brak nadchodzących wizyt"

Karta wizyty:
- "ul. Marszałkowska 10, Warszawa"
- "08:00 - 09:00"
- [Przejdź do wizyty]
```

### Ekran: Szczegóły wizyty

```
Nagłówek: "Szczegóły wizyty"

Sekcje:
- "Dane pacjenta"
- "Badania"
- "Płatność"

Akcje:
- [Rozpocznij wizytę]
- [Zgłoś problem]
```

### Ekran: Kalendarz

```
Nagłówek: "Twój grafik"

Popup dodawania:
- "Typ: Dostępny / Zajęty"
- "Godziny: od - do"
- "Powód blokady" (dla typu Zajęty)

Akcje:
- [Anuluj] [Zapisz]

Sukces: "Grafik zaktualizowany"
```

### Ekran: Błąd połączenia

```
Ikona: [WiFi przekreślone]

Komunikat: "Brak połączenia z internetem"

Podkomunikat: "Sprawdź zasięg i spróbuj ponownie"

Akcja: [Spróbuj ponownie]
```

---

## Checklist dla copywritera

### Przed napisaniem tekstu

- [ ] Czy znam kontekst użycia (gdzie, kiedy, w jakim stanie)?
- [ ] Czy użytkownik jest pod presją czasu?
- [ ] Czy to sytuacja stresowa (błąd, problem)?

### Podczas pisania

- [ ] Czy używam formy "Ty"?
- [ ] Czy tekst jest maksymalnie krótki?
- [ ] Czy wskazuję rozwiązanie (przy błędach)?
- [ ] Czy unikam żargonu technicznego?
- [ ] Czy ton jest partnerski, nie pouczający?

### Po napisaniu

- [ ] Czy mogę usunąć jakieś słowa bez utraty sensu?
- [ ] Czy tekst brzmi naturalnie przeczytany na głos?
- [ ] Czy pasuje do tonu reszty aplikacji?

---

## Antywzorce - czego unikać

### Nadmierna grzeczność

```
✗ "Dziękujemy za skorzystanie z naszej aplikacji!"
✗ "Proszę bardzo, oto Twoje wizyty"
✗ "Czy moglibyśmy prosić o uzupełnienie danych?"
```

### Korpomowa

```
✗ "W celu optymalizacji procesu..."
✗ "Zgodnie z procedurą należy..."
✗ "System wymaga uzupełnienia pól obligatoryjnych"
```

### Infantylizacja

```
✗ "Ups! Coś poszło nie tak!"
✗ "Świetna robota! 🎉"
✗ "Jeszcze tylko jeden krok i gotowe!"
```

### Dramatyzowanie

```
✗ "UWAGA! Krytyczny błąd!"
✗ "Niestety nie możemy kontynuować..."
✗ "Przepraszamy za niedogodności"
```

### Zbędne słowa

```
✗ "Kliknij przycisk poniżej aby kontynuować"
   → "Kontynuuj"

✗ "Twoja wizyta została pomyślnie zakończona"
   → "Wizyta zakończona"

✗ "Aktualnie nie posiadasz żadnych nadchodzących wizyt"
   → "Brak nadchodzących wizyt"
```

---

## Słownik aplikacji

| Termin PL | Kontekst | Uwagi |
|-----------|----------|-------|
| Specjalista | Użytkownik aplikacji | Neutralne, szacunek dla wszystkich zawodów |
| Wizyta | Pojedyncze zlecenie | Podstawowa jednostka pracy |
| Akcja zdrowia | Wizyta grupowa B2B | Termin uPacjenta |
| Grafik | Kalendarz dostępności | Potoczne, zrozumiałe |
| Pobranie | Wizyta z pobraniem krwi | Skrót branżowy |
| Rejestracja | Przypisanie do laboratorium | Proces laboratoryjny |
| Blokada | Niedostępność w grafiku | Czas zarezerwowany |
| Strefa | Obszar dojazdu | Geografia pracy |

---

## Źródła i benchmarki

- [uPacjenta - Rekrutacja](https://upacjenta.pl/rekrutacja) - ton komunikacji firmowej
- [uPacjenta PRO - Google Play](https://play.google.com/store/apps/details?id=pl.upacjenta.nurses) - opis aplikacji
- [Healthcare UX Writing - Dobra Treść](https://dobratresc.com/2024/09/04/healthcare-ux-writing/) - wytyczne branżowe
- [UX Writing - Semcore](https://semcore.pl/ux-writing-poradnik/) - polskie standardy
- [Warszawska OIPiP - oferta uPacjenta](https://woipip.pl/nasze-oferty-pracy/upacjenta-4/) - komunikacja branżowa

---

## Powiązane dokumenty

| Dokument | Opis |
|----------|------|
| [PERSONA.md](./PERSONA.md) | Profil użytkownika |
| [SCREENS.md](./SCREENS.md) | Inwentarz ekranów |
| [FLOWS.md](./FLOWS.md) | Przepływy użytkownika |

---

*Ostatnia aktualizacja: 2026-02-03*
