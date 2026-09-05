# Wniosek projektowy i biznesplan: „Pieśń Zapomnianych”

## 1. Streszczenie wykonawcze

„Pieśń Zapomnianych” to narracyjna gra action-RPG z elementami puzzli, osadzona w onirycznym, półotwartym świecie inspirowanym folklorem Europy Wschodniej i kulturą romską. Rdzeniem doświadczenia jest **Harmonia** — system łączący rytm, muzykę i śpiew polifoniczny z walką, nawigacją oraz zmianą otoczenia.

Celem projektu jest doprowadzenie gry do jakości wymaganej dla komercyjnego wydania na Xbox Series X|S i Windows PC. Wnioskowane wsparcie ma finansować przede wszystkim: ukończenie reprezentatywnego Vertical Slice, przygotowanie warstwy platformowej Xbox, optymalizację, QA, testy zgodności oraz projektowanie i testowanie dostępności.

Kwota finansowania, kwalifikowalność poszczególnych kosztów, zakres świadczeń programu DAP oraz dostępność konkretnych benefitów platformowych **nie są w tym dokumencie przedstawiane jako potwierdzone fakty bez aktualnego źródła Microsoft**. Powinny zostać potwierdzone przed submission i odpowiednio wpisane do finalnego formularza.

## 2. Elevator pitch

„Pieśń Zapomnianych” to narracyjna gra action-RPG, w której muzyka jest narzędziem walki, eksploracji i zmiany świata. Gracz jako niema protagonistka wykorzystuje rytm i polifoniczny śpiew, aby przełamywać system opresji, przywracać głos społecznościom i odzyskiwać utracone dziedzictwo kulturowe.

## 3. Core gameplay

### System Harmonii

System Harmonii jest głównym wyróżnikiem projektu. Akcje gracza są projektowane jako rytmiczne sekwencje, których poprawne wykonanie wpływa jednocześnie na:

- skuteczność konfrontacji,
- rozwiązanie zagadek,
- nawigację po półotwartym świecie,
- zachowanie elementów środowiska,
- warstwę muzyczną i atmosferę sceny.

Projekt nie powinien dodawać pobocznych systemów wyłącznie dla zwiększenia listy funkcji. Każda mechanika musi wzmacniać główną fantazję: **używanie muzyki jako sprawczej siły w świecie**.

## 4. Vertical Slice — zakres demonstracyjny

Vertical Slice ma być reprezentatywnym dowodem jakości, a nie jedynie zbiorem prototypowych funkcji. Powinien zawierać jeden kompletny fragment doświadczenia obejmujący:

1. wejście do lokacji i tutorial systemu Harmonii,
2. eksplorację,
3. konfrontację wykorzystującą rytm,
4. zagadkę środowiskową,
5. zmianę świata wywołaną działaniem gracza,
6. fragment narracyjny,
7. działający zapis stanu,
8. pełną warstwę UI dla docelowej platformy,
9. podstawowy pakiet dostępności,
10. mierzalne cele wydajnościowe.

### Kryteria akceptacji Vertical Slice

- pełna pętla gameplayowa możliwa do przejścia bez ręcznej ingerencji developera,
- brak błędów blokujących progres,
- stabilny zapis i odczyt stanu,
- reprezentatywna jakość artystyczna i audio,
- telemetria profilowania wydajności,
- udokumentowane testy wejścia kontrolera,
- podstawowe scenariusze accessibility wykonane i udokumentowane.

## 5. Xbox / Windows — plan techniczny

Prace platformowe powinny być opisane jako konkretne zadania inżynieryjne, a nie jako ogólne hasło „porting”. Zakres obejmuje:

### Pamięć i wydajność

- profilowanie pamięci CPU/GPU,
- identyfikacja szczytowych obciążeń,
- streaming assetów,
- kontrolę kosztów audio,
- optymalizację shaderów i zasobów,
- analizę CPU frame time i GPU frame time,
- testy długotrwałej stabilności.

Docelowe budżety pamięci i klatkażu muszą wynikać z rzeczywistych pomiarów na docelowym hardware, a nie z założonych liczb wpisanych wcześniej do wniosku.

### Platform services

Zakres do implementacji i testów należy ustalić względem aktualnej dokumentacji Microsoft i wymagań właściwych dla produktu. W szczególności należy zweryfikować:

- tożsamość użytkownika,
- profile i uprawnienia,
- zapis lokalny i chmurowy,
- obsługę wielu użytkowników,
- sytuacje utraty urządzenia wejściowego,
- stany offline/online,
- błędy usług platformowych,
- wymagania sklepu i publikacji.

Nie należy w dokumencie deklarować konkretnego API ani zachowania platformy jako „wymaganego”, dopóki nie zostanie ono potwierdzone aktualnym źródłem technicznym.

### Certyfikacja

Strategia QA powinna obejmować testy wewnętrzne, testy regresyjne, testy platformowe oraz przygotowanie materiałów submission. Terminologia checklist i procesów certyfikacyjnych musi odpowiadać nomenklaturze obowiązującej w aktualnej dokumentacji Microsoft w momencie aplikacji.

## 6. Accessibility

Dostępność jest częścią architektury projektu, a nie etapem końcowym.

### Priorytety

- skalowanie tekstu i czytelność UI,
- napisy i alternatywne kanały informacji,
- nieopieranie krytycznych informacji wyłącznie na kolorze,
- pełne mapowanie wejścia tam, gdzie wspiera je projekt i platforma,
- regulacja czasu reakcji w mechanikach rytmicznych,
- ograniczenie motion sickness,
- opcje dla photosensitivity,
- możliwość pauzy w odpowiednich punktach doświadczenia,
- testy z osobami korzystającymi z technologii wspomagających.

Wartości liczbowe dotyczące rozmiarów tekstu, kontrastu, zakresów regulacji lub numeracji wytycznych nie powinny być przedstawiane jako oficjalne wymagania Microsoft bez bezpośredniego odwołania do aktualnego dokumentu źródłowego.

### Accessibility test plan

Testy należy wykonywać iteracyjnie, co najmniej na poziomie:

- UI/UX,
- napisy i audio cues,
- input/controller,
- cognition i tempo rozgrywki,
- motion/photo sensitivity,
- scenariusze pierwszego uruchomienia,
- pełna ścieżka od menu do zapisu gry.

## 7. Zespół i zdolność wykonawcza

W finalnej aplikacji należy podać wyłącznie rzeczywiste i możliwe do potwierdzenia informacje o:

- statusie prawnym podmiotu,
- liczebności zespołu,
- rolach kluczowych osób,
- doświadczeniu komercyjnym,
- poprzednich wydaniach,
- obecnym stanie projektu,
- własności IP,
- dostępnych zasobach produkcyjnych.

Opis różnorodności zespołu może wspierać kontekst programu, ale nie zastępuje dowodów zdolności do realizacji projektu.

## 8. Budżet

Proponowany budżet roboczy należy traktować jako model kosztowy, a nie potwierdzony limit DAP.

| Obszar | Budżet roboczy USD |
|---|---:|
| Vertical Slice | 100 000 |
| Platform engineering / porting | 150 000 |
| QA / certification readiness | 75 000 |
| Accessibility design & testing | 75 000 |
| **Razem model roboczy** | **400 000** |

Przed submission należy:

- potwierdzić maksymalną dostępną kwotę finansowania,
- potwierdzić kwalifikowalność każdej kategorii,
- rozbić koszty na person-days / vendor quotes / sprzęt / outsourcing,
- przypisać każdemu kosztowi konkretny milestone,
- usunąć pozycje niekwalifikowalne,
- przygotować wariant minimalny i wariant pełny.

## 9. Harmonogram

### Miesiące 1–3

- domknięcie Vertical Slice,
- stabilizacja core loop,
- finalizacja architektury platformowej,
- przygotowanie planu accessibility,
- pierwsza pełna macierz ryzyka.

### Miesiące 4–6

- integracja usług platformowych,
- optymalizacja pamięci i renderingu,
- implementacja accessibility,
- testy wejścia i zapisu,
- regresja Vertical Slice.

### Miesiące 7–9

- pełne testy scenariuszowe,
- QA platformowe,
- profiling i optymalizacja,
- testy accessibility z użytkownikami,
- zamykanie błędów krytycznych.

### Miesiące 10–12

- final QA,
- submission readiness,
- kompletowanie materiałów sklepowych i marketingowych,
- release candidate,
- przygotowanie do publikacji zgodnie z aktualnym procesem Microsoft.

Harmonogram należy skorygować po potwierdzeniu aktualnych terminów onboardingu, dostępności sprzętu, review i submission.

## 10. Go-To-Market

Strategia komercyjna powinna koncentrować się na jasnym pozycjonowaniu gry, jakości materiałów oraz budowaniu listy odbiorców przed premierą. Decyzje dotyczące ceny, promocji, Game Pass, Play Anywhere i innych programów platformowych powinny być przedstawione jako **opcje negocjacyjne / biznesowe**, chyba że istnieje potwierdzenie ich dostępności dla konkretnego tytułu.

Nie należy deklarować, że określony dzień tygodnia, okno wydawnicze lub obecność w konkretnej sekcji sklepu „gwarantuje” zwiększoną ekspozycję. Są to hipotezy marketingowe, które wymagają danych lub ostrożnego języka.

## 11. Dlaczego projekt pasuje do programu

Najsilniejszym argumentem nie powinno być samo pochodzenie zespołu czy temat kulturowy, lecz połączenie:

- wyraźnego twórczego wyróżnika,
- demonstracyjnie wykonalnej mechaniki,
- mierzalnego etapu rozwoju,
- jasno określonej potrzeby finansowania,
- planu platformowego,
- planu dostępności,
- kompetencji zespołu,
- wiarygodnych milestone'ów.

## 12. Evidence package

Do finalnej aplikacji warto przygotować:

- build / playable prototype,
- trailer lub gameplay capture,
- Vertical Slice milestone sheet,
- budżet i założenia kosztowe,
- CV kluczowych członków zespołu,
- dokument własności IP,
- roadmap techniczny,
- accessibility checklist,
- QA matrix,
- risk register,
- target platform matrix,
- plan marketingowy,
- lista kwestii wymagających potwierdzenia przez Microsoft.

## 13. Oświadczenie o dokładności

Dokument jest przygotowany jako uporządkowana, grantowa wersja opisu projektu. Wszystkie elementy zależne od aktualnych zasad Microsoft — zwłaszcza kwoty, eligibility, warunki programu, wymagania techniczne, nazewnictwo procesów, funkcje platformowe, programy handlowe oraz terminy — wymagają końcowej weryfikacji przed submission.
