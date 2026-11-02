# Biblioteka groove'ów perkusyjnych black metalu

**Cel:** dobrać groove perkusyjny do sekcji utworu black metalowego i wczytać go do DAW jako plik MIDI.
**Zakres:** 20 groove'ów z katalogu [grooves.md](grooves.md), 80 plików MIDI w folderze `midi/`, 80 plików MusicXML w folderze `musicxml/` i zasady talerzy dla przejść między sekcjami. Plik nie obejmuje brzmienia perkusji ani miksu.
**Wymagania:** DAW (Digital Audio Workstation, program do nagrywania i aranżacji) z instrumentem perkusyjnym w mapie General MIDI. Tempo riffu musi być znane.
**Jak używać:** znajdź sekcję w tabeli sekcji, wybierz groove, a potem wykonaj kroki z sekcji o wczytaniu pliku MIDI.
**Gotowe, gdy:** groove gra w DAW w tempie riffu, a crash sekcji stoi na pierwszym takcie sekcji.

## Lista terminów

| Termin | Znaczenie |
|---|---|
| groove | Powtarzalny wzór perkusji, który niesie puls sekcji. |
| BM | Black metal. |
| blast beat | Bardzo szybki wzór, w którym werbel gra na każdą ósemkę albo częściej. |
| double kick | Gra stopą na dwóch pedałach ciągłymi szesnastkami. |
| talerz prowadzący | Jeden talerz, który odmierza czas w sekcji, np. hi-hat albo ride. |
| crash sekcji | Pojedyncze uderzenie crasha razem ze stopą na pierwszym takcie sekcji. |
| tempo odczuwalne | Tempo ćwierćnuty, które słuchacz odbiera jako puls. W metrum `6/8` i `12/8` to ćwierćnuta z kropką. |
| werbel na miarę | Średnia liczba uderzeń werbla na jedną odczuwalną miarę. |
| podgatunki | melodyczny (melodic), surowy (raw), norweski (Norwegian), symfoniczny (symphonic), dysonansowy (dissonant), atmosferyczny (atmospheric), blackgaze, DSBM (Depressive Suicidal Black Metal) i Mgła jako osobny styl zespołu. |

## Tabela sekcji wskazuje groove'y dla każdej części utworu

Każdy wiersz podaje groove'y typowe dla sekcji, poziom energii (skala `1–5`) i sposób użycia talerzy. Nazwa podgatunku w nawiasie oznacza, że groove występuje głównie w tym podgatunku.

| Sekcja | Groove'y | Energia | Talerze |
|---|---|---|---|
| Intro | [kick-pulse-wash](grooves.md#kick-pulse-wash); [tom-groove](grooves.md#tom-groove) (dysonansowy); [doom](grooves.md#doom) (dysonansowy, DSBM); [traditional-blast](grooves.md#traditional-blast) od razu w pełnym biegu (surowy, norweski); albo brak perkusji | 1–2 (5) | crash albo narastająca plama talerza do pierwszego taktu całego zespołu |
| Zwrotka | [backbeat](grooves.md#backbeat); [double-kick-backbeat](grooves.md#double-kick-backbeat); [half-time](grooves.md#half-time); [skank](grooves.md#skank) (melodyczny, surowy); [compound](grooves.md#compound) (melodyczny, symfoniczny); [traditional-blast](grooves.md#traditional-blast) (surowy, norweski, blackgaze) | 2–3 (5) | hi-hat albo ride, crash tylko na początku sekcji |
| Blok riffów (instrumentalny) | [traditional-blast](grooves.md#traditional-blast); [double-kick-backbeat](grooves.md#double-kick-backbeat) (Mgła); [double-kick-offbeat-snare](grooves.md#double-kick-offbeat-snare) (norweski); [double-kick-riff-snare](grooves.md#double-kick-riff-snare) (atmosferyczny); [snare-eighths](grooves.md#snare-eighths) (dysonansowy) | 4–5 | ride albo hi-hat zamieniony względem bloku z wokalem, crash na zmianach akordów |
| Refren | [backbeat](grooves.md#backbeat) albo [skank](grooves.md#skank) (melodyczny); [double-kick-backbeat](grooves.md#double-kick-backbeat) (symfoniczny, Mgła); [half-time-double-kick](grooves.md#half-time-double-kick) (blackgaze, Dark Funeral); [compound](grooves.md#compound) z crashem (melodyczny w `6/8`) | 3–4 | zmiana na ride |
| Most / przerywnik | brak perkusji; [half-time](grooves.md#half-time); [tom-groove](grooves.md#tom-groove); [kick-pulse-wash](grooves.md#kick-pulse-wash); [doom](grooves.md#doom) | 1–2 | oszczędnie: bez talerza, crash albo ride |
| Narastanie | [snare-every-beat](grooves.md#snare-every-beat); drabina [half-time](grooves.md#half-time) → [backbeat](grooves.md#backbeat) → [double-kick-backbeat](grooves.md#double-kick-backbeat); [kick-pulse-wash](grooves.md#kick-pulse-wash) przechodzący w blast beat | 2 → 4 | ride albo crash, gęstość crasha rośnie |
| Kulminacja / ściana | [traditional-blast](grooves.md#traditional-blast) po przerzedzeniu (symfoniczny); [half-time-double-kick](grooves.md#half-time-double-kick) z crashem (blackgaze); wolny [backbeat](grooves.md#backbeat) (symfoniczny); plateau [double-kick-backbeat](grooves.md#double-kick-backbeat) (Mgła) | 3–5 | crash albo china jako talerz prowadzący, akcentowane prowadzenie |
| Outro | [kick-pulse-wash](grooves.md#kick-pulse-wash); brak perkusji (DSBM); koda [traditional-blast](grooves.md#traditional-blast) (norweski); [doom](grooves.md#doom) | 1–2 (5) | plama ride'a albo crasha, ostatni crash i wybrzmienie |
| Wstawka (1–4 takty wewnątrz riffu) | [bomb-blast](grooves.md#bomb-blast); [blast-fragment](grooves.md#blast-fragment) | 5 | crash na pierwszym takcie blast beatu |
| Rzadkie / do unikania | [d-beat](grooves.md#d-beat) (rzadki); [hammer-blast](grooves.md#hammer-blast) (skonstruowany, brak użycia w tabulaturach BM); [sextuple-blast](grooves.md#sextuple-blast) (0 taktów w tabulaturach); [gallop](grooves.md#gallop) (lista do unikania) | — | — |

## Werbel na miarę wyznacza poziom energii

Poziom energii zależy przede wszystkim od liczby uderzeń werbla na odczuwalną miarę. Stopa podnosi intensywność tylko w obrębie jednego poziomu.

| Werbel na miarę | Poziom energii |
|---|---|
| `0` | 1 |
| `0.25` | 2 |
| `0.5` | 3 |
| `0.75–1.75` | 4 |
| `2` i więcej | 5 |

Groove bez stopy, groove na tomach i rzadki groove punkowy (snare-eighths, tom-groove, d-beat) stoją o jeden poziom niżej, niż wynika z tabeli.

## Zasady talerzy mówią, gdzie dodać crash sekcji

Pliki MIDI i MusicXML nie zawierają crasha sekcji, bo jego miejsce zależy od formy utworu. Dodaj go według tych zasad:

- **Jeden talerz prowadzący na sekcję.** Zmień go na granicy sekcji. Tak dzieje się na 63% granic sekcji w tabulaturach.
- Uderz crash razem ze stopą na pierwszym takcie sekcji. Nie uderzaj go na każdą pierwszą miarę groove'u.
- Nie łącz crasha i hi-hatu w jednym uderzeniu.
- Traktuj chinę i splash jako kolor. Nie używaj ich jako talerza prowadzącego.
- Wyjątek: w ścianie albo kulminacji użyj chiny albo splasha jako talerza prowadzącego. Służą do tego warianty `china` i `splash`.
- Używaj akcentowanego prowadzenia na crashu tylko w ścianie albo kulminacji. Udział w czasie utworów: blackgaze 19%, dysonansowy 14%, norweski, surowy i atmosferyczny najwyżej 2%.

## Jak wczytać groove do DAW

Każdy groove ma w katalogu tabelę pól, siatkę i linki do plików MIDI. Pliki mają nazwy `midi/<forma>_<wariant>.mid`, gdzie forma to wzór siatki, a wariant to talerz prowadzący.

1. Znajdź sekcję utworu w tabeli sekcji. Wynik: lista pasujących groove'ów.
2. Otwórz wybrany groove w [grooves.md](grooves.md). Wynik: tabela pól, siatka i linki MIDI.
3. Wybierz wariant talerza zgodny z kolumną „Talerze” tabeli sekcji.
4. Przeciągnij plik `.mid` na ścieżkę perkusji w DAW. Plik używa kanału MIDI `10` i mapy General MIDI.
5. Ustaw tempo DAW na tempo riffu. Tempo zapisane w pliku to tempo ćwierćnuty w `BPM` i służy tylko jako punkt wyjścia.
6. Zapętl plik. Każdy plik trwa 4 takty.
7. Dodaj crash sekcji na pierwszym takcie sekcji według zasad talerzy.

Sprawdzenie: groove gra w tempie riffu, a crash sekcji pada razem ze stopą tylko na pierwszym takcie sekcji.

## Stan

- Zrobione: katalog 20 groove'ów, 80 plików MIDI i 80 plików MusicXML.
- Następny krok: wybierz groove dla pierwszej sekcji utworu w tabeli sekcji.
- Powrót po przerwie: otwórz tabelę sekcji i znajdź sekcję, na której skończyłeś.
