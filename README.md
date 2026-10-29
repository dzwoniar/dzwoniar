# Jakub Dzwoniarski

Projekty webowe, narzędzia do pracy z wideo i nauka programowania. W tych repozytoriach można zobaczyć zarówno niewielkie strony w HTML/CSS/JavaScript, jak i aplikacje z osobnym frontendem, API i workerami.

## Od czego zacząć

| Projekt | Co warto obejrzeć | Technologie |
| --- | --- | --- |
| [Astoka](https://github.com/dzwoniar/astoka) | Ingest wideo, transkrypcja i propozycje highlightów; MVP przed eksportem gotowych shortów | Next.js, TypeScript, FastAPI, Celery, PostgreSQL, Docker |
| [Mój Mały Wszechświat](https://github.com/dzwoniar/my-max-universe) | Gra z generowaniem planet, zbieraniem zasobów i lokalnym zapisem postępu | JavaScript, Canvas 2D, Web Audio |
| [Asteroids](https://github.com/dzwoniar/Asteroids-MANUAL-Game) | Ręcznie napisany projekt edukacyjny: pętla gry, sprite'y, kolizje i strzelanie | Python, Pygame |
| [Idea Wnętrz × Overflow](https://github.com/dzwoniar/demo-landing---overflow-x-ideawnetrz) | Landing page z kalkulatorem i ścieżką formularz → podziękowanie | React, TypeScript, Vite, Tailwind CSS |
| [Marsun — lead magnet v2](https://github.com/dzwoniar/marsun.pl-demo-lead-v2) | Formularz i ścieżka pozyskania kontaktu dla materiałów OZE | HTML, CSS, JavaScript |
| [WebFlyx](https://github.com/dzwoniar/webflyx) | Niewielkie repozytorium danych o filmach w Markdown i CSV | Markdown, CSV |

## Pozostałe prototypy stron

- **Usługi i B2B:** [WiseGroup](https://github.com/dzwoniar/wisegroup-demo), [ElektroManiacy](https://github.com/dzwoniar/demo-elektromaniacy.pl), [EKV Malinski](https://github.com/dzwoniar/EKVmalinski.de), [Puremax](https://github.com/dzwoniar/puremax), [JustinClean](https://github.com/dzwoniar/justinclean).
- **Marki lokalne i oferta produktowa:** [Papa Barber](https://github.com/dzwoniar/papa-barber), [Pełna Buła](https://github.com/dzwoniar/pelnabula), [Kinga Nails](https://github.com/dzwoniar/KINGANAILS), [KROY](https://github.com/dzwoniar/KROY), [LEVY Custom](https://github.com/dzwoniar/LEVY-CUSTOM).
- **Warianty koncepcji:** [LawTech v1](https://github.com/dzwoniar/v1-lawtech), [LawTech v2](https://github.com/dzwoniar/v2-lawtech), [Marsun — strona v1](https://github.com/dzwoniar/marsun.pl-demo), [strona v2](https://github.com/dzwoniar/marsun.pl-demo-v2), [lead magnet v1](https://github.com/dzwoniar/marsun.pl-lead).

Repozytoria opisane jako demo prezentują interfejs i interakcje. Zakres integracji formularzy, rezerwacji i płatności jest opisany w README danego projektu. Treści ofertowe w prototypach nie są pomiarami skuteczności wdrożenia.

## O tym repozytorium

To repozytorium pełni również rolę README profilu. Zawiera wcześniejszy prototyp strony **Darmowy Audyt Marketingu** w pliku [`index.html`](index.html).

### Lokalny podgląd strony

Wystarczy przeglądarka i Python 3 jako prosty serwer plików:

```sh
git clone https://github.com/dzwoniar/dzwoniar.git
cd dzwoniar
python -m http.server 8000 --bind 127.0.0.1
```

Otwórz [http://127.0.0.1:8000](http://127.0.0.1:8000). Jeśli Twój system używa nazwy `python3`, zamień nią `python`. Zatrzymanie serwera: `Ctrl+C`.

HTML, CSS i JavaScript znajdują się w `index.html`. Strona pobiera fonty DM Sans i Fraunces z Google Fonts. Skrypt obsługuje popup przy opuszczaniu strony, przepisanie e-maila do formularza, walidację i widok podziękowania.

Formularz zatrzymuje domyślną wysyłkę i zmienia jedynie widok DOM. Repozytorium nie zawiera odbiornika zgłoszeń, bazy danych ani analityki potwierdzającej przyjęcie zgłoszenia. Do sprawdzania interfejsu używaj danych testowych.
