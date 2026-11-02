# Katalog groove'ów perkusyjnych black metalu

**Cel:** opisać 20 groove'ów perkusyjnych: siatkę, tempo, sekcje, podgatunki, warianty talerzy, pliki MIDI i pliki MusicXML.
**Zakres:** 20 groove'ów uporządkowanych według energii, każdy z tabelą pól, siatką i linkami do plików. Plik nie opisuje brzmienia perkusji ani miksu.
**Wymagania:** przeczytaj [sekcję „Jak czytać wpis w katalogu”](#jak-czytać-wpis-w-katalogu) pod indeksem. Wyjaśnia terminy, angielskie nazwy pól, symbole siatki i nazwy wariantów.
**Jak używać:** wybierz groove w indeksie poniżej. Przeczytaj jego tabelę pól, a potem otwórz pliki MIDI albo MusicXML wymienione pod siatką.

Groove'y są uporządkowane od najniższej do najwyższej energii. Energia rośnie razem z liczbą uderzeń werbla na miarę.

| Groove | Energia | Werbel na miarę |
|---|---|---|
| [kick-pulse-wash](#kick-pulse-wash) | 1 | 0 |
| [tom-groove](#tom-groove) | 1 | 0,25 |
| [doom](#doom) | 2 | 0,25 |
| [half-time](#half-time) | 2 | 0,25 |
| [half-time-double-kick](#half-time-double-kick) | 2 | 0,25 |
| [backbeat](#backbeat) | 3 | 0,5 |
| [double-kick-backbeat](#double-kick-backbeat) | 3 | 0,5 |
| [d-beat](#d-beat) | 3 | 1 |
| [compound](#compound) | 3 | 0,5 |
| [gallop](#gallop) | 3 | 0,5 |
| [skank](#skank) | 4 | 1 |
| [double-kick-offbeat-snare](#double-kick-offbeat-snare) | 4 | 1 |
| [snare-every-beat](#snare-every-beat) | 4 | 1 |
| [double-kick-riff-snare](#double-kick-riff-snare) | 4 | 1,75 |
| [snare-eighths](#snare-eighths) | 4 | 2 (bez stopy) |
| [blast-fragment](#blast-fragment) | 4 | 0,5 + 2 na mierze 4 |
| [traditional-blast](#traditional-blast) | 5 | 2 |
| [bomb-blast](#bomb-blast) | 5 | 2 |
| [hammer-blast](#hammer-blast) | 5 | 2 |
| [sextuple-blast](#sextuple-blast) | 5 | 3 (`6/8`) |

## Jak czytać wpis w katalogu

Każdy groove w tym pliku ma tabelę pól, jedną albo więcej siatek oraz linki do plików MIDI i MusicXML.

### Lista terminów

| Termin | Znaczenie |
|---|---|
| BM | Black metal. |
| blast beat | Bardzo szybki wzór, w którym werbel gra na każdą ósemkę albo częściej. |
| werbel na miarę | Średnia liczba uderzeń werbla na jedną odczuwalną miarę. |
| tempo odczuwalne | Tempo ćwierćnuty, które słuchacz odbiera jako puls. W metrum `6/8` i `12/8` to ćwierćnuta z kropką. |
| talerz prowadzący | Jeden talerz, który odmierza czas w sekcji, np. hi-hat albo ride. |
| K+S/s | Liczba uderzeń stopy (K) i werbla (S) na sekundę, czyli gęstość groove'u. |

### Tabela pól opisuje użycie groove'u

Pola mają angielskie nazwy.

| Pole | Treść |
|---|---|
| `Feel` | werbel na miarę, rola stopy i K+S/s przy medianie tempa |
| `Tempo` | tempo odczuwalne jako minimum–mediana–maksimum oraz tempo zapisane w plikach |
| `Sections` | sekcje utworu, w których groove występuje |
| `Subgenres` | podgatunki z udziałem groove'u w czasie utworów |
| `Cymbal variations` | warianty talerzy z udziałem w tabulaturach |
| `Other variations` | odmiany stopy, werbla i przejść |
| `Examples` | utwory z sekundą, w której groove występuje |
| `Caveat` | ograniczenie użycia albo `—` |

### Siatka pokazuje jeden takt

Pierwszy wiersz siatki podaje formę, metrum i tempo pliku. Drugi wiersz numeruje miary. Każdy znak to jedna pozycja: szesnastka w `4/4` i `6/8`, ósemka w `12/8`. Znak `-` oznacza pauzę.

| Wiersz | Instrument | Symbole |
|---|---|---|
| `CY` | talerz | `H` hi-hat, `R` ride, `B` dzwon ride'a, `C` crash, `X` china, `s` splash |
| `SN` | werbel | `S` |
| `TM` | tomy | `T` |
| `BD` | stopa | `K` |

### Nazwa pliku składa się z formy i wariantu

Forma to nazwa siatki z jej pierwszego wiersza. Zwykle równa się nazwie groove'u. Wyjątki: `half-time-pickup`, `backbeat-kick-1-3`, `compound-6-8` i `compound-12-8`. Wariant opisuje talerze.

| Wariant | Talerze w pliku |
|---|---|
| `hat`, `ride`, `bell`, `crash` | Ten talerz jest talerzem prowadzącym. |
| `china`, `splash` | China albo splash jest talerzem prowadzącym w ścianie albo kulminacji. |
| `<talerz>-china`, `<talerz>-splash` | Pierwszy talerz prowadzi. W taktach 2 i 4 china albo splash zastępuje go na pozycji `0` jako kolor. |
| `hat-bell` | Hi-hat prowadzi, a dzwon ride'a gra ósemki między miarami. |
| `ride-wash` | Ride gra na wszystkich 16 pozycjach, bez stopy. |
| `none` | Plik nie ma talerza. |

---

## kick-pulse-wash

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0 · stopa pulsu · 2,5 K+S/s przy medianie |
| Tempo | odczuwalne `67–150–240 BPM` (klasyczny); MIDI `150 BPM` |
| Sections | intro, most / przerywnik, narastanie, outro, ściana (blackgaze) |
| Subgenres | blackgaze 14%, melodyczny 12%, norweski 11%, symfoniczny 8%, dysonansowy 6%, Mgła 6%, atmosferyczny 5%, DSBM 5%, surowy 3% |
| Cymbal variations | crash 52% klasyczny; ride 32% współczesny; hat 34% współczesny; ride-wash ride na wszystkich 16 pozycjach, bez stopy (takt z tabulatury Svartidauði) |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Svartidauði „Flesh Cathedral” 59,5 s; Alcest „Autre temps” 293,6 s; Marduk „Panzer Division Marduk” 130,8 s |
| Caveat | — |

```
kick-pulse-wash · 4/4 · 150 bpm
    1...2...3...4...
CY  C---C---C---C---
SN  ----------------
BD  K---K---K---K---
```
MIDI: [crash](midi/kick-pulse-wash_crash.mid) [ride](midi/kick-pulse-wash_ride.mid) [hat](midi/kick-pulse-wash_hat.mid) [ride-wash](midi/kick-pulse-wash_ride-wash.mid)

MusicXML: [crash](musicxml/kick-pulse-wash_crash.musicxml) [ride](musicxml/kick-pulse-wash_ride.musicxml) [hat](musicxml/kick-pulse-wash_hat.musicxml) [ride-wash](musicxml/kick-pulse-wash_ride-wash.musicxml)

## tom-groove

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,25 · stopa za riffem · 4,0 K+S/s przy medianie |
| Tempo | odczuwalne `73–158–250 BPM` (klasyczny); MIDI `158 BPM` |
| Sections | intro, most / przerywnik (przerywnik na czystej gitarze) |
| Subgenres | programowana perkusja w stylu Summoning (70% jednego utworu); najwyżej 2% w każdym podgatunku |
| Cymbal variations | none 40%; crash 31% (tylko pozycja 0 każdego taktu); hat 17% (ćwierćnuty) |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Summoning „Land of the Dead” 28,1 s; Deathspell Omega „Kénôse I” 9,0 s; Alcest „Autre temps” 170,5 s |
| Caveat | — |

```
tom-groove · 4/4 · 158 bpm
    1...2...3...4...
CY  ----------------
SN  --------S-------
TM  ----T-T---T-T---
BD  K---K-K---K-K---
```
MIDI: [none](midi/tom-groove_none.mid) [crash](midi/tom-groove_crash.mid) [hat](midi/tom-groove_hat.mid)

MusicXML: [none](musicxml/tom-groove_none.musicxml) [crash](musicxml/tom-groove_crash.musicxml) [hat](musicxml/tom-groove_hat.musicxml)

## doom

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,25 · stopa za riffem · 1,3 K+S/s przy medianie |
| Tempo | odczuwalne `51–80–80 BPM` (współczesny); MIDI `80 BPM` |
| Sections | intro, most / przerywnik, outro |
| Subgenres | DSBM 3%, dysonansowy 3%, atmosferyczny 1% |
| Cymbal variations | hat 71%; crash 17%; ride 12% |
| Other variations | werbel na pozycji 10 (3 z 51 taktów); przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Deathspell Omega „Kénôse I” 90,0 s; Agalloch (refren 1) 497,0 s |
| Caveat | — |

```
doom · 4/4 · 80 bpm
    1...2...3...4...
CY  H---H---H---H---
SN  --------S-------
BD  K-K---K---------
```
MIDI: [hat](midi/doom_hat.mid) [crash](midi/doom_crash.mid) [ride](midi/doom_ride.mid)

MusicXML: [hat](musicxml/doom_hat.musicxml) [crash](musicxml/doom_crash.musicxml) [ride](musicxml/doom_ride.musicxml)

## half-time

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,25 · stopa za riffem · 1,0 K+S/s przy medianie |
| Tempo | odczuwalne `95–125–180 BPM` (współczesny); MIDI `125 BPM` |
| Sections | intro, zwrotka (blackgaze), most / przerywnik, outro, strefa wolna |
| Subgenres | blackgaze 42%, atmosferyczny 27%, Mgła 23%, DSBM 21%, dysonansowy 20%, symfoniczny 19%, norweski 16%, surowy 6%, melodyczny 5% (udziały razem z half-time-double-kick) |
| Cymbal variations | hat 52–55%; ride 29–37%; crash 7–13% (blackgaze 26%); hat-splash 17–19% uderzeń splasha; hat-china 24% uderzeń chiny w korpusie współczesnym |
| Other variations | dodatkowa stopa na pozycji 6 (24% taktów); talerz ósemkami; przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Satyricon „Mother North” 280,5 s; Nocturnal Depression „Nostalgia” 69,8 s; Svartidauði „Flesh Cathedral” 336,3 s |
| Caveat | — |

```
half-time · 4/4 · 125 bpm
    1...2...3...4...
CY  H---H---H---H---
SN  --------S-------
BD  K---------------
```
MIDI: [hat](midi/half-time_hat.mid) [ride](midi/half-time_ride.mid) [crash](midi/half-time_crash.mid) [hat-splash](midi/half-time_hat-splash.mid) [hat-china](midi/half-time_hat-china.mid)

MusicXML: [hat](musicxml/half-time_hat.musicxml) [ride](musicxml/half-time_ride.musicxml) [crash](musicxml/half-time_crash.musicxml) [hat-splash](musicxml/half-time_hat-splash.musicxml) [hat-china](musicxml/half-time_hat-china.musicxml)

```
half-time-pickup · 4/4 · 125 bpm
    1...2...3...4...
CY  H---H---H---H---
SN  --------S-------
BD  K-------------K-
```
MIDI: [hat](midi/half-time-pickup_hat.mid) [ride](midi/half-time-pickup_ride.mid) [crash](midi/half-time-pickup_crash.mid) [hat-splash](midi/half-time-pickup_hat-splash.mid) [hat-china](midi/half-time-pickup_hat-china.mid)

MusicXML: [hat](musicxml/half-time-pickup_hat.musicxml) [ride](musicxml/half-time-pickup_ride.musicxml) [crash](musicxml/half-time-pickup_crash.musicxml) [hat-splash](musicxml/half-time-pickup_hat-splash.musicxml) [hat-china](musicxml/half-time-pickup_hat-china.musicxml)

## half-time-double-kick

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,25 · stopa motoryczna · 8,9 K+S/s przy medianie |
| Tempo | odczuwalne `80–125–170 BPM` (współczesny); MIDI `125 BPM` |
| Sections | refren (blackgaze, Dark Funeral), narastanie, kulminacja / ściana |
| Subgenres | liczony razem z half-time (blackgaze 42%, atmosferyczny 27%, Mgła 23%); szczyty w utworach: Mother North 29%, Mountain Magick 18%, Harakiri 16% |
| Cymbal variations | ride 37%; crash 29% (ściany); hat 25%; china 4% (korpus współczesny) |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Satyricon „Mother North” 131,1 s; Dark Funeral „Diabolis Interium” 183,3 s; Harakiri for the Sky „Calling the Rain” 372,5 s |
| Caveat | — |

```
half-time-double-kick · 4/4 · 125 bpm
    1...2...3...4...
CY  R---R---R---R---
SN  --------S-------
BD  KKKKKKKKKKKKKKKK
```
MIDI: [ride](midi/half-time-double-kick_ride.mid) [crash](midi/half-time-double-kick_crash.mid) [hat](midi/half-time-double-kick_hat.mid) [china](midi/half-time-double-kick_china.mid)

MusicXML: [ride](musicxml/half-time-double-kick_ride.musicxml) [crash](musicxml/half-time-double-kick_crash.musicxml) [hat](musicxml/half-time-double-kick_hat.musicxml) [china](musicxml/half-time-double-kick_china.musicxml)

## backbeat

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,5 · stopa za riffem · 2,9 K+S/s przy medianie |
| Tempo | odczuwalne `102–140–180 BPM` (współczesny); MIDI `140 BPM` |
| Sections | zwrotka, refren (symfoniczny, melodyczny), kulminacja / ściana (wolna), główny podkład DSBM |
| Subgenres | DSBM 33%, surowy 19%, norweski 10%, symfoniczny 10%, melodyczny 9%, dysonansowy 9%, Mgła 8%, atmosferyczny 7%, blackgaze 7% |
| Cymbal variations | hat 49–77%; ride 13–41% (DSBM 63%); crash 16% (blackgaze 49%); ride-china pierwsza miara w DSBM (Xasthur); ride-splash pierwsza miara w DSBM (Xasthur) |
| Other variations | stopa na pozycjach 0, 8 i 10 (22% taktów); dodatkowe stopy w stylu punk; przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Peste Noire „Spleen” 0 s; Lifelover „Nackskott” 0 s; Mgła „Exercises in Futility V” 226,6 s |
| Caveat | — |

```
backbeat · 4/4 · 140 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  ----S-------S---
BD  K-----K-K-------
```
MIDI: [hat](midi/backbeat_hat.mid) [ride](midi/backbeat_ride.mid) [crash](midi/backbeat_crash.mid) [ride-china](midi/backbeat_ride-china.mid) [ride-splash](midi/backbeat_ride-splash.mid)

MusicXML: [hat](musicxml/backbeat_hat.musicxml) [ride](musicxml/backbeat_ride.musicxml) [crash](musicxml/backbeat_crash.musicxml) [ride-china](musicxml/backbeat_ride-china.musicxml) [ride-splash](musicxml/backbeat_ride-splash.musicxml)

```
backbeat-kick-1-3 · 4/4 · 140 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  ----S-------S---
BD  K-------K-------
```
MIDI: [hat](midi/backbeat-kick-1-3_hat.mid) [ride](midi/backbeat-kick-1-3_ride.mid) [crash](midi/backbeat-kick-1-3_crash.mid) [ride-china](midi/backbeat-kick-1-3_ride-china.mid) [ride-splash](midi/backbeat-kick-1-3_ride-splash.mid)

MusicXML: [hat](musicxml/backbeat-kick-1-3_hat.musicxml) [ride](musicxml/backbeat-kick-1-3_ride.musicxml) [crash](musicxml/backbeat-kick-1-3_crash.musicxml) [ride-china](musicxml/backbeat-kick-1-3_ride-china.musicxml) [ride-splash](musicxml/backbeat-kick-1-3_ride-splash.musicxml)

## double-kick-backbeat

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,5 · stopa motoryczna · 8,0 K+S/s przy medianie |
| Tempo | odczuwalne `80–107–170 BPM` (współczesny, mediana klasyczna `158 BPM`); MIDI `107 BPM` |
| Sections | zwrotka (symfoniczny), refren (symfoniczny, Mgła), blok riffów (Mgła), kulminacja / ściana (plateau) |
| Subgenres | Mgła 23%, symfoniczny 22%, atmosferyczny 15%, norweski 9%, DSBM 8%, melodyczny 6%, blackgaze 3%, dysonansowy < 1%, surowy 0% (udziały razem z double-kick-offbeat-snare) |
| Cymbal variations | ride 59% współczesny; hat 63% klasyczny; crash 9%; hat-bell dzwon na ósemkach między miarami, pozycje 2, 6, 10, 14 (Mgła); hat-china 3%; hat-splash 18% klasycznych uderzeń splasha |
| Other variations | ride ósemkami; stopa łamana (nieciągła); przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Dimmu Borgir „Mourning Palace” 237,7 s; Mgła „Exercises in Futility V” 362,2 s; Emperor „Inno a Satana” 37,1 s |
| Caveat | — |

```
double-kick-backbeat · 4/4 · 107 bpm
    1...2...3...4...
CY  R---R---R---R---
SN  ----S-------S---
BD  KKKKKKKKKKKKKKKK
```
MIDI: [ride](midi/double-kick-backbeat_ride.mid) [hat](midi/double-kick-backbeat_hat.mid) [crash](midi/double-kick-backbeat_crash.mid) [hat-bell](midi/double-kick-backbeat_hat-bell.mid) [hat-china](midi/double-kick-backbeat_hat-china.mid) [hat-splash](midi/double-kick-backbeat_hat-splash.mid)

MusicXML: [ride](musicxml/double-kick-backbeat_ride.musicxml) [hat](musicxml/double-kick-backbeat_hat.musicxml) [crash](musicxml/double-kick-backbeat_crash.musicxml) [hat-bell](musicxml/double-kick-backbeat_hat-bell.musicxml) [hat-china](musicxml/double-kick-backbeat_hat-china.musicxml) [hat-splash](musicxml/double-kick-backbeat_hat-splash.musicxml)

## d-beat

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 1 · stopa za riffem · 6,6 K+S/s przy medianie |
| Tempo | odczuwalne `144–158 BPM` (tabulatury, bez mediany); MIDI `158 BPM` (wyjątek: tempo z tabulatury) |
| Sections | tylko kolor riffu (riff w intro), nie groove sekcji |
| Subgenres | tylko melodyczny szwedzki (Watain) i Mgła, poniżej 1% czasu |
| Cymbal variations | hat 67%; ride 33%; crash na pozycjach stopy 0, 3, 5, 8, 11, 13 (wersja 1 z Wikipedii) |
| Other variations | takt z tabulatury Watain: stopa na pozycjach 0, 2, 8, 10 pod werblem backbeatu; przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Watain „Malfeitor” 48,6 s; Mgła „Age of Excuse II” 163,4 s |
| Caveat | poniżej 1% czasu, jeden utwór na korpus |

```
d-beat · 4/4 · 158 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  --S---S---S---S-
BD  K--K-K--K--K-K--
```
MIDI: [hat](midi/d-beat_hat.mid) [ride](midi/d-beat_ride.mid) [crash](midi/d-beat_crash.mid)

MusicXML: [hat](musicxml/d-beat_hat.musicxml) [ride](musicxml/d-beat_ride.musicxml) [crash](musicxml/d-beat_crash.musicxml)

## compound

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,5 (ćwierćnuta z kropką) · stopa za riffem · `6/8`: 3,3 K+S/s przy `80 BPM`; `12/8`: 2,2 K+S/s przy `130 BPM` |
| Tempo | `6/8` ćwierćnuta z kropką `69–80–153 BPM` (klasyczny), MIDI `120 BPM`; `12/8` ćwierćnuta z kropką `80–130–175 BPM` (współczesny), MIDI `195 BPM` (każde metrum z własnego korpusu) |
| Sections | zwrotka (melodyczny, symfoniczny), refren (melodyczny w `6/8`, prowadzony crashem), intro (symfoniczny) |
| Subgenres | melodyczny 21%, symfoniczny 10%, atmosferyczny 6%, norweski 5%, DSBM 3%, dysonansowy 3%, blackgaze 1% |
| Cymbal variations | hat 35–52%; ride 23–42%; crash 27% w refrenach; hat-china 24% taktów z chiną to compound |
| Other variations | podział równy albo swingowany; przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Dissection „Where Dead Angels Lie” 103,2 s (`6/8`); Emperor „I Am the Black Wizards” 160,1 s (`12/8`); Dimmu Borgir „Mourning Palace” 10,5 s |
| Caveat | — |

```
compound-6-8 · 6/8 · 120 bpm
    1.....2.....
CY  H-H-H-H-H-H-
SN  ------S-----
BD  K---KK----K-
```
MIDI: [hat](midi/compound-6-8_hat.mid) [ride](midi/compound-6-8_ride.mid) [crash](midi/compound-6-8_crash.mid) [hat-china](midi/compound-6-8_hat-china.mid)

MusicXML: [hat](musicxml/compound-6-8_hat.musicxml) [ride](musicxml/compound-6-8_ride.musicxml) [crash](musicxml/compound-6-8_crash.musicxml) [hat-china](musicxml/compound-6-8_hat-china.musicxml)

```
compound-12-8 · 12/8 · 195 bpm
    1..2..3..4..
CY  HHHHHHHHHHHH
SN  ---S-----S--
BD  K-----K-----
```
MIDI: [hat](midi/compound-12-8_hat.mid) [ride](midi/compound-12-8_ride.mid) [crash](midi/compound-12-8_crash.mid) [hat-china](midi/compound-12-8_hat-china.mid)

MusicXML: [hat](musicxml/compound-12-8_hat.musicxml) [ride](musicxml/compound-12-8_ride.musicxml) [crash](musicxml/compound-12-8_crash.musicxml) [hat-china](musicxml/compound-12-8_hat-china.musicxml)

## gallop

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,5 · stopa motoryczna · 7,3 K+S/s przy medianie |
| Tempo | odczuwalne `125–135 BPM` (klasyczny, bez mediany); MIDI `125 BPM` (wyjątek: tempo z klasycznej tabulatury) |
| Sections | tylko podkład pod solo, unikaj |
| Subgenres | surowy (jeden podkład pod solo, 12 taktów); symfoniczny i blackgaze (po 1–2 takty) |
| Cymbal variations | ride 73%; crash 27% |
| Other variations | odwrócony gallop; przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Peste Noire „Spleen” 192,0 s; Cradle of Filth „Interlude” 80,3 s |
| Caveat | lista do unikania: nawyk z thrash metalu i death metalu |

```
gallop · 4/4 · 125 bpm
    1...2...3...4...
CY  R---R---R---R---
SN  ----S-------S---
BD  K-KKK-KKK-KKK-KK
```
MIDI: [ride](midi/gallop_ride.mid) [crash](midi/gallop_crash.mid)

MusicXML: [ride](musicxml/gallop_ride.musicxml) [crash](musicxml/gallop_crash.musicxml)

## skank

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 1 · stopa za riffem · 5,7 K+S/s przy medianie |
| Tempo | odczuwalne `100–170–227 BPM` (RR); MIDI `170 BPM` (wyjątek: mediana RR, bo mediana współczesna `227 BPM` równa się jej 90. percentylowi) |
| Sections | zwrotka (melodyczny, surowy), alternatywa w bloku riffów, całe utwory surowe |
| Subgenres | surowy 28%, melodyczny 17%, symfoniczny 3%, dysonansowy 3%, norweski 2% (udziały całej rodziny, razem z d-beat) |
| Cymbal variations | ride 59% (surowy 87%); hat 94% u Dissection; bell 21% na stopie; crash 17% na stopie; china 15% na stopie; splash 32% na stopie (bell, crash, china, splash: pozycje stopy 0, 4, 8, 12) |
| Other variations | stopa ósemkami; polka poniżej 5 K+S/s; przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Ildjarn „Natt og tåke” 5,1 s; Dissection „Night's Blood” 20,1 s; Deathspell Omega „Wings of Predation” 6,3 s |
| Caveat | — |

```
skank · 4/4 · 170 bpm
    1...2...3...4...
CY  R-R-R-R-R-R-R-R-
SN  --S---S---S---S-
BD  K---K---K---K---
```
MIDI: [ride](midi/skank_ride.mid) [hat](midi/skank_hat.mid) [bell](midi/skank_bell.mid) [crash](midi/skank_crash.mid) [china](midi/skank_china.mid) [splash](midi/skank_splash.mid)

MusicXML: [ride](musicxml/skank_ride.musicxml) [hat](musicxml/skank_hat.musicxml) [bell](musicxml/skank_bell.musicxml) [crash](musicxml/skank_crash.musicxml) [china](musicxml/skank_china.musicxml) [splash](musicxml/skank_splash.musicxml)

## double-kick-offbeat-snare

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 1 · stopa motoryczna · 14,5 K+S/s przy medianie |
| Tempo | odczuwalne `120–174–185 BPM` (klasyczny); MIDI `174 BPM` |
| Sections | blok riffów (szybkie łańcuchy riffów norweskich, melodyczny) |
| Subgenres | norweski 12% (razem z double-kick-backbeat i half-time-double-kick); bloki riffów melodycznych; 4 klasyczne utwory |
| Cymbal variations | hat 72%; ride 28% |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Emperor „I Am the Black Wizards” 10,8 s; Gorgoroth „Krig” 137,3 s |
| Caveat | — |

```
double-kick-offbeat-snare · 4/4 · 174 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  --S---S---S---S-
BD  KKKKKKKKKKKKKKKK
```
MIDI: [hat](midi/double-kick-offbeat-snare_hat.mid) [ride](midi/double-kick-offbeat-snare_ride.mid)

MusicXML: [hat](musicxml/double-kick-offbeat-snare_hat.musicxml) [ride](musicxml/double-kick-offbeat-snare_ride.musicxml)

## snare-every-beat

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 1 · stopa motoryczna · 12,0 K+S/s przy medianie |
| Tempo | odczuwalne `120–144–200 BPM` (współczesny); MIDI `144 BPM` |
| Sections | narastanie, blok intensyfikacji |
| Subgenres | melodyczny 6%, symfoniczny 2%, Mgła 2%, atmosferyczny 2%, norweski 1% |
| Cymbal variations | hat 53–55%; ride 21–38%; crash 9–20% (symfoniczny 41%, DSBM 65%) |
| Other variations | marsz: stopa ósemkami albo ćwierćnutami (poniżej 25% taktów); przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Watain „Malfeitor” 261,3 s; Mayhem „Funeral Fog” 288,2 s; Mgła „Age of Excuse II” 333,4 s |
| Caveat | — |

```
snare-every-beat · 4/4 · 144 bpm
    1...2...3...4...
CY  H---H---H---H---
SN  S---S---S---S---
BD  KKKKKKKKKKKKKKKK
```
MIDI: [hat](midi/snare-every-beat_hat.mid) [ride](midi/snare-every-beat_ride.mid) [crash](midi/snare-every-beat_crash.mid)

MusicXML: [hat](musicxml/snare-every-beat_hat.musicxml) [ride](musicxml/snare-every-beat_ride.musicxml) [crash](musicxml/snare-every-beat_crash.musicxml)

## double-kick-riff-snare

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 1,75 · stopa motoryczna · 12,0 K+S/s przy medianie |
| Tempo | odczuwalne `100–150 BPM` (bez mediany); MIDI `125 BPM` (wyjątek: takt z tabulatury) |
| Sections | blok riffów (atmosferyczny) |
| Subgenres | atmosferyczny (Drudkh, Wolves in the Throne Room); klasa X (inne) to 19% czasu w podgatunku dysonansowym i 13% w atmosferycznym |
| Cymbal variations | ride u Drudkh; hat 37% (klasa X) |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Drudkh „Forests in Fire and Gold” 0 s; Wolves in the Throne Room „Queen of the Borrowed Light” 474,9 s |
| Caveat | — |

```
double-kick-riff-snare · 4/4 · 125 bpm
    1...2...3...4...
CY  R-R-R-R-R-R-R-R-
SN  S---S-S--S--S-SS
BD  KKKKKKKKKKKKKKKK
```
MIDI: [ride](midi/double-kick-riff-snare_ride.mid) [hat](midi/double-kick-riff-snare_hat.mid)

MusicXML: [ride](musicxml/double-kick-riff-snare_ride.musicxml) [hat](musicxml/double-kick-riff-snare_hat.musicxml)

## snare-eighths

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 2 · bez stopy · 4,0 K+S/s przy medianie |
| Tempo | odczuwalne `120 BPM` (jedna tabulatura); MIDI `120 BPM` |
| Sections | blok riffów (dysonansowy) |
| Subgenres | dysonansowy (25% czasu utworów Krallice); 89 taktów, w tym 62 w jednej tabulaturze |
| Cymbal variations | hat z jednej tabulatury |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Krallice „Fatestorm Sanctuary” 188,2 s |
| Caveat | jedna tabulatura |

```
snare-eighths · 4/4 · 120 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  S-S-S-S-S-S-S-S-
BD  ----------------
```
MIDI: [hat](midi/snare-eighths_hat.mid)

MusicXML: [hat](musicxml/snare-eighths_hat.musicxml)

## blast-fragment

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 0,5 + 2 na mierze 4 · stopa za riffem · 4,8 K+S/s przy medianie (9,5 K+S/s we fragmencie na mierze 4) |
| Tempo | odczuwalne `73–143–250 BPM` (klasyczny); MIDI `143 BPM` |
| Sections | wstawka (1–4 takty wewnątrz riffu) |
| Subgenres | głównie dysonansowy (78 taktów współczesnych); korpus klasyczny: symfoniczny 3,7%, norweski 2,8%, Marduk/Dark Funeral 0,9%, surowy 0,8%, melodyczny 0,7% |
| Cymbal variations | hat jako talerz prowadzący blast beatu; ride jako talerz prowadzący blast beatu |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Mayhem „From the Dark Past” 236,7 s; Mayhem „Funeral Fog” 54,3 s; Darkthrone „Under a Funeral Moon” 208,0 s |
| Caveat | wstawka 1–4 takty, nie groove sekcji |

```
blast-fragment · 4/4 · 143 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  ----S-------S-S-
BD  K-------K--K-K-K
```
MIDI: [hat](midi/blast-fragment_hat.mid) [ride](midi/blast-fragment_ride.mid)

MusicXML: [hat](musicxml/blast-fragment_hat.musicxml) [ride](musicxml/blast-fragment_ride.musicxml)

## traditional-blast

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 2 · stopa motoryczna · 11,3 K+S/s przy medianie |
| Tempo | odczuwalne `142–170–196 BPM` (współczesny); MIDI `170 BPM` |
| Sections | blok riffów, zwrotka (surowy, norweski, blackgaze), intro od razu w pełnym biegu, kulminacja po przerzedzeniu, koda w outro |
| Subgenres | surowy 29%, dysonansowy 29%, norweski 28%, Mgła 15%, symfoniczny 14%, atmosferyczny 13%, melodyczny 10%, blackgaze 4%, DSBM 1% (cała rodzina blast beatów) |
| Cymbal variations | hat 46–59%; ride 30–42%; bell 6–7% (blackgaze 61%); crash 3–6%; hat-splash 31% uderzeń splasha w blast beatach |
| Other variations | grind: talerz razem z werblem; blast freehand (nazwany w źródłach, bez siatki); przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Darkthrone „Transilvanian Hunger” 0 s; Mayhem „Funeral Fog” 0 s |
| Caveat | — |

```
traditional-blast · 4/4 · 170 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  -S-S-S-S-S-S-S-S
BD  K-K-K-K-K-K-K-K-
```
MIDI: [hat](midi/traditional-blast_hat.mid) [ride](midi/traditional-blast_ride.mid) [bell](midi/traditional-blast_bell.mid) [crash](midi/traditional-blast_crash.mid) [hat-splash](midi/traditional-blast_hat-splash.mid)

MusicXML: [hat](musicxml/traditional-blast_hat.musicxml) [ride](musicxml/traditional-blast_ride.musicxml) [bell](musicxml/traditional-blast_bell.musicxml) [crash](musicxml/traditional-blast_crash.musicxml) [hat-splash](musicxml/traditional-blast_hat-splash.musicxml)

## bomb-blast

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 2 · stopa motoryczna · 13,5 K+S/s przy medianie |
| Tempo | odczuwalne `125–135–185 BPM` (klasyczny); MIDI `135 BPM` |
| Sections | wstawka (1–4 takty wewnątrz riffu) |
| Subgenres | 5 klasycznych utworów (51 s, u Dark Funeral 10% tabulatury); 7 taktów współczesnych |
| Cymbal variations | hat 67%; ride 17%; bell 13% |
| Other variations | stopa triolami szesnastkowymi (intro Dark Funeral); przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Dark Funeral „Diabolis Interium” 15,4 s; Darkthrone „Under a Funeral Moon” 259,3 s |
| Caveat | wstawka 1–4 takty, nie groove sekcji |

```
bomb-blast · 4/4 · 135 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  S-S-S-S-S-S-S-S-
BD  KKKKKKKKKKKKKKKK
```
MIDI: [hat](midi/bomb-blast_hat.mid) [ride](midi/bomb-blast_ride.mid) [bell](midi/bomb-blast_bell.mid)

MusicXML: [hat](musicxml/bomb-blast_hat.musicxml) [ride](musicxml/bomb-blast_ride.musicxml) [bell](musicxml/bomb-blast_bell.musicxml)

## hammer-blast

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 2 · stopa motoryczna · 11,3 K+S/s przy medianie (stopa i werbel unisono) |
| Tempo | brak danych, 1 takt z tabulatury w `116 BPM`; MIDI `170 BPM` (wyjątek: skonstruowany, mediana traditional-blast) |
| Sections | brak w tabulaturach BM, tylko jako odniesienie |
| Subgenres | brak udokumentowanego użycia w BM |
| Cymbal variations | hat bez danych o talerzach |
| Other variations | przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Cradle of Filth „Dusk and Her Embrace” 127,4 s |
| Caveat | skonstruowany, 1 takt z tabulatury |

```
hammer-blast · 4/4 · 170 bpm
    1...2...3...4...
CY  H-H-H-H-H-H-H-H-
SN  S-S-S-S-S-S-S-S-
BD  K-K-K-K-K-K-K-K-
```
MIDI: [hat](midi/hammer-blast_hat.mid)

MusicXML: [hat](musicxml/hammer-blast_hat.musicxml)

## sextuple-blast

| Field | Wartość |
|---|---|
| Feel | werbel na miarę 3 (`6/8`) · stopa motoryczna · 10,0 K+S/s przy medianie |
| Tempo | brak (0 taktów w tabulaturach); MIDI `150 BPM`, czyli ćwierćnuta z kropką `100 BPM` (skonstruowany, `6/8`) |
| Sections | brak w tabulaturach BM, tylko jako odniesienie |
| Subgenres | brak; Garza wymienia tremolo w podziale sekstolowym (Immortal, Panopticon, Behemoth, Abigail Williams) |
| Cymbal variations | hat skonstruowany; ride skonstruowany |
| Other variations | naprzemienne uderzenia na 12 ósemkach triolowych taktu `12/8` (połowa gęstości uderzeń); przejścia: 1–2 miary na tomach albo tremolo na werblu przez 1 miarę na końcu grupy 4, 8 lub 16 taktów |
| Examples | Immortal „Grim and Dark” 30 s (lista Garzy); Deathspell Omega „Abscission” 74 s (odczyt w `12/8`) |
| Caveat | skonstruowany, 0 taktów w tabulaturach |

```
sextuple-blast · 6/8 · 150 bpm
    1.....2.....
CY  H-H-H-H-H-H-
SN  -S-S-S-S-S-S
BD  K-K-K-K-K-K-
```
MIDI: [hat](midi/sextuple-blast_hat.mid) [ride](midi/sextuple-blast_ride.mid)

MusicXML: [hat](musicxml/sextuple-blast_hat.musicxml) [ride](musicxml/sextuple-blast_ride.musicxml)
