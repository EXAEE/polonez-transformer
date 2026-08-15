# Mechanizm dachu segmentowego – Auto-Transform

## Cel

Jeden z kluczowych elementów transformacji: dach, który z pozycji niskiej (Classic) przechodzi w pozycję podwyższoną (High/Cargo) w sposób kontrolowany, bezpieczny i odwracalny.

---

## Koncepcja mechaniczna (Warstwa 1 – realna)

### Segmenty

- **Segment A** (przedni, nad kabiną) – może być stały lub lekko ruchomy
- **Segment B** (środkowy)
- **Segment C** (tylny)

W najprostszej wersji wystarczą **dwa ruchome segmenty** (B + C).

### Ruch

Każdy ruchomy segment:
- porusza się po prowadnicach (szyny / rolki / tuleje),
- jest podnoszony przez siłownik liniowy (elektryczny preferowany),
- w pozycji końcowej wchodzi w **mechaniczną blokadę** (nie polega tylko na siłowniku).

### Siłowniki

- Typ: liniowe 12/24 V lub 48 V (z integracją z systemem EV)
- Skok: zależny od wysokości podniesienia (cel: +350–500 mm)
- Siła: dobrana z zapasem do masy segmentu + wiatru + śniegu
- Redundancja: minimum 2 siłowniki na segment lub jeden + sprężyny wspomagające

### Prowadnice

- Sztywne szyny montowane do spaceframe (słupki B/C i górna rama)
- Rolki lub ślizgi z możliwością regulacji
- 3D printed tuleje / prowadniki jako elementy zużywalne i łatwe do wymiany

### Blokady

Krytyczne dla bezpieczeństwa:
- Mechaniczne rygle / sworznie wsuwane w gniazda spaceframe
- Aktywowane sprężyną + odblokowywane siłownikiem lub ręcznie
- Czujnik krańcowy potwierdzający zablokowanie
- Jazda dozwolona **tylko** przy potwierdzonych blokadach

---

## Sekwencja podnoszenia (High)

1. Odblokowanie rygli pozycji dolnej
2. Uruchomienie siłowników – równomierne podnoszenie
3. Dojście do pozycji górnej
4. Wsuniecie rygli pozycji górnej
5. Potwierdzenie czujników → gotowość do jazdy

Opuszczanie – sekwencja odwrotna + kontrola prędkości (nie wolno „spadać”).

---

## Uszczelnienie i hałas

- Uszczelki wielowarstwowe na krawędziach segmentów
- Labiryntowe styki + docisk w pozycji dolnej
- W pozycji górnej: dodatkowe fartuchy / plandeki boczne (opcjonalne, jak w kamperach)

---

## Awaryjne procedury

- Ręczne spuszczanie ciśnienia / odblokowanie siłowników
- Mechaniczna korba lub pompa ręczna jako backup
- Możliwość demontażu segmentu w warunkach serwisowych

---

## Materiały segmentów dachu

- Rama segmentu: lekka stal / aluminium / kompozyt
- Poszycie: laminat, blacha, lub duże elementy drukowane + wzmocnienia
- Izolacja termiczna i akustyczna w środku

---

## Prototypowanie (rekomendowana ścieżka)

1. Makieta 1:1 jednego segmentu na prostej ramie
2. Test siłowników + prowadnic + blokad bez poszycia
3. Dodanie uszczelnień i pomiar sztywności
4. Integracja z spaceframe
5. Dopiero potem pełna sekwencja i jazda próbna

---

To jest mechanizm, który da się zbudować, przetestować i utrzymać w duchu projektu. Pełny „Transformer” budujemy na tym fundamencie, a nie odwrotnie.
