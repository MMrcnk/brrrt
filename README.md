# BRRRT — A-10 nad pustynią

Gra przeglądarkowa w stylu Smashy Road: latasz A-10 Thunderbolt II nad dużą pustynią i niszczysz czołgi T-55.

## Sterowanie

| Telefon | Klawiatura | Akcja |
|---|---|---|
| Joystick (lewa połowa ekranu) | Strzałki / WASD | Kierunek lotu |
| Duży przycisk (prawy dół) | Spacja | Ogień (przytrzymaj) |
| ZMIEŃ | Q / E | Minigun GAU-8 ↔ rakiety Hydra 70 |
| Pauza | P | Pauza |

## Zasady

- 100 pkt za każdy zniszczony T-55
- kolejne zniszczenia w ciągu 4 s → combo do x5
- rekord zapisuje się lokalnie w przeglądarce

## Uruchomienie

Jeden plik `index.html`, bez zależności i bez budowania.

- lokalnie: otwórz `index.html` w przeglądarce
- GitHub Pages: Settings → Pages → Source: `main` / root

Na iPhonie: Safari → Udostępnij → „Do ekranu początkowego”, gra uruchomi się na pełnym ekranie.

## Struktura kodu (`index.html`)

- **Generowanie świata** — góry, oazy, wydmy, drogi, kaktusy (ziarno losowe stałe → ta sama mapa)
- **Kawałki terenu** — teren renderowany do kafli 512×512 i cache'owany
- **Czołgi** — AI jazdy, wieża śledzi samolot, pasek życia, wybuch
- **Broń** — CCIP (celownik na ziemi), pociski, rakiety
- **Dźwięk** — Web Audio, syntezowany (bez plików audio)
