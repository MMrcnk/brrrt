# brrrt

Gra 3D w przeglądarce w stylu Smashy Road: latasz A-10 Thunderbolt II nad pustynią (wydmy, góry, oazy) i niszczysz czołgi T-55. Silnik: three.js r128 (CDN).

## Sterowanie

| Telefon | Klawiatura | Akcja |
|---|---|---|
| Joystick (lewa połowa ekranu) | Strzałki / WASD | Kierunek lotu |
| Duży przycisk (prawy dół) | Spacja | Ogień (przytrzymaj) |
| ZMIEŃ | Q / E | Minigun GAU-8 ↔ rakiety Hydra 70 |
| Pauza | P | Pauza |
| Joystick do końca | — | Przyspieszenie |
| Joystick w przeciwną stronę | — | Przewrót (Immelmann) i lot w nową stronę |

## Zasady

- 100 pkt za każdy zniszczony T-55
- kolejne zniszczenia w ciągu 4 s → combo do x5
- rekord zapisuje się lokalnie w przeglądarce

## Uruchomienie

Jeden plik `index.html`, bez budowania. three.js ładuje się z cdnjs.

- lokalnie: otwórz `index.html` w przeglądarce
- GitHub Pages: Settings → Pages → Source: `main` / root

Na iPhonie: Safari → Udostępnij → „Do ekranu początkowego”, gra uruchomi się na pełnym ekranie.

## Struktura kodu (`index.html`)

- **Generowanie świata** — góry, oazy, wydmy, drogi, kaktusy (ziarno losowe stałe → ta sama mapa)
- **Teren 3D** — low-poly kafle 60×60 generowane wokół gracza; samolot wznosi się nad wydmami i górami
- **Czołgi** — AI jazdy, wieża śledzi samolot, pasek życia, wybuch
- **Broń** — CCIP (celownik na ziemi), pociski, rakiety
- **Dźwięk** — Web Audio, syntezowany (bez plików audio)

Gra działa tylko w poziomie.
