# Komponowanie utworu black metalowego krok po kroku z bramkami kontrolnymi

**Cel:** Ten plik prowadzi od wyboru podgatunku do sprawdzonego demo utworu black metalowego w 13 fazach.
**Zakres:** Plik obejmuje melodię, harmonię, riffy, formę i aranżację. Sprzęt, miks i tekst są poza zakresem. Wyjątek: produkcja wchodzi w zakres, gdy zmienia słyszalność harmonii.
**Wymagania:** gitara, DAW (Digital Audio Workstation, program do nagrywania i edycji dźwięku) z piano rollem albo klawiatura do szkicowania oraz dostęp do nagrań utworów wzorcowych. Plik zawiera wszystkie tabele i progi potrzebne do pracy.
**Jak używać:** Przechodź przez fazy po kolei. Każda faza kończy się bramką. Przejdź do następnej fazy dopiero wtedy, gdy każdy punkt bramki jest spełniony. Jeśli bramka nie przechodzi, wykonaj polecenie z linii „Jeśli bramka nie przechodzi”.
**Gotowe, gdy:** każdy punkt bramki G12 jest zaznaczony, a co najmniej jeden riff przeszedł selekcję bez zmian.

## Lista terminów

Plik używa poniższych nazw konsekwentnie. Oznaczenia P1–P14, N1–N3, F1–F13 i D1–D15 to pułapki opisane w tabeli audytu w fazie 10.

| Termin | Znaczenie |
|---|---|
| bramka | Lista warunków na końcu fazy. Przejdź dalej dopiero, gdy wszystkie są spełnione. |
| bramka miękka | Bramka, której próg możesz przekroczyć, jeśli zapiszesz jedno zdanie uzasadnienia. |
| pokrętło | Jedna decyzja stylistyczna w briefie, np. jakość akordów. |
| pedał | Dźwięk trzymany albo powtarzany pod zmieniającymi się akordami. Odwrócony pedał leży w najwyższym głosie zamiast w basie. |
| pole dźwiękowe | Zestaw dźwięków dostępnych w utworze wokół pedału. |
| warstwa wolna | Szkielet akordów i długich dźwięków, który słychać jako melodię pod szybką fakturą. |
| głos górny | Linia z najwyższych dźwięków kolejnych akordów. |
| akordy blokowe | Wszystkie dźwięki akordu zagrane razem, bez rozkładania. |
| rytm harmoniczny | Tempo zmian akordów, mierzone w sekundach na harmonię. |
| dwudźwięk | Dwa dźwięki grane razem, np. pryma i kwinta. |
| power chord | Dwudźwięk z prymy i kwinty, często z oktawą, bez tercji. |
| przesuwanie równoległe | Przenoszenie tego samego chwytu w górę albo w dół gryfu bez zmiany kształtu. |
| tremolo picking (tremolo) | Szybkie, równe kostkowanie jednego dźwięku albo akordu. |
| palm muting | Tłumienie strun krawędzią dłoni przy mostku. |
| DI | Direct input: sygnał gitary nagrany bez wzmacniacza i przesteru. |
| groove | Powtarzalny wzór perkusji o określonej liczbie uderzeń na sekundę. Rodzaje groove'ów opisuje tabela w fazie 5. |
| blast beat (blast) | Groove z naprzemienną stopą i werblem przy co najmniej 9 uderzeniach na sekundę. |
| skank | Groove z naprzemienną stopą i werblem przy 5–9 uderzeniach na sekundę. |
| half-time | Groove odczuwany jako połowa tempa, z werblem raz na cztery odczuwane miary (na 3. mierze taktu `4/4`). |
| d-beat | Punkowy groove (od zespołu Discharge) z podwójnym uderzeniem stopy przed werblem. |
| podwójna stopa | Ciągłe szesnastki stopy grane na dwóch pedałach. |
| odczuwana miara | Jednostka pulsu, którą słyszy słuchacz: ćwierćnuta, a w metrum złożonym ćwierćnuta z kropką. |
| werbel na miarę | Średnia liczba uderzeń werbla na odczuwaną miarę. Wyznacza charakter groove'u. |
| gęstość stopy | Liczba uderzeń stopy na odczuwaną miarę. Wyznacza intensywność groove'u, nie jego charakter. |
| drabina groove'ów | Kolejność groove'ów od najgęstszego do najrzadszego przy tym samym pulsie. Opisuje ją faza 5. |
| rzadki groove | Groove, w którym stopa gra pojedyncze uderzenia: half-time, backbeat, skank, d-beat. |
| talerz prowadzący | Talerz, który odmierza puls: hi-hat, ride, crash albo dzwon ride'a (wypukły środek talerza ride). |
| fill | Krótkie przejście perkusji na końcu frazy, zwykle na tomach albo werblu. |
| arkusz perkusji | Tabela z jednym wierszem na sekcję, która zbiera wszystkie decyzje perkusyjne. Wypełniasz ją w fazie 9. |
| model pisania perkusji | Sposób podziału pracy: kto i w jakiej kolejności pisze partię perkusji (modele A–D z fazy 0). |
| powierzchnia perkusji | Sposób nagrania albo zaprogramowania perkusji, który słychać w brzmieniu. |
| trigger | Czujnik na bębnie, który zastępuje albo wzmacnia jego dźwięk próbką. |
| velocity | Siła uderzenia zapisana w nucie MIDI. |
| kwantyzacja | Wyrównanie nut do siatki rytmicznej, podawane w procentach. |
| warstwa basu | Rola basu pod blastem albo podwójną stopą: ściana tremolo (bas gra tremolo z gitarą) albo podłoga stopy (bas gra ósemki ze stopą). |
| przerzedzenie | Usunięcie perkusji, klawiszy albo przesterowanej gitary na 8–16 taktów przed kulminacją. |
| breakdown | Zwolniona sekcja z rytmicznym, tłumionym riffem, typowa dla metalcore'u i death metalu. |
| chug-stop | Nagłe zatrzymanie zespołu po serii tłumionych uderzeń. |
| hook | Chwytliwy motyw, który słuchacz zapamiętuje. |
| nośnik melodii | Instrument albo układ instrumentów, który niesie melodię. |
| ekonomia riffów | Sposób użycia riffów: rotacja (mało przejść na riff) albo pętla (dużo przejść na riff). |
| `m2`, `m3`, `M3` | Sekunda mała, tercja mała, tercja wielka. |
| `♭2`, `♯7` | Stopnie skali zapisane cyfrą arabską. |
| `i`, `♭II`, `IVmaj7` | Akordy zapisane cyfrą rzymską: mała litera oznacza mol, wielka oznacza dur. |
| DSBM | Depressive suicidal black metal: wolny, powtarzalny podgatunek oparty na pętlach. |
| typ Mgły | Utwór w manierze zespołu Mgła: długie bloki, jednogłosowe linie, plateau zamiast kulminacji. |

## Przegląd faz: jedno przejście zajmuje 1–2 dni robocze

Jedno pełne przejście dla utworu o długości 5–8 minut zajmuje około 1–2 dni roboczych. Do tego dolicz co najmniej jedną noc przerwy między fazami 11 i 12.

| Faza | Wynik fazy | Bramka | Typowy czas |
|---|---|---|---|
| 0. Brief | Arkusz pokręteł (5 pokręteł, produkcja, perkusja, szablon formy, ekonomia riffów, rola na albumie) | G0: pokrętła są spójne | 10–15 min |
| 1. Kotwica | Strój, pedał, pole dźwiękowe | G1: pedał jest grywalny i słyszalny | 10 min |
| 2. Warstwa wolna | Szkielet 2–4 taktów z akordów albo długich dźwięków | G2: kontrola harmonii | 20–40 min |
| 3. Głos górny | Śpiewna linia melodyczna | G3: test fortepianu | 15–30 min |
| 4. Realizacja | Riff na gitarze (archetyp + układ akordu) | G4: brzmienie pod przesterem | 30–60 min |
| 5. Tempo i perkusja | Tempo, groove każdego riffu (werbel na miarę i gęstość stopy), rytm harmoniczny w sekundach | G5: groove i sekundy na harmonię | 20–30 min |
| 6. Rodzina riffów | Riffy 2–4 wyprowadzone z riffu 1 | G6: każdy riff ma zapisane pochodzenie | 1–2 h |
| 7. Plan powtórzeń | Mapa powtórzeń | G7: jedna zmiana na cykl | 20 min |
| 8. Forma i przejścia | Mapa sekcji z taktami, sekundami i regułą kulminacji | G8: forma i przejścia | 45–60 min |
| 9. Aranżacja | Siatka ról (6 instrumentów × sekcje) i arkusz perkusji | G9: aranżacja | 1,5–3,5 h |
| 10. Audyt pułapek | Wypełniona tabela audytu | G10: brak pułapki bez zwolnienia | 20–30 min |
| 11. Demo i odsłuch | Pełne demo i notatki z odsłuchu | G11: protokół odsłuchu | 1–2 h + przerwa |
| 12. Selekcja | Decyzja: zostaw, przepisz albo odrzuć | G12: lista końcowa | 20 min |

## Brief: wybierz podgatunek i ustaw pokrętła (faza 0)

**Dane wejściowe:** pomysł na utwór.

### Podgatunki: cechy rozpoznawcze i utwory wzorcowe

Każdy podgatunek ma własny język dźwiękowy. Wybierz podgatunek po cechach, a potem sprawdź go na utworach wzorcowych.

| Podgatunek | Cechy rozpoznawcze | Utwory wzorcowe |
|---|---|---|
| norweski | Centrum na otwartej strunie, `♭2` jako interwał definiujący, dwudźwięki przesuwane o półton albo tryton nad pedałem, arpeggia tremolo, blast `170–210 BPM` na zmianę z wolnym `3/4` | Mayhem „Freezing Moon”, Emperor „I Am the Black Wizards”, Immortal „Blashyrkh”, Thorns „Aerie Descent” |
| raw | 2–4 riffy w wielu powtórzeniach, jeden stały groove w `136–190 BPM`, dwudźwięki pedałowe, brak klawiszy | Darkthrone „Transilvanian Hunger”, Ildjarn „Natt og tåke”, Mütiilation „Transylvania” |
| symfoniczny | Rdzeń norweski plus akordy kolorystyczne i funkcyjne (`add9`, `sus2`, `dim7`, `V` z molowej harmonicznej), medianta `i–♯iii`, metrum `6/8` i `3/4`, klawisze niosą melodię | Emperor „Inno a Satana”, Emperor „With Strength I Burn”, Dimmu Borgir „The Promised Future Aeons”, Arcturus *Aspera Hiems Symfonia* |
| szwedzki (melodyczny) | Molowa eolska z dźwiękiem prowadzącym w kadencji `♭VI–V–i`, dwie gitary w tercjach diatonicznych, arpeggia z chromatycznym ogonem, forma piosenkowa, `190–250 BPM` | Dissection „Where Dead Angels Lie”, Dissection „Night's Blood”, Watain „Malfeitor” |
| atmosferyczny | Pedał z wolnym głosem górnym, akordy `sus2`, `maj7`, `add9` grane tremolo, 1–8 taktów na akord, bardzo długie formy | Wolves in the Throne Room „I Will Lay Down My Bones Among the Rocks and Roots”, Drudkh „Forests in Fire and Gold”, Agalloch „In the Shadow of Our Pale Companion”, Summoning „Land of the Dead” |
| DSBM | Tempo `90–147 BPM`, pętle dwóch akordów, westchnienie `♭6–5`, czyste arpeggio nad pedałem, nierozwiązane współbrzmienia | Shining „Ytterligare ett steg närmare total jävla utfrysning”, Silencer „Sterile Nails and Thunderbowels”, Nocturnal Depression „Nostalgia”, Xasthur „Screaming at Forgotten Tears” |
| blackgaze | Tonika durowa albo mieszana, `IVmaj7` i `♭VImaj7`, akordy kolorystyczne zamiast power chordów, długie narastania od ciszy do głośności | Deafheaven „Dream House”, Alcest „Souvenirs d'un autre monde”, Harakiri for the Sky „Calling the Rain” (odłam post-black, molowy) |
| dysonansowy | `m2` i tryton jako struktura, kotwica w pedale, przesuwanie równoległe, klastry, mało powtórzeń, częste zmiany tempa | Deathspell Omega „Kénôse I”, Deathspell Omega „Abscission”, Svartidauði „Flesh Cathedral”, Misþyrming „Söngur heiftar”, Krallice „Fatestorm Sanctuary” |
| typ Mgły | Molowa eolska z mocną toniką, dwudźwięki nad pedałem sugerujące `i–iv–♭VI–♭VII`, westchnienie `♭6–5`, linia tremolo zmieniająca dźwięk co 4–8 szesnastek, długie powtórzenia | Mgła „Exercises in Futility V”, Mgła „Age of Excuse II” |

### Ustawienia pokręteł według podgatunku

Tabela podaje domyślne ustawienia pięciu pokręteł harmonicznych dla każdego podgatunku. Przepisz wiersz swojego podgatunku do arkusza pokręteł.

| Podgatunek | Jakość akordów | Dialekt dysonansu | Rytm harmoniczny | Poziom powtórzeń | Nośnik melodii |
|---|---|---|---|---|---|
| norweski | dwudźwięki, trójdźwięki sugerowane arpeggiem, przesuwane barré molowe | strukturalny i rzadki | 1 akord na takt albo wolniej (1,0–2,8 s) | średni: mało riffów, ten sam riff w dwóch tempach | gitara rytmiczna, czasem osobna melodia na górze |
| raw | dwudźwięki pedałowe, power chordy | brak albo minimalny, rzadziej twarde dwudźwięki | bardzo wolny (co najmniej 1,6 s) | wysoki: 2–4 riffy | górny głos gitary |
| symfoniczny | `add9`, `sus2`, zwiększone, `dim7`, funkcyjne `V` | funkcyjny z kolorem | szybszy: 4–5 akordów na sekcję | niski albo średni: długie formy z refrenem | klawisze |
| szwedzki | power chordy plus tercje dwóch gitar | funkcyjny | 1–2 akordy na takt w średnim tempie | średni: forma piosenkowa | dwie gitary w tercjach |
| atmosferyczny | `sus2`, `sus4`, `maj7`, `add9` na otwartych strunach | miękki | 1–8 taktów na akord, celowo ponad 4 s | wysoki | gitara prowadząca albo klawisze |
| DSBM | trójdźwięki molowe, zwiększone, klastry | miękki do klastrów | 1–2 takty na akord (1,6–5,3 s) | wysoki: pętle, bloki do 64 taktów | czysta gitara |
| blackgaze | `IVmaj7`, `♭VImaj7`, `add9`, `6/9`, `sus2` | miękki | 1–2 takty na akord | średni: długie łuki, mało riffów | partia prowadząca nad ścianą akordów |
| dysonansowy | dwudźwięki trytonowe i `m2`, klastry | twardy | wolna kotwica pod gęstą powierzchnią | niski: forma przekomponowana | kilka niezależnych linii |
| typ Mgły | dwudźwięki sugerujące trójdźwięki | brak albo minimalny | wolny | wysoki | gitara prowadząca |

Produkcja jest niezależnym pokrętłem. Ulver na *Nattens Madrigal* łączy surową produkcję z prostymi eolskimi melodiami.

### Model pisania perkusji i powierzchnia perkusji

Zdecyduj przed pierwszą nutą, kto pisze perkusję i jak ona zabrzmi. Model pisania perkusji wynika z tego, kto trzyma formę utworu, a nie z podgatunku. W każdym modelu nagrywasz perkusję jako pierwszą, do gitary pomocniczej.

| Model | Przebieg | Przykłady | Typowy wynik |
|---|---|---|---|
| A. kompozytor programuje, perkusista dodaje | Kompozytor pisze z programowaną perkusją. Perkusista dodaje fille i ozdobniki w ramach planu. | Satyricon, Ihsahn solo | partia prowadzona formą, zmiany na granicach sekcji, oszczędna gra |
| B. demo gitar, potem perkusista | Gitarzysta nagrywa gitary z możliwie najprostszą perkusją pomocniczą. Perkusista pisze partię sam po tygodniach słuchania. | Mayhem (Hellhammer), Agalloch, Deafheaven | partia prowadzona riffem, akcenty ride'a za riffem |
| C. wspólne aranżowanie na próbie | Perkusista i kompozytor szukają razem groove'ów i filli. Riffy mogą się przy tym zmienić. | Alcest, Krallice, Watain | riff i perkusja zależne od siebie |
| D. najpierw perkusja | Perkusja powstaje pierwsza, często improwizowana. Utwór dzielisz na bloki według niej. | Mgła, Leviathan | forma blokowa, groove wyznacza granicę bloku |

Powierzchnia perkusji musi pasować do celu produkcji. Triggerowana, idealnie równa stopa brzmi jak współczesny death metal i kłóci się z surową produkcją.

| Powierzchnia perkusji | Kiedy |
|---|---|
| żywa bez triggerów | norweski w manierze lat 1992–95, raw, atmosferyczny |
| żywa ze stopą zmieszaną z triggerem | wypolerowany symfoniczny, szwedzki, współczesny dysonansowy |
| programowana humanizowana | każdy podgatunek, gdy celem jest brzmienie żywej perkusji |
| programowana statyczna | tylko raw, DSBM i atmosferyczny typu Summoning |

### Kroki

1. Wybierz podgatunek docelowy z tabeli podgatunków.
2. Jeśli chcesz świadomej hybrydy, wybierz drugi podgatunek.
3. Wypełnij arkusz pokręteł poniżej według tabeli ustawień pokręteł.
4. Wybierz model pisania perkusji i powierzchnię perkusji z tabel powyżej.
5. Wybierz jeden albo dwa utwory wzorcowe z tabeli podgatunków.

### Arkusz pokręteł (szablon)

| Pokrętło | Opcje | Twoje ustawienie |
|---|---|---|
| Jakość akordów | dwudźwięki / power chordy · trójdźwięki molowe · akordy kolorystyczne (`sus2`, `add9`, `maj7`) · dysonansowe dwudźwięki / klastry | |
| Dialekt dysonansu | brak · miękki (sekundy wewnątrz akordów) · strukturalny i rzadki (`♭2`, `♭5`) · funkcyjny (`♯7`, `V`) · twardy (`m2` / tryton jako harmonia) | |
| Rytm harmoniczny | sekundy na harmonię (domyślnie ≥ 1 s, najlepiej ok. 2 s, w atmosferycznym do 10 s i więcej) | |
| Poziom powtórzeń | niski (forma przekomponowana, bez powrotów materiału) · średni (łańcuch riffów) · wysoki (pętle, bloki 32–64 taktów) | |
| Nośnik melodii | kształt gitary rytmicznej · gitara prowadząca · dwie gitary w tercjach · klawisze · czysta gitara · niezależne linie | |
| Cel produkcji | lo-fi / surowa · klarowna | |
| Model pisania perkusji | A · B · C · D | |
| Powierzchnia perkusji | żywa bez triggerów · żywa ze stopą z triggerem · programowana humanizowana · programowana statyczna | |
| Szablon formy | szablon podgatunku z tabeli szablonów w fazie 8 | |
| Ekonomia riffów | rotacja (mało przejść na riff) · pętla (dużo przejść na riff) | |
| Rola na albumie | otwieracz · epik · zamknięcie · interludium · brak | |

### Bramka G0: pokrętła są spójne

- [ ] Wypełnij wszystkie jedenaście wierszy arkusza pokręteł.
- [ ] Dopasuj ustawienia do jednego wiersza tabeli ustawień pokręteł albo nazwij hybrydę wprost.
- [ ] Jeśli cel produkcji to surowa, wybierz perkusję żywą bez triggerów albo programowaną statyczną (pułapka D12).
- [ ] Dopasuj szablon formy do podgatunku albo nazwij hybrydę.
- [ ] Wybierz jeden dialekt dysonansu na sekcję, nie „wszystkiego po trochu”.

Przykład nazwanej hybrydy: „surowa produkcja + język dźwiękowy typu Mgły”. Produkcja i język dźwiękowy to niezależne pokrętła.

**Jeśli bramka G0 nie przechodzi:** wróć do kroku 3 i przyjmij najbliższy wiersz tabeli ustawień pokręteł jako ustawienie domyślne.

**Możesz tu przerwać.** Arkusz pokręteł jest gotowy. Następna faza: kotwica.

## Kotwica: strój, pedał i pole dźwiękowe (faza 1)

**Dane wejściowe:** arkusz pokręteł z fazy 0.

### Kroki

1. Wybierz strój `E` standard albo `D` standard. Obniżony strój nie jest wymogiem black metalu.
2. Wybierz pedał: otwartą niską strunę, dron syntezatora albo odwrócony wysoki pedał.
3. Jeśli pedał to otwarta struna, użyj `E` albo `A`. W stroju `D` użyj także `D`.
4. Jeśli podgatunek to atmosferyczny albo blackgaze, rozważ odwrócony wysoki pedał.
5. Zapisz domyślne pole dźwiękowe: eolskie z dostępnym `♭2`, czyli sumę eolskiego i frygijskiego nad pedałem.
6. Dodaj do pola składnik podgatunku według tabeli poniżej.

Tabulatury pokazują, że Deathspell Omega od albumu *Kénôse* grają w stroju `D` standard („a Les Paul, a standard D tuning”). Analizy kanonu norweskiego opisują te same utwory raz jako frygijskie, raz jako molowe. Dlatego traktuj `♭2` jako kolor wewnątrz rodziny molowej, a nie jako nakaz skali.

| Podgatunek albo kolor | Dodaj do pola |
|---|---|
| szwedzki, symfoniczny | `♯7` |
| kolor dorycki w dowolnym podgatunku | naturalną `6` |
| blackgaze | tonację durową |
| dysonansowy | słabą tonację z kotwicą |

### Bramka G1: pedał jest grywalny i słyszalny

- [ ] Sprawdź, czy pedał to otwarta struna albo trzymany dron, który brzmi pod chwytanymi kształtami.
- [ ] Zapisz pole dźwiękowe jako listę dźwięków, np. `E F F♯ G A B C D` nad `E`.
- [ ] Sprawdź, czy pole to *jedno* pole z rodziny molowej wokół pedału, a nie lista „złowrogich skal” (pułapka N2).

**Jeśli bramka G1 nie przechodzi:** zmień pedał na otwartą strunę wybranego stroju.

**Możesz tu przerwać.** Strój, pedał i pole dźwiękowe są zapisane. Następna faza: warstwa wolna.

## Warstwa wolna: szkielet harmoniczny (faza 2)

**Dane wejściowe:** pedał i pole dźwiękowe z fazy 1.

**To najważniejsza faza.** Pod tremolo i blastami słuchacz słyszy jako melodię następstwo akordów i długich dźwięków. Tremolo zamienia każdy dźwięk w dźwięk trzymany, a blast zalewa powierzchnię rytmiczną. Ucho schodzi więc do następnej warstwy zmian, czyli do zmian akordów. Gdy perkusja nie daje akcentów, zmiana akordu wyznacza też słyszany początek taktu. Dlatego szkielet powstaje przed riffem.

### Kroki

1. Wybierz wolne narzędzie szkicu: klawiaturę, piano roll w DAW albo akordy blokowe na gitarze.
2. Naszkicuj **2–4 takty** akordów albo długich dźwięków w półnutach albo całych nutach.
3. Zacznij od domyślnego zestawu ruchów z listy poniżej.
   - `i`, `♭II`, molowe `♭vi` albo `iii`, `♭V` osiągnięte o półton.
   - Trójdźwięki molowe oddalone o półton albo `m3`.
   - Technika Rucha: jeden molowy chwyt barré przesuwany równolegle nad otwartym pedałem o półton albo `M3`.
4. Jeśli podgatunek ma własne ruchy, zamień nimi ruchy domyślne według tabeli poniżej.
5. Zapisz progresję cyframi rzymskimi **i** nazwami akordów.

Molowe `♭vi` (trójdźwięk molowy o `M3` pod toniką) to ruch diagnostyczny black metalu. Ogólny metal używa w tym miejscu durowego `♭VI`. Ciąg trójdźwięków molowych odległych o `M3` albo `m3` usuwa poczucie tonacji diatonicznej.

### Przykład: technika Rucha (styl Thorns)

Snorre Ruch z Thorns przesuwa jeden molowy chwyt barré o półton i tercję wielką nad otwartą struną `E`. Każdy akord odpowiada mu uderzenie pustej struny `E`. Przykład gra się w `3/4` w tempie ok. `125 BPM`: barré tremolo na miarach 1–2, pusta struna `E` na mierze 3.

```
          Em          Fm          E♭m         Cm          Bm          Em
e|--3---------|--4---------|--2---------|------------|------------|--3---------|
B|--5---------|--6---------|--4---------|--4---------|--3---------|--5---------|
G|--4---------|--5---------|--3---------|--5---------|--4---------|--4---------|
D|--2---------|--3---------|--1---------|--5---------|--4---------|--2---------|
A|------------|------------|------------|--3---------|--2---------|------------|
E|--------0-0-|--------0-0-|--------0-0-|--------0-0-|--------0-0-|--------0-0-|
```

- Wynik: każdy akord jest molowy, a kolor wynika tylko z położenia podstawy względem pedału `E`: `F` to `♭II`, `C` to molowe `♭vi`, `B` to molowe `v`.
- Głos górny: `G–A♭–G♭–E♭–D–G`, opadająca linia chromatyczna z powrotem.
- Sprawdzenie: jeden takt `3/4` w `125 BPM` trwa ok. 1,4 s, więc mieści się w progu 1 s na harmonię.
- Wariant: zamień `Fm–E♭m` na `A♭m–Gm` albo zsuwaj chwyt półtonami od `A♭m` do `Cm`.

| Podgatunek | Ruchy podgatunku |
|---|---|
| szwedzki | `♭VI–V–i` |
| symfoniczny | `i–♯iii` i jedna kadencja funkcyjna |
| atmosferyczny | cykle `sus2` / `maj7` |
| DSBM | pętla dwóch akordów |
| blackgaze | `IVmaj7` albo zapożyczony `♭VImaj7` |
| dysonansowy | przesuwane równolegle dwudźwięki trytonowe albo `m2` |

### Bramka G2: kontrola harmonii

- [ ] Umieść co najmniej jeden niediatoniczny ruch trójdźwięku molowego: `♭vi`, `iii`, relację półtonu albo `m3` (pułapka P3).
- [ ] Jeśli podgatunek to blackgaze, umieść zamiast tego co najmniej jeden akord kolorystyczny, np. `IVmaj7`.
- [ ] Sprawdź, czy `♭2` to jeden kolor z wielu, a nie jedyny środek mroku. Nadużyty `♭2` staje się „klatką obniżonych supertonik” (Stabler).
- [ ] Jeśli podgatunek to nie blackgaze, usuń durową *tonikę* i ruch `I–IV–V` (pułapka P7, N1).
- [ ] Zostaw akordy durowe tylko jako zdarzenia chromatyczne.
- [ ] Jeśli podgatunek nie dopuszcza kadencji `V–i`, zamknij frazę inaczej (pułapka P14).
- [ ] **Test ucha:** zagraj szkielet zwykłymi akordami blokowymi, czysto i wolno. Szkielet ma już brzmieć mrocznie (blackgaze: słodko-gorzko).

Kadencję `V–i` dopuszczają: szwedzki, funkcyjny biegun symfonicznego (np. Bal-Sagoth) i wczesny Gorgoroth. Inne zamknięcia to `♭VI→i`, `♭VII→i`, `♭II→i`, medianta→`i` albo otwarte zakończenie na pedale.

Mrok musi wynikać z ruchu podstaw akordów, nie z przesteru. Przester mocno obniża przyjemność brzmienia akordów molowych, a słuchacze metalu reagują na dysonans strukturalny, nie na brud brzmienia. Dlatego test ucha odbywa się bez przesteru.

**Jeśli bramka G2 nie przechodzi:** zamień jeden akord diatoniczny na trójdźwięk molowy o `M3` niżej od toniki (`i–♭vi`). Potem powtórz test ucha.

**Możesz tu przerwać.** Szkielet jest zapisany cyframi rzymskimi i nazwami akordów. Następna faza: głos górny.

## Głos górny: melodia wyprowadzona ze szkieletu (faza 3)

**Dane wejściowe:** szkielet 2–4 taktów z fazy 2.

### Kroki

1. Wypisz najwyższy dźwięk każdego akordu szkieletu.
2. Połącz te dźwięki w linię.
3. Wygładź linię: prowadź ją głównie sekundami, w zakresie około oktawy.
4. Jeśli podgatunek to symfoniczny, poszerz zakres, bo melodię niosą tam klawisze.
5. Dodaj jedno zabarwienie: dźwięk sąsiedni `♭2`, westchnienie `♭6–5` albo chromatyczny dźwięk sąsiedni (`E–D♯–E`).
6. Jeśli chcesz zastosować model Ihsahna, napisz osobną śpiewną melodię nad oscylacją akordów.

### Bramka G3: test fortepianu

Zakres testu zależy od faktury sekcji.

| Jeśli… | To… |
|---|---|
| sekcja ma typową fakturę | przeprowadź test na całej melodii |
| sekcja to ściana dysonansowa albo ściana akordów blackgaze | przeprowadź test tylko na głosie górnym i zaakceptuj słabszy wynik, bo te faktury zależą od barwy |

- [ ] Zagraj samą melodię na fortepianie albo gitarze akustycznej, bez przesteru i perkusji. Melodia ma być rozpoznawalna i warta słuchania (test Ihsahna).
- [ ] Sprawdź, czy zakres melodii mieści się w około oktawie. Wyjątek: symfoniczny i dysonansowy.
- [ ] Jeśli podgatunek to norweski, raw albo DSBM, ogranicz skoki większe niż kwarta do jednego lub dwóch na frazę.
- [ ] Zaśpiewaj albo zanuć melodię po trzech odsłuchach.

**Jeśli bramka G3 nie przechodzi:** wróć do fazy 2 i zmień jeden akord tak, żeby głos górny poruszał się sekundą.

**Możesz tu przerwać.** Melodia przeszła test fortepianu. Następna faza: realizacja riffu.

## Realizacja riffu na gitarze (faza 4)

**Dane wejściowe:** szkielet z fazy 2 i melodia z fazy 3.

### Kroki

1. Wybierz archetyp riffu z tabeli archetypów poniżej.
2. Ułóż tercje, rozszerzenia i dźwięki dysonansowe na **wyższych** strunach.
3. Ułóż podstawy akordów i drony na niskich strunach.
4. Jeśli grasz arpeggio tremolo, trzymaj chwyt i graj około 4 uderzeń na strunę.
5. Jeśli grasz arpeggio tremolo, nie kładź dwóch sąsiednich dźwięków na jednej strunie. Wtedy dźwięki „lepią się” do siebie.
6. Dopasuj gęstość akordu do produkcji według tabeli poniżej.

| Archetyp riffu | Gdzie występuje |
|---|---|
| riff na pedale (pusta struna na zmianę z ruchomymi kwintami) | norweski |
| dwudźwięki kwintowe grane tremolo | norweski, raw |
| arpeggio tremolo nad chwytem akordu | norweski |
| wolny vamp `i–♭II` (powtarzany motyw dwóch akordów) | norweski |
| trzymany dźwięk tremolo nad dwudźwiękami pedałowymi | typ Mgły |
| arpeggio molowe z chromatycznym ogonem | szwedzki |
| pełny akord grany tremolo | blackgaze, atmosferyczny |
| dysonansowe dwudźwięki przesuwane równolegle | dysonansowy |
| chwyt barré przesuwany równolegle z odpowiedzią pedału | norweski (Thorns, Mayhem *De Mysteriis Dom Sathanas*) |
| power chordy na chromatycznych podstawach nad stałym groove'em | raw (Ildjarn, Vlad Tepes, Akitsa) |

Tercje układasz wysoko, bo przester wytwarza tony kombinacyjne. Tony kombinacyjne nisko ułożonej tercji spadają w subbas, więc akord molowy traci charakter i brzmi jak błoto. Przesterowana kwinta sama sugeruje już tercję wielką.

| Jeśli… | To… |
|---|---|
| produkcja jest lo-fi albo riff idzie pod szybki blast | użyj dwudźwięków |
| miks jest klarowny | użyj pełnych trójdźwięków i rozszerzeń |

### Bramka G4: brzmienie pod przesterem

- [ ] Nagraj riff dwa razy: czysto (albo DI) i z docelowym przesterem.
- [ ] Sprawdź w nagraniu z przesterem, czy słychać *jakość* akordu: mol, dur albo dysonans.
- [ ] Jeśli niskie tercje zamieniają się w błoto, przenieś je wyżej na gryfie (pułapka P4).
- [ ] Sprawdź, czy struny wybrzmiewają bez niezamierzonego palm mutingu (pułapka P1).
- [ ] Sprawdź, czy tremolo jest równe, a zmiany akordów wpadają w czas. Liczba uderzeń nie ma znaczenia (pułapka P12).
- [ ] Sprawdź, czy riff powstał z chwytów nad pedałem, a nie z gamy granej na jednej strunie (pułapka P11, N2).

Wyjątki od ostatniego punktu: szwedzkie linie gamowe i jednogłosowe linie typu Mgły.

**Jeśli bramka G4 nie przechodzi:** zredukuj chwyt do dwudźwięku albo przenieś go na otwarte wyższe struny. Potem nagraj riff ponownie.

**Możesz tu przerwać.** Riff 1 jest nagrany czysto i z przesterem. Następna faza: tempo i perkusja.

## Tempo, groove perkusji i rytm harmoniczny (faza 5)

**Dane wejściowe:** riff 1 z fazy 4.

### Werbel wyznacza charakter groove'u, a stopa jego intensywność

Nazwij groove po liczbie uderzeń werbla na odczuwaną miarę, bo ta liczba wyznacza charakter groove'u. Gęstość stopy zapisz osobno, bo wyznacza intensywność. Half-time z pojedynczą stopą i half-time z podwójną stopą mają ten sam charakter, ale inną energię.

Licz też uderzenia stopy i werbla na sekundę, nie zapisane BPM. Zapis w połowie albo w podwójnym tempie nie zmienia tego, co słyszy słuchacz. Dla szesnastek licz wzorem `uderzenia/s = 16 × BPM / 240`. Blast szesnastkowy w `138 BPM` to nadal blast beat.

| Groove | Plik w bibliotece | Werbel na miarę | Stopa | Definicja |
|---|---|---|---|---|
| tradycyjny blast beat | `traditional-blast` | 2 | połowa strumienia | naprzemienna stopa i werbel, co najmniej 9 uderzeń/s |
| blast `6/8` | — | 2 | połowa strumienia | blast beat w metrum `6/8` |
| skank | `skank` | 1 | na mierach | naprzemienna stopa i werbel, 5–9 uderzeń/s. Poniżej 5 uderzeń/s to polka. |
| podwójna stopa z werblem na słabą ósemkę | `double-kick-offbeat-snare` | 1 | ciągła | werbel na każdej słabej ósemce nad szesnastkami stopy |
| werbel na każdą miarę | `snare-every-beat` | 1 | ciągła albo ósemki | do `130 BPM` brzmi jak marsz, powyżej jak napęd |
| podwójna stopa + backbeat | `double-kick-backbeat` | 0,5 | ciągła | werbel na 2. i 4. mierze nad szesnastkami stopy |
| backbeat | `backbeat` | 0,5 | na atakach riffu | werbel na 2. i 4. mierze taktu |
| d-beat | `d-beat` | 0,5 | podwójne uderzenie przed werblem | punkowy wzór, w black metalu rzadki |
| groove złożony | `compound` | 0,5 | na atakach riffu | groove w `6/8` albo `12/8`, werbel raz na dwie ćwierćnuty z kropką |
| half-time | `half-time` | 0,25 | na atakach riffu | werbel na 3. mierze taktu `4/4`, w metrum złożonym na 3. ćwierćnucie z kropką |
| half-time + podwójna stopa | `half-time-double-kick` | 0,25 | ciągła | half-time nad szesnastkami stopy |
| doom | `doom` | 0,25 | na atakach riffu | wolny groove w `50–80 BPM` |
| groove na tomach | `tom-groove` | 0,25 | na atakach riffu | tomy niosą groove zamiast werbla |
| puls stopy i plama talerzy | `kick-pulse-wash` | 0 | puls | stopa odmierza puls, talerz wybrzmiewa, werbla brak |
| stały groove raw | — | 1–2 | zależna od groove'u | jeden groove przez cały utwór, tylko w podgatunku raw |
| tacet | — | 0 | brak | perkusja milczy jako zapisana rola sekcji |

Siatki, tempa i pliki MIDI dla każdego groove'u z kolumny „Plik w bibliotece” zawiera [biblioteka groove'ów (`grooves/README.md`)](grooves/README.md). Otwórz ją, żeby pobrać gotowy wzór. Galop (`gallop`) jest w bibliotece tylko jako wzór do unikania (pułapka D7).

### Drabina groove'ów: zmieniaj groove o jeden szczebel przy stałym pulsie

Przy tym samym tempie ten sam naprzemienny wzór stopy i werbla daje kolejne groove'y przez dzielenie gęstości. Dlatego zmiana groove'u nie wymaga zmiany tempa. 85% zmian groove'u w nagraniach zachowuje tempo i metrum. Większość zmian przesuwa groove o jeden szczebel drabiny:

`tradycyjny blast` → `skank`, `podwójna stopa z werblem na słabą ósemkę` albo `podwójna stopa + backbeat` → `backbeat` → `half-time`

Do blastu wchodzisz z biegnącej stopy, czyli z podwójnej stopy albo backbeatu w tym samym BPM. Half-time kontrastuje z backbeatem, a nie z blastem. Skok z half-time prosto do blastu jest rzadki.

Prawdziwa zmiana tempa wyróżnia podgatunek. Symfoniczny i dysonansowy zmieniają tempo na ok. 30% granic sekcji. Typ Mgły i DSBM nie zmieniają tempa wcale.

### Typ riffu wskazuje groove

Najpierw piszesz perkusję do riffu, potem do formy. Tabela podaje groove pasujący do każdego typu riffu.

| Typ riffu | Groove | Przykład |
|---|---|---|
| tremolo | blast albo skank. Druga opcja: wolniejszy groove pod tremolo (half-time albo backbeat), czyli „tremolo nad pulsem”. | Darkthrone „Transilvanian Hunger” (blast), half-time pod tremolo w DSBM i blackgaze |
| trzymane akordy, długie dźwięki | half-time albo doom. Druga opcja: blast pod trzymanymi akordami. | Emperor „In the Wordless Chamber” (half-time), Deathspell Omega „Abscission” i Wolves in the Throne Room „Mountain Magick” (blast pod akordami) |
| riff rytmiczny na pedale | backbeat albo podwójna stopa + backbeat, stopa na atakach riffu | Keep of Kalessin „Reclaim” |
| synkopa na słabej mierze | skank | Wolves in the Throne Room „Ex Cathedra” |
| riff w `6/8` albo `12/8` | groove złożony albo blast `6/8` | Dissection, Immortal „Grim and Dark” |

Sprzeczność między riffem a groove'em może być celowa. Perkusja w normalnym tempie pod gitarą tremolo w sekstolach brzmi „jednocześnie szybko i wolno” (Myrkur „Elleskudt”).

### Profil perkusji według podgatunku

Profil podaje środek podgatunku, nie regułę. Udział blastu w pojedynczych utworach norweskich waha się od 0 do 54%. Cisza perkusji to udział czasu utworu bez perkusji.

| Podgatunek | Główny groove poza blastem | Udział blastu (budżet) | Tempo odczuwane | Cisza perkusji |
|---|---|---|---|---|
| norweski | half-time, backbeat, podwójna stopa | ok. 28%, do ok. 55% w utworze | `143 BPM` | 7% |
| raw | skank albo polka, backbeat | 0–99% (stały groove) | `145 BPM` | 6% |
| symfoniczny | podwójna stopa + backbeat | ok. 14% | `148 BPM` | 3% |
| szwedzki | groove złożony, skank | ok. 10% | `151 BPM` | 6% |
| atmosferyczny | half-time, podwójna stopa + backbeat | ok. 13% | `135 BPM` | 9% |
| DSBM | backbeat, half-time | ok. 1% | `101 BPM` | 19% |
| blackgaze | half-time | ok. 4% (blast tylko w typie Deafheaven) | `126 BPM` | 17% |
| dysonansowy | half-time | ok. 29%, do ok. 55% w utworze | `151 BPM` | 8% |
| typ Mgły | podwójna stopa + backbeat, half-time | ok. 15% | `162 BPM` | 18% |

Szwedzki styl blastowy (Marduk „Panzer Division Marduk”, Dark Funeral „Diabolis Interium”) blastuje przez ok. 75% utworu. To inny styl niż szwedzki melodyczny z tabeli.

### Kroki

1. Wybierz tempo z tabeli temp poniżej.
2. Wybierz groove każdego riffu z tabeli typów riffu.
3. Policz uderzenia na sekundę wzorem `16 × BPM / 240`.
4. Nazwij groove według tabeli groove'ów: werbel na miarę i uderzenia na sekundę.
5. Zapisz gęstość stopy osobno: stopa na atakach riffu albo ciągłe szesnastki.
6. Jeśli groove jest rzadki, wypisz ataki riffu i zaznacz te, które dubluje stopa.
7. Zapisz wstępny talerz prowadzący: hi-hat, ride, crash albo dzwon ride'a. Ostateczny wybór zapada w fazie 9.
8. Policz czas trwania każdej harmonii wzorem poniżej.
9. Jeśli metrum to `6/8`, sprawdź, czy BPM liczy ćwierćnuty z kropką.
10. Jeśli BPM w `6/8` liczy ćwierćnuty z kropką, daj każdemu akordowi 2–4 takty.

W kroku 6 stopa dubluje pierwszą miarę i synkopy riffu. Daje to ok. 1 uderzenie stopy na miarę w backbeacie i ok. 0,7 w half-time. Pod blastem i podwójną stopą stopa jest pulsem, więc plan ataków nie jest potrzebny.

Tempo i groove wyznaczają, ile taktów potrzebuje jeden akord.

| Groove i podgatunek | Tempo | Typowy czas akordu | Sekundy na akord |
|---|---|---|---|
| blast `4/4` (norweski, raw, islandzki) | `170–250 BPM` | 1–2 takty, w raw 8–16 uderzeń na dwudźwięk | 1,0–2,8 s. Powyżej ok. `240 BPM` wybierz 2 takty. |
| blast `6/8` (Immortal, Emperor) | `180–220 BPM` | 1 takt `6/8` | 0,55–0,67 s, gdy BPM liczy ćwierćnuty z kropką. 1,6–2,0 s, gdy BPM liczy ósemki. |
| stały groove raw | `136–146 BPM` | 1 takt albo więcej | co najmniej 1,6 s |
| średnie tempo (szwedzki) | `120–160 BPM` | 1 takt, 2 akordy na takt tylko przy wolnym końcu zakresu | 1,5–2,0 s na takt |
| DSBM (`3/4`, `6/8`, `8/4`) | `90–147 BPM` | 1–2 takty | 1,6–5,3 s |
| bloki atmosferyczne | `95–195 BPM` | 1–8 taktów | do ponad 10 s, celowo |
| half-time albo wolne powtórzenie riffu | ok. połowa tempa blastu | te same akordy | ten sam czas w sekundach |

Wzór do kroku 8:

**sekundy na harmonię = `takty na akord × miary w takcie × 60 / BPM`**

Przykład: 1 takt `4/4` przy `220 BPM` trwa `4 × 60 / 220` = **1,09 s**. To wartość na granicy, więc wybierz 2 takty, czyli 2,18 s.

Przykład do kroku 10: gdy BPM w `6/8` liczy ćwierćnuty z kropką, jeden takt trwa tylko 0,55–0,67 s. Dlatego akord potrzebuje 2–4 taktów.

### Bramka G5: groove i sekundy na harmonię

To bramka miękka. Jeśli przekraczasz próg, zapisz jedno zdanie uzasadnienia.

- [ ] Sprawdź, czy każda harmonia trwa **co najmniej ok. 1 s**, najlepiej **ok. 1,5–3 s** (pułapka P2).
- [ ] Jeśli tempo przekracza ok. `240 BPM`, daj każdemu akordowi 2 takty zamiast 1.
- [ ] Przenieś każdą szybszą progresję do sekcji half-time albo średniego tempa.
- [ ] Oznacz każde odstępstwo jako zamierzone.
- [ ] Zapisz groove jako werbel na miarę i uderzenia na sekundę.
- [ ] Sprawdź, czy groove każdego riffu pasuje do typu riffu albo czy sprzeczność jest zamierzona.
- [ ] Jeśli groove jest rzadki, sprawdź, czy stopa leży na atakach riffu (pułapka D2).
- [ ] Sprawdź, czy planowany udział blastu mieści się w budżecie z profilu perkusji podgatunku (pułapka D13).
- [ ] Zagraj riff z pętlą perkusji w docelowym tempie. Zmiany akordów mają być słyszalne i wyznaczać początek taktu.

Dozwolone odstępstwa: statyka atmosferyczna (ponad 4 s na harmonię), gęsta dysonansowa powierzchnia nad wolną kotwicą i szwedzkie średnie tempo bliskie `120 BPM`. Budżet blastu nie dotyczy raw ze stałym groove'em ani szwedzkiego stylu blastowego.

**Jeśli bramka G5 nie przechodzi:** wybierz poprawkę z tabeli poniżej.

| Jeśli… | To… |
|---|---|
| harmonia trwa krócej niż ok. 1 s | podwój liczbę taktów na akord |
| groove zasłania zmiany akordów albo blast przekracza budżet | przesuń groove riffu o jeden szczebel w dół drabiny przy tym samym tempie |
| stopa gra przeciw atakom riffu | przenieś stopę na ataki riffu (krok 6) |

**Możesz tu przerwać.** Tempo, groove każdego riffu i sekundy na harmonię są zapisane. Następna faza: rodzina riffów.

## Rodzina riffów wyprowadzona z riffu 1 (faza 6)

**Dane wejściowe:** riff 1 z fazy 4 oraz tempo i groove z fazy 5.

### Kroki

1. Napisz riff 2 z riffu 1 jedną transformacją z listy poniżej.
2. Napisz riff 3 z riffu 1 jedną transformacją z listy poniżej.
3. Przeprowadź każdy nowy riff przez skrócone fazy 2–5: szkielet, głos górny, realizację i kontrolę sekund.

Transformacje:

- ten sam kontur przesunięty o mediantę chromatyczną (`M3` albo `m3`),
- ta sama komórka nad nowym pedałem (`A` → `E` albo na `♭II`),
- augmentacja half-time,
- wariant pytanie–odpowiedź ze zmienioną odpowiedzią,
- ta sama diatoniczna komórka powtórzona o półton albo `m3` dalej (model Arcturus, np. `Cm–B♭–A♭`, potem `C♯m–B–A`).

Spójność utworu wynika z pokrewieństwa riffów. Neige z Alcest chce „dwóch albo trzech riffów, które mają czas się rozwinąć”, a nie sześciu riffów w jednym utworze. W Dissection każdy riff wyrasta z końca poprzedniego.

### Bramka G6: każdy riff ma zapisane pochodzenie

Liczba riffów w utworze ma górny limit zależny od podgatunku.

| Podgatunek | Riffy w utworze (limit górny) |
|---|---|
| norweski | 5–10 |
| raw | 3–4 |
| symfoniczny | ok. 7 |
| szwedzki | 8–11 |
| atmosferyczny | 6–14 |
| DSBM | 1–2 riffy wypełniające co najmniej 50% czasu |
| blackgaze | 4–9 |
| dysonansowy | 6–12 |
| typ Mgły | 5 |

- [ ] Zapisz przy każdym riffie jego pochodzenie, np. „riff 2 = kontur riffu 1, `M3` w dół”.
- [ ] Sprawdź liczbę riffów z tabelą limitów powyżej.
- [ ] Sprawdź, czy każda sekcja ma 2–4 spokrewnione riffy.
- [ ] Sprawdź, czy żaden riff nie jest obcy wszystkim pozostałym (pułapka P9, „sałatka riffów”).
- [ ] Sprawdź, czy każdy riff przeszedł bramki G2–G5.

**Jeśli bramka G6 nie przechodzi:** usuń niespokrewniony riff albo przepisz go jako transformację riffu 1.

**Możesz tu przerwać.** Rodzina riffów ma zapisane pochodzenie. Następna faza: plan powtórzeń.

## Plan powtórzeń: jedna zmiana na cykl (faza 7)

**Dane wejściowe:** rodzina riffów z fazy 6 i pokrętło „Poziom powtórzeń” z fazy 0.

### Kroki

1. Ustal liczbę powtórzeń każdego riffu jako wielokrotność 2 albo 4.
2. Zapisz dla każdego powtórzenia **jeden** zmieniany parametr z listy poniżej.
3. Jeśli blok to długa pętla (DSBM, atmosferyczny), trzymaj nierozwiązane współbrzmienie zamiast zmian.
4. Oznacz perkusję każdego riffu jako stałą albo przearanżowaną według tabeli perkusji w powtórzeniach.
5. Zmieniaj perkusję w kolejności: najpierw talerze, potem stopa, na końcu werbel.
6. Jeśli riff wraca później w utworze, daj mu inną perkusję niż przy pierwszym wystąpieniu.

Parametry do zmiany: groove, rejestr albo dublowanie oktawowe, wejście drugiej gitary, zmieniony ostatni takt, podmiana jednego dźwięku, nowy pedał pod tą samą linią, tempo. W pętli zmienianą warstwą może być perkusja albo czysta gitara zamiast riffu.

Parametry perkusji do zmiany:

- talerz: zamiana talerza prowadzącego albo przesunięcie akcentu,
- stopa: stopa na atakach riffu zamiast ciągłej albo odwrotnie,
- groove: ten sam riff z nowym groove'em.

Nierozwiązane współbrzmienia do kroku 3: trójdźwięk zwiększony, klaster nad pedałem albo chromatyczna linia `i–V+–V`.

Perkusja stała trzyma ten sam groove we wszystkich powtórzeniach. Perkusja przearanżowana daje powtórzonemu riffowi nowy groove w ok. 1 z 5 powtórzeń, zwykle jako narastanie o jeden szczebel: puls stopy z talerzem → werbel na każdą miarę → half-time → podwójna stopa → blast.

| Podgatunek | Perkusja w powtórzeniach | Co się zmienia |
|---|---|---|
| raw | stała | nic: takty dosłownie, najwyżej jedna zamiana talerza albo jeden fill pod koniec |
| DSBM | stała | ozdobnik albo fill. Pętle typu Lifelover i Xasthur są prawie dosłowne. |
| typ Mgły | stała | tylko talerze |
| atmosferyczny | stała w długich blokach | wzór talerza |
| norweski | przearanżowana | nowy groove w ok. 1 z 5 powtórzeń, najczęściej w ostatnim |
| symfoniczny | przearanżowana | narastanie przez całą sekcję |
| dysonansowy | przearanżowana | albo dosłowne powtórzenie, albo nowy groove |
| szwedzki, blackgaze | zmienna w każdym powtórzeniu | werbel, stopa i talerze |

Riff powracający w późniejszej sekcji ma w nagraniach inną perkusję w 83% przypadków. W raw ten udział wynosi 60%.

### Mapa powtórzeń (szablon)

| Sekcja | Riff | Powtórzenia | Zmiana w cyklu | Perkusja w cyklu |
|---|---|---|---|---|
| A | R1 | 4 | 1: bez zmian · 2: + oktawa · 3: ride zamiast hi-hatu · 4: ostatni takt na `♭II` | stała, w cyklu 3 zmiana talerza |
| … | | | | |

W kolumnie „Perkusja w cyklu” wpisz jedną z wartości: stała, talerz, stopa, groove albo fill.

### Bramka G7: jedna zmiana na cykl

Limit powtórzeń bez zmian zależy od podgatunku (pułapka P8).

| Jeśli… | To… |
|---|---|
| podgatunek to raw | dopuść 8–32 powtórzeń (Fenriz) |
| podgatunek to typ Mgły | dopuść riff 2-taktowy do 32 razy |
| blok to pętla DSBM | dopuść dosłowne przejścia albo jedną zmienianą warstwę na przejście |
| blok trzyma nierozwiązane napięcie | dopuść więcej niż 4 cykle bez zmian |
| żaden z powyższych przypadków | ogranicz blok bez zmian do ok. 4 cykli |

- [ ] Sprawdź każdy blok z limitem z tabeli powyżej.
- [ ] Sprawdź, czy żaden cykl nie zmienia więcej niż jednego parametru naraz.
- [ ] Sprawdź, czy poziom powtórzeń zgadza się z pokrętłem „Poziom powtórzeń” z fazy 0.
- [ ] Sprawdź, czy perkusja każdego riffu jest oznaczona jako stała albo przearanżowana zgodnie z tabelą podgatunków.
- [ ] Jeśli blok jest hipnotyczną pętlą, sprawdź brak filli i zmian groove'u wewnątrz bloku (pułapka D6).
- [ ] Sprawdź, czy zmiany perkusji idą w kolejności: talerze, stopa, werbel.
- [ ] Sprawdź, czy żadne powtórzenie nie zmienia naraz groove'u, fillu i talerza prowadzącego (pułapka P8).
- [ ] Jeśli podgatunek to nie raw, sprawdź, czy każdy powracający riff ma inną perkusję niż za pierwszym razem.

W hipnotycznej pętli zmiana perkusji pada dopiero na styku cykli, nie wewnątrz bloku.

**Jeśli bramka G7 nie przechodzi:** podziel blok albo przypisz zmianę cyklom, które jej nie mają.

**Możesz tu przerwać.** Mapa powtórzeń jest gotowa. Następna faza: forma i przejścia.

## Forma i przejścia między sekcjami (faza 8)

**Dane wejściowe:** mapa powtórzeń z fazy 7 i pokrętła „Szablon formy”, „Ekonomia riffów” oraz „Rola na albumie” z fazy 0.

### Szablony formy według podgatunku

Każdy podgatunek ma własny szablon formy. Okno kulminacji to ułamek długości utworu, np. 0,75 oznacza trzy czwarte utworu.

| Podgatunek | Forma | Długość | Sekcje | Udział intro / outro | Kulminacja (reguła → okno) | Riffy (limit) / jednostka powtórzenia | Udział wokalu |
|---|---|---|---|---|---|---|---|
| norweski | łańcuch riffów w wielu tempach | 4,5–6,5 min | 13–16 | 0–10% / 0–11% | szczyt rejestru → 0,69–0,87 | 8–10 / riff 2–4 takty × 2–4 | 20–45% |
| raw | pętla kilku riffów na jednym groovie | 3–6 min | 9–10 | 0% / 0–9% | brak, jedna nowość w 0,39–0,53 | 3–4 / riff 4 takty × 4–8 | ok. 33% |
| symfoniczny | zwrotka/refren w pierwszej połowie, druga połowa przekomponowana | 4,8–6,2 min | 11–19 | 4–14% / 0–4% | blast po przerzedzeniu albo powrót zawieszenia → 0,69–0,92 | ok. 7 / bloki 4–24 taktów | 39–62% |
| szwedzki | zwrotka/przedrefren/refren × 2, solo, interludia, refren końcowy | 5,9–7 min | 14–19 | 5–20% / 9–26% (oba instrumentalne) | ostatni hook w tercjach → 0,79–0,82 | 8–11 / jednostki 8–16 taktów | 35–41% |
| atmosferyczny | długi łuk bloków z ambientowym interludium | 6–15 min | 11–25 | 0–15% / 0–9% (+ intro jako osobny utwór albumu) | końcowe narastanie → 0,78–0,91 | 6–14 / siatka 16 taktów | 26–29% |
| DSBM | pętla + spadek bez perkusji + instrumentalny ogon | 5–8 min (do 20) | 3–12 | 0–12% / ogon 21–27% | brak (pętla) | 1–2 riffy wypełniają ≥ 50% czasu / pętla 4–8 taktów | 14–37% |
| blackgaze | ciche intro → bloki → czysty reset → długie outro | 6–11,5 min | 7–12 | 4–19% / 14–37% | szczyt rejestru albo warstw → 0,65–0,84 | 4–9 / bloki 16–32 taktów | 29–39% |
| dysonansowy | pary riffów w blokach tempa + rekapitulacja + koda | 4,7–16 min | 7–35 | 9–31% / 16–28% | unikalny późny riff albo repryza tematu → 0,62–0,79 | 6–12 / pary riffów × 2 | nieustalony |
| typ Mgły | bloki 8/16/24/32 taktów, plateau | 7–8,3 min | 12–13 | 5–13% / 7–9% | plateau, ostatni blok po jedynym spadku (ok. 0,7) | 5 / do 32 odtworzeń | 21–47% |

### Kroki: szablon i mapa sekcji

1. Wybierz szablon formy podgatunku z tabeli szablonów.
2. Nazwij ekonomię riffów: rotacja albo pętla.
3. Zapisz mapę sekcji jako ciąg wzorca z taktami, np. `Intro(8) A×4 B×4 A×4 C×2 Outro(16)`.
4. Policz sekundy na takt wzorem `miary w takcie × 60 / BPM`.
5. Rozpisz każde powtórzenie w mapie sekcji.
6. Zsumuj czas wszystkich sekcji.
7. Porównaj całkowitą długość oraz udział intro i outro z szablonem.

Rotacja występuje w norweskich łańcuchach riffów i w blackgaze typu Deafheaven. Pętla występuje w raw, DSBM, typie Mgły i w blackgaze typu Alcest albo Harakiri for the Sky.

### Kroki: otwarcie i kulminacja

8. Wybierz otwarcie z tabeli otwarć poniżej.
9. Umieść pierwszy wokal po instrumentalnym przedstawieniu pierwszego riffu.
10. Jeśli podgatunek to raw, DSBM albo typ Mgły, zdecyduj, czy utwór w ogóle ma kulminację.
11. Jeśli utwór ma kulminację, umieść ją według reguły podgatunku z tabeli szablonów.
12. Przerzedź fakturę przed kulminacją: usuń perkusję, klawisze albo przesterowaną gitarę na 8–16 taktów.
13. Przywróć pełny zespół blastem, partią prowadzącą klawiszy albo najwyższym rejestrem.

Przerzedzenie z kroku 12 trwa zwykle ok. 13–60 s. Nie buduj kulminacji breakdownem (pułapki P10, F6).

| Otwarcie | Gdzie występuje |
|---|---|
| blast *in media res* (od razu w środku akcji, w 1. takcie) | raw, otwieracz norweskiego albumu, typ Misþyrming. Norweskie utwory spoza pozycji otwierającej tak nie zaczynają. |
| riff całego zespołu bez blastu | norweski (poza otwieraczem), symfoniczny, szwedzki, atmosferyczny, blackgaze, dysonansowy |
| wejście samej gitary (4–16 taktów, 5–60 s), potem zespół | raw (Ildjarn), typ Mgły, blackgaze, szwedzki (Watain), norweski (Emperor) |
| czyste albo akustyczne intro | szwedzki, odłam post-black, DSBM, dysonansowy |
| uwertura klawiszy albo ambient | symfoniczny, atmosferyczny. Na albumie lepiej jako osobny utwór intro. |

Sposób budowania kulminacji zależy od podgatunku:

- norweski: szczyt rejestru z solówką albo partią klawiszy w wolnej strefie utworu,
- symfoniczny: zwolnienie i przerzedzenie (klawisze i głos mówiony nad trzymanymi akordami), potem powrót pełnego zespołu z blastem,
- szwedzki: ostatni refren albo powracający riff przearanżowany w tercjach,
- atmosferyczny: narastanie z niezależnym basem i werblem na każdą miarę, potem szczyt z partią prowadzącą nad blastem,
- blackgaze: rejestr i liczba warstw w długiej ścianie outro, nie gęstość perkusji,
- dysonansowy: unikalny późny riff z blastem albo repryza tematu,
- raw, DSBM, typ Mgły: brak narastania, zamiast niego nowość, spadek albo jeden drop.

### Kroki: riffy, granice sekcji i centra tonalne

14. Przypisz riffy do sekcji: liczbę różnych riffów, powtórzenia, powroty i riff kończący.
15. Jeśli riff wraca przekształcony, zmień najpierw groove albo tempo, a dopiero potem dźwięki.
16. Oznacz każdą granicę sekcji znacznikami z listy znaczników granicy poniżej, w podanej kolejności.
17. Zaplanuj przesunięcia centrum tonalnego o półton, cały ton albo tryton.
18. Nie przesuwaj nowej sekcji o tercję wielką.
19. Wybierz zakończenie z tabeli zakończeń poniżej.
20. Jeśli utwór należy do albumu, zapisz jego rolę i sprawdź punkty albumowe bramki G8.

Przesunięcie o tercję wielką nie brzmi w black metalu jak nowa sekcja. Trójdźwięki molowe odległe o `M3` występują już wewnątrz progresji, więc słuchacz słyszy je jako dalszy ciąg tej samej sekcji.

| Zakończenie | Gdzie występuje |
|---|---|
| nowa szybka koda i nagłe zatrzymanie | norweski, symfoniczny, raw (Ildjarn), atmosferyczny (Drudkh, z wydłużoną pętlą) |
| wybrzmienie w wolnej strefie | norweski, typ Mgły (ambientowe outro bez perkusji) |
| powrót riffu otwierającego, potem wybrzmienie albo wyciszenie | raw, szwedzki |
| długie, przerzedzające się outro | blackgaze, dysonansowy, atmosferyczny (Agalloch) |
| wolna koda z trzymanych akordów | szwedzki (Watain „Malfeitor”) |
| wyciszenie | raw, pętle DSBM, epik atmosferyczny |
| statyczny ogon: ostatni riff powtórzony wiele razy | norweski (Darkthrone „Kathaarian Life Code”) |

Liczba różnych riffów z kroku 14 musi mieścić się w zakresie szablonu. Zdecyduj też, czy utwór kończy się riffem otwierającym. Zmiana groove'u albo tempa to najczęstsza transformacja powrotu w black metalu.

Znaczniki granicy wybieraj w tej kolejności. Procent podaje, jak często znacznik występuje na granicach sekcji w nagraniach.

1. Crash ze stopą na 1. mierze nowej sekcji (79%).
2. Zamiana talerza prowadzącego, np. hi-hat na ride (71%). Zamiana nad niezmienionym groove'em wystarcza jako pełny znacznik.
3. Zmiana groove'u przy tym samym tempie (55%).
4. Fill w ostatnim takcie przed granicą (42%): 1–2 miary na tomach albo 1 miara tremolo na werblu, na końcu grupy 4, 8 albo 16 taktów.
5. Zmiana tempa (15%). W symfonicznym i dysonansowym ok. 30%, w typie Mgły i DSBM 0%.
6. Zmiana faktury, włączenie albo wyłączenie wokalu, wejście albo zejście perkusji (w DSBM 43% granic).

Nagłe cięcia są idiomatyczne: 60% granic nie ma fillu.

| Jeśli… | To… |
|---|---|
| podgatunek to raw | oznacz granicę liczbą powtórzeń albo włączeniem/wyłączeniem wokalu. Zostaw ok. połowę granic bez crasha. |
| każdy inny podgatunek | oznacz granicę co najmniej jednym znacznikiem perkusji z listy powyżej |

Udział granic z fillem zależy od podgatunku:

| Podgatunek | Granice z fillem |
|---|---|
| raw | najwyżej ok. 20% |
| atmosferyczny | ok. 25% |
| symfoniczny, dysonansowy, DSBM | ok. 35–40% |
| norweski, szwedzki, typ Mgły | ok. 45–50% |
| blackgaze | do ok. 70% |

### Bramka G8: forma i przejścia

To bramka miękka. Jeśli przekraczasz próg, zapisz jedno zdanie uzasadnienia.

- [ ] Sprawdź, czy mapa sekcji ma postać ciągu wzorca z taktami i sekundami każdej sekcji.
- [ ] Sprawdź, czy całkowita długość mieści się w zakresie szablonu z tolerancją ±20%.
- [ ] Sprawdź, czy typ formy pasuje do szablonu (pułapka F1).
- [ ] Sprawdź, czy pierwszy wokal pada po pierwszym przedstawieniu riffu, co najmniej ok. 6 s od początku.
- [ ] Jeśli podgatunek to raw albo typ Mgły, sprawdź brak intro albo wejście gitary najwyżej 16 taktów.
- [ ] Sprawdź, czy intro wewnątrz utworu zajmuje najwyżej 20% utworu (pułapka F5).
- [ ] Sprawdź, czy kulminacja leży w oknie podgatunku i wynika z nazwanej reguły.
- [ ] Jeśli podgatunek to nie raw ani DSBM, sprawdź przerzedzenie 8–16 taktów przed ostatnim wzrostem (pułapki P10, F6).
- [ ] Sprawdź, czy ostatniego wzrostu nie przygotowuje breakdown ani chug-stop.
- [ ] Sprawdź, czy każda granica sekcji ma znacznik.
- [ ] Jeśli podgatunek to nie raw, atmosferyczny ani DSBM, sprawdź, czy ok. 9 na 10 granic ma znacznik perkusji (pułapki F4, D4).
- [ ] Jeśli podgatunek to atmosferyczny albo DSBM, sprawdź, czy co najmniej ok. 3 na 4 granic mają znacznik perkusji.
- [ ] Jeśli podgatunek to nie raw, sprawdź, czy żaden groove nie zajmuje ponad ok. 70% taktów (pułapka F4).
- [ ] Sprawdź, czy udział granic z fillem mieści się w zakresie podgatunku z tabeli fillów (pułapka D1).
- [ ] Sprawdź brak galopów, chug-stopów i pauzy zespołu pod solowym fillem na granicach (pułapka D7).
- [ ] Sprawdź, czy liczba riffów i powtórzeń mieści się w szablonie, a powroty są zaplanowane.
- [ ] Sprawdź, czy przekształcone powroty zmieniają groove albo tempo przed zmianą dźwięków.
- [ ] Sprawdź, czy zakończenie pasuje do podgatunku według tabeli zakończeń.
- [ ] Jeśli utwór kończy się wyciszeniem, sprawdź, czy forma to raw, pętla albo epik atmosferyczny (pułapka F9).
- [ ] Sprawdź, czy żadna nowa sekcja nie przesuwa tonacji o tercję wielką.
- [ ] Jeśli podgatunek to blackgaze albo atmosferyczny, sprawdź, czy narastanie od ciszy do głośności nie jest pospieszne.
- [ ] Jeśli podgatunek to blackgaze albo atmosferyczny, sprawdź, czy intro zajmuje 4–19% utworu.

Szkielet zwrotka/refren pasuje tylko do szwedzkiego, do pierwszej połowy symfonicznego i do świadomej wolnej formy piosenkowej typu Summoning. Mediana czasu do pierwszego wokalu w korpusie Smialek wynosi 19 s. Utwory raw, DSBM i typu Mgły mogą świadomie nie mieć kulminacji.

### Bramka G8: punkty albumowe

Sprawdź te punkty tylko wtedy, gdy utwór należy do albumu.

- [ ] Sprawdź, czy album ma najwyżej jeden utwór intro, trwający najwyżej ok. 6 min i 13% czasu albumu.
- [ ] Jeśli podgatunek to raw, DSBM albo typ Mgły, sprawdź, czy album nie ma utworu intro (pułapka F5).
- [ ] Sprawdź, czy album ma najwyżej 3 interludia, każde zbudowane z materiału albumu (pułapka F11).
- [ ] Sprawdź, czy najdłuższy utwór leży w ostatniej tercji albumu (pułapka F13).
- [ ] Sprawdź, czy utwory albumu różnią się łukiem i tempem (pułapka F12).

Wyjątek od punktu o najdłuższym utworze: album świadomie w manierze norweskiej albo raw z lat 1992–95.

**Jeśli bramka G8 nie przechodzi:** wybierz poprawkę z tabeli poniżej. Nie naprawiaj problemów formy dodawaniem warstw.

| Jeśli… | To… |
|---|---|
| typ formy albo długość nie pasuje do szablonu | zmień wybór szablonu (krok 1) |
| kulminacja leży poza oknem albo brak przerzedzenia | przesuń kulminację albo wstaw przerzedzenie (kroki 11–13) |
| granica sekcji nie ma znacznika | dodaj znacznik z listy znaczników granicy (krok 16) |
| za dużo albo za mało granic z fillem | zamień fille na cięcia albo odwrotnie według tabeli fillów (krok 16) |
| zakończenie nie pasuje do podgatunku | wybierz zakończenie z tabeli zakończeń (krok 19) |

**Możesz tu przerwać.** Mapa sekcji ma takty, sekundy i kulminację. Następna faza: aranżacja.

## Aranżacja: role instrumentów w sekcjach (faza 9)

**Dane wejściowe:** mapa sekcji z fazy 8 i pokrętło „Nośnik melodii” z fazy 0.

### Kroki: siatka ról

1. Wypełnij siatkę ról (6 instrumentów × każda sekcja) domyślnymi rolami podgatunku z listy poniżej.
2. Oznacz każdą komórkę odbiegającą od roli domyślnej i zapisz powód.

### Domyślne role instrumentów według podgatunku

Każda lista podaje role sześciu instrumentów: gitary rytmicznej, drugiej gitary, basu, perkusji, wokalu i klawiszy.

**Norweski**

- Gitara rytmiczna: riff tremolo z dwudźwięków albo akordów, czysta gitara w czystych przerwach.
- Druga gitara: inne dźwięki w szybkich blokach, unisono w wolnych blokach, solo w kulminacji.
- Bas: dublowanie podstawy, pedał pod solówką, tercje w interludiach, krótki fragment samego basu (Mayhem).
- Perkusja: blast tradycyjny, backbeat i podwójna stopa w zwrotkach, half-time w mostkach, zmiana groove'u na prawie każdej granicy.
- Wokal: krzyk na ok. 3 z 4 bloków riffu. Brak w intro, czystych przerwach, pod solówką i w outro.
- Klawisze: brak w głównych blokach, plama od późniejszych sekcji, partia prowadząca w kulminacji (Emperor).

**Raw**

- Gitara rytmiczna: dwudźwięki tremolo w warstwach unisono od pierwszego taktu.
- Druga gitara: unisono, rozdzielone głosy tylko na riffie-nowości.
- Bas: dublowanie podstawy, zwykle niesłyszalne. Na końcu bas może przejść rejestr wyżej.
- Perkusja: stały groove raw (blast tradycyjny ok. `138 BPM` albo skank ok. `190 BPM`).
- Wokal: krzyk od pierwszego bloku, na co drugim bloku, brak w outro.
- Klawisze: brak w utworze, najwyżej interludia dungeon synth między utworami.

**Symfoniczny**

- Gitara rytmiczna: riff akordowy, trzymane power chordy w kulminacji, milknie w zawieszeniu.
- Druga gitara: tercje w refrenach, unisono albo inne dźwięki w zwrotkach.
- Bas: dublowanie, niezależna linia w zwrotkach (Emperor), pedał w środkowej części `3/4`.
- Perkusja: podwójna stopa + backbeat i backbeat, ride albo prowadzenie crashem (Cradle of Filth) w refrenie, blast tradycyjny dopiero w końcowym bloku.
- Wokal: krzyk w prawie każdym bloku, głos mówiony i chór w zawieszeniu i kulminacji.
- Klawisze: uwertura, plama w każdym refrenie, partia prowadząca w mostkach i w zawieszeniu.

**Szwedzki**

- Gitara rytmiczna: unisono w zwrotkach, riff zharmonizowany w tercjach w refrenie, czyste albo akustyczne interludia.
- Druga gitara: milknie w zwrotkach, tercje w refrenach i outro, solo w środku utworu (0,35–0,56).
- Bas: dublowanie z trzymanymi dźwiękami, tercje z linią harmonii w hookach i outro.
- Perkusja: podwójna stopa w zwrotkach, backbeat (także w `6/8`), skank i ride pod hookami w tercjach.
- Wokal: krzyk w zwrotkach i refrenach. Intro, solówka i outro są instrumentalne.
- Klawisze: brak.

**Atmosferyczny**

- Gitara rytmiczna: czyste albo akustyczne intro, akordy tremolo, przester w połowie zwrotki i w całym refrenie.
- Druga gitara: milknie w zwrotkach, partia prowadząca w refrenie i kulminacji.
- Bas: pedał w intro, niezależna linia w narastaniach, trzymane dźwięki w interludiach.
- Perkusja: długie bloki half-time, skank albo blast, cisza w interludium, werbel na każdą miarę w narastaniu.
- Wokal: brak w intro i narastaniach, krzyk w zwrotkach, koniec przed ostatnią sekcją.
- Klawisze: utwór intro na albumie, partia prowadząca (Summoning) albo powrót syntezatora w kulminacji.

**DSBM**

- Gitara rytmiczna: czyste arpeggio przeciw przesterowanym power chordom, sama czysta gitara w interludium.
- Druga gitara: niezależna linia (czysta przeciw przesterowanej), wysoka linia późno w utworze.
- Bas: dublowanie, pedał w interludium.
- Perkusja: half-time albo backbeat zmieniany co przejście pętli, cisza w interludiach (mediana 17% czasu) i pod mówionym albo krzyczanym wokalem.
- Wokal: krzyk nisko w miksie, także przez fragmenty bez perkusji, brak w ogonie (ostatnie 21–27%).
- Klawisze: plama albo brak, dron w interludium.

**Blackgaze**

- Gitara rytmiczna: warstwowanie od jednej gitary w intro, akordy tremolo, czysty reset, ściana trzymanych akordów w kulminacji.
- Druga gitara: wejście w tercjach, unisono pod blastem, tercje w refrenie.
- Bas: dublowanie, pedał w cichych sekcjach i outro.
- Perkusja: half-time (ok. 42% czasu) i puls stopy, blast tylko w typie Deafheaven jako wczesny szczyt, cisza w czystym resecie.
- Wokal: krzyk albo czysty w blokach, brak w intro, resecie i ogonie.
- Klawisze: brak.

**Dysonansowy**

- Gitara rytmiczna: unisono, czyste trzymane akordy w intro i outro, wariacja w parze riffów.
- Druga gitara: unisono z pierwszą.
- Bas: pedał w intro i outro, niezależna linia albo tercje w wariacyjnej połowie pary riffów.
- Perkusja: blast i half-time na zmianę w parach riffów, zmiana tempa na każdej granicy, outro rozpada się do samych talerzy.
- Wokal: krzyk jako faktura. Brak danych o rozmieszczeniu.
- Klawisze: ambient, organy i chór w intro, plama albo rozstrojony fortepian w outro, zwykle brak w blokach.

**Typ Mgły**

- Gitara rytmiczna: akordy tremolo, jednogłosowa linia tremolo pod hookiem.
- Druga gitara: niezależny hook prowadzący tremolo, kwarty i kwinty.
- Bas: dublowanie, pedał pod hookiem prowadzącym.
- Perkusja: podwójna stopa + backbeat, backbeat albo half-time w blokach z wokalem, blast w blokach instrumentalnych, nowy groove co blok, dzwon ride'a na słabych ósemkach.
- Wokal: krzyk tylko w blokach bez blastu. Hook w refrenie jest instrumentalny.
- Klawisze: brak, plama dopiero w ostatnim refrenie i outro.

### Kroki: gitary i nośnik melodii

3. Wybierz rolę gitar dla każdej sekcji z tabeli ról gitar poniżej.
4. Jeśli podgatunek ma solówki, umieść je w oknie podgatunku z tabeli solówek poniżej (pułapka F7).
5. Przypisz nośnik melodii z arkusza pokręteł według tabeli nośników poniżej.

| Rola gitar | Typowe miejsce |
|---|---|
| unisono | zwrotki, w raw przez cały utwór |
| warstwa oktawowa | brak stałego miejsca |
| tercje albo seksty | hooki: refreny, główny riff, outro |
| niezależna linia | norweskie szybkie bloki, hook prowadzący typu Mgły |
| czysta albo akustyczna gitara | interludia, pętle DSBM |
| tacet (jedna gitara milknie) | sekcja kontrastu |

| Podgatunek | Miejsce solówki |
|---|---|
| szwedzki | środek utworu (0,35–0,56) |
| norweski | późno, w wolnej strefie (0,69–0,87) |
| atmosferyczny typu Agalloch | solówka dozwolona |
| raw, DSBM, blackgaze, dysonansowy, typ Mgły | brak solówek |

| Nośnik melodii | Podgatunek |
|---|---|
| dwie gitary w tercjach diatonicznych | szwedzki, tylko wybrane fragmenty |
| klawisze | symfoniczny. Klawisze niosą też dźwięki kolorystyczne `♭2`, `♭6–5` i `V7`. |
| czyste arpeggio | DSBM |
| partia prowadząca nad ścianą akordów | blackgaze |
| niezależne linie | dysonansowy (Krallice) |

### Kroki: bas

6. Ustaw bas domyślnie na dublowanie podstawy albo oktawy w rytmie gitary.
7. Jeśli podgatunek to nie raw ani DSBM, wybierz co najmniej jedną sekcję uwolnienia basu z tabeli poniżej.
8. Jeśli bas ma być słyszalny, unikaj ścisłego ruchu równoległego z gitarą.
9. Zrób basowi miejsce: usuń niskie dźwięki gitary z zakresu basu (Pytten).

Krok 9 zastępuje podnoszenie głośności basu. W raw i DSBM bas może dublować gitarę przez cały utwór.

| Uwolnienie basu | Gdzie |
|---|---|
| trzymany pedał | ciche sekcje, outro, pod partią prowadzącą tremolo |
| tercje | hooki (Dissection) |
| niezależna linia | narastania w atmosferycznym, część wariacyjna dysonansowej pary riffów |
| krótki fragment samego basu | dowolna sekcja (Mayhem) |

### Kroki: perkusja i arkusz perkusji

Arkusz perkusji zbiera wszystkie decyzje perkusyjne w jednej tabeli. Perkusję piszesz do riffu, potem do formy. Wokal dostaje w niej miejsce, ale nie wyznacza groove'u.

10. Załóż arkusz perkusji z szablonu poniżej, jeden wiersz na sekcję.
11. Przepisz do arkusza groove każdej sekcji z fazy 5.
12. Jeśli groove zmienia się między sekcjami, przesuń go o jeden szczebel drabiny groove'ów przy stałym pulsie.
13. Przypisz każdej sekcji jeden talerz prowadzący z tabeli talerzy prowadzących.
14. Zaplanuj crash ze stopą na 1. takcie sekcji i fraz, na zmianach akordów i na wejściach blastu.
15. Zapisz plan fillu dla każdej granicy: funkcję następnej sekcji i decyzję „fill” albo „cięcie”.
16. Jeśli groove jest rzadki, umieść stopę na podzbiorze ataków riffu, a bas na atakach gitary.
17. Jeśli groove to blast albo podwójna stopa, wybierz warstwę basu z tabeli warstw basu.
18. Jeśli sekcja ma wokal, daj jej ten sam albo lżejszy groove, bez dodatkowych filli i crashy.
19. Jeśli perkusja jest programowana, sprawdź partię z listą perkusji programowanej poniżej.

Gotowe siatki i MIDI groove'ów do kroku 11 zawiera [biblioteka groove'ów (`grooves/README.md`)](grooves/README.md). Agent `drums-composer` (`agents/drums-composer.md`) wypełnia arkusz perkusji, jeśli podasz mu fragment utworu.

#### Arkusz perkusji (szablon)

| Sekcja | Groove | Stopa | Talerz prowadzący | Crash | Perkusja w powtórzeniach | Znacznik granicy | Plan fillu | Warstwa basu | Miejsce dla wokalu |
|---|---|---|---|---|---|---|---|---|---|
| A | backbeat | na atakach riffu | hi-hat | 1. takt, zmiany akordów | stała | crash + zamiana talerza | cięcie | dublowanie gitary | wokal nad lżejszym groove'em |
| … | | | | | | | | | |

#### Talerz prowadzący do kroku 13

| Jeśli… | To… |
|---|---|
| groove to skank, podwójna stopa + backbeat albo backbeat w DSBM | ride |
| groove to blast w symfonicznym | ride |
| groove to blast w raw | hi-hat |
| podgatunek to blackgaze, a sekcja to ściana albo kulminacja | crash albo dzwon ride'a |
| podgatunek to dysonansowy | hi-hat albo crash, splash i crash jako kolor |
| podgatunek to typ Mgły, a groove to podwójna stopa + backbeat | hi-hat, dzwon ride'a na słabych ósemkach jako kolor |
| groove to half-time, werbel na każdą miarę albo puls stopy | crash albo plama ride'a |
| każdy inny przypadek | hi-hat |

Zasady talerzy:

- Trzymaj jeden talerz prowadzący przez całą sekcję. Dysonansowy, blackgaze i typ Mgły mogą go zmieniać także wewnątrz sekcji.
- Poza raw zamieniaj talerz prowadzący na ok. 6 z 10 granic. Kierunek jest dowolny: ride podnosi energię, hi-hat ją uspokaja.
- Pod blastem uderzaj talerz razem ze stopą.
- Traktuj chinę i splash jako kolor w środku sekcji, nie jako talerz prowadzący.
- Nie uderzaj crasha i hi-hatu w jednym uderzeniu, bo perkusista ma tylko dwie ręce.
- Nie uderzaj crasha na każdą pierwszą miarę groove'u. Prowadź crashem tylko w ścianie albo kulminacji (blackgaze, dysonansowy, symfoniczny typu Cradle of Filth).
- Pod melodyczną partią prowadzącą albo hookiem klawiszy ogranicz crashe, bo talerze i gitara tremolo dzielą to samo wysokie pasmo (Pytten). W DSBM szum crashy jest zamierzony.
- W raw uderzaj crash na ok. połowie początków sekcji i prawie nigdy w zwykłych taktach.

Szczegóły zapisane w ghost notes, dzwonie ride'a albo tomach przetrwają tylko w klarownej produkcji. W raw wydawaj szczegół na wybór groove'u i zamiany talerza, bo one przetrwają surowe brzmienie.

#### Talerze i fille według podgatunku

| Podgatunek | Crash na 1. takcie sekcji | Takty z prowadzeniem crashem | Fille na minutę | Granice z fillem |
|---|---|---|---|---|
| norweski | 92% | 1% | 3,5 | 45% |
| raw | 48% | 2% | 0,7 | 18% |
| symfoniczny | 93% | 10% | 2,8 | 36% |
| szwedzki | 90% | 3% | 4,0 | 48% |
| atmosferyczny | 61% | 1% | 1,6 | 23% |
| DSBM | 66% | 4% | 1,3 | 39% |
| blackgaze | 96% | 19% | 2,5 | 67% |
| dysonansowy | 62% | 14% | 3,2 | 37% |
| typ Mgły | 100% | 8% | 1,5 | 48% |

Zasady filli do kroku 15:

- Domyślnie nie graj fillu na granicy. Nagłe cięcie jest idiomatyczne.
- Graj fill 1–2 miary na tomach albo 1 miarę tremolo na werblu, w ostatnim takcie grupy 4, 8 albo 16 taktów.
- Przed ok. połową wejść blastu zagraj krótki fill rozbiegowy.
- Zostaw fille całotaktowe i dłuższe dla norweskiego, szwedzkiego i dysonansowego.
- Rozłóż fille na cały utwór i album. Zasób filli zużyty w pierwszych utworach albumu nuży w następnych.

#### Warstwa basu do kroków 16–17

W rzadkim groove'ie ataki stopy są podzbiorem ataków basu, a ataki basu podzbiorem ataków gitary. W uderzeniach całego zespołu stopa, bas i gitara grają razem. Pod blastem i podwójną stopą stopa jest pulsem, więc wybierasz warstwę basu.

| Warstwa basu | Co gra bas | Podgatunek |
|---|---|---|
| ściana tremolo | tremolo razem z gitarą | norweski, raw, symfoniczny |
| podłoga stopy | ósemki razem ze stopą | szwedzki, atmosferyczny typu Wolves in the Throne Room, blackgaze typu Deafheaven, typ Mgły |
| mieszana | linię między gitarą a stopą, gdy gitara gra wolniej niż blast | dysonansowy |

Podłoga stopy jest słyszalna jako rytm nawet wtedy, gdy przester zasłania wysokość dźwięku basu.

#### Miejsce dla wokalu do kroku 18

Wokal idzie nad lżejszym groove'em, a najcięższy groove leży w blokach instrumentalnych (typ Mgły, norweski). Raw, norweski i zwrotki typu Deafheaven grają blast także pod wokalem. W DSBM perkusja może zamilknąć pod mówionym albo krzyczanym wokalem.

#### Lista perkusji programowanej do kroku 19

- Rozpisz partię na dwie ręce i dwie nogi.
- Nie łącz crasha i hi-hatu w jednym uderzeniu.
- Nie pisz szesnastek pojedynczej stopy powyżej ok. `160–180 BPM`.
- Zróżnicuj velocity: werbel w blaście ok. 90–110, werbel w groove'ach ok. 115–125.
- Ustaw kwantyzację na ok. 90–95%, chyba że powierzchnia perkusji to programowana statyczna.
- Jeśli podgatunek to raw albo DSBM, możesz zostawić statyczny wzór, ale nie rażące brzmienie sampli.

### Kroki: wokal i klawisze

20. Rozmieść wokal na gotowej formie instrumentalnej, bo w większości opisanych praktyk wokal powstaje na końcu.
21. Utrzymaj udział wokalu w zakresie szablonu: domyślnie ok. 50% czasu, w symfonicznym do ok. 60%.
22. Zostaw instrumentalne fragmenty z listy poniżej.
23. Jeśli podgatunek używa klawiszy, umieść je jako znaczniki sekcji z listy poniżej.
24. Zostaw co najmniej jeden typ sekcji bez klawiszy, np. sekcje przejściowe albo wolne.
25. Jeśli podgatunek to raw, nie używaj klawiszy wewnątrz utworu. Zbuduj ambient warstwami gitar tremolo.

Fragmenty instrumentalne do kroku 22:

- przedstawienie riffu otwierającego,
- intro i outro w szwedzkim,
- bloki blastowe typu Mgły,
- ogon DSBM (ostatnie 20–25% utworu),
- czysty reset w blackgaze.

Utwory post-black prowadzone czystym wokalem mogą zostawić wokal krzyczany na finałową kulminację. W DSBM wokal może trwać przez fragmenty bez perkusji.

Miejsca klawiszy do kroku 23: uwertura albo intro, plama w refrenie, odsłonięta partia prowadząca w zawieszeniu albo kulminacji, partia prowadząca w kodzie. Krok 25 nie dotyczy atmosferycznego prowadzonego klawiszami (typ Summoning).

### Kroki: szkic spoza gitary rytmicznej

26. Naszkicuj co najmniej jedną sekcję od groove'u, partii prowadzącej, klawiszy albo wokalu (pułapka N3).
27. Sprawdź, czy sekcje nie mają wszystkie tego samego instrumentu prowadzącego.

Groove perkusji to pełnoprawny punkt wyjścia do kroku 26. Tak pracują Mgła i Leviathan w modelu D z fazy 0.

### Bramka G9: aranżacja

- [ ] Sprawdź, czy siatka ról jest wypełniona dla każdej sekcji.
- [ ] Sprawdź, czy każde odstępstwo od roli domyślnej ma zapisany powód.
- [ ] Sprawdź, czy nośnik melodii zgadza się z arkuszem pokręteł.
- [ ] Sprawdź, czy tercje dwóch gitar leżą w sekcjach z hookiem, a zwrotki w unisonie albo oktawie.
- [ ] Sprawdź, czy solówki leżą w oknie podgatunku i są tematyczne, nie popisowe (pułapki P6, F7).
- [ ] Jeśli podgatunek to raw, DSBM, blackgaze, dysonansowy albo typ Mgły, sprawdź brak solówek albo zapisane uzasadnienie.
- [ ] Jeśli podgatunek to nie raw ani DSBM, sprawdź, czy bas opuszcza podstawę w co najmniej jednej sekcji (pułapka F2).
- [ ] Sprawdź, czy udział wokalu mieści się w szablonie, a przedstawienie riffu otwierającego jest instrumentalne (pułapka F3).
- [ ] Sprawdź fragmenty instrumentalne podgatunku z listy w kroku 22.
- [ ] Jeśli utwór ma klawisze, sprawdź, czy co najmniej jeden typ sekcji ich nie ma (pułapka F8).
- [ ] Jeśli utwór ma klawisze, sprawdź, czy brzmienia są mroczne i nie zasłaniają gitar (pułapka P13).
- [ ] Jeśli podgatunek to raw, sprawdź brak klawiszy wewnątrz utworu.
- [ ] Sprawdź, czy co najmniej jedna sekcja powstała poza gitarą rytmiczną (pułapka N3).

Zwolnione z punktu o tercjach: norweskie szybkie bloki i hooki prowadzące typu Mgły.

Punkty perkusji bramki G9:

- [ ] Sprawdź, czy arkusz perkusji ma wiersz dla każdej sekcji, a model pisania i powierzchnia perkusji są wpisane w arkuszu pokręteł.
- [ ] Sprawdź, czy mieszanka groove'ów pasuje do profilu perkusji podgatunku z fazy 5, a blast mieści się w budżecie (pułapka D13).
- [ ] Sprawdź, czy każda sekcja ma jeden talerz prowadzący, a zamiany padają na granicach (pułapka D4).
- [ ] Sprawdź, czy crashe leżą na początkach sekcji i fraz, zmianach akordów i wejściach blastu, nie na każdej mierze 1 (pułapka D3).
- [ ] Sprawdź, czy powierzchnia talerzy pasuje do epoki utworu wzorcowego (pułapka D15).
- [ ] Sprawdź, czy każda granica ma plan fillu, a fille trwają najwyżej 2 miary (pułapka D1).
- [ ] Jeśli groove jest rzadki, sprawdź, czy stopa leży na atakach riffu (pułapka D2).
- [ ] Jeśli riff to tremolo, sprawdź, czy werbel nie pada na każdą zmianę akordu (pułapka D14).
- [ ] Sprawdź, czy pod każdym blastem i podwójną stopą warstwa basu jest wybrana zgodnie z podgatunkiem albo uzasadniona.
- [ ] Sprawdź, czy sekcje z wokalem nie mają dodatkowych filli ani crashy, a najcięższy groove leży w blokach instrumentalnych.
- [ ] Sprawdź, czy jeden perkusista może zagrać partię, albo czy powierzchnia to programowana statyczna (pułapka D11).
- [ ] Jeśli perkusja jest programowana, sprawdź listę perkusji programowanej (pułapki F10, D8, D10).
- [ ] Jeśli cel to raw albo norweski, sprawdź brak idealnie równych, triggerowanych blastów (pułapka D12).

Zwolnienia z punktów perkusji:

| Punkt | Zwolnione podgatunki |
|---|---|
| jeden talerz prowadzący na sekcję | dysonansowy, blackgaze, typ Mgły |
| fille najwyżej 2 miary | norweski, szwedzki, dysonansowy |
| werbel poza zmianami akordów | symfoniczny i szwedzki w utworach opartych na backbeacie |
| najcięższy groove poza wokalem | raw, norweski, zwrotki typu Deafheaven |

**Jeśli bramka G9 nie przechodzi:** usuń warstwę łamiącą regułę (klawisze, wokal albo drugą gitarę), zanim cokolwiek dodasz. Potem sprawdź, czy każda sekcja nadal ma jedną oznaczoną zmianę względem sąsiednich sekcji.

**Możesz tu przerwać.** Siatka ról i arkusz perkusji są wypełnione. Następna faza: audyt pułapek.

## Audyt listy pułapek (faza 10)

**Dane wejściowe:** mapa sekcji z fazy 8 i siatka ról z fazy 9.

### Kroki

1. Wypełnij tabelę audytu dla całego utworu.
2. Oznacz każdy wiersz jednym statusem z tabeli statusów poniżej.

| Status | Kiedy | Co wpisać w kolumnie „Gdzie / uwaga” |
|---|---|---|
| **OK** | pułapka nie występuje | nic |
| **Zwolnione** | kolumna „Zwolnione podgatunki” obejmuje twój podgatunek | nazwę podgatunku |
| **Do poprawy** | pułapka występuje bez zwolnienia | takt albo riff |

### Tabela audytu

| # | Pułapka | Zwolnione podgatunki | Status | Gdzie / uwaga |
|---|---|---|---|---|
| P1 | Nawyki death i thrash metalu (palm muting z „chugiem”, riffy oparte na rytmie) | hybrydy blackened death i blackened thrash | | |
| P2 | Harmonia szybsza niż ok. 1 s na akord pod blastami | dysonansowy (gęsta powierzchnia nad wolną kotwicą), szwedzki w średnim tempie bliskim `120 BPM` | | |
| P3 | Harmonia diatoniczna z samych power chordów | raw, typ Mgły (dwudźwięki sugerujące trójdźwięki) | | |
| P4 | Tercje i klastry ułożone nisko pod dużym przesterem | raw, gdy mętność jest zamierzona, a melodia nadal słyszalna | | |
| P5 | Nadmiar molowej harmonicznej albo skali frygijskiej dominantowej | szwedzki, symfoniczny biegun funkcyjny, wczesny Gorgoroth (nadal bez przedawkowania) | | |
| P6 | Popisowe solówki (shred) | szwedzki, symfoniczny | | |
| P7 | Przeciek „wesołej” tonacji durowej | blackgaze, folkowy i pogański atmosferyczny. Akordy durowe jako zdarzenia chromatyczne są dozwolone wszędzie. | | |
| P8 | Powtórzenia bez rozwoju albo za mało powtórzeń | brak | | |
| P9 | Sałatka riffów | brak | | |
| P10 | Breakdowny, chug-stopy, formuła czystego refrenu | blackgaze bliski post-hardcore'owi | | |
| P11 | Melodie z przebiegów gamowych zamiast z chwytów | szwedzki (linie gamowe), typ Mgły (linie jednogłosowe), linie arpeggiowe typu Ulver | | |
| P12 | Niechlujne albo spięte tremolo | raw (luz jest tolerowany) | | |
| P13 | Klawisze zasłaniające gitary | symfoniczny: sprawdzasz proporcję, nie obecność klawiszy | | |
| P14 | Kadencje `V–i` wszędzie, częste „poprawne” modulacje | szwedzki, symfoniczny biegun funkcyjny, wczesny Gorgoroth | | |
| N1 | Nadkorekta „tylko akordy molowe” | brak | | |
| N2 | Pisanie z list „złowrogich skal” | brak | | |
| N3 | Szkicowanie tylko na gitarze rytmicznej | brak | | |
| Inne | Jedno arpeggio przez minuty, za dużo pogłosu, riffy zbyt złożone dla blastów, zmiany tonacji o `M3` | blackgaze (tylko dla pogłosu) | | |
| F1 | Szablon zwrotka/refren narzucony stylom łańcucha riffów | szwedzki, pierwsza połowa symfonicznego, wolna forma piosenkowa typu Summoning | | |
| F2 | Bas przyklejony do podstawy gitary w każdej sekcji | raw, DSBM | | |
| F3 | Wokal na każdym riffie | symfoniczny ma najwyższy udział wokalu, ale nadal instrumentalne otwarcie | | |
| F4 | Blast bez przerwy, bez zmiany sekcji | raw. DSBM prawie nie używa blastów, więc pułapka go nie dotyczy. | | |
| F5 | Za długie albo źle umieszczone intro | atmosferyczny (utwór intro), symfoniczny (uwertura), dysonansowy (klamra intro i outro), blackgaze (ciche intro w utworze) | | |
| F6 | Kulminacja przez breakdown | blackgaze bliski post-hardcore'owi | | |
| F7 | Solo w stylu, który go nie ma, albo solo jako domyślna kulminacja | szwedzki (solo w 0,35–0,56), norweski (solo w 0,69–0,87), atmosferyczny typu Agalloch | | |
| F8 | Klawisze w każdej sekcji | atmosferyczny prowadzony klawiszami (typ Summoning), intro i outro dungeon synth | | |
| F9 | Wyciszenie na końcu formy zmierzającej do celu | raw, epik atmosferyczny, pętle DSBM | | |
| F10 | Statyczna programowana perkusja | raw, DSBM, typ Summoning (tylko statyczny wzór, nie rażące brzmienie sampli) | | |
| F11 | Interludia bez materiału (album) | album, którego interludia są zbudowane z materiału albumu | | |
| F12 | Jednolitość albumu: każdy utwór z tym samym tempem, łukiem i długością | album pomyślany jako jedno dzieło (numerowane części), nadal z różnymi blokami tempa | | |
| F13 | Epik na początku nowoczesnego albumu długich form | norweski i raw w manierze lat 1992–95 | | |
| D1 | Za dużo filli: fill na końcu każdej 4-taktowej frazy albo cały zasób filli zużyty na początku | szwedzki, blackgaze, symfoniczny, dysonansowy, fille rozbiegowe przed blastem w norweskim | | |
| D2 | Stopa przeciw atakom riffu w rzadkich groove'ach | blast i podwójna stopa (stopa jest pulsem), stały groove raw | | |
| D3 | Crash na każdej mierze 1 groove'u albo crash i hi-hat w jednym uderzeniu | prowadzenie crashem w ścianie albo kulminacji: blackgaze, dysonansowy, symfoniczny typu Cradle of Filth, refreny `6/8` typu Dissection | | |
| D4 | Ten sam talerz prowadzący i ten sam groove pod zmieniającymi się riffami | raw, długie pętle atmosferyczne i DSBM | | |
| D6 | Fille albo zmiany groove'u wewnątrz hipnotycznej pętli | norweski, symfoniczny, dysonansowy, DSBM typu Nocturnal Depression (ozdobnik w każdym przejściu) | | |
| D7 | Nawyki death metalu i metalcore'u: galopy, chug-stopy, pauza zespołu pod solowym fillem, zatrzymania jako domyślne przejście | riffy z zatrzymaniami typu Immortal w konkretnym utworze, blackgaze bliski post-hardcore'owi | | |
| D8 | Statyczna maszyna poza raw i DSBM albo rażące brzmienie sampli w dowolnym podgatunku | raw i DSBM (tylko statyczny wzór), typ Summoning, zadeklarowana estetyka mechaniczna | | |
| D10 | Płaskie velocity i 100% kwantyzacji w programowanej partii | raw i DSBM (sztywny czas dozwolony, velocity nadal zróżnicowane), zadeklarowana estetyka mechaniczna | | |
| D11 | Partia niegrywalna: trzy kończyny na talerzach, pojedyncza stopa szesnastkami powyżej ok. `160–180 BPM`, nieosiągalne fille | zadeklarowane projekty maszynowe | | |
| D12 | Triggerowana, „klikająca” precyzja w celu raw albo norweskim | współczesny dysonansowy, wypolerowany symfoniczny i szwedzki | | |
| D13 | Blast jako domyślny groove utworu | raw ze stałym groove'em, szwedzki styl blastowy (Marduk, Dark Funeral), norweski i dysonansowy do ok. 55% utworu | | |
| D14 | Werbel na każdej zmianie akordu w riffach tremolo | symfoniczny i szwedzki w utworach opartych na backbeacie | | |
| D15 | Powierzchnia talerzy z niewłaściwej epoki: prowadzenie crashem, chiną albo dzwonem w pastiszu lat 90. albo sam hi-hat w ścianie blackgaze | Peste Noire (prowadzenie crashem w raw), Cradle of Filth | | |

Numery D5 i D9 nie występują. D5 pokrywa się z pułapką P2, a D9 (stopa dublująca tremolo) nie potwierdziła się w pomiarach.

### Bramka G10: brak pułapki bez zwolnienia

- [ ] Sprawdź, czy żaden wiersz nie ma statusu **Do poprawy**.
- [ ] Sprawdź, czy każdy wiersz **Zwolnione** nazywa podgatunek, który go uzasadnia.

**Jeśli bramka G10 nie przechodzi:** wróć do fazy, która odpowiada za wiersz.

| Wiersz z „Do poprawy” | Wróć do |
|---|---|
| P2, D2, D13 | fazy 5 |
| P9 | fazy 6 |
| P8, D6 | fazy 7 |
| P10, F1, F4, F5, F6, F9, D7 | fazy 8 |
| D4 | fazy 8, krok 16 |
| P13, F2, F3, F7, F8, F10 | fazy 9 |
| D1, D3, D8, D10, D11, D12, D14, D15 | fazy 9, kroki 10–19 |
| F11–F13 | punktów albumowych bramki G8 |
| pozostałe wiersze | faz 2–4 |

**Możesz tu przerwać.** Tabela audytu nie ma wierszy „Do poprawy”. Następna faza: demo i odsłuch.

## Demo i odsłuch kontrolny (faza 11)

**Dane wejściowe:** kompletna aranżacja z fazy 9 i czysty audyt z fazy 10.

### Kroki

1. Nagraj pełne demo: gitary, bas, programowaną perkusję i klawisze, jeśli ich używasz.
2. Zmiksuj demo zgrubnie na docelowym poziomie produkcji.
3. Zrób przerwę na co najmniej jedną noc.
4. Przeprowadź protokół odsłuchu z bramki G11 i zapisuj uwagi ze znacznikami czasu.

### Bramka G11: protokół odsłuchu

- [ ] **Odsłuch na zimno:** odtwórz utwór raz w całości bez zatrzymywania. Zaznacz każdy moment spadku uwagi.
- [ ] **Odsłuch akordów:** zanuć warstwę wolną razem z blastami w pełnym tempie.
- [ ] **Porównanie A/B:** odtwarzaj na zmianę demo i utwór wzorcowy z fazy 0 przy wyrównanej głośności.
- [ ] **Odsłuch w połowie tempa** (albo wolnej wersji): sprawdź, czy riffy działają jako melodia, nie tylko jako faktura.
- [ ] **Odsłuch formy ze stoperem:** zapisz czas pierwszego wokalu, przerzedzenia, kulminacji i początku outro.
- [ ] Zamień zapisane czasy na ułamki długości utworu i porównaj je z szablonem z fazy 8.
- [ ] **Odsłuch samej perkusji:** nazwij znacznik każdej granicy (crash, zamiana talerza, groove, fill) i porównaj go z arkuszem perkusji.
- [ ] Policz fille na minutę i porównaj je z tabelą talerzy i filli z fazy 9 (raw ok. 0,7, szwedzki ok. 4).
- [ ] **Porównanie A/B talerzy:** porównaj epokę brzmienia talerzy i gęstość crashy z utworem wzorcowym.
- [ ] **Zewnętrzne ucho** (opcjonalnie): puść utwór jednemu słuchaczowi i zapytaj, który riff został w pamięci.

Każdy znacznik spadku uwagi oznacza problem powtórzeń albo przejść (fazy 7–8). W porównaniu A/B język dźwiękowy ma należeć do tej samej rodziny, a różnice mają być zamierzone. Jeśli słuchaczowi żaden riff nie został w pamięci, wróć do fazy 3.

**Jeśli bramka G11 nie przechodzi:** przejdź do fazy wskazanej przy każdej uwadze. Nie naprawiaj problemów dodawaniem warstw.

**Możesz tu przerwać.** Demo ma notatki z odsłuchu ze znacznikami czasu. Następna faza: selekcja.

## Selekcja riffów i decyzja końcowa (faza 12)

**Dane wejściowe:** demo i notatki z odsłuchu z fazy 11.

Selekcjonuj ostro. Mgła odrzuca „znacznie ponad osiemdziesiąt procent” riffów. Wolves in the Throne Room nagrywa demo każdej melodii w całości przed nagraniem albumu.

### Kroki

1. Oceń każdy riff jedną decyzją: zostaw, przepisz albo odrzuć.

> **UWAGA:** Zapisz odrzucony riff w osobnym pliku, zanim usuniesz go z projektu. Bez kopii riff przepada, a może przydać się w innym utworze.

2. Usuń odrzucone riffy z mapy sekcji.
3. Przejdź listę kontrolną bramki G12.
4. Jeśli selekcja odrzuciła albo zmieniła riff, powtórz fazy 6–11 tylko dla zmienionych sekcji.

### Bramka G12: lista końcowa

- [ ] Sprawdź, czy pod każdym riffem leży pedał albo dron jako kotwica.
- [ ] Sprawdź, czy każda harmonia trwa co najmniej ok. 1 s, najlepiej ok. 2 s.
- [ ] Sprawdź, czy akordy durowe są zdarzeniami chromatycznymi, bez durowej toniki poza blackgaze.
- [ ] Sprawdź, czy riffy powstały z pedału i ruchu chwytów, nie z gamy.
- [ ] Sprawdź, czy utwór ma co najmniej jeden niediatoniczny ruch trójdźwięku molowego (w blackgaze: `IVmaj7`).
- [ ] Sprawdź, czy `♭2` to świadomy kolor, a nie jedyny środek mroku.
- [ ] Sprawdź, czy głos górny jest śpiewny, głównie sekundowy i działa na fortepianie albo gitarze akustycznej.
- [ ] Sprawdź, czy tercje i rozszerzenia leżą wysoko, a niskie struny niosą podstawy i drony.
- [ ] Sprawdź, czy struny wybrzmiewają bez niezamierzonego palm mutingu.
- [ ] Sprawdź, czy każda sekcja ma jeden dialekt dysonansu.
- [ ] Sprawdź, czy każda sekcja ma 2–4 spokrewnione riffy.
- [ ] Sprawdź, czy każde powtórzenie zmienia dokładnie jeden parametr albo trzyma nierozwiązane napięcie.
- [ ] Sprawdź, czy `V–i` występuje tylko tam, gdzie podgatunek ją dopuszcza, a molowa harmoniczna jest dawkowana.
- [ ] Sprawdź brak breakdownów. Ciężar ma wynikać ze zwolnienia i przerzedzenia.
- [ ] Sprawdź brak przesunięć tonacji o `M3` dla nowych sekcji.
- [ ] Sprawdź, czy gęstość harmonii pasuje do produkcji.
- [ ] Sprawdź, czy mapa sekcji mieści się w szablonie formy, a reguła kulminacji jest spełniona albo kulminacji świadomie brak.
- [ ] Sprawdź, czy każda granica sekcji ma znacznik: crash, talerz prowadzący, groove, fill, tempo, fakturę albo włączenie/wyłączenie wokalu.
- [ ] Sprawdź, czy arkusz perkusji mieści się w profilu perkusji podgatunku.
- [ ] Sprawdź, czy granice oznaczają głównie crash, zamiana talerza albo zmiana groove'u, a fille są krótkie i rozłożone na cały utwór.
- [ ] Sprawdź, czy w rzadkich groove'ach stopa leży na atakach riffu.
- [ ] Sprawdź, czy pod każdym blastem warstwa basu jest wybrana.
- [ ] Sprawdź, czy udział wokalu mieści się w szablonie, a przedstawienie riffu otwierającego jest instrumentalne.
- [ ] Jeśli podgatunek to nie raw ani DSBM, sprawdź, czy bas co najmniej raz opuszcza podstawę.

**Gotowe, gdy:** każdy punkt jest zaznaczony, a co najmniej jeden riff przeszedł selekcję bez zmian.

## Diagnoza demo: objaw wskazuje fazę do poprawy

Gdy demo brzmi źle, znajdź objaw w tabeli i wróć do wskazanej fazy.

| Objaw słyszalny w demo | Prawdopodobna przyczyna | Wróć do |
|---|---|---|
| Brzmi jak thrash albo death metal | palm muting, szybkie zmiany akordów, przebiegi gamowe | faza 4, faza 5 |
| Brzmi jak power metal albo muzyka klasyczna | kadencje `V–i`, wszędzie molowa harmoniczna, akordy `dim7` | faza 2 |
| Brzmi jak rock albo pop | diatoniczne power chordy, durowa tonika, `I–IV–V` | faza 2 |
| Melodia znika pod blastami | akordy zmieniają się szybciej niż co ok. 1 s, tercje leżą za nisko | faza 5, faza 4 |
| Akordy brzmią jak błoto | niskie tercje albo klastry pod dużym przesterem | faza 4 |
| Nudzi po minucie | powtórzenia bez zmian | faza 7 |
| Brzmi jak zszywanka | niespokrewnione riffy | faza 6 |
| Zmiana sekcji nie rejestruje się | przesunięcie o tercję wielką | faza 8 |
| Brzmi jednowymiarowo | wszystko naszkicowane na gitarze rytmicznej | faza 9 |
| „Złowrogo”, ale generycznie | `♭2` jako jedyny środek, pisanie z listy skal | faza 2, faza 1 |
| Brzmi jak piosenka popowa | zwrotka/refren narzucone stylowi łańcucha riffów (F1) | faza 8, krok 1 |
| Sekcje zlewają się | brak znaczników granic (F4) | faza 8, krok 16 |
| Kulminacja nie działa | zła pozycja albo brak przerzedzenia przed nią | faza 8, kroki 11–13 |
| Wokal nie daje riffom oddychać | wokal na każdym riffie (F3) | faza 9, kroki 20–22 |
| Bas niesłyszalny i nic nie wnosi | brak uwolnienia, ścisły ruch równoległy (F2) | faza 9, kroki 6–9 |
| Klawisze brzmią jak rozmyta plama | klawisze w każdej sekcji (F8) | faza 9, kroki 23–25 |
| Każda sekcja kończy się tym samym przejściem na tomach | za dużo filli (D1) | faza 9, krok 15 |
| Groove brzmi gęsto, ale riff znika | stopa przeciw atakom riffu (D2), werbel na zmianach akordów (D14) | faza 5, krok 6 |
| Perkusja brzmi jak death metal | blast jako domyślny groove (D13), galopy i chug-stopy (D7) | faza 5, krok 2, faza 8 |
| Sekcje nie rejestrują się mimo zmiany groove'u | brak crasha na mierze 1 albo brak zamiany talerza | faza 8, krok 16 |
| Perkusja brzmi jak maszyna | statyczna maszyna (D8), płaskie velocity (D10) | faza 9, krok 19 |
| Pętla przestaje hipnotyzować | fille wewnątrz bloku (D6) | faza 7, krok 4 |
| Brzmi zbyt nowocześnie jak na wzór z lat 90. | prowadzenie crashem albo dzwonem, triggerowane blasty (D12, D15) | faza 9, kroki 13–14 |

## Granice tego procesu

Proces opiera się na uproszczeniach. Poniżej każde uproszczenie ma podany zakres.

**Model na teraz:** każda harmonia trwa co najmniej 1 s.
**Zakres modelu:** reguła przenosi wartość bazową z popu i rocka (de Clercq: akordy trwają tam 1–4 s w każdym tempie) na black metal. Żaden eksperyment nie sprawdził jej pod blastami. W skrajnych tempach decyduje ucho.

**Model na teraz:** szablony formy z fazy 8 i domyślne role z fazy 9 opisują typowy utwór podgatunku.
**Zakres modelu:** każdy szablon opiera się na ok. 3 utworach na podgatunek, rozpisanych z tabulatur (pewność średnio-niska). Dlatego każdy próg faz 8 i 9 to bramka miękka.

**Model na teraz:** progi perkusyjne z faz 5, 7, 8 i 9 opisują typową partię perkusji podgatunku.
**Zakres modelu:** profile perkusji opierają się na jednej tabulaturze na utwór i 2–7 utworach na podgatunek (pewność średnio-niska). Tabulatury najsłabiej oddają talerze. Traktuj każdy próg perkusyjny jako bramkę miękką i ufaj nagraniu wzorcowemu bardziej niż liczbom.

Dane o utworach pochodzą głównie z tabulatur. Przykład techniki Rucha w fazie 2 jest ilustracją, nie transkrypcją.

Zasada „unikaj zamknięcia `V–i`” (pułapka P14) to wniosek z mechanizmu: pętla riffu domyka się już melodycznie, więc kadencja harmoniczna jest zbędna. Żadne źródło black metalowe nie formułuje tej zasady wprost.

Przejście przez wszystkie bramki daje utwór poprawny stylistycznie, ale nie gwarantuje dobrego utworu. Pokrętła skopiowane bez własnego materiału dają pastisz.

## Stan

- Zrobione: wpisz ostatnią zaliczoną bramkę, np. `G5`, i datę.
- Następny krok: pierwsza faza po ostatniej zaliczonej bramce.
- Powrót po przerwie: otwórz arkusz pokręteł z fazy 0 i mapę sekcji, potem przeczytaj bramkę ostatniej zaliczonej fazy.
