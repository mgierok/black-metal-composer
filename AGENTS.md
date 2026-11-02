# Zasady zapisu treści w repozytorium

Ten plik określa sposób zapisu instrukcji i informacji we wszystkich plikach repozytorium. Stosuj każdą zasadę przy tworzeniu i przy edycji pliku.

## Agenci w repozytorium

Instrukcje agentów leżą w folderze `agents/`. Każdy plik opisuje jednego agenta w formacie niezależnym od narzędzia. Claude Code uruchamia agenta przez opakowanie w `.claude/agents/` o tej samej nazwie.

| Agent | Plik z instrukcjami | Kiedy użyć |
|---|---|---|
| `drums-composer` | `agents/drums-composer.md` | Operator podaje fragment utworu black metalowego i prosi o partię perkusji. |

- Gdy operator prosi o pracę agenta z tabeli, przeczytaj w całości jego plik z instrukcjami i wykonaj go.
- Nowego agenta zapisz w `agents/<nazwa>.md` i dopisz go do tabeli.
- Dla Claude Code dodaj opakowanie `.claude/agents/<nazwa>.md` z frontmatterem i poleceniem przeczytania pliku z `agents/`.

## Zasada nadrzędna

Czytelnik nie może sam odtwarzać celu tekstu, jego hierarchii ani brakujących kroków. Gdy inna zasada koliduje z tą, wygrywa ta.

## Skrypty piszesz po angielsku i bez tych zasad

Skrypt to plik z kodem wykonywalnym, np. `.py`, `.sh` albo `.js`.

- Pisz skrypt w całości po angielsku: kod, komentarze, docstringi i komunikaty wypisywane przez skrypt.
- Nie stosuj do skryptów pozostałych zasad z tego pliku.
- Gdy plik Markdown musi pasować do formatu sprawdzanego przez skrypt, zachowaj ten format. Nie zmieniaj skryptu, żeby dopasować go do tych zasad.

## 1. Język

- Pisz nowe treści po polsku. Wyjątek: skrypty piszesz po angielsku.
- Używaj pełnych polskich znaków. Nie zastępuj ich znakami ASCII.
- Zostaw w oryginale nazwy plików, komendy, identyfikatory kodu, tytuły utworów i nazwy zespołów.
- Zostaw ustalony angielski termin muzyczny (np. `blast beat`, `tremolo picking`). Wyjaśnij go przy pierwszym użyciu.
- Nie tłumacz istniejących plików angielskich bez prośby użytkownika.
- W istniejącym pliku angielskim pisz po polsku tylko całą nową sekcję.

## 2. Budowa pliku

- Użyj jednego nagłówka `#` jako tytułu.
- Po tytule umieść blok orientacyjny: cel pliku, zakres, wymagania i sposób użycia.
- Gdy plik zawiera procedurę, dodaj do bloku warunek ukończenia.
- Nie umieszczaj w bloku orientacyjnym spisu treści ani streszczenia sekcji.
- Ułóż treść w kolejności: orientacja → zasada → przykład → kroki → sprawdzenie → następny krok.
- Pomiń element, który w danym pliku nie ma funkcji.

## 3. Nagłówki

- Zachowaj hierarchię `#` → `##` → `###` bez pomijania poziomów.
- Nazwij sekcję jej treścią albo wynikiem.
- Umieść informację wyróżniającą na początku nagłówka.
- Nazywaj powtarzające się części tak samo we wszystkich plikach.
- Nie zastępuj nagłówka pogrubionym zdaniem.

| Źle | Dobrze |
|---|---|
| `## Informacje` | `## Jak zbudować riff na pedale` |
| `## Część 2` | `## Zmiana tercji zmienia tryb akordu` |
| `## Uwagi` | `## Dlaczego blast beat zasłania zmiany akordów` |

Same nagłówki muszą tworzyć logiczny konspekt pliku.

## 4. Terminy

- Wyjaśnij termin przy pierwszym użyciu jednym zdaniem.
- Używaj potem tej samej nazwy w całym pliku. Nie stosuj synonimów.
- Rozwiń skrót przy pierwszym użyciu, np. "DAW (Digital Audio Workstation)".
- W pliku z więcej niż pięcioma terminami dodaj listę terminów.

## 5. Instrukcje

Stosuj te zasady do każdego numerowanego kroku, zadania i bramki:

1. Zacznij krok od czasownika w trybie rozkazującym, 2. osoba liczby pojedynczej: `zagraj`, `otwórz`, `ustaw`.
2. Zapisz jedną czynność w kroku. Wyjątek: dwie czynności wykonywane jednocześnie.
3. Zmieść krok w 20 słowach. Kod w backtickach liczy się jako jedno słowo.
4. Umieść warunek przed czynnością.
5. Używaj tego samego terminu dla tej samej rzeczy we wszystkich krokach.
6. Podaj wynik albo warunek ukończenia w kroku lub zaraz po nim.

| Źle | Dobrze | Powód |
|---|---|---|
| Należy ustawić tempo. | Ustaw tempo na `180 BPM`. | forma bezosobowa |
| Dokonaj sprawdzenia strojenia. | Sprawdź strojenie. | rzeczownik odczasownikowy |
| Tempo jest ustawiane na 180. | Ustaw tempo na `180 BPM`. | strona bierna |
| Ogarnij riff. | Zagraj riff w tempie `120 BPM` bez błędu. | idiom bez wyniku |
| Po prostu zagraj w sumie wolniej. | Zagraj o `10 BPM` wolniej. | słowa asekuracyjne |
| Zwolnij, jeśli riff traci puls. | Jeśli riff traci puls, zwolnij o `10 BPM`. | warunek po czynności |

## 6. Warunki i rozgałęzienia

- Zapisz dwie lub więcej ścieżek w tabeli "Jeśli… / To…".
- Nie ukrywaj wyjątku na końcu akapitu, gdy zmienia on wykonanie całego zadania.

| Jeśli… | To… |
|---|---|
| tonacja riffu jest ustalona | przejdź do fazy 2. |
| tonacja nie jest ustalona | wybierz pedał w fazie 1. |

## 7. Zdania i akapity

**Akapit**

- Zacznij akapit od zasady albo wniosku.
- Zapisz jedną myśl w akapicie.
- Zacznij nowy akapit, gdy zmienia się pytanie, perspektywa albo czynność czytelnika.
- Sprawdź akapit dłuższy niż 6 zdań. Zostaw go tylko wtedy, gdy podział przerwie łańcuch przyczyny i skutku.

**Zdanie**

- Pisz w stronie czynnej, gdy wiadomo, kto lub co działa.
- Umieść główny wniosek przed wyjątkiem.
- Podziel zdanie z dwoma niezależnymi krokami albo zagnieżdżonymi warunkami.
- Nie używaj podwójnych zaprzeczeń.
- Używaj zaimka tylko z jednoznacznym odniesieniem.
- Nazywaj relację wprost: "`E` jest tercją wielką nad `C`", nie "jest wyżej od niego".
- Sprawdź zdanie dłuższe niż 25 słów.
- Nie używaj średników.
- Nie pisz stylem telegraficznym. Zachowaj czasowniki i spójniki `bo`, `jeśli`, `więc`, `potem`.

## 8. Listy i tabele

| Forma | Kiedy |
|---|---|
| Lista numerowana | Kolejność ma znaczenie. |
| Lista punktowana | Elementy są równorzędne. |
| Checklista `- [ ]` | Czytelnik śledzi ukończenie. |
| Tabela | Porównujesz te same cechy kilku elementów. |
| Akapit | Wyjaśniasz jeden łańcuch przyczyny i skutku. |

- Nazwij kolumny tabeli konkretnie.
- Trzymaj jeden rodzaj danych w kolumnie.
- Nie wkładaj wieloetapowych wyjaśnień do komórek.
- Umieść wniosek tuż przed tabelą albo tuż po niej.
- Nie zamieniaj każdego zdania w punkt listy.

## 9. Formatowanie

- Pogrubiaj tylko najważniejszą zasadę albo etykietę.
- Zapisuj w backtickach: dźwięki, akordy, interwały, wzory, tempo, ścieżki i komendy (np. `Em`, `♭2`, `1–♭3–5`, `180 BPM`).
- Używaj cytatu blokowego tylko dla przykładu tekstu albo wydzielonego zadania.
- Nie przekazuj znaczenia samym kolorem, emoji ani pozycją.
- Stosuj jeden zapis dla jednej rzeczy w pliku (np. `♭5`, nigdy równolegle `b5`).

**Nazwy dźwięków**

- Stosuj anglosaski zapis dźwięków: `C D E F G A B`.
- Zapisuj dźwięk o półton niższy od `B` jako `B♭`. Nie używaj polskich nazw `H` ani `B` w znaczeniu `B♭`.
- Zapisuj znaki chromatyczne symbolami `♯` i `♭` (np. `F♯`, `E♭`). Nie używaj polskich końcówek `-is` i `-es` (np. `fis`, `es`).
- Zapisuj akord molowy z małym `m` (np. `Em`, `B♭m`), nie małą literą (np. `e`).

## 10. Przykłady

- Umieść przykład zaraz po zasadzie, której dotyczy.
- Podaj w przykładzie dane wejściowe, kroki, wynik i sposób sprawdzenia.
- Pokaż najpierw przypadek typowy. Oznacz odstępstwo osobno.

## 11. Treść poboczna

- Oddziel minimum od pogłębienia i od treści opcjonalnej osobnymi sekcjami.
- Nie wstawiaj zastrzeżenia między krok a jego wynik.
- Nie umieszczaj polecenia w uwadze ani w komentarzu bocznym.

## 12. Linki i odwołania

- Nazwij w tekście linku cel linku. Nie używaj "tutaj" ani "więcej".
- Przy linku do wymaganej wiedzy dopisz, po co czytelnik ma tam iść.
- Nie dawaj kilku linków do prawie tej samej treści bez wskazania różnicy.
- W odwołaniu do kodu podaj ścieżkę pliku i nazwę funkcji.

## 13. Długie pliki

- Dodaj punkt `Możesz tu przerwać` po każdej większej operacji.
- Powtórz krótki wzór obok zadania zamiast pisać "patrz wyżej".
- Po dłuższej dygresji przypomnij dane wejściowe jednym zdaniem.
- Zakończ plik z procedurą blokiem `## Stan`:

```markdown
## Stan

- Zrobione: ...
- Następny krok: ...
- Powrót po przerwie: ...
```

## 14. Uproszczenia

- Nie usuwaj związku przyczyna–skutek, warunku działania zasady ani kroku potrzebnego do powtórzenia wyniku.
- Oznacz uproszczenie etykietą `**Model na teraz:**`.
- Podaj zaraz po nim zakres pod etykietą `**Zakres modelu:**`.

## 15. Operacje nieodwracalne

- Wstaw blok `**UWAGA:**` przed każdą czynnością destrukcyjną albo nieodwracalną.
- Zacznij blok od polecenia albo warunku. Potem podaj ryzyko.

> **UWAGA:** Nie uruchamiaj `python make_midi.py` bez kopii folderu `midi/`. Skrypt usuwa nieaktualne pliki `.mid` i nadpisuje pozostałe.

## Szablon pliku

```markdown
# Konkretny tytuł

**Cel:** ...
**Zakres:** ...
**Wymagania:** ...
**Jak używać:** ...
**Gotowe, gdy:** ...

## Zasada

## Przykład

## Kroki

1. Czasownik + jedna czynność + wynik.

## Stan

- Zrobione: ...
- Następny krok: ...
- Powrót po przerwie: ...
```

## Kontrola przed zakończeniem

- [ ] Tekst jest po polsku, z pełnymi polskimi znakami.
- [ ] Blok orientacyjny podaje cel, zakres, wymagania i sposób użycia.
- [ ] Nagłówki same tworzą logiczny konspekt.
- [ ] Każde pojęcie ma jedną nazwę i jest wyjaśnione przy pierwszym użyciu.
- [ ] Każdy krok spełnia 6 zasad z sekcji 5.
- [ ] Tekst nie ma średników, stylu telegraficznego ani słów asekuracyjnych.
- [ ] Żadna uwaga nie ukrywa polecenia.
- [ ] Każda operacja nieodwracalna ma blok `UWAGA` z powodem.
- [ ] Skracanie nie usunęło definicji, warunku ani kroku rozumowania.
