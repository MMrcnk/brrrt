# brrrt

Gra 3D w przeglądarce w stylu Smashy Road: A-10C Thunderbolt II nad bliskowschodnią pustynią. Silnik: three.js r128 (CDN). Tylko w poziomie.

## Misja — poziom 1

Zniszcz wszystkie ważne punkty: stanowiska SAM (■), baterie artylerii (●) i sztab (★). Licznik CELE u góry ekranu, czerwone znaczniki przy krawędzi pokazują kierunek.

Dodatkowo: 10 strażnic przy drogach (worki z piaskiem, 2 jeepy, czasem czołg) — opcjonalne cele. Seria zniszczeń x2, x3… gdy kolejny wróg padnie w ciągu 4 s. Budynki w osadach można zburzyć, a drogi zbombardować (jeepy zawracają przed lejem). Start w losowym miejscu strefy neutralnej.

## Strefy

| Strefa | Gdzie | Wrogowie |
|---|---|---|
| Neutralna | pustynia między regionami: pola naftowe, ruiny, obozy Beduinów, wraki | sporadycznie czołg lub jeep |
| Wroga | 4 regiony z miastem, wioskami, rafinerią, SAM i artylerią (oddalone o 1000+ m) | więcej czołgów i jeepów, garnizony |
| Wojenna | do 480 m od sztabu (pas 480–820 m to strefa wroga) | najwięcej wrogów, grupy czołgów |

Drogi tworzą sieć: autostrady między miastami i sztabem, drogi gruntowe do wiosek, rafinerii i pól naftowych, ze skrzyżowaniami.

Zbiorniki i odwierty na polach naftowych i w rafineriach wybuchają po trafieniu rakietą i ranią wrogów w pobliżu (reakcja łańcuchowa).

## Sterowanie

| Telefon | Klawiatura | Akcja |
|---|---|---|
| Joystick góra / dół | W / S, ↑ / ↓ | Wznoszenie / opadanie (pułap 180 m) |
| Joystick lewo / prawo | A / D, ← / → | Skręt |
| Strzałka ▲ | Shift | Dopalacz |
| Strzałka ▼ | X / Ctrl | Hamowanie |
| Duży przycisk | Spacja | Ogień |
| ZMIEŃ | Q / E | Minigun → Hydra → Maverick |
| FLARY | F | Wyrzut flar — gubią rakiety SAM |
| Pauza | P | Pauza |

## Zrzuty

| Dym | Zawartość |
|---|---|
| Zielony | 8 × AGM-65 Maverick (naprowadzane, stożek 90°) |
| Czerwony | Naprawa: +60 kadłuba (A-10 ma 160) |

## Uruchomienie

Jeden plik `index.html`, bez budowania. GitHub Pages: Settings → Pages → `main` / root.

## Celowanie
Celownik na środku ekranu — minigun i Hydry lecą tam, gdzie wskazuje. Im bliżej cel, tym mniejszy rozrzut. Celownik czerwienieje nad wrogiem.
