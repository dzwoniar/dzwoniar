# Jakub Dzwoniarski

Buduję narzędzia do automatyzacji procesów, integracji API i pracy z danymi. Łączę problem biznesowy z implementacją, walidacją i testami.

**JavaScript / TypeScript · Node.js · Python**

**[Otwórz interaktywne demo portalu →](https://dzwoniar.github.io/portal-projektowy-demo/)** Zmień status zadania, przełącz widok klienta i sprawdź symulację powiadomienia. Bez konta i konfiguracji.

## Wybrane projekty

| Projekt | Co rozwiązuje | Co sprawdzić |
| --- | --- | --- |
| [Portal Projektowy Demo](https://github.com/dzwoniar/portal-projektowy-demo) | Wspólny plan pracy klienta i zespołu: zadania, komentarze, KPI i outbox | Adapter danych w pamięci, ograniczenia widoków, bezpieczne renderowanie DOM; 6 testów |
| [Faktury Cashflow](https://github.com/dzwoniar/faktury-cashflow) | Faktury i płatności CSV → rozrachunki, prognoza przepływów i dashboard HTML | Kwoty w groszach, daty, częściowe płatności, deterministyczność; 61 testów |
| [Raport Kliencki PL](https://github.com/dzwoniar/raport-kliencki-pl) | Meta Ads CSV i feedback klienta → KPI oraz raport decyzyjny HTML | Walidacja lejka, źródła danych i jawne N/A; 14 testów |
| [Lead Magnet Express](https://github.com/dzwoniar/lead-magnet-express) | Brief JSON + SVG → landing z opcjonalną integracją MailerLite | Generator, kontrakt formularza, walidacja i testy Workera na atrapach usług |

Każde z tych repozytoriów ma instrukcję uruchomienia, mapę kodu i CI. Przykłady korzystają z danych syntetycznych; zakres demonstracji opisuje README.

## Więcej kodu

- [Astoka](https://github.com/dzwoniar/astoka) — lokalny prototyp pipeline’u wideo: Next.js, FastAPI, Celery, PostgreSQL i MinIO; import, transkrypcja i propozycje highlightów.
- [AI Tech Tutor](https://github.com/dzwoniar/ai-tech-tutor) — lokalny transkrypt JSONL → instrukcja Markdown/HTML; parser, cykl sesji i testy offline.
- [Mój Mały Wszechświat](https://github.com/dzwoniar/my-max-universe) i [Asteroids](https://github.com/dzwoniar/Asteroids-MANUAL-Game) — gry w Canvas 2D oraz Pythonie/Pygame.

<details>
<summary>O repozytorium profilu i wcześniejszym landing page</summary>

To repozytorium wyświetla README profilu i zachowuje wcześniejszy prototyp „Darmowy Audyt Marketingu” w [index.html](index.html). HTML, CSS i JavaScript są w jednym pliku, a fonty pochodzą z Google Fonts. Formularz tylko waliduje dane i zmienia widok; nie ma odbiornika zgłoszeń.

```sh
git clone https://github.com/dzwoniar/dzwoniar.git
cd dzwoniar
python -m http.server 8000 --bind 127.0.0.1
```

Podgląd: [http://127.0.0.1:8000](http://127.0.0.1:8000). Używaj danych testowych.

</details>
