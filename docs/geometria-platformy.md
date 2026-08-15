# Geometria platformy – Polonez Transformer

## Cel

Dedykowane podwozie nośne zaprojektowane od zera pod:
- zmienną konfigurację nadwozia (Auto-Transform),
- modularność,
- serwisowalność,
- niskokosztową budowę (rury + spawanie + drukowane elementy pomocnicze).

---

## Założenia wymiarowe (wstępne, do iteracji)

| Parametr                    | Wartość orientacyjna     | Uwagi |
|----------------------------|--------------------------|-------|
| Rozstaw osi                | 2550–2700 mm            | Blisko klasycznego Poloneza, z możliwością wersji dłuższej |
| Szerokość toru             | 1450–1550 mm            | Szerszy niż oryginał dla stabilności |
| Prześwit (konfiguracja niska) | 160–190 mm            | |
| Wysokość platformy do podłogi | ~350–400 mm          | |
| Długość całkowita platformy | ~3900–4200 mm         | |

---

## Architektura spaceframe

### Główne elementy

1. **Dwa podłużne progi nośne** (dolne)
   - Profil prostokątny lub rura o przekroju zapewniającym sztywność na zginanie i skręcanie
   - Preferowane: stal 40×60 / 50×50 / 40×80 mm (grubość 2–3 mm) lub odpowiedniki ze złomu

2. **Poprzeczki**
   - Przednia (strefa silnika / power packu)
   - Środkowe (podłoga + mocowania baterii)
   - Tylna (most / zawieszenie + strefa transformacji)

3. **Górna rama / klatka**
   - Punkty mocowania segmentów dachu
   - Prowadnice i gniazda siłowników
   - Słupki B i C jako elementy nośne i prowadzące

4. **Strefa baterii**
   - Centralna, niska, modularna
   - Kasety wsuwane z boku lub od góry
   - Oddzielona od strefy transformacji mechanicznej

5. **Strefa power packu**
   - Przód lub centralnie (do decyzji)
   - Łatwy demontaż całego bloku

---

## Punkty krytyczne pod Auto-Transform

- Słupki i prowadnice dachu muszą przenosić siły zarówno w pozycji dolnej, jak i górnej.
- Blokady mechaniczne dachu powinny wchodzić w gniazda będące częścią spaceframe (nie tylko w panele).
- Tylna część ramy musi pozwalać na otwarcie konfiguracji Truck bez utraty sztywności skrętnej (dodatkowe krzyżulce lub aktywowane wzmocnienia).

---

## Materiały i metoda budowy

- **Główna struktura:** spawana stal (MIG), profile ze złomu lub hurtowni
- **Elementy pomocnicze, jigs, dystanse, osłony:** druk 3D
- **Możliwość wersji skręcanej** (na śrubach wysokiej wytrzymałości) dla osób bez spawarki – wolniejsza, ale dostępna

---

## Następny krok geometryczny

1. Dokładny rysunek 2D podłużnic + poprzeczek
2. Definicja punktów mocowania siłowników dachu
3. Definicja interfejsu kaset baterii
4. Prosty model 3D w FreeCAD (do wrzucenia później do `/cad`)
