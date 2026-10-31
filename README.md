# Jakub Dzwoniarski

Buduję narzędzia do automatyzacji procesów, integracji API i pracy z danymi. W projektach łączę problem biznesowy z implementacją, walidacją wejścia, testami i dokumentacją techniczną.

Pracuję z JavaScriptem/TypeScriptem, Node.js i Pythonem. Poniżej są wybrane projekty, które można uruchomić lokalnie i sprawdzić na syntetycznych danych.

## Projekty na początek

| Projekt | Problem i implementacja | Co sprawdzić w kodzie |
| --- | --- | --- |
| [Faktury i cashflow](https://github.com/dzwoniar/faktury-cashflow) | CSV z fakturami i płatnościami → stan rozrachunków, scenariusze przepływów i samodzielny dashboard HTML | Kwoty w groszach, daty, częściowe płatności, deterministyczność; 61 testów |
| [Raport Kliencki PL](https://github.com/dzwoniar/raport-kliencki-pl) | Dane Meta Ads i feedback klienta → KPI oraz memo decyzyjne HTML | Walidacja lejka, rozdzielenie danych platformy i deklaracji, jawne N/A; 14 testów |
| [Lead Magnet Express](https://github.com/dzwoniar/lead-magnet-express) | Brief JSON + SVG → landing; opcjonalny Worker integrujący formularz z MailerLite | Konfiguracja poza kodem, walidacja, zgoda, honeypot, obsługa błędów i testy z atrapami |
| [AI Tech Tutor](https://github.com/dzwoniar/ai-tech-tutor) | Transkrypt lokalnej sesji pomocy → instrukcja Markdown/HTML z krokami i obrazami | Cykl życia sesji, parser JSONL, generator, indeks i sześć testów offline |

Te cztery repozytoria mają instrukcje uruchomienia, przykłady oraz CI. Przykłady są syntetyczne; status prototypu i ograniczenia są opisane w każdym README. Klucze usług oraz rzeczywiste dane operacyjne pozostają poza repozytoriami.

## Inne obszary

- [Astoka](https://github.com/dzwoniar/astoka) — prototyp pipeline’u wideo: Next.js, FastAPI, Celery, PostgreSQL, MinIO, transkrypcja i propozycje highlightów. Eksport gotowych shortów pozostaje etapem rozwoju.
- [Mój Mały Wszechświat](https://github.com/dzwoniar/my-max-universe) — gra w Canvas 2D: generowanie planet, zasoby, walka, Web Audio i lokalny zapis postępu.
- [Asteroids](https://github.com/dzwoniar/Asteroids-MANUAL-Game) — projekt edukacyjny w Pythonie i Pygame: sprite’y, pętla gry, kolizje i strzelanie.
- [Idea Wnętrz × Overflow](https://github.com/dzwoniar/demo-landing---overflow-x-ideawnetrz) — prototyp React/TypeScript z kalkulatorem i ścieżką formularza.

Pozostałe landing pages dokumentują eksperymenty z interfejsem i ścieżkami konwersji. Ich README wskazują, które formularze i integracje są symulowane.

## Jak przeglądać

Zacznij od README wybranego projektu, uruchom testy i syntetyczny przykład, a następnie przejdź do modułów wskazanych w mapie kodu. Najwięcej moich decyzji technicznych widać w walidacji danych, obsłudze braków informacji i granicach integracji.

## O tym repozytorium

Repozytorium pełni rolę README profilu i zachowuje wcześniejszy prototyp strony „Darmowy Audyt Marketingu” w [index.html](index.html). HTML, CSS i JavaScript są w jednym pliku, a fonty pochodzą z Google Fonts.

```sh
git clone https://github.com/dzwoniar/dzwoniar.git
cd dzwoniar
python -m http.server 8000 --bind 127.0.0.1
```

Podgląd: [http://127.0.0.1:8000](http://127.0.0.1:8000). Formularz tej historycznej strony tylko waliduje dane i zmienia widok; nie ma odbiornika zgłoszeń. Do sprawdzania używaj danych testowych.
