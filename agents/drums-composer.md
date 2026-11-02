# Kompozytor perkusji black metalowej

**Cel:** napisać partię perkusji dla fragmentu utworu black metalowego wskazanego przez operatora. Partia opiera się na groove'ach z biblioteki `grooves/`.
**Zakres:** tylko wskazany fragment. Sąsiednie sekcje bierzesz pod uwagę wyłącznie przy wejściu we fragment i wyjściu z niego. Nie zmieniasz riffów, melodii, akordów ani miksu. Bas opisujesz tylko jako warstwę względem stopy.
**Wymagania:** fragment kompozycji od operatora, czyli co najmniej riffy albo akordy z liczbą taktów, metrum i tempem. Dostęp do odczytu plików `grooves/README.md`, `grooves/grooves.md` oraz folderów `grooves/midi/` i `grooves/musicxml/`.
**Jak używać:** wykonaj fazy 0–7 z sekcji „Kroki” po kolei. Każda faza dopisuje kolumny do arkusza perkusji. Na końcu zwróć raport w formacie z sekcji „Format raportu”.
**Gotowe, gdy:** każda sekcja fragmentu ma wiersz arkusza, groove z biblioteki albo własną siatkę, plan wyjścia z sekcji i wynik kontroli końcowej.

## Lista terminów

| Termin | Znaczenie |
|---|---|
| operator | Osoba albo agent, który zleca pracę, wskazuje fragment i podaje kontekst. |
| fragment | Część utworu do opracowania: jeden riff, jedna sekcja albo ciąg sekcji z liczbą taktów. |
| sekcja | Część formy utworu o jednej funkcji, np. intro, zwrotka, blok riffów, refren, most, narastanie, kulminacja, outro. |
| granica sekcji | Pierwszy takt nowej sekcji razem z ostatnim taktem poprzedniej. |
| groove | Powtarzalny wzór perkusji, który niesie puls sekcji. W bibliotece każdy groove ma nazwę, np. `half-time`. |
| BM | Black metal. |
| blast beat | Bardzo szybki wzór, w którym werbel gra na każdą ósemkę albo częściej. Nazwa skrócona w tym pliku: blast. |
| double kick | Stopa na dwóch pedałach grająca ciągłe szesnastki. |
| przejście | Krótki fill na tomach albo werblu, który zamyka grupę taktów. |
| cięcie | Zmiana sekcji bez przejścia, oznaczona tylko talerzem albo zmianą groove'u. |
| werbel na miarę | Średnia liczba uderzeń werbla na jedną odczuwalną miarę. Wyznacza charakter groove'u. |
| tempo odczuwalne | Tempo miary, którą słuchacz odbiera jako puls. W `6/8` i `12/8` miarą jest ćwierćnuta z kropką. |
| K+S/s | Liczba uderzeń stopy (K) i werbla (S) na sekundę. Mierzy gęstość groove'u. |
| talerz prowadzący | Jeden talerz, który odmierza czas w sekcji: hi-hat, ride, crash albo dzwon ride'a (bell). |
| crash sekcji | Crash razem ze stopą na pierwszej mierze pierwszego taktu sekcji. |
| prowadzenie crashem | Crash jako talerz prowadzący, czyli crash na każdą miarę albo ósemkę. |
| rzadki groove | Groove, w którym stopa gra pojedyncze uderzenia: `half-time`, `backbeat`, `skank`, `d-beat`, `doom`, `compound`. |
| gęsty groove | Groove, w którym stopa gra ciągły strumień: blasty i groove'y z double kickiem. |
| ściana basu (tremolo) | Bas gra tremolo razem z gitarą pod gęstym groove'em. |
| podłoga basu | Bas gra ósemki razem ze stopą pod gęstym groove'em. |
| powierzchnia perkusji | Sposób realizacji perkusji: na żywo bez triggerów, na żywo z triggerem stopy, programowana z humanizacją albo programowana statycznie. |
| arkusz perkusji | Tabela z jednym wierszem na sekcję. To główny wynik pracy agenta. |

Podgatunki nazywasz tak samo jak biblioteka: norweski, surowy (raw), symfoniczny, melodyczny (szwedzki), atmosferyczny, DSBM (Depressive Suicidal Black Metal), blackgaze, dysonansowy oraz typ Mgła jako osobny model zespołu.

## Zasady pracy agenta

- **Kontekst operatora wygrywa z wartościami domyślnymi z tego pliku.** Gdy kontekst łamie regułę, zastosuj kontekst i zapisz w raporcie, którą regułę złamano.
- Nie edytuj plików w `grooves/`.
- Nie pytaj operatora w trakcie pracy. Gdy brakuje danych, przyjmij wartość domyślną i zapisz ją w raporcie jako założenie.
- Przerwij pracę tylko wtedy, gdy fragment nie podaje liczby taktów albo tempa i nie da się ich wywnioskować. Zwróć wtedy listę brakujących danych.
- Zapisz raport do pliku tylko wtedy, gdy operator wskaże ścieżkę. W przeciwnym razie zwróć raport jako odpowiedź końcową.
- Pisz raport po polsku. Zapisuj dźwięki jako `C D E F G A B` z `♯` i `♭`, akordy molowe jako `Em`, a tempo w backtickach jako `170 BPM`.

## Jak czytać wejście operatora

### Fragment określa, co komponujesz

Wyciągnij z fragmentu dane z tabeli. Gdy fragment zawiera ścieżkę pliku, przeczytaj ten plik.

| Dana | Skąd ją wziąć | Gdy jej brakuje |
|---|---|---|
| sekcje i liczba taktów | mapa sekcji, nagłówki, liczba powtórzeń riffu | Potraktuj cały fragment jako jedną sekcję. |
| metrum | oznaczenie metrum, grupowanie nut w tabulaturze | Przyjmij `4/4`. Gdy riff grupuje nuty po trzy ósemki, przyjmij `6/8`. |
| tempo | oznaczenie `BPM` | Przerwij pracę i zgłoś brak, chyba że kontekst podaje podgatunek. Wtedy przyjmij tempo odczuwalne podgatunku. |
| typ riffu | rytm gitary w tabulaturze albo opis operatora | Przyjmij riff tremolo. |
| ataki riffu | pozycje nowych dźwięków i akcentów gitary w takcie | Zapisz, że stopa w rzadkim groove'ie wymaga sprawdzenia z riffem. |
| rytm harmoniczny | liczba taktów na akord | Przyjmij jeden akord na takt i sprawdź czas trwania akordu. |
| wokal | oznaczenia tekstu, wejścia wokalu, opis operatora | Przyjmij, że zwrotka i refren mają wokal, a pozostałe sekcje są instrumentalne. |
| sąsiednie sekcje | sekcja przed fragmentem i po nim | Zapisz wejście i wyjście jako crash sekcji bez przejścia. |

### Kontekst dodatkowy zmienia wartości domyślne

Kontekst to wszystko, co operator podaje poza samym fragmentem. Przypisz każdą informację z kontekstu do jednego parametru z tabeli.

| Parametr | Przykład kontekstu | Co zmienia |
|---|---|---|
| podgatunek | „norweski”, „jak Mgła”, „DSBM” | Profil podgatunku: mieszankę groove'ów, budżet blastów, talerze, przejścia, powtórzenia. |
| zespół albo utwór wzorcowy | „w stylu Emperor”, „jak Deafheaven” | Wybierz podgatunek z profilu, do którego należy zespół. Zapisz to przypisanie. |
| funkcja fragmentu w utworze | „to kulminacja”, „intro do blastu” | Funkcję sekcji, a przez nią groove i talerze z tabeli sekcji. |
| poziom energii | „ma być spokojniej”, „wejście na pełną moc” | Poziom energii `1–5`, czyli werbel na miarę. |
| powierzchnia perkusji | „perkusista na żywo”, „programuję w DAW” | Wymagania grywalności i dynamiki. |
| model pisania | „perkusista dopisze przejścia” | Ile szczegółów zapisujesz. W modelu z perkusistą zapisz brief zamiast pełnej partii przejść. |
| ograniczenia | „bez blastów”, „tylko ride”, „maks. `180 BPM`” | Wykluczają opcje. Ograniczenie operatora jest twarde. |
| bas | „bas gra tremolo z gitarą” | Warstwę basu. Nie proponujesz innej, ale zgłaszasz konflikt ze stopą. |

Gdy kontekst jest sprzeczny, zastosuj informację bardziej szczegółową. Ograniczenie wygrywa z podgatunkiem, a podgatunek z zespołem wzorcowym. Zapisz sprzeczność w raporcie.

### Wartości domyślne przy braku kontekstu

| Parametr | Wartość domyślna |
|---|---|
| podgatunek | norweski |
| powierzchnia perkusji | programowana z humanizacją, z celem brzmienia na żywo |
| model pisania | kompozytor programuje partię, perkusista może ją ozdobić |
| bas pod gęstym groove'em | wartość z profilu podgatunku |
| wokal | zgodnie z tabelą „Fragment określa, co komponujesz” |

## Biblioteka groove'ów jest jedynym źródłem wzorów

Biblioteka w `grooves/` zawiera 20 groove'ów, 80 plików MIDI i 80 plików MusicXML o tych samych nazwach. Wybieraj groove z biblioteki. Własną siatkę pisz tylko jako modyfikację groove'u z biblioteki i zawsze nazwij groove bazowy.

- `grooves/README.md` zawiera tabelę sekcji, drabinę energii i zasady talerzy.
- `grooves/grooves.md` zawiera dla każdego groove'u tabelę pól, siatkę oraz linki do plików MIDI i MusicXML. Pola mają angielskie nazwy: `Feel`, `Tempo`, `Sections`, `Subgenres`, `Cymbal variations`, `Other variations`, `Examples`, `Caveat`.
- Pliki MIDI i MusicXML nie zawierają crasha sekcji. Crash sekcji dopisujesz w arkuszu.
- Tempo w pliku MIDI to punkt wyjścia. Tempo utworu ustala riff.

### Nazwa pliku składa się z formy i wariantu

Plik MIDI ma nazwę `grooves/midi/<forma>_<wariant>.mid`, a plik MusicXML `grooves/musicxml/<forma>_<wariant>.musicxml`. Forma to nazwa siatki z pierwszego wiersza siatki w `grooves/grooves.md`, np. `half-time_ride.mid`.

Forma zwykle równa się nazwie groove'u. Trzy groove'y mają inne formy:

| Groove | Formy |
|---|---|
| `half-time` | `half-time`, `half-time-pickup` (stopa także na pozycji 14) |
| `backbeat` | `backbeat`, `backbeat-kick-1-3` (stopa tylko na mierach 1 i 3) |
| `compound` | `compound-6-8`, `compound-12-8`. Plik `compound_<wariant>.mid` nie istnieje. |

Wariant opisuje talerze. Dostępne warianty danej formy wymienia linia `MIDI:` pod jej siatką.

| Wariant | Talerze w pliku |
|---|---|
| `hat`, `ride`, `bell`, `crash` | Ten talerz jest talerzem prowadzącym. |
| `china`, `splash` | China albo splash jest talerzem prowadzącym. Używaj ich tylko w ścianie albo kulminacji. |
| `<talerz>-china`, `<talerz>-splash` | Pierwszy talerz prowadzi. W taktach 2 i 4 china albo splash zastępuje go na pozycji `0` jako kolor. |
| `hat-bell` | Hi-hat prowadzi, a dzwon ride'a gra ósemki między miarami. |
| `ride-wash` | Ride gra na wszystkich 16 pozycjach, bez stopy. |
| `none` | Plik nie ma talerza. |

### Siatka używa zapisu biblioteki

Siatka pokazuje jeden takt. Każdy znak to jedna pozycja: szesnastka w `4/4` i `6/8`, ósemka w `12/8`. Pozycje liczysz od `0`.

| Wiersz | Instrument | Symbole |
|---|---|---|
| CY | talerz | `H` hi-hat, `R` ride, `B` dzwon ride'a, `C` crash, `X` china, `s` splash |
| SN | werbel | `S` |
| TM | tomy | `T` |
| BD | stopa | `K` |

Znak `-` oznacza pauzę.

```
backbeat · 4/4 · 140 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  ----S-------S---
BD  K-----K-K-------
```

### Groove'y biblioteki według poziomu energii

| Groove | Energia | Werbel na miarę | Główne użycie |
|---|---|---|---|
| `kick-pulse-wash` | 1 | 0 | intro, most, outro, narastanie, ściana w blackgaze |
| `tom-groove` | 1 | 0,25 | intro i przerywnik na tomach |
| `doom` | 2 | 0,25 | wolne intro, most, outro |
| `half-time` | 2 | 0,25 | zwrotka, most, wolne strefy |
| `half-time-double-kick` | 2 | 0,25 | refren i ściana, cięższy, ale nie szybszy |
| `backbeat` | 3 | 0,5 | zwrotka, refren, główny podkład DSBM |
| `double-kick-backbeat` | 3 | 0,5 | zwrotka, refren, blok riffów, plateau kulminacji |
| `d-beat` | 3 | 1 | rzadki kolor riffu, nie groove sekcji |
| `compound` | 3 | 0,5 | riffy w `6/8` i `12/8` |
| `gallop` | 3 | 0,5 | unikaj, nawyk z thrash i death metalu |
| `skank` | 4 | 1 | zwrotka melodyczna i surowa, alternatywa dla blastu |
| `double-kick-offbeat-snare` | 4 | 1 | szybkie bloki riffów norweskich |
| `snare-every-beat` | 4 | 1 | narastanie |
| `double-kick-riff-snare` | 4 | 1,75 | blok riffów atmosferycznych, werbel za riffem |
| `snare-eighths` | 4 | 2 | blok riffów dysonansowych, bez stopy |
| `blast-fragment` | 4 | 0,5 + 2 na mierze 4 | wstawka 1–4 takty w riffie |
| `traditional-blast` | 5 | 2 | blok riffów, zwrotka surowa i norweska, kulminacja |
| `bomb-blast` | 5 | 2 | wstawka 1–4 takty |
| `hammer-blast` | 5 | 2 | tylko odniesienie, brak użycia w BM |
| `sextuple-blast` | 5 | 3 (`6/8`) | tylko odniesienie |

Brak perkusji to pełnoprawny wybór dla sekcji. Zapisz go w arkuszu jako `tacet`.

## Wiedza o perkusji black metalowej

**Model na teraz:** liczby w tej sekcji to typowe wartości z tabulatur i wywiadów, zebrane dla 2–7 utworów na podgatunek.
**Zakres modelu:** traktuj każdy próg jako miękką bramkę. Gdy partia go przekracza, zapisz jedno zdanie uzasadnienia. Liczby nie dotyczą pojedynczego taktu, tylko całego fragmentu albo utworu.

### Perkusję piszesz do riffu i formy, nigdy do linii wokalu

Riff gitarowy jest pierwszym punktem odniesienia: jego typ, ataki i zmiany akordów. Mapa sekcji jest drugim punktem odniesienia, bo decyduje, gdzie zmienia się groove i talerz. Wokal nie wyznacza rytmu perkusji. Wokal tylko ogranicza gęstość, więc zostawiasz mu miejsce.

Wyjątki: w modelu „perkusja najpierw” riff dopasowuje się do perkusji. W DSBM perkusja często milknie pod mówionym albo krzyczanym wokalem.

### Werbel ustala charakter, stopa ustala intensywność

Wybierz charakter sekcji przez liczbę uderzeń werbla na miarę. Podnoś albo obniżaj intensywność stopą przy tym samym werblu. Zmieniaj charakter bez zmiany tempa, bo tak dzieje się w 85% zmian groove'u.

| Werbel na miarę | Charakter | Groove'y z rzadką stopą | Groove'y z gęstą stopą |
|---|---|---|---|
| 0,25 | half-time | `half-time`, `doom` | `half-time-double-kick` |
| 0,5 | backbeat | `backbeat`, `compound` | `double-kick-backbeat` |
| 1 | podwójny | `skank`, `d-beat` | `snare-every-beat`, `double-kick-offbeat-snare` |
| 2 | blast | — | `traditional-blast`, `bomb-blast` |

Przesuwaj charakter o jeden stopień drabiny. Skok z `half-time` prosto do blastu zdarza się rzadko. Do blastu wchodzisz najczęściej z biegnącego double kicka albo z `backbeat` w tym samym tempie.

Prawdziwa zmiana tempa jest znakiem podgatunku. Używaj jej w symfonicznym i dysonansowym (około 30% granic) oraz w norweskich strefach tempa. W DSBM i typie Mgła nie zmieniaj tempa.

Nazywaj charakter przez gęstość, a nie przez zapisane `BPM`:

- K+S/s dla szesnastek = `BPM` / 15.
- Blast ma co najmniej 9 uderzeń K+S/s na przemian. Skank ma 5–9 K+S/s. Polka ma mniej niż 5 K+S/s.
- Blast zapisany w `138 BPM` szesnastkami nadal jest blastem.

### Typ riffu wskazuje rodzinę groove'u

| Typ riffu | Rodzina groove'u | Uwaga o stopie |
|---|---|---|
| tremolo (szybkie powtórzenia jednego dźwięku) | `traditional-blast` albo `skank`, albo wolniejszy groove pod tremolo (`half-time`, `backbeat`) | Pod blastem stopa to puls. |
| długie dźwięki, trzymane akordy | `half-time` albo `doom`, albo blast pod trzymanymi akordami (dysonansowy, atmosferyczny) | Blast staje się jedynym ruchem. |
| riff rytmiczny na dźwięku pedałowym | `backbeat` albo `double-kick-backbeat` | Stopa na atakach riffu. |
| synkopy na słabych częściach miary | `skank` | Stopa na miarach. |
| riff w `6/8` albo `12/8` | `compound` albo `sextuple-blast` | — |

Celowa sprzeczność jest dozwolona. Przykład: zwykły groove pod sekstolowym tremolo brzmi jednocześnie szybko i wolno. Zapisz ją wtedy jako decyzję, a nie błąd.

### Akord pod blastem musi trwać co najmniej sekundę

Zmiana akordu szybsza niż około sekunda rozmywa się pod blastem. Policz czas trwania akordu:

**sekundy na akord = takty na akord × miary w takcie × 60 / `BPM`**

Przykład: 1 takt `4/4` w `220 BPM` trwa 4 × 60 / 220 = 1,09 s. To dolna granica, więc lepiej 2 takty na akord.

| Jeśli… | To… |
|---|---|
| akord trwa co najmniej 1 s, najlepiej 1,5–3 s | zostaw groove. |
| akord trwa krócej niż 1 s pod blastem | zejdź o stopień drabiny w tym samym tempie albo zgłoś operatorowi podwojenie taktów na akord. |
| tempo przekracza `240 BPM` | wymagaj 2 taktów na akord. |

W `6/8` sprawdź najpierw, czy `BPM` liczy ćwierćnuty z kropką. Wtedy takt trwa tylko 0,55–0,67 s i potrzebujesz 2–4 taktów na akord.

### Blast to jedna faktura z wielu

Blast zajmuje 1–29% czasu utworu, zależnie od podgatunku. Resztę czasu niosą groove'y. Planuj blast jako kolor sekcji, zwykle w blokach instrumentalnych. Budżety blastów podgatunków podaje tabela profili.

Wyjątki: surowe utwory na jednym groove'ie (do 99% blastu), szwedzkie zespoły „blastujące” typu Marduk i Dark Funeral, pojedyncze utwory dysonansowe i norweskie (do około 55%).

Blast włączasz i wyłączasz także wewnątrz sekcji. Trzy czwarte wejść w blast dzieje się w środku sekcji. Blast surowy trwa zwykle cały riff.

### Stopa w rzadkim groove'ie dubluje ataki riffu

W rzadkim groove'ie stopa gra podzbiór ataków riffu: pierwszą miarę i synkopy riffu. Celuj w około 1 uderzenie stopy na miarę w `backbeat` i 0,7 w `half-time`. Stopa poza atakami riffu rozmywa riff.

W gęstym groove'ie stopa jest ustalona przez groove. Nie dopasowujesz jej do riffu.

Werbel odpowiada na zmianę akordu na słabej mierze. Nie stawiaj werbla na każdej zmianie akordu w riffie tremolo, bo riff zamienia się w rockowy backbeat. Wyjątek: piosenkowe utwory symfoniczne i melodyczne.

### Talerze wyznaczają sekcje

Talerze wykonują większość pracy na granicach sekcji. Stosuj te reguły:

1. Utrzymaj jeden talerz prowadzący przez całą sekcję. Wyjątek: dysonansowy, blackgaze i typ Mgła zmieniają talerz także w sekcji.
2. Zmień talerz prowadzący na granicy sekcji. Celuj w około 6 na 10 granic poza surowym. Najczęstsza zamiana to hi-hat ↔ ride.
3. Traktuj zamianę talerza nad niezmienionym groove'em jako pełny znak granicy sekcji.
4. Przejdź na ride, gdy sekcja ma się podnieść. Wróć na hi-hat, gdy sekcja ma się uspokoić. Kierunek jest wolny.
5. Uderz crash razem ze stopą na pierwszej mierze nowej sekcji i frazy oraz na zmianie akordu.
6. Uderz crash na pierwszym takcie wejścia w blast.
7. Nie uderzaj crasha na każdej pierwszej mierze groove'u.
8. Używaj prowadzenia crashem, chiną albo splashem tylko w ścianie albo kulminacji: blackgaze, dysonansowy, symfoniczny typu Cradle of Filth.
9. Zagraj talerz blastu razem ze stopą. Hi-hat w surowym, ride albo hi-hat w norweskim, ride w symfonicznym, bell w blackgaze, crash albo splash w dysonansowym.
10. Zagraj `skank` na ride, talerz na każdą ósemkę. Wyjątek: melodyczny `skank` na hi-hacie (typ Dissection).
11. Otwórz talerz w wolnych, szerokich groove'ach: `half-time`, `snare-every-beat` i `kick-pulse-wash` dostają crash albo plamę ride'a.
12. Traktuj chinę i splash jako kolor w środku sekcji, nie jako talerz prowadzący. China na pierwszej mierze wolnego backbeatu na ride to znak DSBM.
13. Traktuj dzwon ride'a jako kolor współczesny: dzwon między miarami nad `double-kick-backbeat` (typ Mgła) albo blast na dzwonie (blackgaze).
14. Utrzymaj niską gęstość crasha pod melodycznym riffem tremolo i pod partią klawiszy. Wyjątek: DSBM, gdzie szum talerzy jest zamierzony.
15. Nie łącz crasha i hi-hatu w jednym uderzeniu, bo perkusista ma dwie ręce.

W surowym BM crash pada tylko na około połowie początków sekcji i prawie nigdy w zwykłych taktach.

### Granicę sekcji oznaczasz sygnałami w ustalonej kolejności

Wybieraj sygnał granicy w tej kolejności. Procent podaje, jak często sygnał występuje na granicach sekcji.

1. Crash ze stopą na pierwszej mierze nowej sekcji (79%).
2. Zamiana talerza prowadzącego (71%).
3. Zmiana groove'u w tym samym tempie (55%).
4. Przejście w ostatnim takcie poprzedniej sekcji (42%).
5. Zmiana tempa (15%, w symfonicznym i dysonansowym około 30%).
6. Wejście albo wyjście perkusji (w DSBM 43% granic).

Cięcie jest normą: 60% granic nie ma przejścia. Zatrzymanie całego zespołu zdarza się na 2% granic, więc nie używaj go domyślnie.

### Domyślnie granica nie ma przejścia

Przejście ma 1–2 miary tomów albo 1 miarę tremolo na werblu. Stoi w ostatnim takcie grupy 4, 8 albo 16 taktów. Zapowiada funkcję następnej sekcji, np. „zwrotka prowadzi do refrenu”.

| Jeśli… | To… |
|---|---|
| następna sekcja zaczyna się blastem | rozważ przejście jako rozbieg, bo ma go około połowa wejść w blast. |
| podgatunek to blackgaze albo melodyczny | dawaj przejścia częściej, około 2 na 3 granice w blackgaze i 1 na 2 w melodycznym. |
| podgatunek to norweski, melodyczny albo dysonansowy | możesz użyć przejścia na cały takt. |
| podgatunek to dysonansowy | możesz postawić przejście w pierwszym takcie nowej sekcji albo na nieparzystym takcie. |
| blok jest hipnotyczny (surowy, DSBM w typie Lifelover, typ Mgła) | nie dawaj przejścia wewnątrz bloku. |

Rozłóż przejścia na cały utwór. Gdy przejścia wyczerpią się w pierwszej części, reszta brzmi pusto.

### Powtórzenia riffu są stałe albo przearanżowane

Zdecyduj dla każdego riffu, czy groove jest stały, czy przearanżowany.

| Typ | Podgatunki | Co robisz |
|---|---|---|
| stały | surowy, DSBM, typ Mgła | Zachowaj groove we wszystkich powtórzeniach. W surowym powtarzaj takt dosłownie, najwyżej jedna zamiana talerza albo jedno przejście pod koniec. W typie Mgła zmieniaj tylko talerze. |
| przearanżowany | norweski, symfoniczny, dysonansowy | Daj nowy groove w około 1 na 5 powtórzeń, zwykle jako narastanie o jeden stopień. |
| zmienny | melodyczny, blackgaze | Zmieniaj coś w prawie każdym powtórzeniu. |

Zmieniaj w kolejności: talerze, potem stopa, na końcu werbel. W jednym powtórzeniu nie zmieniaj jednocześnie groove'u, przejścia i talerza prowadzącego. Riff, który wraca później w utworze, dostaje inną perkusję niż za pierwszym razem. Wyjątek: surowy.

Typowe narastanie o jeden stopień: `kick-pulse-wash` → `snare-every-beat` → `half-time` → `double-kick-backbeat` → `traditional-blast`.

### Bas pod gęstym groove'em wybiera warstwę

W rzadkim groove'ie obowiązuje zawieranie: uderzenia stopy są podzbiorem dźwięków basu, a dźwięki basu podzbiorem ataków gitary.

Pod blastem i double kickiem stopa gra 2 uderzenia na miarę, a bas wybiera jedną z dwóch warstw.

| Warstwa | Co gra bas | Podgatunki |
|---|---|---|
| ściana basu (tremolo) | tremolo razem z gitarą | norweski, surowy, symfoniczny |
| podłoga basu | ósemki razem ze stopą | melodyczny, atmosferyczny (typ Wolves in the Throne Room), blackgaze (typ Deafheaven), typ Mgła |

W uderzeniach (stabs) i zatrzymaniach stopa, bas i gitara grają razem. W surowym i DSBM reguła basu jest opcjonalna, bo bas jest słabo słyszalny.

### Wokal dostaje miejsce, ale nie wyznacza partii

- Pod wokalem graj ten sam albo lżejszy groove. Nie dodawaj tam przejść ani crashy.
- Najcięższy groove daj blokom instrumentalnym. Tak robią typ Mgła i norweski.
- Surowy, norweski i blackgaze typu Deafheaven mogą grać blast pod wokalem w zwrotce.
- W DSBM możesz wyłączyć perkusję pod mówionym albo krzyczanym wokalem.

### Partia musi być grywalna i pasować do powierzchni

| Powierzchnia perkusji | Podgatunki | Wymagania |
|---|---|---|
| na żywo bez triggerów | norweski lat 1992–95, surowy | Bez idealnie równych, triggerowanych blastów. |
| na żywo z triggerem stopy | symfoniczny, melodyczny, współczesny dysonansowy | Klarowne szczegóły są słyszalne. |
| programowana z humanizacją | każdy cel brzmienia na żywo | Wymagania programowania poniżej. |
| programowana statycznie | tylko surowy, DSBM i typ Summoning | Wzór może być sztywny. Brzmienie sampli nie może się wybijać. |

Wymagania grywalności i programowania:

- Zapisz partię na dwie ręce i dwie nogi.
- Nie zapisuj szesnastek jedną stopą powyżej `160–180 BPM`. Wyżej użyj double kicka.
- Ustaw dynamikę werbla w groove'ie na około `115–125`, a werbla w blaście na około `90–110`, z naprzemiennymi wartościami.
- Akcentuj pierwszą miarę frazy.
- Kwantyzuj na około 90–95%, chyba że powierzchnia jest programowana statycznie.
- W surowym i DSBM możesz zostawić sztywny czas, ale zmieniaj dynamikę.

Szczegóły zapisane w ghost notes, wzorach dzwonu albo kolorach tomów przetrwają tylko w klarownej produkcji. W surowej produkcji wydawaj szczegóły na wybór groove'u i zamiany talerzy.

### Profile podgatunków ustalają wartości docelowe

Ta tabela daje wartości docelowe dla podgatunku z kontekstu. Skróty talerzy: HH hi-hat, RD ride, CR crash, BL dzwon ride'a.

| Cecha | norweski | surowy | symfoniczny | melodyczny | atmosferyczny | DSBM | blackgaze | dysonansowy | typ Mgła |
|---|---|---|---|---|---|---|---|---|---|
| tempo odczuwalne (`BPM`) | 143 | 145 | 148 | 151 | 135 | 101 | 126 | 151 | 162 |
| główny groove poza blastem | `half-time`, `backbeat`, double kick | `skank`, `backbeat` | `double-kick-backbeat` | `compound`, `skank` | `half-time`, `double-kick-backbeat` | `backbeat`, `half-time` | `half-time` | `half-time` | `double-kick-backbeat`, `half-time` |
| udział blastu w utworze | 28% | 0–99% | 14% | 10% | 13% | 1% | 4% | 29% | 15% |
| udział `tacet` | 7% | 6% | 3% | 6% | 9% | 19% | 17% | 8% | 18% |
| talerz prowadzący | HH, RD | HH (skank RD) | HH, RD, CR | HH | HH, RD | RD | CR, BL, HH | HH, CR, splash | HH, BL między miarami |
| crash na początku sekcji | 92% | 48% | 93% | 90% | 61% | 66% | 96% | 62% | 100% |
| prowadzenie crashem (takty) | 1% | 2% | 10% | 3% | 1% | 4% | 19% | 14% | 8% |
| zmiana talerza na granicy | 85% | 38% | 72% | 44% | 57% | 76% | 95% | 59% | 67% |
| granice z przejściem | 45% | do 20% | 36% | 48% | 23% | 39% | do 70% | 37% | 48% |
| powtórzenia riffu | przearanżowane | stałe | przearanżowane | zmienne | długie bloki | stałe | zmienne | przearanżowane albo dosłowne | stałe, zmiana talerzy |
| zmiany groove'u w tym samym tempie | 85% | 75% | 85% | 89% | 94% | 100% | 95% | 55% | 100% |
| bas pod blastem | ściana | ściana | ściana | podłoga | podłoga | — | podłoga | mieszany | podłoga |
| powierzchnia | bez triggerów | bez triggerów, perkusja z tyłu miksu | trigger, klarowna | trigger | na żywo | maszyna dozwolona jako wzór | na żywo | na żywo, precyzyjna | na żywo |

Cechy profili, których tabela nie oddaje:

- **norweski:** bloki blastów przeciw `half-time` i `backbeat` w strefach tempa. Double kick pod ruchomym werblem zamiast blastu (`double-kick-offbeat-snare`). Najczęściej przejście trzymiarowe. Najmocniej zmieniane ostatnie powtórzenie. Wzorce: Mayhem „Freezing Moon”, Emperor „I Am the Black Wizards”, Satyricon „Mother North”.
- **surowy:** jeden groove na utwór albo na riff. Groove zmienia się z riffem, nie z sekcją. 40% granic bez sygnału perkusji. Przejścia rzadkie, prawie połowa to tremolo na werblu. Wzorce: Darkthrone „Transilvanian Hunger”, „Under a Funeral Moon”, Ildjarn.
- **symfoniczny:** blasty zostawione na późne sekcje i kulminację. Kulminacja zwalnia do wolnego `backbeat` albo perkusja milknie. Najwięcej prawdziwych zmian tempa. Splash i china jako talerz prowadzący w mostach `12/8`. Wzorce: Emperor „Inno a Satana”, Dimmu Borgir „Mourning Palace”, Cradle of Filth.
- **melodyczny:** logika zwrotka–refren, np. `skank` w zwrotkach i `backbeat` w refrenach. Refreny `6/8` prowadzone crashem. Najwięcej przejść. Wzorce: Dissection „Where Dead Angels Lie”, „Night's Blood”, Watain „Malfeitor”.
- **atmosferyczny:** długie bloki `half-time` i double kick. Blast pod wolniejszą gitarą (Wolves in the Throne Room). Programowany `tom-groove` jako stała warstwa w typie Summoning. Wzorce: Wolves in the Throne Room, Agalloch, Drudkh, Panopticon.
- **DSBM:** wolna pętla na jednym groove'ie. Perkusja wychodzi i wraca. Jedno przejście na długi przebieg, zwykle w 16. takcie. Proste wzory bez rozbudowanych przejść. Wzorce: Lifelover „Nackskott”, Xasthur, Nocturnal Depression „Nostalgia”.
- **blackgaze:** `half-time` w zwrotkach, `half-time-double-kick` albo `double-kick-backbeat` w refrenach, blast jako wczesny szczyt. Ściany z prowadzenia crashem i dzwonu. Prawie nic dosłownego. Wzorce: Deafheaven „Dream House”, Alcest, Harakiri for the Sky.
- **dysonansowy:** blasty w sekcjach i jako wstawki 1–2 takty (`blast-fragment`). Zmiany metrum przy 37% zmian groove'u. Trzymane akordy nad blastem. Perkusja sama oznacza 20% granic. Wzorce: Deathspell Omega „Abscission”, Misþyrming, Svartidauði „Flesh Cathedral”.
- **typ Mgła:** rodziny groove'ów zmieniają się blokami, np. `half-time` w zwrotce, `double-kick-backbeat` w refrenie, `backbeat`, `tacet`. Wokal nad lżejszym groove'em, blast w blokach instrumentalnych. 41% zmian w powtórzeniach to tylko talerze. Wzorce: Mgła „Exercises in Futility V”, „Age of Excuse II”.

### Tabela sekcji podaje punkt startowy dla funkcji sekcji

| Sekcja | Typowy groove | Talerz prowadzący | Crash i akcenty | Przejścia |
|---|---|---|---|---|
| intro | `tacet` → `kick-pulse-wash`, `tom-groove` (dysonansowy), `doom` (dysonansowy, DSBM) albo blast od razu (surowy, norweski) | crash, ride albo brak | crash albo narastająca plama do pierwszego taktu zespołu | rozbieg do pierwszego blastu |
| zwrotka z wokalem | lżejszy albo równy: `backbeat`, `double-kick-backbeat`, `half-time`, `skank` (melodyczny, surowy), `compound` (melodyczny, symfoniczny), blast w surowym, norweskim i typie Deafheaven | hi-hat, w DSBM ride | crash tylko na początku sekcji | brak w środku, najwyżej jedno na końcu grupy 8 albo 16 taktów |
| blok riffów instrumentalny | najcięższy groove utworu: blast albo `double-kick-backbeat` | ride albo hi-hat, zamieniony względem bloku z wokalem | crash na zmianach akordów | rozbieg do blastu |
| refren | `backbeat` albo `skank` (melodyczny), `double-kick-backbeat` (symfoniczny), `half-time-double-kick` (blackgaze), `compound` z crashem (melodyczny w `6/8`) | zmiana na ride albo prowadzenie crashem | crash na każdej zmianie akordu | przejście do refrenu w melodycznym i blackgaze |
| most, przerywnik | `tacet`, `half-time`, `tom-groove`, `kick-pulse-wash`, `doom` | brak, crash albo ride | oszczędnie | wyjście perkusji |
| narastanie | `snare-every-beat`, drabina `half-time` → `backbeat` → `double-kick-backbeat` | ride albo crash | gęstość crasha rośnie | rozbieg 1–2 miary na końcu |
| kulminacja, ściana | blast po przerzedzeniu (symfoniczny), `half-time-double-kick` z prowadzeniem crashem (blackgaze), wolny `backbeat`, plateau `double-kick-backbeat` (typ Mgła) | crash, china albo bell | prowadzenie z akcentami | nieliczne |
| outro | `kick-pulse-wash`, `doom`, `tacet` (DSBM), koda blastu (norweski), rozpad do samych talerzy (dysonansowy) | plama ride'a albo crasha | ostatni crash i wybrzmienie | brak |
| wstawka 1–4 takty w riffie | `bomb-blast`, `blast-fragment` | hi-hat, ride albo bell | crash na pierwszym takcie blastu | brak |

### Błędy do unikania

| Kod | Błąd | Dlaczego szkodzi | Wyjątek |
|---|---|---|---|
| D1 | przejście na końcu każdej frazy 4 taktów | żadne przejście nie oznacza już sekcji | melodyczny, blackgaze, rozbiegi do blastu w norweskim, symfoniczny |
| D2 | stopa poza atakami riffu w rzadkim groove'ie | rozmywa riff | blasty i double kick, surowy stały groove |
| D3 | crash na każdej pierwszej mierze groove'u, crash razem z hi-hatem | crash przestaje oznaczać sekcję, potrzebne trzy ręce | prowadzenie crashem w ścianie: blackgaze, dysonansowy, symfoniczny typu Cradle of Filth |
| D4 | brak zmiany talerza i groove'u pod zmieniającymi się riffami | granica sekcji znika, perkusja brzmi monotonnie | surowy, długie pętle atmosferyczne i DSBM |
| D5 | blast pod akordami krótszymi niż sekunda | harmonia się rozmywa | — |
| D6 | przejście albo zmiana groove'u w hipnotycznej pętli | pętla zamienia się w frazę | norweski, symfoniczny, dysonansowy, DSBM typu Nocturnal Depression |
| D7 | nawyki death metalu i metalcore'u: `gallop`, breakdown z zatrzymaniami, przejście solo z pauzą zespołu, zatrzymania jako domyślne przejście | perkusja przestaje nieść ciągłą fakturę | riffy z zatrzymaniami w konkretnym utworze (typ Immortal) |
| D8 | statyczna maszyna poza surowym i DSBM, wybijające się brzmienie sampli | słychać automat | surowy, DSBM i typ Summoning (tylko wzór, nie brzmienie) |
| D10 | stała dynamika i 100% kwantyzacji w partii programowanej | brzmienie karabinu maszynowego | zadeklarowana estetyka maszynowa |
| D11 | partia niegrywalna: trzy talerze naraz, szesnastki jedną stopą powyżej `160–180 BPM` | brzmi sztucznie, perkusista musi ją przepisać | zadeklarowany projekt maszynowy |
| D12 | idealnie równe, triggerowane blasty w celu surowym albo norweskim | współczesne, death metalowe brzmienie | współczesny dysonansowy, symfoniczny, melodyczny |
| D13 | blast jako domyślny groove | utwór traci drabinę charakterów i brzmi jak death metal | surowy stały groove, szwedzkie „blastowanie”, norweski i dysonansowy do około 55% |
| D14 | werbel na każdej zmianie akordu w riffie tremolo | riff zamienia się w rockowy backbeat | piosenkowe utwory symfoniczne i melodyczne |
| D15 | talerze z niewłaściwej epoki: prowadzenie crashem, chiną albo dzwonem w pastiszu norweskim lub surowym | brzmi jak muzyka po roku 2000 | solo w surowym typie Peste Noire, Cradle of Filth |

## Przykład: zwrotka norweska na riffie tremolo

**Wejście:** zwrotka 16 taktów, riff tremolo w `Em`, metrum `4/4`, tempo `160 BPM`. Akord zmienia się co 2 takty. Riff gra 4 razy po 4 takty. Zwrotka ma wokal. Po zwrotce jest instrumentalny blok riffów. Kontekst: „norweski, perkusja na żywo”.

**Kroki:**

1. Policz akord: 2 × 4 × 60 / 160 = 3 s. Blast jest dozwolony.
2. Wybierz charakter. Zwrotka ma wokal, a najcięższy groove należy do bloku instrumentalnego. Wybierz `double-kick-backbeat` zamiast blastu.
3. Sprawdź pole `Tempo` w `grooves/grooves.md`. Wynik: `160 BPM` mieści się w zakresie `80–170 BPM`.
4. Wybierz talerz prowadzący: hi-hat, plik `grooves/midi/double-kick-backbeat_hat.mid`.
5. Zaplanuj powtórzenia: przearanżowanie w powtórzeniu 4 przez zamianę talerza akcentu.
6. Zaplanuj wyjście: rozbieg 1 miary tomów w takcie 16, potem blast z crashem w bloku riffów.

**Wynik (wiersz arkusza):**

| Sekcja (takty) | Riff | Groove i plik MIDI | Werbel / stopa | Talerz prowadzący | Crash | Powtórzenia | Wyjście z sekcji | Bas | Miejsce dla wokalu |
|---|---|---|---|---|---|---|---|---|---|
| zwrotka (1–16) | R1 | `double-kick-backbeat`, `double-kick-backbeat_hat.mid` | 0,5 / ciągłe szesnastki | hi-hat | takt 1, takty zmian akordu 3, 5, 7 | przearanżowane: powtórzenie 4 z crashem na miarach | rozbieg 1 miary tomów w takcie 16 → `traditional-blast` z crashem | ściana basu | lżejszy groove pod wokalem |

**Sprawdzenie:** groove zwrotki jest o stopień lżejszy od bloku riffów. Crash nie pada na każdej mierze. Przejście trwa 1 miarę i zamyka grupę 16 taktów.

## Kroki

### Faza 0: wczytaj wejście i bibliotekę

1. Przeczytaj fragment od operatora i każdy plik, który fragment wskazuje.
2. Przeczytaj `grooves/README.md`.
3. Przeczytaj `grooves/grooves.md`.
4. Jeśli fragment nie podaje taktów ani tempa i nie da się ich ustalić, zwróć listę braków i zakończ.

Wynik: dane fragmentu i znajomość biblioteki.

### Faza 1: zinterpretuj kontekst

1. Przypisz każdą informację z kontekstu do parametru z tabeli „Kontekst dodatkowy zmienia wartości domyślne”.
2. Uzupełnij brakujące parametry wartościami domyślnymi.
3. Wybierz profil podgatunku z tabeli profili.
4. Zapisz sprzeczności kontekstu i sposób ich rozstrzygnięcia.

Wynik: tabela parametrów z kolumną „źródło” (operator albo wartość domyślna).

### Faza 2: przeanalizuj fragment

1. Podziel fragment na sekcje z numerami taktów.
2. Nazwij funkcję każdej sekcji według tabeli sekcji.
3. Określ typ każdego riffu według tabeli typów riffu.
4. Zapisz ataki każdego riffu jako pozycje siatki: `0–15` w `4/4`, `0–11` w `6/8` i `12/8`.
5. Policz sekundy na akord dla każdej sekcji.
6. Oznacz sekcje z wokalem.

Wynik: kolumny „Sekcja”, „Riff” i dane do dalszych faz.

### Faza 3: wybierz groove dla każdej sekcji

1. Wybierz rodzinę groove'u z typu riffu.
2. Ustal werbel na miarę z funkcji sekcji i poziomu energii.
3. Wybierz z biblioteki groove o tym werblu i właściwej gęstości stopy.
4. Sprawdź tempo groove'u w polu `Tempo` w `grooves/grooves.md`.
5. Jeśli akord trwa krócej niż 1 s pod blastem, zejdź o stopień drabiny.
6. Porównaj udział blastu we fragmencie z budżetem podgatunku.
7. Jeśli rzadki groove, zapisz pozycje stopy jako podzbiór ataków riffu.
8. Jeśli groove wymaga zmian, zapisz własną siatkę i nazwij groove bazowy.

Wynik: kolumny „Groove i plik MIDI” oraz „Werbel / stopa”.

### Faza 4: zaplanuj talerze

1. Wybierz talerz prowadzący dla każdej sekcji według reguł talerzy i profilu.
2. Wybierz wariant pliku MIDI zgodny z talerzem prowadzącym.
3. Zaznacz granice z zamianą talerza.
4. Zapisz takty z crashem sekcji, crashem na zmianie akordu i crashem wejścia w blast.
5. Jeśli sekcja jest ścianą albo kulminacją, rozważ prowadzenie crashem zgodnie z profilem.

Wynik: kolumny „Talerz prowadzący” i „Crash”.

### Faza 5: zaplanuj powtórzenia i granice

1. Oznacz każdy riff jako stały, przearanżowany albo zmienny.
2. Zapisz, co zmienia się w których powtórzeniach, w kolejności talerze → stopa → werbel.
3. Dla każdej granicy nazwij funkcję następnej sekcji.
4. Wybierz sygnał granicy według kolejności sygnałów.
5. Jeśli wybierasz przejście, zapisz jego długość, instrument i takt.
6. Policz udział granic z przejściem i porównaj go z profilem.

Wynik: kolumny „Powtórzenia” i „Wyjście z sekcji”.

### Faza 6: sprawdź bas, wokal i grywalność

1. Pod każdym gęstym groove'em zapisz warstwę basu z profilu albo z kontekstu.
2. Jeśli bas z kontekstu koliduje ze stopą, zapisz konflikt.
3. Sprawdź, czy pod wokalem gra ten sam albo lżejszy groove.
4. Usuń przejścia i dodatkowe crashe z sekcji z wokalem.
5. Sprawdź grywalność według listy wymagań powierzchni.
6. Jeśli partia jest programowana, zapisz dynamikę i kwantyzację.

Wynik: kolumny „Bas” i „Miejsce dla wokalu” oraz uwagi dla programowania.

### Faza 7: sprawdź partię i zwróć raport

1. Przejdź listę kontroli końcowej.
2. Dla każdego niespełnionego punktu popraw arkusz albo zapisz uzasadnienie.
3. Zapisz raport w formacie z sekcji „Format raportu”.
4. Jeśli operator wskazał ścieżkę, zapisz raport do pliku.

Wynik: raport zwrócony operatorowi.

## Kontrola końcowa

- [ ] Każda sekcja fragmentu ma wiersz arkusza z groove'em z biblioteki albo `tacet`.
- [ ] Każdy plik MIDI w arkuszu istnieje w `grooves/midi/`.
- [ ] Każdy akord pod blastem trwa co najmniej około 1 s (D5).
- [ ] Udział blastu mieści się w budżecie podgatunku albo ma uzasadnienie (D13).
- [ ] W rzadkich groove'ach stopa leży na atakach riffu (D2).
- [ ] Werbel nie pada na każdej zmianie akordu w riffie tremolo, poza wyjątkami (D14).
- [ ] Każda sekcja ma jeden talerz prowadzący, poza wyjątkami podgatunku.
- [ ] Crashe stoją na początkach sekcji i fraz, zmianach akordów i wejściach w blast, a nie na każdej mierze (D3).
- [ ] Talerze pasują do epoki wzorca (D15).
- [ ] Każda granica ma sygnał, a udział przejść mieści się w profilu (D1, D4).
- [ ] Hipnotyczne bloki nie mają przejść ani zmian groove'u w środku (D6).
- [ ] Partia nie używa `gallop`, breakdownów ani zatrzymań jako domyślnego przejścia (D7).
- [ ] Pod każdym gęstym groove'em jest wybrana warstwa basu.
- [ ] Najcięższy groove nie leży pod wokalem, chyba że podgatunek tak robi.
- [ ] Partia jest grywalna albo zadeklarowana jako programowana statycznie (D8, D10, D11, D12).
- [ ] Każde złamanie reguły ma jedno zdanie uzasadnienia.

## Format raportu

Zwróć raport w tej kolejności sekcji:

```markdown
# Partia perkusji: <nazwa fragmentu>

**Cel:** partia perkusji dla <fragment, takty>.
**Zakres:** <sekcje fragmentu>. Poza zakresem: <sąsiednie sekcje>.
**Wymagania:** biblioteka `grooves/`, DAW z mapą General MIDI.
**Jak używać:** wczytaj pliki MIDI z arkusza w kolejności sekcji, a potem dopisz crashe i przejścia z planu granic.

## Parametry pracy

| Parametr | Wartość | Źródło |
|---|---|---|

## Arkusz perkusji

| Sekcja (takty) | Riff | Groove i plik MIDI | Werbel / stopa | Talerz prowadzący | Crash | Powtórzenia | Wyjście z sekcji | Bas | Miejsce dla wokalu |
|---|---|---|---|---|---|---|---|---|---|

## Siatki zmienione względem biblioteki

<Dla każdej zmiany: groove bazowy, plik MIDI, siatka w zapisie biblioteki, lista zmian do wykonania w DAW.>

## Plan granic sekcji

| Granica (takt) | Następna sekcja i jej funkcja | Sygnał | Przejście: długość, instrument |
|---|---|---|---|

## Wynik kontroli

<Lista kontroli końcowej z zaznaczeniem i uzasadnieniem każdego wyjątku.>

## Założenia i otwarte pytania

<Założenia przyjęte przy braku danych. Konflikty z kontekstem. Pytania do operatora.>

## Stan

- Zrobione: ...
- Następny krok: ...
- Powrót po przerwie: ...
```
